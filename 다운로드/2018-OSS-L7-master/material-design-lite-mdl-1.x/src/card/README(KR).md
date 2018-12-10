## 소개

Material Design Lite (MDL)의 **카드** 구성요소는  &mdash; 사진, 일부 텍스트 및 링크와 같은 &mdash; 하나의 주제에 관한 데이터가 포함된 가상 종이를 나타내는 사용자 인터페이스 요소입니다. 

카드는 다양한 유형의 개체로 구성된 관련 콘텐츠를 일관되게 표시하는 편리한 수단입니다. 가변 길이 캡션이 있는 사진처럼 크기나 지원되는 작업이 상당히 다를 수 있는 비슷한 개체를 표시하는 데에도 적합합니다. 카드의 내용에 따라 일정한 폭과 가변 높이가 있습니다.

카드는 사용자 인터페이스에서 상당히 새로운 기능으로, 사용자는 카드를 통해 더 복잡하고 자세한 정보에 액세스 할 수 있습니다. 카드의 디자인과 사용은 전반적인 사용자 경험에서 중요한 요소가 될 것입니다. 자세한 내용은 카드 구성 요소의 [Material Design 사양 페이지](http://www.google.com/design/spec/components/cards.html)를 참조하십시오.

### MDL **카드** 구성요소를 포함시키기 위해서는:

&nbsp;1. `<div>` 엘리먼트를 코딩하십시오; 이것은 카드의 모든 내용을 담는 "외부" 컨테이너입니다
```html
<div>
</div>
```
&nbsp;2. div 안에는 하나 이상의 "내부" div를 코딩합니다. 각 div는 원하는 내용 블록마다 하나씩 작성합니다. 제목, 이미지, 일부 텍스트 및 작업 표시 줄이 포함 된 카드에는 모든 "내부" div, 즉 모든 형제가 포함됩니다.
```html
<div>
  <div>
  ...
  </div>
  <div>
  ...
  </div>
  <div>
  ...
  </div>
  <div>
  ...
  </div>
</div>
```
&nbsp;3. `class` 속성을 사용하여 하나 이상의 MDL 클래스를 공백으로 구분하여 "외부" div와 "내부" div에 추가하십시오 (의도된 용도에 따라 다름).
```html
<div class="mdl-card">
  <div class="mdl-card__title">
  ...
  </div>
  <div class="mdl-card__media">
  ...
  </div>
  <div class="mdl-card__supporting-text">
  ...
  </div>
  <div class="mdl-card__actions">
  ...
  </div>
</div>
```
&nbsp;4. 표준 HTML 요소 및 선택적으로 추가 MDL 클래스를 사용하여 의도된 용도에 따라 각 "내부" div에 내용을 다시 추가하십시오.
```html
<div class="mdl-card">
  <div class="mdl-card__title">
    <h2 class="mdl-card__title-text">title Text Goes Here</h2>
  </div>
  <div class="mdl-card__media">
    <img src="photo.jpg" width="220" height="140" border="0" alt="" style="padding:20px;">
  </div>
  <div class="mdl-card__supporting-text">
    This text might describe the photo and provide further information, such as where and
    when it was taken.
  </div>
  <div class="mdl-card__actions">
    <a href="(URL or function)">Related Action</a>
  </div>
</div>
```

카드 구성요소를 사용할 준비가 되었습니다.

#### 예제

제목, 이미지, 텍스트 및 액션이 있는 카드 (그림자 없음)

```html
<div class="mdl-card">
  <div class="mdl-card__title">
     <h2 class="mdl-card__title-text">Auckland Sky Tower<br>Auckland, New Zealand</h2>
  </div>
  <div class="mdl-card__media">
    <img src="skytower.jpg" width="173" height="157" border="0" alt=""
     style="padding:10px;">
  </div>
  <div class="mdl-card__supporting-text">
  The Sky Tower is an observation and telecommunications tower located in Auckland,
  New Zealand. It is 328 metres (1,076 ft) tall, making it the tallest man-made structure
  in the Southern Hemisphere.
  </div>
  <div class="mdl-card__actions">
     <a href="http://en.wikipedia.org/wiki/Sky_Tower_%28Auckland%29">Wikipedia entry</a>
  </div>
</div>
```

이미지, 캡션 및 텍스트가 있는 카드 (레벨 -3 그림자) :

```html
<div class="mdl-card mdl-shadow--4dp">
  <div class="mdl-card__media"><img src="skytower.jpg" width="173" height="157" border="0"
   alt="" style="padding:10px;">
  </div>
  <div class="mdl-card__supporting-text">
    Auckland Sky Tower, taken March 24th, 2014
  </div>
  <div class="mdl-card__supporting-text">
  The Sky Tower is an observation and telecommunications tower located in Auckland,
  New Zealand. It is 328 metres (1,076 ft) tall, making it the tallest man-made structure
  in the Southern Hemisphere.
  </div>
</div>
```

## 구성 옵션

MDL CSS 클래스는 미리 정의 된 다양한 시각적 및 동작 향상 기능을 카드에 적용합니다. 아래의 표는 사용 가능한 클래스와 그 효과를 나열합니다.

| MDL 클래스 | 효과 | 비고 |
| ----------- | -------- | --------- |
| `MDL 카드` | div 요소를 MDL 카드 컨테이너로 정의합니다. | "외부" div에 필수 |
| `mdl-card-border` | 카드 섹션에 적용된 테두리를 추가합니다. | "내부" div에 사용 |
| `mdl-shadow--2dp에서 mdl-shadow--16dp 까지` | 카드에 다양한 음영 깊이 (2, 3, 4, 6, 8 또는 16)를 지정합니다. | 선택 사항, "외부" div로 이동; 생략하면 그림자가 없습니다 |
| `mdl-card__title` | div를 카드 제목 컨테이너로 정의 | "내부" 제목 div에 필수 |
| `mdl-card__title-text` | 카드 제목에 적절한 텍스트 특성 지정 | 헤드 태그 (H1 - H6) 제목 부분에 필수 |
| `mdl-card__subtitle-text` | 카드 자막에 텍스트 특성 지정 | 선택 과목. title 요소의 자식이어야 합니다. |
| `mdl-card__media` | div를 카드 미디어 컨테이너로 정의 | "내부" 미디어 부문에 필수 |
| `mdl-card__supporting-text` | div를 카드 본문 텍스트 컨테이너로 정의하고 본문 텍스트에 적절한 텍스트 특성을 지정합니다. | "내부" 본문 텍스트 div에 필요합니다. 중간에 컨테이너 없이 텍스트가 div 안에 직접 이동합니다. |
| `mdl-card__actions` | div를 카드 작업 컨테이너로 정의하고 적절한 텍스트 특성을 작업에 할당합니다. | "내부" 작업 div에 필요합니다. 내용이 컨테이너에 끼어 있지 않고 div 안에 직접 저장됩니다. |
| `mdl-card__menu` | 요소를 오른쪽 상단 메뉴 버튼으로 정의 | 선택 과목. `mdl-card` 요소의 자식이어야 합니다. |
