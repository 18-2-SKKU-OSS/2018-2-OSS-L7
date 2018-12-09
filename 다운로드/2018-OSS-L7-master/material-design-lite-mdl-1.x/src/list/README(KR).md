## 소개
목록은 여러줄의 아이템을 하나의 연속 요소로써 수직으로 표시합니다. 내용 옵션에 대해 더 알기위해서 [Material Design
Spec](https://www.google.com/design/spec/components/lists.html)를 참고하세요.

### MDL **목록** 요소를 포함하려면:

## 기본 항목으로 목록을 만들어라.

&nbsp;1. `mdl-list` 클래스와 `<ul>` 요소를 코딩하세요 ; 이것은 "외부" 컨테이너입니다, 그것은 목록 요소의 모든것을 담고 있습니다.

```html
<ul class='mdl-list'>
</ul>
```
&nbsp;2. `mdl-list__item` 클래스에 필요한 많은 `<li>` 요소를 코딩하세요 ; 이것은 많은 **item's** 요소를 보유하기 위한 것입니다.

```html
<ul class='mdl-list'>
  <li class="mdl-list__item"></li>
  <li class="mdl-list__item"></li>
  <li class="mdl-list__item"></li>
</ul>
```

&nbsp;3. 예를 들어 적절한 콘텐츠 유형 변경 클래스를 가지는 `<li>`의 하위 항목으로 당신의 콘텐츠를 추가하세요.

```html
<ul class='mdl-list'>
  <li class="mdl-list__item">
    <span class="mdl-list__item-primary-content"></span>
  </li>
  <li class="mdl-list__item">
    <span class="mdl-list__item-primary-content"></span>
  </li>
  <li class="mdl-list__item">
    <span class="mdl-list__item-primary-content"></span>
  </li>
</ul>
```

## 구성 옵션

The MDL CSS 클래스는 미리 정의 된 다양한 시각적 개선 사항을 목록에 적용합니다. 아래의 표는 사용 가능한 클래스와 그 효과를 나열합니다.

| MDL 클래스        | 효과           | 언급  |
| ------------- |:-------------:| -----:|
| .mdl-list | 목록을 MDL 구성요소로 정의합니다. | - |
| .mdl-list__item | 목록의 항목을 정의합니다. | 필요 |
| .mdl-list__item--two-line | 목록의 항목을 두 줄로 정의합니다. | 선택적 2 줄 목록 변형 |
| .mdl-list__item--three-line | 목록의 항목을 세 줄로 정의합니다. | 선택적 3 행 목록 변형 |
| .mdl-list__item-primary-content | 기본 콘텐츠 하위 구분을 정의합니다. |-|
| .mdl-list__item-avatar | 아바타 하위 구분을 정의합니다. |-|
| .mdl-list__item-icon | 아이콘 하위 구분을 정의합니다. |-|
| .mdl-list__item-secondary-content | 보조 콘텐츠 하위 구분을 정의합니다. | 필요 `.mdl-list__item--two-line` or `.mdl-list__item--three-line` |
| .mdl-list__item-secondary-info | 정보 하위 구분을 정의합니다. | 필요 `.mdl-list__item--two-line` or `.mdl-list__item--three-line` |
| .mdl-list__item-secondary-action | 행동 하위 분류를 정의합니다. | 필요 `.mdl-list__item--two-line` or `.mdl-list__item--three-line` |
| .mdl-list__item-text-body | 텍스트 본문 하위 분류를 정의합니다. | 필요 `.mdl-list__item--three-line` |
