## 소개

Material Design Lite (MDL)의 **button** 구성요소는 표준 HTML `<button>` 요소의 향상된 버전입니다. 버튼은 사용자가 클릭하거나 터치 할 때 발생할 동작을 명확하게 전달하는 텍스트 와 / 또는 이미지로 구성됩니다. MDL 버튼 구성요소는 다양한 유형의 버튼을 제공하며 표시 및 클릭 효과를 모두 추가 할 수 있습니다.

버튼은 사이트의 내용이나 기능에 관계없이 대부분의 사용자 인터페이스의 유비쿼터스 기능입니다. 따라서 이들의 설계 및 사용은 전반적인 사용자 경험에서 중요한 요소입니다. 자세한 내용은 버튼 구성 요소의 [Material Design 상세 페이지](http://www.google.com/design/spec/components/buttons.html)를 참조하십시오.

사용할 수 있는 버튼 표시 유형은 *flat* (기본값), *raised*, *fab*, *mini-fab* 및 *icon*입니다. 이러한 유형은 일반 (밝은 회색) 또는 *colored* 일 수 있으며 처음부터 또는 프로그래밍적으로 *disabled* 될 수 있습니다. *fab*, *mini-fab* 및 *icon* 단추 유형은 일반적으로 텍스트가 아닌 캡션으로 작은 이미지를 사용합니다.

### MDL **button** 구성요소 포함시키기:

&nbsp;1. `<button>`요소를 작성하십시오. ID 또는 이벤트 핸들러와 같은 원하는 속성 및 값을 포함하고 적절한 텍스트 캡션 또는 이미지를 추가하십시오.
```html
<button>Save</button>
```
&nbsp;2. 'class` 속성을 사용하여 하나 이상의 MDL 클래스를 공백으로 구분하여 버튼에 추가하십시오.
```html
<button class="mdl-button mdl-js-button mdl-button--raised">Save</button>
```

버튼 구성요소를 사용할 준비가 되었습니다.

#### 예제

"raised" 효과 버튼
```html
<button class="mdl-button mdl-js-button mdl-button--raised">Save</button>
```

"fab" 효과 버튼
```html
<button class="mdl-button mdl-js-button mdl-button--fab">OK</button>
```

"icon"과 "colored" 효과 버튼
```html
<button class="mdl-button mdl-js-button mdl-button--icon mdl-button--colored">?</button>
```

## 구성 옵션

MDL CSS 클래스는 미리 정의 된 다양한 시각 및 동작 효과 향상 기능을 버튼에 적용합니다. 아래의 표는 사용 가능한 클래스와 그 효과를 나열합니다.

| MDL 클래스 | 효과 | 비고 |
| ----------- | -------- | --------- |
| `mdl-button` | 버튼을 MDL 구성 요소로 정의 | 필수 |
| `mdl-js-button` | 기본 MDL 동작을 버튼에 할당 | 필수 |
| (없음) | *flat* 디스플레이 효과를 버튼에 적용합니다 (기본값) |  |
| `mdl-button-raised` | *raised* 표시 효과 적용 | *fab*, *mini-fab* 및 *icon*과 상호 배타적입니다. |
| `mdl-button-fab` | *fab* (원형) 디스플레이 효과 적용 | *raised*, *mini-fab* 및 *icon*과 상호 배타적입니다. |
| `mdl-button - mini-fab` | *mini-fab* (소형 fab 원형) 디스플레이 효과 적용 | *raised*, *fab* 및 *icon*과 상호 배타적입니다. |
| `mdl-button-icon` | *icon* (작은 일반 원형) 표시 효과 적용 | *raised*, *fab* 및 *mini-fab*와 상호 배타적입니다. |
| `mdl-button-colored` | *colored* 표시 효과를 적용합니다 (버튼 유형에 따라 기본 색상이나 강조 색상). 색깔은 `material.min.css`에 정의되어 있습니다. |
| `mdl-button-primary` | *primary* 색상 표시 효과 적용 색깔은 `material.min.css`에 정의되어 있습니다. |
| `mdl-button-accent` | *accent* 색상 표시 효과 적용 | 색깔은 `material.min.css`에 정의되어 있습니다. |
| `mdl-js-ripple-effect` | *ripple* 클릭 효과 적용 | 다른 클래스와 함께 사용할 수 있습니다 |

>**참고:** 사용 가능한 모든 버튼 유형의 비활성화 된 버전이 제공되며 표준 HTML boolean 속성 `disabled`를 사용하여 호출됩니다. `<button class="mdl-button mdl-js-button mdl-button--raised mdl-js-ripple-effect" disabled>Raised Ripples Disabled</button>`. `mdl-button-disabled` 클래스를 같은 스타일을 얻기 위해 대신 사용할 수 있지만 이 클래스의 경우 요소의 기능을 비활성화 하지는 않습니다.
>이 속성은 스크립팅을 통해 프로그래밍 방식으로 추가되거나 제거 될 수 있습니다.
