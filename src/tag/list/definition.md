---
layout: home
---

# 정의목록
정의 목록은 특정 용어와 그 정의를 표현할 때 사용하는 태그입니다.
> 사전적의미를 표현할때 자주 사용됩니다. 그외에는 잘 사용하지 않는 테그 입니다.

## Difinition List
`dl`테그는 정의 목록 입니다. 정의목록(Definition List)의 약자입니다.

사전처럼 용어를 설명하는 목록을 만들때 사용합니다.  
예) A는 B이다 

`<dl></dl>`테그는 `dt`테그와 `dd`테그를 감싸는 역할을 합니다.


dl은 여러개 쌍의 dt/dd를 포함할 수 있습니다.

## Definition description
`dd` 정의 설명 목록으로 출력이 됩니다. 정의설명(definition description)의 약자입니다. 용어를 설명할때 사용합니다.

* dd : 정의 설명
describes each term


```html
<dl>
    <dt>what is Web</dt>
    <dd>web is ....</dd>
    <dd>....</dd>
</dl>
```

## Definition term
`dt` 정의 용어 목록의 제목과 같이 표시됩니다. 
정의용어(definition term)의 약자 입니다. 정의되는 용어의 제목을 넣을때 사용한다.

* dt : 용어정의
defines terms 또는 name

dt /dd 는 순서대로 한개의 묽음으로 처리하여 작성을 해주어야 합니다.
dd는 한개 이상으로 반드시 같이 정의해 주어야 합니다.

```html
<dl>
    <dt>what is Web</dt>
    <dd>web is ....</dd>

    <dt>what is interner</dt>
    <dd>internet is ....</dd>
</dl>
```

