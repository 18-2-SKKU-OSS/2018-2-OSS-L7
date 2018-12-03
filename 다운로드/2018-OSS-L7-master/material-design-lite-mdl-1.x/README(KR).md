# Material Design Lite

[![GitHub version](https://badge.fury.io/gh/google%2Fmaterial-design-lite.svg)](https://badge.fury.io/gh/google%2Fmaterial-design-lite)
[![npm version](https://badge.fury.io/js/material-design-lite.svg)](https://badge.fury.io/js/material-design-lite)
[![Bower version](https://badge.fury.io/bo/material-design-lite.svg)](https://badge.fury.io/bo/material-design-lite)
[![Gitter version](https://img.shields.io/gitter/room/gitterHQ/gitter.svg)](https://gitter.im/google/material-design-lite)
[![Dependency Status](https://david-dm.org/google/material-design-lite.svg)](https://david-dm.org/google/material-design-lite)

> [Material Design](http://www.google.com/design/spec/material-design/introduction.html) 은
바닐라 CSS, JS 및 HTML의 구성 요소를 구현한 것이다.

Material Design Lite (MDL)를 사용하면 저신이 디자인할 웹사이트의 재질이나 디자인의 느낌을 확인 할 수 있습니다.
MDL은 자바스크립트 프레임워크나 라이브러리에 의존하지 않습니다.
교차 장치 사용에 최적화되고
브라우저에서 정상적으로 최적화되며 이동 중에도 액세스 할 수있는 환경을 제공합니다.

> ### 제한적 지원

> Material Design Lite 는 현재
> [Material Components for the web](https://github.com/material-components/material-components-web) 로 이동이 되었으며 개발을 제한적으로 지원 하고 있습니다.

> 핵심 개발자에 의한 MDL 개발은 더 이상 진행되지 않지만 저희는 기꺼이 PR을 검토하고 치명적인 버그를 수정하고
> 새로운 릴리즈를 발표 할 것입니다. 그러나 중요한 변경사항은 허용 되지 않을 것입니다.

## 귀하의 사이트에서 MDL을 사용하기위해

**이 문서는 MDL에 기여하거나 컴파일 할 개발자를 대상으로합니다.
웹 사이트 또는 웹 앱에서 MDL을 사용하려는 경우
[getmdl.io](http://getmdl.io).**

## 브라우저 지원


| IE9 | IE10 | IE11 | Chrome | Opera | Firefox | Safari | Chrome (Android) | Mobile Safari |
|-----|------|------|--------|-------|---------|--------|------------------|---------------|
| B   | A    | A    | A      | A     | A       | A      | A                | A             |

A 등급 브라우저가 완벽하게 지원됩니다. B 등급 브라우저는 CSS 전용 환경으로 최적화 됩니다.

### 다운로드 / 복제

Git을 사용하여 repo 복제:

```bash
git clone https://github.com/google/material-design-lite.git
```

또는 [download](https://github.com/google/material-design-lite/archive/master.zip)
이 저장소를 받으셔도 됩니다.

위도우 유저, 라인 엔딩으로 인해 컴파일하는데 문제가 있다면
당신은`lf` (unix) 라인 결말로 저장소를 체크 아웃하도록 자식을 설정한다.
 `core.eol`를 사용해서 설정 할 수 있습니다.

```bash
git config core.eol lf
git config core.autocrlf input
git rm --cached -r .
git reset --hard
```

> 주의!, 마스터 브랜치는 불안정하여. 프로덕션 환경에서는 사용하지 마십시오.
안정성을 위해 리포지토리, npm 또는 bower의 태그가 지정된 상태를 사용하십시오!

## 변경사항 요청

MDL은 현재 핵심 개발자가 더 이상 개발하지 않고 제한된 지원모드에 있습니다.
큰 변경 사항이 없는한에서 우리는 기꺼이 새로운 기능에 대한 요청을
받아 들이곘습니다.

## 기여하고 싶습니까?

버그를 발견 했을 경우, 질문이 있거나 기여하고 싶다면 우리를 팔로우 하세요.
[guidelines](https://github.com/google/material-design-lite/blob/mdl-1.x/CONTRIBUTING.md),
Material Design Lite를 개선하기 위해서 우리의 wiki가 도움이 됩니다.
[wiki](https://github.com/google/material-design-lite/wiki)에 방문하여 자세한 정보를 얻을 수 있습니다.

우리의 기본 branch인 `mdl-1.x`를 사용해 주세요.

주의! [Material Components for Web](https://github.com/material-components/material-components-web), (MDL v2)는 초기 알파 단계에 있습니다 (즉, 모든 것이 유동적이며 언제든지 변경될 수 있음). 주의해서 사용하십시오.

그러나 우리는 사람들이 MCW를 테스트하고 다른 프레임 워크 및 라이브러리와의 통합을 통해 자신의 경험에 대한 피드백을 제공하는 것을 절대적으로 환영합니다.

## 특허(License)

© Google, 2015. Licensed under an
[Apache-2](https://github.com/google/material-design-lite/blob/master/LICENSE)
license.
