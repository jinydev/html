---
layout: home
---

# HTML head 영역

HTML은 `head`테그를 통하여 페이지의 다양한 정보를 추가합니다.



head는 다양한 문서의 정보를 담고 있습니다.



head 테그의 정보는 브라우저 화면에 출력을 하지 않지만, 문서가 어떤 정보와 동작을 추가로 필요하는지에 대한 정보를 입력합니다.


문서의 정보를 출력합니다.

## head 테그
head 영역은 `<head></head>` 테그로 감싸져 있습니다.

```html
<head> 
</head>
```
## head 내용
화면에 보이지 않는 
문서의 환경, 설정에 관련된 테그를 입력을 합니다.

* 타이틀 (title)
* 메타 (meta)
* 스타일 (style)
* 자바스크립트 (script)
* 링크 (link)
* 기본경로 (base)

## 타이틀
해더에는 문서의 제목을 제공하기 위하여 title 테그를 사용할 수 있습니다.

타이틀 테그는 head 영역안에 선언을 해주도록 합니다.

```html
<title>hello world 페이지 입니다.</title>
```

## Meta 테그



## title
페이지의 제목을 표시하는 테그 입니다.head 안에 선언을 합니다.
브라우저 상단에 페이지 타이들 제목이 출력 됩니다.

```html
<title>페이지 제목입니다.</title>
```

낭독기에서도 제일 먼저 읽어 주는 것이 타이틀 입니다.

> 주의할점
타이틀에 특수문자는 삽입하지 않습니다.

```html
<title>현재위치 - 타이틀</title>
```

순서로 지정하는 것을 추천합니다.



## 파비콘

파비콘 아이콘을 출력합니다.



```html
<lin rel="shortcut" href="/favicon.ico" />
```





## base
문서 안에서 상대 url를 사용할때 기준이 되는 url을 말합니다.
`base`테그는 하나만 존재합니다.

```html
<base href="/asserts/images">
```



## link

외부 리소스와의 관계를 명시합니다. 보통 css 스타일을 별도의 파일로 작성을 하는 경우 `link`테그를 사용합니다.

```html
<link rel="stylesheet" href="/style.css">
```



또한 파비콘을 출력할때도 link 테그를 사용합니다.





## style

css 스타일을 선언할때 사용합니다.



## script

자바스크립트의 코드를 삽입해야 하는 경우 사용합니다.



## meta

메트 테그는 SNS등에 계시될때 최적화된 데이터를 출력할 수 있도록 설정하는 정보값 입니다.









