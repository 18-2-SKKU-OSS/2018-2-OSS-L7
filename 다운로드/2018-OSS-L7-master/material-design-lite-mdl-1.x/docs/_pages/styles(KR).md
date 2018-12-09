---
layout: styles
title: Styles
bodyclass: styles
include_prefix: ../
---

  <div class="styles__content">
    <p>
      Material Design Lite는 웹용으로 특별히 제작 된 Material Design의 경량 구현입니다. 다른 플랫폼에 대한 자세한 지침 및 사양은
      <a href="https://www.google.com/design/spec/material-design">
        Material Design site
      </a>
    </p>

    <h2 class="mdl-typography--subhead">Typography</h2>
    <dl class="typo-styles">
      <dt>h1</dt>
      <dd>
        <div class="typo-styles__demo mdl-typography--display-4">Light 112sp</div>
        <div class="typo-styles__desc">
          <span class="typo-styles__name">display-4</span>
          <span class="typo-styles__weight">font weight 300</span>
        </div>
      </dd>
      <dt>h2</dt>
      <dd>
        <div class="typo-styles__demo mdl-typography--display-3">Regular 56sp</div>
        <div class="typo-styles__desc">
          <span class="typo-styles__name">display-3</span>
          <span class="typo-styles__weight">font weight 400</span>
        </div>
      </dd>
      <dt>h3</dt>
      <dd>
        <div class="typo-styles__demo mdl-typography--display-2">Regular 45sp</div>
        <div class="typo-styles__desc">
          <span class="typo-styles__name">display-2</span>
          <span class="typo-styles__weight">font weight 400</span>
        </div>
      </dd>
      <dt>h4</dt>
      <dd>
        <div class="typo-styles__demo mdl-typography--display-1">Regular 34sp</div>
        <div class="typo-styles__desc">
          <span class="typo-styles__name">display-1</span>
          <span class="typo-styles__weight">font weight 400</span>
        </div>
      </dd>
      <dt>h5</dt>
      <dd>
        <div class="typo-styles__demo mdl-typography--headline">Regular 24sp</div>
        <div class="typo-styles__desc">
          <span class="typo-styles__name">headline</span>
          <span class="typo-styles__weight">font weight 400</span>
        </div>
      </dd>
      <dt>h6</dt>
      <dd>
        <div class="typo-styles__demo mdl-typography--title">Regular 20sp</div>
        <div class="typo-styles__desc">
          <span class="typo-styles__name">title</span>
          <span class="typo-styles__weight">font weight 500</span>
        </div>
      </dd>
    </dl>
    <div class="code-with-text">
      <strong>Note</strong>: This portion is only to demonstrate header and display styles for out CSS. For more typography guidelines, please refer to the <a href="https://www.google.com/design/spec/material-design">Material Design spec</a>.
    </div>
    <div class="styles__download">
      <a class="download-btn download-btn--font" href="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B0J8hsRkk91LRjU4U1NSeXdjd1U/RobotoTTF.zip">
        <i class="material-icons">file_download</i>
        Download Roboto Font
      </a>
      <span class="download__size">1.21 MB (.zip)</span>
    </div>
    <div class="code-with-text">
      To embed Roboto into your web page, copy the code as the first element in the <code>&lt;head&gt;</code> of your HTML document.
      <pre class="language-markup"><code>&lt;link rel="stylesheet" href="http://fonts.googleapis.com/css?family=Roboto:300,400,500,700" type="text/css"&gt;</code></pre>
    </div>
  </div>

  <div class="styles__ribbon styles__ribbon--icons">
    <a href="http://google.github.io/material-design-icons/" class="ribbon__imagecontainer">
      <img src="../assets/icons.svg" class="ribbon__image">
      <div class="ribbon__caption ribbon__caption--split">
        앞으로 화살표 <i class="material-icons">미리보기 아이콘</i>
      </div>
    </a>
  </div>

  <div class="styles__content mdl-grid mdl-grid--no-spacing">
    <div class="mdl-cell mdl-cell--8-col mdl-cell--5-col-desktop left-col">
      <h3>아이콘</h3>
      <p>Material Design 아이콘는 Google Material Design 사양에 포함 된 공식 오픈 소스 아이콘입니다. 이러한 것들이 포함되어 있습니다</p>
    </div>
    <div class="mdl-cell mdl-cell--8-col mdl-cell--7-col-desktop right-col">
      <ul>
        <li>SVG 24px 및 48px에 모든 버전의 아이콘</li>
        <li>모든 아이콘이 SVG와 CSS 으로 나뉘어진다.</li>
        <li>웹 (PNG)을 대상으로하는 1x, 2x 아이콘</li>
        <li>iOS (PNG)를 타겟팅하는 1x, 2x, 3x 아이콘</li>
        <li>Hi-dpi 버전의 모든 아이콘 (hdpi, mdpi, xhdpi, xxhdpi, xxxhdpi) (PNG)</li>
      </ul>
    </div>
    <div class="mdl-cell mdl-cell--8-col mdl-cell--5-col-desktop left-col">
      <h3>시작하기</h3>
      <p>아이콘을 가져 오는 몇 가지 옵션이 있습니다.</p>
      <h3>압축 파일을 받운로드</h3>
      <p>마스터에서 모든 아이콘 중 최신버전의 안정적인 압축파일 (~ 57MB)를 가져옵니다.</p>
      <div class="styles__download">
        <a class="download-btn download-btn--icons" href="https://github.com/google/material-design-icons/releases/download/2.0.0/material-design-icons-2.0.0.zip">
          <i class="material-icons">file_download</i>
          Download
        </a>
      </div>
    </div>
    <div class="mdl-cell mdl-cell--8-col mdl-cell--7-col-desktop right-col">
      <h3>Bower</h3>
      <div class="code-with-text">
        <strong> Bower </ strong> 패키지 관리자를 사용하여 아이콘을 설치하십시오.
        <pre class="language-markup"><code>$ bower install material-design-icons --save</code></pre>
      </div>
      <h3>npm</h3>
      <div class="code-with-text">
        You can also find all the icons on <strong>npm</strong>.
        <pre class="language-markup"><code>$ npm install material-design-icons --save</code></pre>
      </div>
      <h3>사용법</h3>
      <p>포함 된 모든 index.html 파일을보고 세트에 포함 된 모든 아이콘을 미리보십시오. 프로젝트에 가장 적합한 방식으로 아이콘을 자유롭게 사용할 수 있습니다.</p>
      <h3>구조</h3>
      <p>일반적으로 아이콘 카테고리에는 여러 개의 아이콘이 포함 된 다음 디렉토리가 포함됩니다.</p>
      <ul>
        <li>1x, 2x Web</li>
        <li>1x, 2x, 3x iOS</li>
        <li>drawable hdpi, mdpi, xhdpi, xxhdpi, xxxhdpi</li>
        <li>svg</li>
      </ul>
      <p>프로젝트에 필요한 아이콘 해상도를 결정하고 복사 한 다음 사용할 아이콘을 참조하십시오.</p>
    </div>
    <div class="mdl-cell mdl-cell--8-col mdl-cell--5-col-desktop left-col">
      <h3>Spritesheets</h3>
      <p>머티리얼 디자인 아이콘에는 SVG 및 CSS Sprite가 포함되어 있습니다. 이것들은 svg-sprite와 css-sprite 아래의 sprites 디렉토리에서 찾을 수 있습니다.</p>
      <h3> CSS Sprites 사용하기</h3>
      <p>CSS Spritesheets 를 사용하려면 사용할 아이콘 카테고리에 대한 스타일 시트를 참조한 다음 MARK_UP에 아이콘 정의를 포함하십시오. 예 : css-sprite-av에서 재생 아이콘 중 하나를 사용합니다.</p>
      <p>그게 다야! 프로젝트를 배포 할 때 해당 CSS 및 SVG / PNG 파일을 게시하는 것을 잊지 마십시오.</p>
    </div>
    <div class="mdl-cell mdl-cell--8-col mdl-cell--7-col-desktop right-col">
      <div class="code-with-text">
        스타일 시트 참조 :
        <pre class="language-markup"><code>&lt;link href="css-sprite/sprite-av-black.css" rel="stylesheet"&gt;</code></pre>
      </div>
      <div class="code-with-text">
        아이콘을 배경으로 사용할 요소를 만듭니다:
        <pre class="language-markup"><code>&lt;div&gt;&lt;/div&gt;</code></pre>
      </div>
      <div class="code-with-text">
        위의 스타일 시트에서 얻을 수있는 <code> icon </ code> Spritesheets와 특정 <code> icon icon-ic_play-circle_outline_black_24dp </ code>을 참조하는 클래스를 추가하십시오.
        <pre class="language-markup"><code>&lt;div class="icon icon-ic_play-circle_outline_black_24dp"&gt;&lt;/div&gt;</code></pre>
      </div>
    </div>
    <div class="mdl-cell mdl-cell--8-col mdl-cell--5-col-desktop left-col">
      <h3>SVG Sprites 사용하기</h3>
      <p>마찬가지로 SVG Sprites를 사용하려면 아이콘 카테고리의 스타일 시트를 참조한 다음 MARK_UP에 아이콘 정의를 포함시킵니다.</p>
    </div>
    <div class="mdl-cell mdl-cell--8-col mdl-cell--7-col-desktop right-col">
      <div class="code-with-text">
        E.g: <code> svg-sprite-av </ code>에있는 재생 아이콘 중 하나를 사용하려면 스타일 시트를 참조하십시오:
        <pre class="language-markup"><code>&lt;link href="svg-sprite/svg-sprite-av.css" rel="stylesheet"&gt;</code></pre>
      </div>
      <div class="code-with-text">
        아이콘을 배경으로 사용할 요소를 만듭니다:
        <pre class="language-markup"><code>&lt;div&gt;&lt;/div&gt;</code></pre>
      </div>
      <div class="code-with-text">
        그런 다음 아이콘의 크기를 설정하십시오. 인라인 또는 클래스를 통해 수행 할 수 있습니다. 이 예제에서는 클래스를 사용합니다.
        <pre class="language-markup"><code>&lt;style&gt;
  .svg-ic_play_circle_outline_24px-dims { width: 24px; height: 24px; }
&lt;/style&gt;</code></pre>
      </div>
      <div class="code-with-text">
        Finally, set the dimension and specific ifcon <code>svg-ic_play_circle_outline_24px</code>, which you can get from the above stylesheet.
        <pre class="language-markup"><code>&lt;div class="svg-ic_play_circle_outline_24px svg-ic_play_circle_outline_24px-dims"&gt; &lt;/div&gt;</code></pre>
       </div>
      <h3>Polymer Icons</h3>
      <p>Polymer로 설정된 아이콘을 사용하려면 <strong> & lt; iron-icons & gt; -element </ strong>를 사용하여 아이콘을 사용하는 것이 좋습니다.
      <h3>License</h3>
      <p>모든 아이콘은 <strong> 기여 4.0 국제 라이센스 </ strong> 아래에 출시됩니다. </p>
    </div>
  </div>
  <div class="styles__ribbon styles__ribbon--colors">
    <a class="ribbon__imagecontainer">
      <img src="../assets/colors.svg" class="ribbon__image">
      <div class="ribbon__caption">
        색상 팔레트
      </div>
    </a>
  </div>
  <div class="styles__content mdl-grid mdl-grid--no-spacing">
    <div class="mdl-cell mdl-cell--8-col mdl-cell--5-col-desktop left-col">
      <h3>색상 팔레트</h3>
      <p>확장 색상 표를 사용하는 경우 첫 번째 색상을 앱의 기본 색상으로 사용하고 다른 색상은 악센트로 사용하십시오.</p>
      <p><strong> 모든 색상 및 접근 가능성 비율보기 </ strong> 이 기능은 컬러 배경에 흰색 또는 검정색 텍스트를 사용할 때 적절한 명암비와 알파 값에 대한 정보가 포함됩니다.<p>
      <div class="styles__download">
        <a class="download-btn download-btn--swatches" href="http://material-design.storage.googleapis.com/publish/material_v_4/material_ext_publish/0B0J8hsRkk91LSGx6b0w3WWpMQ1k/color_swatches.zip">
          <i class="material-icons">file_download</i>
          Download color swatches
        </a>
        <span class="download__size">0.02 MB (.zip)</span>
      </div>
      <div class="styles__download">
        <a class="download-btn download-btn--customizer" href="../customize/index.html">
          <i class="material-icons">arrow_forward</i>
          Try the custom CSS Theme Builder
        </a>
      </div>
    </div>
    <div class="mdl-cell mdl-cell--8-col mdl-cell--7-col-desktop right-col">
      <a href="../customize/index.html"><img class="customizer" src="../assets/customizer.png"></a>
    </div>
  </div>
