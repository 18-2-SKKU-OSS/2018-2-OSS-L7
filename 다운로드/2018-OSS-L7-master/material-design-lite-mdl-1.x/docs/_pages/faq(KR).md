---
layout: styles
title: FAQ
bodyclass: faq
include_prefix: ../
---

<div class="docs-text-styling">
  <section class="docs-toc">
    <h3>Contents</h3>
    <nav class="section-content">
      <ul>
        <li><a href="#where-should-i-use">Material Design Lite (MDL)는 어디에 사용해야합니까?</a></li>
        <li><a href="#css-naming-conventions">MDL은 어떤 CSS 명명 규칙을 사용합니까?</a></li>
        <li><a href="#progressive-enhancement">MDL은 점진적 향상을 지원합니까?</a></li>
        <li><a href="#browser-support">MDL이 지원하는 브라우저는 무엇입니까?</a></li>
        <li><a href="#polymer">MDL은 Polymer와 잘 작동합니까?</a></li>
        <li><a href="#bootstrap">MDL은 부트 스트랩과 비슷합니까?</a></li>
        <li><a href="#existing-implementations">기존의 Material CSS 구현과 비교하면 어떻습니까?</a></li>
        <li><a href="#options-available">MDL의 축소판, CDN 또는 Sass 버전을 사용해야합니까?</a></li>
        <li><a href="#official-cdn">공식 CDN은 어떤 서비스를 사용합니까?</a></li>
        <li><a href="#web-starter-kit">How does MDL relate to Web Starter Kit?</a></li>
        <li><a href="#mdl-in-production">MDL은 Web Starter Kit와 어떤 관련이 있습니까?</a></li>
        <li><a href="#mdl-showcase">MDL을 사용하는 사이트를 선보일 수 있습니까?</a></li>
        <li><a href="#individual-components">개별 MDL 구성 요소 (예 : 버튼)를 만들거나 사용할 수 있습니까?</a></li>
        <li><a href="#report-an-issue">MDL의 문제점을 어떻게보고합니까?</a></li>
        <li><a href="#getting-help">MDL 사용에 관한 질문은 어디서 얻을 수 있습니까?</a>
        <li><a href="#slide-decks">MDL에서 프레젠테이션이나 슬라이드 데크를 사용할 수 있습니까?</a></li>
        <li><a href="#new-components">Can I request or contribute components to MDL?</a></li>
        <li><a href="#alternate-preprocessor">MDL에 구성 요소를 요청하거나 기여할 수 있습니까?</a></li>
        <li><a href="#issue-updates">관심있는 문제로 계속 업데이트하려면 어떻게해야합니까?</a></li>
      </ul>
    </nav>
  </section>

<h2 id="where-should-i-use">Material Design Lite (MDL)는 어디에 사용해야합니까?</h2>

[Material Design](https://www.google.com/design/spec/material-design/introduction.html)관심이 있다면 CSS, JavaScript 및 HTML과 같은 바닐라 웹 기술을 사용한 경험을 통해 MDL을 고려해 볼 수 있습니다. 마케팅 페이지, 기사, 블로그 및 특히 app-y가 아닌 일반 웹 콘텐츠와 같이 콘텐츠가 많은 웹 사이트에 최적화됩니다. 일부 색상을 선택하고 템플릿을 사용자 지정하고 재료 경험을 제공하려는 경우 해당 프로세스를보다 간단하게 만드는 데 도움을줍니다.

머티리얼 디자인을위한 몇 가지 커뮤니티 위주의 옵션이 있지만, 우리의 경험에 따르면 웹과 관련하여 머티리얼 사양에 몇 가지 차이가 있음을 보여줍니다. 이러한 격차를 어떻게 보충해야하는지 짐작하기보다, Material Design 팀과의 긴밀한 협력을 통해 오늘날 표준과 양립 할 수있는 Material 라이브러리를 제공하고있고 이것은 아직도 진화중이다.

<h2 id="css-naming-conventions">MDL은 어떤 CSS 명명 규칙을 사용합니까?</h2>

MDL은 다음을 사용하여 작성되었습니다. [BEM](https://en.bem.info/method/). BEM은 Block, Element, Modifier를 나타냅니다. 이 클래스는 CSS 클래스 이름을 구성하는 데 사용되는 메서드로, 일관성 있고 격리되며 표현력이 뛰어납니다. BEM 방법에 대해 더 자세히 알기위한 자료는 다음과 같습니다:

* [CSSWizardry](http://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/)
* [CSS-Tricks](https://css-tricks.com/bem-101/)
* [Smashing Magazine](http://www.smashingmagazine.com/2012/04/16/a-new-front-end-methodology-bem/)

이는 BEM을 이해하는 데 필요한 데이터를 단순화하는 훌륭한 리소스입니다. 발명가의 방법론을 읽고 싶다면, [Yandex provides the resource](https://en.bem.info/). 이 참조는 CSS뿐 아니라 사용하는 전체 자바 스크립트 설정에도 적용됩니다.

우리 [wiki](https://github.com/google/material-design-lite/wiki/Understanding-BEM) MDL에 특별히 사용 된 네임 스페이스에 대한 섹션을 포함합니다.

<h2 id="progressive-enhancement">MDL은 점진적 향상을 지원합니까?</h2>

MDL의 구성 요소는 점진적 향상을 염두에두고 설계되었습니다. 우리는 가능한 한 많이 네이티브 HTML 요소를 기반으로 '향상된 기능'을 위해 꼭 필요한 자바 스크립트를 사용합니다.

O한 가지 예가 '텍스트 만'재질 디자인 템플릿입니다. Chrome DevTools에서 자바 스크립트를 사용하지 않으면 페이지가 여전히 CSS를 훌륭하게 렌더링합니다:

![A preview of a template rendering in an older version of IE](../assets/template-preview.png)

이렇게하면 중요한 내용을 먼저 렌더링 한 다음 재질 디자인 단추 잔물결 및 팝 아웃 메뉴 구성 요소로 페이지를 '향상'할 수 있습니다.

향상된 경험을 위해 polyfills를 가져올 수 있지만 MDL은 IE9에서 JavaScript가없는 환경으로 최적화됩니다. 레이아웃과 같이 구성 요소가 JavaScript 기능을 필요로하는 경우, 개발시 이를 위해 계획해야합니다. IE10 + 브라우저가 완벽하게 지원됩니다. 브라우저 지원에 대한 자세한 내용은 '어떤 브라우저에서 MDL을 지원합니까?'를 참조하십시오.
참고 : MDL 사이트 자체는 가능하면 점진적 향상 기능을 사용하려고 시도합니다. 그러나 우리는 JS에 더 의존하는 사이트의 측면 (예 : 구성 요소 페이지)을 가지고 있습니다. MDL 템플릿 및 구성 요소는 JS를 사용하여 렌더링 할 수있을뿐만 아니라 렌더링을 시도합니다.

<h2 id="browser-support">MDL이 지원하는 브라우저는 무엇입니까?</h2>

MDL experience는 모든 브라우저의 마지막 두 버전에서 작동해야합니다, 우리가 정상적으로 IE9와 같은 브라우저에서만 CSS로 최적화됩니다. [Cutting-the-mustard](https://github.com/google/material-design-lite/blob/9e6c6ec9237715bfa04b307f786e9073f943e6be/src/mdlComponentHandler.js#L333) test.

우리 [browser compatibility matrix](https://github.com/google/material-design-lite/#browser-support) 공식적으로 지원하는 브라우저에 대한 최신 정보가 있습니다. 구성 요소의 경우 최소한 우리는 [querySelector](https://developer.mozilla.org/en-US/docs/Web/API/Document/querySelector), [classList](https://developer.mozilla.org/en-US/docs/Web/API/Element/classList) 그리고 [addEventListener](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener), which can be [polyfilled](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills) 필요에 따라. 우리의 템플릿은 주로 Flexbox를 사용하기 때문에 IE10 이상에서 작동합니다.

oldIE에서 MDL 지원을 향상시키기 위해 현재 사용중인 polyfill은 다음과 같습니다.:

```html
<!--[if IE]>
<script src="//cdnjs.cloudflare.com/ajax/libs/es5-shim/4.2.0/es5-shim.min.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/classlist/2014.01.31/classList.min.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/selectivizr/1.0.2/selectivizr-min.js"></script>
<![endif]-->
```

IE10 표준 모드 [removes](http://bit.ly/1dypChT) 조건부 주석을 지원하므로 위의 내용은 IE9와 같은 이전 버전의 IE에서만 해석됩니다.

우리는 공식적으로 IE8을 지원하지 않습니다. 즉, 일부 구성 요소는 CSS 전용 (또는 기본 HTML 요소) 환경을 다른 구성 요소보다 사용하면 성능이 저하됩니다. 예 :

**버튼**

<img alt="Buttons rendering in IE8" src="../assets/button_degradation.png">

**테이블**

<img alt="Tables gracefully degrading in IE8" src="../assets/table_degradation.png">

**슬라이더 (degrade to input fields)**

<img alt="Sliders degrading in IE8 to input fields" src="../assets/sliders_degradation.png">

<h2 id="polymer">MDL은 Polymer와 잘 작동합니까? 종이 요소를 대체합니까?</h2>

MDL은 블로그, 마케팅 페이지 및 전통적인 텍스트 기반 웹 페이지와 같은 정적 컨텐츠 사이트에 최적화 된 경험을 제공하는 데 중점을 둡니다.

<a href="https://elements.polymer-project.org/browse?package=paper-elements">Paper</a> 내장 요소는 <a href="http://polymer-project.org">Polymer</a> 개별적으로 사용하거나 함께 구성하여 재료 디자인 스타일 사이트를 만들고 완전히 향상된 사용자 상호 작용을 지원하는 완전히 캡슐화 된 구성 요소입니다.

즉, MDL은 폴리머 요소와 함께 사용할 수 있습니다. Polymer는 웹 구성 요소의 기능을 사용하여 해당 구성 요소에 사용 된 디자인을 캡슐화합니다. MDL은 사용자 지정 구성 요소 내의 스타일에 영향을주지 않습니다.

<h2 id="bootstrap">MDL은 부트 스트랩과 비슷합니까?</h2>

*Bootstrap 대신에 사용한다면, 같은 수준의 구성 요소 스타일링을 기대할 수 있습니까?*

머티리얼 디자인은 부트 스트랩의 많은 부분을 대체 할 수 있습니다. 그러나 Bootstrap이 제공하는 모든 기능과 기능을 일치시키려는 것은 아닙니다. 대신 MDL은 Material Design 사양에 지정된 구성 요소를 구현하려고합니다. 이를 통해 가장 포괄적이고 정확한 솔루션을 제공 할 수 있습니다.

<h2 id="existing-implementations">기존의 Material CSS 구현과 비교하면 어떻습니까?</h2>

*구체화, 재료 부트 스트랩 등*

우리는 커뮤니티가 CSS 라이브러리에 Material Design을 구현하는 방법을 스스로 제안하는 훌륭한 일을한다고 생각합니다.

사용 가능한 크고 다양한 구현은 종종 스펙에 대한 해석으로 상당히 진보적이며 그들의 의견은 머티리얼 디자인 팀이 '올바른'것으로 간주하는 것을 항상 반영하는 것은 아닙니다.MDL은 Material Design 및 Chrome UX 팀과 긴밀히 협력하여 개발되었으며 규격 준수에 대한 정기적 인 검토를 거칩니다. 아직 완전히 구체화되지 않은 사양의 영역을 다룰 때 MDL은 Material Design에 충실하려고하는 방식으로 이러한 문제를 해결하는 방법에 대한 검토 의견을 제시 할 수 있습니다.

<h2 id="options-available">MDL의 축소판, CDN 또는 Sass 버전을 사용해야합니까?</h2>

*나만의 버전을 만들거나 축소 된 버전을 다운로드하거나 단순히 CDN 개체를 참조해야합니까?*

**축소판 : **MDL을 처음 사용하는 경우, CSS / JS의 축소판이 포함 된 '시작하기'페이지와 사전 제작 된 템플릿 (선택 사항)이 포함 된 기본 패키지 중 하나를 다운로드하는 것이 좋습니다.

**CDN: **프로토 타입을 작성하거나 MDL CSS 및 JS 파일의 자체 복사본을 호스팅하지 않으려는 경우 CDN을 사용하여 많이 캐시 된 버전을 제거 할 수 있습니다.

**Customiser: **MDL로 새 사이트를 만들고 사용자 지정 색 구성표를 사용하는 경우 기본 패키지를 다운로드 한 다음 Customiser 도구를 사용하여 사용자 지정 빌드를 생성하는 것이 좋습니다. 이것을 사용하여 자신의 필요에 맞게 material.min.css 파일을 무시할 수 있습니다.

**Sass: **모두 들어가기를 원한다면 원본 소스, 문서 및 템플릿을 포함하는 Sass 버전의 MDL을 얻을 수 있습니다. 이 버전은 CSS 변수와 익숙한 Sass 선량을 사용하여 최대의 맞춤 설정을 가능하게합니다.

<h2 id="official-cdn">공식 CDN은 어떤 서비스를 사용합니까?</h2>

공식 CDN은 다음을 사용하여 호스팅됩니다. [Google Cloud Storage](https://cloud.google.com/storage/).

<h2 id="web-starter-kit">MDL은 Web Starter Kit와 어떤 관련이 있습니까?</h2>

MDL은 Web Starter Kit에서 제공하는 스타일 가이드의 진화 단계입니다. [Web Starter Kit](https://developers.google.com/web/tools/starter-kit/) 많은 개발자들이 자신의 사이트에서 머티리얼 디자인을 원했음이 분명해졌습니다.

WSK Styleguide는 Material Design과 완벽하게 일치하지 않았으며 단순히 아이디어를 기반으로했습니다. WSK 프로젝트에서 MDL은 개발자를위한 이러한 요구를 충족시키기 위해 탄생했습니다. 이 과정에서 가능한 한 충실한 사양으로 구현합니다.

<h2 id="mdl-in-production">어떤 Google 제품도 제작 과정에서 MDL을 사용합니까?</h2>

MDL은 몇 가지 다른 Google 제품에서 프로덕션에 사용됩니다. 이것들은 구식의 불완전한 버전을 사용하지만 전개 된 경험이 어떻게 보이는지 보여줍니다. 예:

[Google Services](https://developers.google.com/mobile/add) 사이드:

![Google Services site screenshot](../assets/google-services.png)

[RichMediaGallery](http://www.richmediagallery.com/) by DoubleClick:

![RichMediaGallery screenshot](../assets/rich-media-gallery.png)

Google 쇼핑을 포함한 다가오는 프로젝트에서 많은 다른 팀이 사용하고 있습니다.

<h2 id="mdl-showcase">MDL을 사용하는 사이트를 선보일 수 있습니까?</h2>

<a href="/showcase/">Showcase</a> 프로덕션에서 MDL을 사용하는 Google 사이트의 초기 목록입니다.

사이트 추가를 요청하려면 [new issue](https://github.com/Google/material-design-lite/issues/new?title=Site%20Showcase%20Request&body=Please%20include:%0A*%20Description%0A*%20Primary%20Link%0A*%20Screenshot)우리의 GitHub issue tracker에 링크, 사이트 설명 및 제안 스크린 샷을 포함해서 보내야합니다.

가까운 시일 내에 적절하게 연마 된 쇼케이스를 사이트에 추가하기를 희망합니다.

<h2 id="individual-components">개별 MDL 구성 요소 (예 : 버튼)를 만들거나 사용할 수 있습니까?</h2>

V1의 MDL을 위해 우리는 페이지에 몇 가지 다른 구성 요소가 필요할 것 같은 사람들의 유스 케이스에 중점을두고 있으며 대부분의 MDL 라이브러리를 포함하고자합니다. 즉, 단일 구성 요소를 독창적으로 따는 것에 대한 지원 및 문서는 최소화됩니다.

즉, 단일 (또는 더 적은 수의) 구성 요소를 사용하여 빌드를 생성해야하는 경우 Sass 빌드와 함께 Gulp를 사용해야합니다. [comment out](https://github.com/google/material-design-lite/blob/master/src/material-design-lite.scss) material-design-lite.scss에서 필요하지 않은 구성 요소, [comment out](https://github.com/google/material-design-lite/blob/master/gulpfile.js#L191) Gulpfile에서 필요하지 않은 스크립트와`gulp '를 실행하여 빌드를 생성하십시오.

우리는 좀 더 모듈화 된 방식으로 구성 요소를 제공하는 것에 대해 이야기했지만 post V1 타임 라인에서이를 탐구 할 것입니다.

<h2 id="report-an-issue">MDL 문제를 어떻게보고합니까?</h2>

이슈를 사용하여 문제를 알려주세요[GitHub repo](https://github.com/google/material-design-lite/issues).

<h2 id="getting-help">MDL 사용에 관한 질문은 어디서 얻을 수 있습니까?</h2>

MDL 사용자와 개발자 커뮤니티는 질문을하고 질문에 답변 할 수 있도록 [Stack Overflow](http://stackoverflow.com), 'Material-Design-Lite` 태그를 사용합니다.

<h2 id="slide-decks">MDL에서 프레젠테이션이나 슬라이드 데크를 사용할 수 있습니까?</h2>

우리는 MDL의 Google I / O 2015에서 미리보기를했고 그  슬라이드에서 다음을 찾을 수 있습니다. [SpeakerDeck](https://speakerdeck.com/gauntface/material-design-lite-preview).

<h2 id="new-components">MDL에 구성 요소를 요청하거나 기여할 수 있습니까?</h2>

아직 제공하지 않은 MDL에서 구현하고자하는 구성 요소 또는 템플릿이 있을 수 있습니다. 언제든지 제안하십시오. <a href="https://github.com/Google/material-design-lite/issues/new?title=%5BComponent%20Request%5D%20%7BComponent%7D&body=Please%20include:%0A*%20Description%0A*%20Material%20Design%20Spec%20link%0A*%20Use%20Case%28s%29">Issue Tracker</a>. 우리가 모두 구현할 수 있다고 보장 할 수는 없지만 일정한 간격으로 요청을 검토 할 것입니다.

<h2 id="alternate-preprocessor">MDL이 비-전처리를 지원합니까?</h2>

*Stylus, Less, PostCSS, etc.*

MDL은 Sass를 사용하여 구현되었으며 현재 변경 계획이 없습니다. 포트를 다른 선행 처리기로 유지하고 싶다면 환영 할 만하다.

<h2 id="issue-updates">관심있는 문제로 계속 업데이트하려면 어떻게해야합니까?</h2>

전체 리포지토리를 보면서 스트림에 많은 추가 노이즈가 발생할 수 있습니다. 관심있는 문제 만 업데이트하려면 해당 문제를 구독하면됩니다. 이것은 오른쪽 사이드 바에있는 "Subscribe"버튼을 클릭하여 문제 페이지에서 수행됩니다.

<img alt="Subscribing to a single issue" src="../assets/faq/subscribe-single-issue.png">
