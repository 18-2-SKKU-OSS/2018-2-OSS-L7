## 소개

Material Design Lite (MDL)의 **배지** 구성요소는 화면상의 알림 요소입니다. 배지는 일반적으로 숫자 또는 기타 문자가 포함된 작은 원으로 구성되며 다른 객체 가까이에 나타납니다. 배지는 객체와 관련된 추가 항목이 있는 알리미와 항목이 몇 개 있는지에 대한 표시기가 될 수 있습니다.


배지를 사용하여 눈에 잘 뜨지 않는 항목에 사용자의 주의를 끌거나 주의가 필요할 수 있음을 강조 할 수 있습니다. 예를 들면 :

* "새 메시지"알림 뒤에는 읽지 않은 메시지 수를 포함하는 배지가 올 수 있습니다.
* "장바구니에 구입하지 않은 항목이 있습니다"라는 알림에는 장바구니에 있는 항목 수를 나타내는 배지가 포함될 수 있습니다.
* "토론에 참여하십시오!" 버튼에는 현재 토론에 참여중인 사용자의 수를 나타내는 배지가 있을 수 있습니다.

배지는 대부분의 상황에서 링크 근처에 위치하므로 사용자는 배지가 나타내는 추가 정보에 편리하게 액세스할 수 있습니다. 그러나 의도에 따라 배지 자체가 링크의 일부일 수도 있고 아닐 수도 있습니다.

배지는 사용자 인터페이스의 새로운 요소로 사용자에게 추가적인 관련 콘텐츠를 찾는 데 도움이 되는 시각적 단서를 제공합니다. 따라서 이들의 설계 및 사용은 전반적인 사용자 경험에서 중요한 요소입니다.

### MDL **배지** 구성요소를 포함하기 위해서는:

&nbsp;1. `<a>` (앵커 / 링크) 또는 `<span>` 요소를 코딩하십시오. 원하는 속성 및 내용을 아무거나 포함하시면 됩니다.
```html
<a href="#">This link has a badge.</a>
```
&nbsp;2. `class` 속성을 사용하여 하나 이상의 MDL 클래스를 공백으로 구분하여 요소에 추가하십시오.
```html
<a href="#" class="mdl-badge">This link has a badge.</a>
```
&nbsp;3. 배지에 `data-badge` 속성과 인용 문자열 값을 추가하십시오.
```html
<a href="#" class="mdl-badge" data-badge="5">This link has a badge.</a>
```

배지 구성요소를 사용할 준비가 되었습니다.

> **참고 :** 배지 구성 요소의 크기가 작기 때문에 'data-badge' 값은 일반적으로 1 ~ 3자를 포함해야 합니다. 3자를 초과하는 것이 오류를 일으키지는 않지만 일부 문자는 배지 바깥에 떨어져서 보기가 어렵거나 불가능할 수 있습니다. `data-badge` 속성의 값은 배지의 중앙에 있습니다.

#### 예제

링크 내의 배지.
```html
<a href="#" class="mdl-badge" data-badge="7">This link contains a badge.</a>
```

링크에 포함되지 않았지만 근처에 있는 배지.
```html
<a href="#">This link is followed by a badge.</a>
<span class="mdl-badge" data-badge="12"></span>
```

배지 안쪽에 너무 많은 글자가 있는 링크 내부 배지.
```html
<a href="#" class="mdl-badge" data-badge="123456789">
This badge has too many characters.</a>
```

배지 배경색이 없는 링크 내부 배지.
```html
<a href="#" class="mdl-badge mdl-badge--no-background" data-badge="123">
This badge has no background color.</a>
```

## 구성 옵션

MDL CSS 클래스는 미리 정의된 다양한 시각적 개선 효과를 배지에 적용합니다. 아래의 표는 사용 가능한 클래스와 그 효과를 나열합니다.

| MDL 클래스 | 효과 | 비고 |
|-----------|--------|---------|
| `mdl-badge` | 배지를 MDL 구성요소로 정의합니다 | 스팬 또는 링크 필요 |
| `mdl-badge--no-background` | 배지에 open-circle 효과 적용 | 옵션 |
| `mdl-badge--overlap` | 배지와 컨테이너를 겹치게 함 | 옵션 |
| `data-badge="value"` | 배지에 문자열 값 할당 | 클래스가 아니라 별도의 속성. 스팬 또는 링크 필요 |
