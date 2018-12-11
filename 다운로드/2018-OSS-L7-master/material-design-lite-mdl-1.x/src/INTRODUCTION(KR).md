# Material Design Lite

## 소개
**Material Design Light (MDL)** 은 Google의 **머티리얼 디자인(Material Design)** 철학 : "우수한 디자인의 기본 원칙을 혁신과 가능성으로 종합한 사용자를 위한 시각적 언어 기술과 과학."  에 기반한 웹 개발자를 위한 구성요소 라이브러리입니다. 머티리얼 디자인의 목표와 원칙을 이해하는 것은 MDL 구성요소들을 올바르게 사용하는 데 매우 중요합니다. 당신이 아직 [Material Design 소개](http://www.google.com/design/spec/material-design/introduction.html)를 읽지 않았을 경우, 구성요소들을 사용하기 전에 읽어 주십시오.

MDL의 구성요소들은 CSS, JavaScript, 그리고 HTML을 이용하여 제작되었습니다. 당신은 MDL의 구성요소들을 사용하여 매력적이고 일관되며 기능적인 웹 페이지 및 웹 앱을 개발할 수 있습니다.  MDL로 개발된 페이지는 브라우저 이식성, 장치 독립성 및 우아한 성능 저하(graceful degradation)와 같은 최신 웹 디자인 원칙을 준수합니다.

MDL 컴포넌트 라이브러리에는 머티리얼 디자인 개념을 따르기 위해 알맞은 버튼, 체크 박스 및 텍스트 필드와 같은 새로운 버전의 일반적인 사용자 인터페이스 컨트롤들이 포함되어 있습니다. 또한 라이브러리에는 카드, 열 레이아웃, 슬라이더, 회전자, 탭, 타이포그래피 등과 같은 고급 기능들과 특수 기능들이 포함되어 있습니다.

MDL은 무료로 다운로드하여 사용할 수 있으며 [Material Design Lite](http://www.getmdl.io/)와 같은 빌드 라이브러리 또는 개발 환경과 함께 또는 사용할 수 있습니다. 더 많은 생산성과 이식성, 그리고 &mdash; 다른 무엇보다도 &mdash; 유용한 웹 페이지를 원하는 사람이 사용할 수 있는 크로스 브라우저, 크로스 OS 웹 개발자 툴킷입니다. 

## 시작하기

### 구성요소 가져오기
구성요소를 가져오려면 [GitHub MDL 저장소](https://github.com/google/material-design-lite)를 클론 하거나 다운로드하십시오. 전체 패키지 (최상위 폴더와 그 아래의 모든 폴더)를 당신이 HTML 페이지를 작성할 프로젝트 폴더에 복사합니다. 이렇게 하면 당신의 프로젝트가 MDL의 모든 구성요소와 자산에 액세스할 수 있으며 문제가 생기더라도 항상 원본 파일을 참조할 수 있습니다. :-)

### master CSS와 자바스크립트 포함하기
프로젝트의 각 HTML 페이지에 표준 상대 경로 참조(standard relative-path references) 및 Material Icon 폰트를 사용하여 축소된 (압축된) CSS 및 JavaScript 파일을 포함시킵니다. 이 예제에서는 MDL 패키지 폴더의 복사본이 프로젝트 폴더에 있다고 가정합니다.

```html
<link rel="stylesheet" href="css/material.min.css">
<script src="js/material.min.js"></script>
<link rel="stylesheet" href="//fonts.googleapis.com/icon?family=Material+Icons">
```

그게 다입니다! 이제  당신은 MDL 구성요소를 사용할 준비가 되었습니다

### 구성요소 사용하기
일반적으로, HTML 페이지에서 MDL 구성요소를 사용하려면 다음 기본 단계를 따르십시오.

1. 사용하려는 MDL 구성요소에 따라`<button>`,`<div>`,`<ul>`같은 표준 HTML 요소로 시작하십시오. 그러면 페이지의 요소들이 설정되고 MDL로의 변환이 준비됩니다. <br> <br>
2. 요소에 따라 하나 이상의 MDL 관련 CSS 클래스를 추가합니다 (예 : mdl-button 또는 mdl-tabs__panel). 클래스는 요소에 MDL 개선 사항을 적용하고 효과적으로 MDL 구성 요소로 변환합니다. <br> <br>
3. 여러 장치의 여러 브라우저에서 페이지를 보면서 구성 요소가 예상대로 보이고 작동하는지 확인하십시오.

> **HTML 요소 및 MDL CSS 클래스에 대한 참고 사항**
> Material Design Lite는 HTML 요소에 적용할 수 있는 CSS *독립 클래스*들을 사용하여 구성요소를 구성합니다. 일부 구성요소들의 경우 거의 모든 요소를 사용할 수 있습니다. 다른 구성요소들의 경우 일부 요소들은 다른 요소들보다 시각적 또는 동작 성능이 뛰어납니다. 각 구성요소들의 README 파일에 있는 예제들은 해당 구성요소로 잘 작동되는 요소를 사용합니다. 예제에 표시된 것 이외의 요소를 사용해야 하는 경우 실험을 통해 응용 프로그램에 가장 적합한 HTML 요소와 MDL CSS 클래스 조합을 찾으십시오.

## 그다음에 할 일은 무엇입니까?
MDL 클래스와 그 효과, 코딩 시 고려 사항, 구성 옵션 등 컴포넌트 사용에 대한 자세한 지침은 각 컴포넌트의 README.md 파일에서 찾을 수 있습니다. 다양한 옵션을 사용하는 작업 예제들은 각 구성 요소의`demo.html` 페이지에 있습니다.

## 라이센스

Copyright Google, 2015. Licensed under an Apache-2 license.
