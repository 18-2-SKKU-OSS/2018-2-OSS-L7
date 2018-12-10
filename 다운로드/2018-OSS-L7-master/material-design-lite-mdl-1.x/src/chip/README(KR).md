## 소개

The Material Design Lite (MDL) **칩** 구성요소는 작고 대화형  요소입니다.
칩은 연락, 텍스트, 규칙, 아이콘 및 사진에 일반적으로 사용됩니다.

## MDL 칩 구성 요소를 포함하려면:

&nbsp;1. 칩을 위한 컨테이너 요소를 생성하십시오; 일반적으로 `<span>` 와 `<div>`가 사용되지만 모든 컨테이너 요소가 동일하게 작동합니다. 상호 작용이 필요한 경우, `<button>`을 사용하거나, `tabindex` 속성을 컨테이너에 추가하세요.

```html
<span>
</span>
```

&nbsp;2. 텍스트 래퍼와 MDL 클래스를 추가하십시오.

```html
<span class="mdl-chip">
    <span class="mdl-chip__text">Chip Text</span>
</span>
```

&nbsp;3. 삭제 가능한 칩의 경우, 삭제 아이콘을 추가하십시오. 이 태그는 `<a>`, `<button>`이거나 `<span>`과 같은 비대화형 태그일 수 있습니다.

```html
<span class="mdl-chip">
    <span class="mdl-chip__text">Chip Text</span>
    <a href="#" class="mdl-chip__action"><i class="material-icons">cancel</i></a>
</span>
```

&nbsp;4. 콘택트 칩은 콘택트 아이콘을 가지는 다른 컨테이너를 따라 컨테이너에 추가된 `mdl-chip--contact` 클래스를 가질 필요가 있다. 사진의 아이콘 컨테이너는 일반적으로 `<img>`태그이지만 다른 콘텐트 유형은 약간의 추가된 부가 css와 함께 이용될 수 있다.

```html
<span class="mdl-chip">
    <span class="mdl-chip__contact mdl-color--teal mdl-color-text--white">A</span>
    <span class="mdl-chip__text">Chip Text</span>
    <a href="#" class="mdl-chip__action"><i class="material-icons">cancel</i></a>
</span>
```

## 예제

콘택트 이미지가 `background-image`와 함께 `<span>`인 콘택트 칩 기반의 버튼

```html
<style>
    .demo-chip .mdl-chip__contact {
        background-image: url("./path/to/image");
        background-size: cover;
    }
</style>

<button class="mdl-chip demo-chip">
    <span class="mdl-chip__contact">&nbsp;</span>
    <span class="mdl-chip__text">Chip Text</span>
    <a href="#" class="mdl-chip__action"><i class="material-icons">cancel</i></a>
</button>
```

## CSS 클래스

| MDL 클래스 | 효과 | 비고 |
|-----------|--------|---------|
| `mdl-chip` | 요소를 MDL 칩 컨테이너로 정의 | "외부" 컨테이너에 필요함 |
| `mdl-chip--contact` | MDL 칩을 콘택트 스타일 칩으로 정의 | 선택 사항, "외부" 컨테이너로 이동합니다 |
| `mdl-chip__text` | 요소를 칩의 텍스트로 정의 | 	"내부" 텍스트 컨테이너에 필요 |
| `mdl-chip__action` | 요소를 칩의 동작으로 정의 | "내부" 동작 컨테이너가 있는 경우 필수입니다 |
| `mdl-chip__contact` | 요소를 칩의 콘택트 컨테이너로 정의 | `mdl-chip--contact` 클래스가 "외부" 컨테이너에있는 경우 "내부" 컨택 컨테이너에 필요합니다 |