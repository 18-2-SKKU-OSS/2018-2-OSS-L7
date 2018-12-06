# Contributing to Material Design Lite

여러분이 지금보다 더 나은 Material Design Lite를 만들고, 소스 코드에 참여하는 것을 적극 환영합니다. 아래의 가이드라인을 따라주시기 바랍니다:

 - [Code of Conduct](#coc)
 - [Question or Problem?](#question)
 - [Issues and Bugs](#issue)
 - [Feature Requests](#feature)
 - [Submission Guidelines](#submit)
 - [Coding Rules](#rules)
 - [Signing the CLA](#cla)

## <a name="coc"></a> Code of Conduct

Material Design Lite 프로젝트의 배포자이자 관리자로써, 이슈 게시, 문서 업데이트, pull request제출, 의견에 대한 피드백 및 기타 다른 활동을 통해 기여하는 모든 사람들을 존중할 것을 맹세합니다.

Material Design Lite의 채널(GitHub, StackOverflow, Google+, Twitter, 등)을 통한 커뮤니케이션은 건설적이어야 하며, 개인 공격, 유해물이나 악의적인 선동, 공개적 또는 사적인 괴롭힘, 모욕, 그 외의 프로페셔널 하지 못한 행동은 엄격히 금합니다.

우리는 성별, 성 정체성, 성적 취향, 장애, 나이, 인종, 민족성, 종교 또는 경험 수준에 관계없이 이 프로젝트에 참여한 모든 사람들에게 예의와 존중을 보여줄 것을 약속합니다. 우리는 Material Design Lite 프로젝트에 기여하는 누구에게든 이와 같이 할 것입니다.

커뮤니티 회원이 이 행동강령을 위반할 경우, Material Design Lite 프로젝트의 관리자는 적절하다고 판단하여, 이슈, 의견 및 PR을 삭제하거나 계정을 차단하는 행동을 취할 수 있습니다.

허용되지 않는 행위에 직면했거나, 목격한 경우 또는 기타 다른 우려사항이 있다면, addyo@google.com로 연락주세요.

## <a name="question"></a> Got a Question or Problem?

Material Design Lite 사용법에 질문이 있을 경우, [StackOverflow][stackoverflow]를 방문하여 `material-design-lite`태그를 클릭하세요. GitHub 이슈에 관해서도 찾아볼 수 있습니다.

중요 문서가 누락되었다고 생각되면, 언제든 문제를 제기하세요. 도와드리겠습니다. 아래의 질문 예시를 참고하세요:

```
Component (if any):

무엇을 하려고 하시나요? 아니면 무엇을 더 찾으려고 하시는지요?

어디서 보셨나요?

이 정보를 어디서 찾을 것으로 예상하셨나요?
```

새로운 디자인의 템플릿을 찾고 있는 경우:

```
찾고 있는 템플릿에 대해 간략히 알려주세요.

디자인 설계 관점에서 이 템플릿이 흥미롭거나 어렵게 만드는 점은 무엇인가요?

우연히 발견했을 수도 있습니다. 이런 형식의 페이지를 잘 나타낸 URL를 제공해 주세요.
```

## <a name="issue"></a> Found an Issue?
소스 코드에 버그가 있거나 문서의 실수가 발견되면, [GitHub Repository][github]에 이슈를 제출하여 주십시오. 해결법과 함께 pull request를 보내주시면 더욱 도움이 됩니다.
 
[below](#submit)가이드라인을 참고하세요.

## <a name="feature"></a> Want a Feature?
[GitHub Repository][github]에 이슈를 제출하여 새로운 기능을 요청할 수 있습니다.

아래 예시를 참고하세요:

```
새로운 컴포넌트 인가요? 아니면, 기존 컴포넌트에서 기능이 빠져있나요?
컴포넌트 이름:
컴포넌트 Material Design spec URL(있을 경우):

이 컴포넌트나 기능으로, 당시에는 하지 못했던 무엇을 할 수 있나요?

우연히 발견했을 수도 있습니다. 이 컴포넌트나 기능의 사용이 잘 반영된 URL이나 스크린샷을 제공해 주세요.
```

새로운 기능의 실행을 원하실 경우 어떤 종류의 변경인지 고려하십시오:

* **Major Changes** 프로젝트에 기여하고 싶은 바가 [issue tracker][]에서 먼저 논의되어야만, 우리의 노력을 보다 잘 조율하고, 중복 작업을 방지하며 여러분의 변경 실행을 지원하여, 성공적으로 프로젝트에 반영되도록 할 수 있습니다.
* **Small Changes**은 반영하여 pull request를 통해 [GitHub Repository][github]에 제출하시면 됩니다.

## <a name="submit"></a> Submission Guidelines

### Submitting an Issue
이슈를 제출하기 전, 아카이브를 먼저 검색해 보세요. 이미 해당 질문에 답변이 되었을 수도 있습니다.

보고되지 않은 버그 이슈라고 판단될 경우, 새로운 이슈를 개설하세요. 
중복된 이슈의 보고는 자제하여, 이슈의 해결 및 새로운 기능 추가를 위한 노력이 최대화 되도록 도와주시기 바랍니다. 아래 정보를 제공하시면, 보다 신속하게 이슈를 해결할 수 있습니다:

* **Overview of the Issue** - 에러를 알려주시면, non-minified stack trace가 도와드립니다.
* **Motivation for or Use Case** - 여러분에게 왜 버그인지 설명해 주세요
* **Material Design Lite Version(s)** - 구형 버전인가요?
* **Browsers and Operating System** - 모든 브라우저에서 발생하는 문제인가요? 아니면 IE9에서만 문제인가요?
* **Reproduce the Error** - (JSBin 을 사용하는) 실제 상황이나 구체적인 과정을 제공해 주세요.
* **Related Issues** - 이전에 유사한 이슈가 보고된 적 있나요?
* **Suggest a Fix** - 자체적으로 버그를 수정할 수 없을 경우, 문제의 원인(코드 또는 커밋 명령어)은 알려줄 수 있을 것입니다.

**도움을 받으셨다면, 다른 이들도 도와주세요. Good karma rulez!**

아래 예시를 참고하세요:

```
MDL version:
Browser:
Browser version:
Operating system:
Operating system version:
URL, if applicable (you can use a [codepen as a starting point][http://codepen.io/pen/def?fork=xGWgXa]):

어떤 단계에서 문제가 재발하나요:
1.
2.
3.

예상되는 결과는 무엇입니까?

예상 결과 대신 어떤 일이 발생하나요?

아래에 다른 정보들도 제공해 주시고, 가능하면 스크린샷을 첨부해 주십시오.
```

### Submitting a Pull Request
pull request 제출 전, 다음 가이드라인을 고려해 주세요:

* 이중의 노력을 들이지 않으려면, [GitHub](https://github.com/google/material-design-lite/pulls)에서 여러분의 제출과 관련하여 개설/종료된 pull request를 검색해 보세요.
* pull request를 보내기 전 [Contributor License Agreement (CLA)](#cla)에 서명해 주십시오. 서명 없이는 코드를 허락할 수 없습니다.
* 새로운 git 브랜치에서 여러분의 변경사항을 적용하세요:

     ```shell
     git checkout -b my-fix-branch master
     ```

* **적절한 테스트 사례가 포함된** 패치를 생성하세요.
* 우리의 [Coding Rules](#rules)을 따르세요.
* 모든 Material Design Lite 테스트 묶음을 실행하고(`gulp test`), 모든 테스트가 통과되도록 하세요.
* 추적해서는 안 되는 파일(e.g `node_modules`, `gulp-cache`, `.tmp`, `.idea`)의 확인은 피하세요. 이를위해 [global .gitignore](https://help.github.com/articles/ignoring-files/#create-a-global-gitignore)의 사용을 권장합니다.
* 여러분 PR 의 일부로 `/css`와 `/js`에 있는 파일들의 recompiled 버전을 포함시키지 마십시오. 우리가 자동으로 생성합니다.
* descriptive commit message를 사용하여 변경을 커밋하세요.

     ```shell
     git commit -a
     ```
  Note: 커밋 선택사항 `-a` 옵션 설정 명령어는 자동으로 편집된 파일들을 “add” 및 “rm” 합니다.

* 모든 테스트가 통과되도록 내부적으로 변경 사항을 구축하세요:

    ```shell
   gulp
    ```

* GitHub로 여러분의 브랜치를 푸쉬하세요:

    ```shell
    git push origin my-fix-branch
    ```

* GitHub에서 `material-design-lite:master`로 pull request를 보내세요.
* 만약 우리가 변경을 제안하면:
  * 요구사항을 업데이트 하세요.
  * 테스트가 여전히 통과되는지 Material Design Lite 테스트 묶음을 재 실행하세요.
  * 여러분의 브랜치를 재설정하고, GitHub repository로 강제 푸쉬하세요(여러분의 pull request를 업데이트 해줍니다):

    ```shell
    git rebase master -i
    git push origin my-fix-branch -f
    ```

끝입니다! 기여해 주셔서 감사합니다!

#### pull request 병합 후

pull request가 병합된 후, 여러분의 브랜치를 안전하게 삭제하고 메인(upstream) 저장소에서 변경사항을 끌어올 수 있습니다:

* GitHub web UI 또는 다음과 같이 여러분의 로컬 쉘을 통해 GitHub 의 원격 브랜치를 삭제하세요:

    ```shell
    git push origin --delete my-fix-branch
    ```

* 마스터 브랜치 체크아웃:

    ```shell
    git checkout master -f
    ```

* 로컬 브랜치 삭제:

    ```shell
    git branch -D my-fix-branch
    ```

* 최신 upstream 버전으로 여러분의 마스터 업데이트:

    ```shell
    git pull --ff upstream master
    ```

## <a name="rules"></a> Coding Rules

우리는 [JSCS configuration][jscs-config]에 기록된 일부 소수의 예외를 제외하고, [Google JavaScript style guide][js-style-guide]를 전반적으로 따릅니다.

[JSCS](http://jscs.info)는 스타일 가이드에 반대되는 코드를 linting 하기 위한 도구이며, 에디터와 빌드 툴 모두에 사용 가능한 플러그인을 가지고 있습니다. 우리의 스타일 가이드와 일치하도록 여러분의 코드를 자동으로 지정하길 원하면, JSCS [autoformatting][autoformatting] 기능을 사용하면 됩니다.

## <a name="cla"></a> Signing the CLA

pull request를 보내기 전 배포자 라이선스 동의(CLA)에 서명해 주십시오. 코드 변경을 허가 받으려면, 반드시 CLA에 서명해야 합니다. 간단한 절차입니다, 약속해요!

* 개인 : [simple click-through form][individual-cla].
* 기업 : [print, sign and one of scan+email, fax or mail the form][corporate-cla].

*이 가이드는 [AngularJS contribution guidelines](https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md) 가이드라인을 참고하였습니다.*

[github]: https://github.com/google/material-design-lite
[issue tracker]: https://github.com/google/material-design-lite/issues
[individual-cla]: http://code.google.com/legal/individual-cla-v1.0.html
[corporate-cla]: http://code.google.com/legal/corporate-cla-v1.0.html
[js-style-guide]: http://google-styleguide.googlecode.com/svn/trunk/javascriptguide.xml
[jsbin]: http://jsbin.com/
[stackoverflow]: http://stackoverflow.com/questions/tagged/material-design-lite
[global-gitignore]: https://help.github.com/articles/ignoring-files/#create-a-global-gitignore
[autoformatting]: https://medium.com/@addyosmani/auto-formatting-javascript-code-style-fe0f98a923b8
[jscs-config]: https://github.com/google/material-design-lite/blob/master/.jscsrc
