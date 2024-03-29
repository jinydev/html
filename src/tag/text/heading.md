---
layout: home
---

# 제목 테그
html은 문서내 제목을 쉽게 표기하여 위하여 미리 사전에 정의한 테그들이 존재합니다.

html은 기본적으로 6개의 제목 테그를 지원합니다.  
> 하지만, 실제 개발에서 주로 사용되는 테그는 1~3 까지이 테그만 이용이 됩니다.

## Heading 테그
제목을 표현하는 요소를 말합니다. Heading 테그는 글자의 크기에 따라서 6가지가 있습니다.


### 글자 크기
html의 제목 테그는 `<h숫자> </h숫자>` 형태로 사용합니다. 숫자는 크게 6종류를 제공합니다.
> `H`는 `Heading`의 약자를 말합니다.

Heading 테그는 굵은 글씨로 표현이 됩니다.

문서네에서 제목을 계층적 표현합니다. h뒤에 붇는 숫자가 클수록 큰 글자에서 작은 글자 형태로 지정됩니다.
h1> h2> h3 > h4 > h5 > h6

### H1 테그
H1 요소는 `한페이지`에 `한번만 사용`하는 것을 추천합니다.

### h테그의 속성
`H`요소는 블럭 속성을 가지고 있습니다. 
h테그 안에는 `텍스트` 또는 `inline` 요소들을 포함할 수 있습니다.



## 작성문법
heading 테그를 html 문서를 만들어 봅니다.

```html
<!DOCTYPE html>
<html>
    <head> 
    </head>
    <body>
        
        <h1>Hello world</h1>
        <h2>Hello world</h2>
        <h3>Hello world</h3>
        <h4>Hello world</h4>
        <h5>Hello world</h5>
        <h6>Hello world</h6>

    </body>
</html>
```



## php 응용
php를 이용하여 6개의 h테그를 생성 출력해 봅니다.

```php
<!DOCTYPE html>
<html>
    <head> 
    </head>
    <body>
<?php 
    for ($i=1;$i<=6;$i++) {
        echo "<h".$i.">Hello world</h".$i.">";
    }
?>
    </body>
</html>
```








