---
layout: home
---

# HTML 요소란?
HTML의 요소란 `태그(tag)`의 또다른 표현법 입니다.

## 태그
태그는 HTML 페이지에서 객체를 만들 때 사용하는 것입니다. 그리고 태그를 사용해 만들어진 객체를 요소라고 부릅니다. 

```html
<p>Hello World</p>
```

위의 예에서 `Hello World` 문장을 특수한 기호 `<p>`와 `</p>`로 감싸져 있는 것을 볼 수 있습니다.
이렇게 출력할 문장을 감싸고 있는 특수기호를 HTML에서는 태그라고 합니다.

### 태그의 특징
태그는 일반적으로 `시작태그`와 `종료태그`로 되어 있습니다. 하지만 일부 몇몇 태그는 종료태그가 없는 `단일 태그`도 있습니다.


### 단일태그
`<br>` 태그는 문장의 출력을 다음줄에서 시작하라는 구분 태그 입니다. 대표적으로 종료가 없는 태그 입니다. 

```html
Hwllo
<br>
World
```

예시와 같이 단일로 작성합니다.


HTML5에서는 단일태그를 사용할때 혼돈을 줄이기 위하여 `<br/>`형태로 사용을 하는 것을 권장합니다.

```html
<br/>
```
> 어떠한표기 방법을 사용해도 상관없지만 대부분의 개발지는 XHTML5 방법을선호합니다.


### 태그의 중첩
일부 태그는 태그 내부에 다른 태그를 넣을 수 있습니다. 

```html
<header>
    <h1>Hello World</h1>
</header>
```

`header` 태그 안에는 `h1` 태그를 감싸고 있습니다.

> 그는모두W3C 재단에서 미리 정해놓았습니다


## 속성
HTML 태그는 출력될 문장 또는 내용을 감싸는 형태로 가지고 있습니다. 이와 별개로 테그에 속성을 부여하여 더 많은 마크업 동작이 가능하도록 설정할 수 있습니다.

즉 속성은 태그의 추가적인 정보를 지정할때 사용합니다.

```html
<h1 title="header">Hello World</a>
```

속성은 시작태그 또는 단일테그 안에 속성명과 값을 지정합니다.

> 속성의 종류는 W3C 재단에서 표준으로 정의해 놓았습니다.


