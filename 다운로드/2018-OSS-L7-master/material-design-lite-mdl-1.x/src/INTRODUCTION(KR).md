# Material Design Lite

## 소개
**Material Design Light (MDL)** 은 Google의 **머티리얼 디자인(Material Design)** 철학 : "우수한 디자인의 기본 원칙을 혁신과 가능성으로 종합한 사용자를 위한 시각적 언어 기술과 과학."  에 기반한 웹 개발자를 위한 구성 요소 라이브러리입니다. 머티리얼 디자인의 목표와 원칙을 이해하는 것은 MDL 구성 요소를 올바르게 사용하는 데 매우 중요합니다. 당신이 아직 [Material Design 소개](http://www.google.com/design/spec/material-design/introduction.html)를 읽지 않았을 경우, 구성 요소들을 사용하기 전에 읽어 주십시오.

MDL의 구성 요소들은 CSS, JavaScript, 그리고 HTML을 이용하여 제작되었습다. 당신은 MDL의 구성 요소들을 사용하여 매력적이고 일관되며 기능적인 웹 페이지 및 웹 앱을 개발할 수 있습니다.  MDL로 개발된 페이지는 브라우저 이식성, 장치 독립성 및 우아한 성능 저하(graceful degradation)와 같은 최신 웹 디자인 원칙을 준수합니다.

MDL 컴포넌트 라이브러리에는 머티리얼 디자인 개념을 따르기 위해 알맞은 버튼, 체크 박스 및 텍스트 필드와 같은 새로운 버전의 일반적인 사용자 인터페이스 컨트롤들이 포함되어 있습니다. 또한 라이브러리에는 카드, 열 레이아웃, 슬라이더, 회전자, 탭, 타이포그래피 등과 같은 고급 기능들과 특수 기능들이 포함되어 있습니다.

MDL은 무료로 다운로드하여 사용할 수 있으며 [Material Design Lite](http://www.getmdl.io/)와 같은 빌드 라이브러리 또는 개발 환경과 함께 또는 사용할 수 있습니다. 더 많은 생산성과 이식성, 그리고 &mdash; 다른 무엇보다도 &mdash; 유용한 웹 페이지를 원하는 사람이 사용할 수 있는 크로스 브라우저, 크로스 OS 웹 개발자 툴킷입니다. 

## Getting started

### Get the components
To obtain the components, clone or download the [GitHub MDL repository](https://github.com/google/material-design-lite). Copy the entire package (the top-level folder and everything below it) to the project folder where you will write your HTML pages. This ensures that your project can access all of MDL's components and assets, and that you always have the original files for reference in case you break something. :-)

### Include the master CSS and JavaScript
In each HTML page in your project, include the minified (compressed) CSS and JavaScript files using standard relative-path references and the Material Icon font. This example assumes that a copy of the MDL package folders resides in your project folder.


```html
<link rel="stylesheet" href="css/material.min.css">
<script src="js/material.min.js"></script>
<link rel="stylesheet" href="//fonts.googleapis.com/icon?family=Material+Icons">
```

That's it! You are now ready to use the MDL components.

### Use the components
In general, follow these basic steps to use an MDL component in your HTML page.

1. Start with a standard HTML element, such as `<button>`, `<div>`, or `<ul>`, depending on the MDL component you want to use. This establishes the element in the page and readies it for MDL modification.<br><br>
2. Add one or more MDL-specific CSS classes to the element, such as `mdl-button` or   `mdl-tabs__panel` again depending on the component. The classes apply the MDL enhancements to the element and effectively turn it into an MDL component.<br><br>
3. View the page, preferably in multiple browsers on multiple devices, to ensure that the component looks and behaves as expected.

>**A note about HTML elements and MDL CSS classes**
>Material Design Lite uses CSS *independent classes*, which can apply to any HTML element, to construct components. For some components, you can use almost any element. For other components, some elements give better visual or behavioral performance than others. The examples in each component's README file use elements that perform well as that component. If you must use elements other than those shown in the examples, we encourage you to experiment to find the best combination of HTML elements and MDL CSS classes for your application.

## What's next?
Detailed instructions for using the components, including MDL classes and their effects, coding considerations, and configuration options, can be found in each component's `README.md` file. Working examples using various options are in each component's `demo.html` page.

## License

Copyright Google, 2015. Licensed under an Apache-2 license.
