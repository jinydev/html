---
layout: home
---

# 웹 페이지 구축을 HTML 마스터하기

## 01.[HTML 소개](basic)
HTML(Hypertext Markup Language)은 월드 와이드 웹용 웹 페이지 및 애플리케이션을 만드는 데 사용되는 표준 마크업 언어입니다.  

### 웹의 역사
* [웹의 탄생](/basic/history)

### 웹문서
* [웹문서 HTML](/basic/doc)
* [HTML 표준 및 버전](/basic/standard)

## 02.[개발 환경 설정](/setup)
실습을 위한 브라우저와 코드 편집기를 설치합니다. 또한, 작성한 HTML 코드를 실행해 볼 수 있는 확장 기능들에 대해서 알아보도록 합니다.

### 브라우저
웹 브라우저는 World Wide Web의 웹 사이트 및 기타 온라인 콘텐츠에 액세스, 표시 및 상호 작용하는 데 사용되는 소프트웨어 응용 프로그램입니다.

* [브라우저 종류 및 도구](/setup/browser)

### 에디터 선택
* [편집기 구성](/setup/editor)
* 편집기의 종류
* [VSCode](/setup/editor/vscode)
    * [확장 패키지](/setup/editor/vscode_extension)

### 실습준비
HTML 작성 및 실습을 하기 위해서는 브라우저와 코드편집기가 필요로 합니다.

* 브라우저 설치 : 크롬
  > 크롬 브라우저는 최신의 HTML/CSS 스팩을 지원하고 있습니다. 또한, 다양한 개발자 도구가 지원 되기 때문에, 개발자에게 선호되는 브라우저 입니다. 

* 편집기: vscode
  > html 코드를 작성하기 위한 텍스트 편집기 입니다.

* 웹서버 : 라이브서버
  > vs코드의 확장 기능을 통하여 간단한 웹서버를 구동해 봅니다.

* 운영하기 : 클라우드
  > 실제로 웹사이트를 운영하기 위해서는 클라우드와 같은 외부의 서버가 필요로 합니다. 또한 이를 접속하여 관리할 수 있는 몇개의 도구들이 더 필요로 합니다.


## 03.[HTML 문서 구조와 구문](/html)
HTML 문서란 무엇이고, 어떻게 작성을 하는지에 대해서 알아 보도록 합니다.

### 03-1.무작정 따라하기
먼저 브라우저에 hello를 출력하는 문서를 만들어 봅니다
* [Hello World 만들어 보기](/html/hello)

### 03-2.문서구조
HTML 문서 구조에 대해서 알아 봅니다.
* [마크업이란](/html/markup)

HTML 문서의 3가지 영역
* [html](/html/structure)
* [head](/html/structure/head)
* [body](/html/structure/body)

해석하지 않는 주석코드 영역
* [주석](/html/comment)

### 03-3.코드작성
Emmet은 개발자가 일반적인 코드 패턴에 대한 약어를 사용하여 코드를 더 빠르고 효율적으로 작성할 수 있도록 하는 HTML 및 기타 웹 코드 작성을 위한 속기 구문입니다.  
* [emmet](/html/emmet)

### 03-4.HTML문서
HTML 문서는 `UTF-8(BOM)` 형식의 텍스트 문서로 작성합니다.
* [html 문서란](/html)
* [파일명과 확장자](/html/extention)
* [작성규칙](/html/style)

### 03-5.HTML 태그 및 요소 이해
본격적으로 HTML 문서 작성법을 학습하기 위해서는 몇가지 용어에 대해서 알아 두어야 합니다. HTML을 배우다 보면 `태그`, `속성`이라는 이야기를 많이 들어 봅니다. 이를 다른 말로 `요소`라고도 이야기를 합니다. HTML 요소란 무엇인지에 대하여 학습해 보도록 하겠습니다.

* [요소란?](/html/element)
* [테그란?](/html/element#tag)
* 속성 사용
* [속성이란?](/html/element#attr)


### [중첩 요소](/html/nested)
HTML에서 중첩 요소는 다른 요소 내에 포함된 요소입니다.


## 04.기본 [HTML 요소](/tag)
본격적인 HTML 테그에 대해서 학습해 보도록 합니다.

### 텍스트
* [제목 만들기](/tag/text/heading)
* [단락 작업](/tag/text/paragraph)
* [br](/tag/text/br)
* [hr](/tag/text/hr)
* [entity](/tag/text/entity)
* [ruby](/tag/text/ruby)
* [폰트](/tag/text/fontshape)

### 목록 만들기
* [ul](/tag/text/list)
* [ol](/tag/text/list)

### 하이퍼링크 요소
* [링크](/tag/text/link)

### 이미지
웹 페이지에 이미지를 삽입합니다.

* [img](/tag/image)
* figure : 캡션대상 지정하기
* figcaption
* [picture](/tag/image/picture)

### 백터 그래픽 SVG
* [svg](/tag/svg)

## 05.시맨틱 HTML5
시만텍 테그는 HTML 5.x에 도입된 기능으로, 문서를 해석할때 표현을 명백히 하기 위한 테그들 입니다.

### 05-1.[시맨틱이란](/semantic)
* [HTML5의 문서 구조](/semantic/html5)
* [웹 브라우저 버젼 고려하기](/semantic/ver)

### 05-2.[시맨틱 태그](/semantic/tag)
* 레이아웃을 위한 HML5 시맨틱 태그들
* 의미 있는 마크업 만들기

## 06.[HTML 양식](/form)
입력 양식은 시용자에게 입력받는 공간을 의미합니다. 웹2.0 시대를 접어들면서 서버와의 데이터를 주고 받는 상호 관계를 가지게 됩니다. 이를 위하여 정보를 입력하고 전달하기 위해서 폼을 사용합니다.


* form 테그

* 입력요소 : input

* Select : 목록 나열하기

*  Textarea

*  Button

* 기타

* 양식 만들기
* 입력 유형 및 속성
* 양식 확인

## 07.[HTML 표](/table)

### 07-1.테이블 구조
* [테이블 생성](/table)
* [테이블 요소](/table) 
* [테이블 속성](/table/attr)

### 07-2.테이블 병합
* [셀 병합](/table/merge)

### 07-3.테이블 서식 및 스타일 지정 
* [스타일](/table/style)

## 08.[레이아웃](/layout)
현대 웹 페이지는 공간 분할 태그를 서용­하여 웹 페이지의 레이아웃을 설계합니다.  

### 08-1.[레이아웃이란?](/layout)

### 08-2.공간 분할 태그
가장 대표적인 공간 분할 태그는 `div` 태그입니다.
* [div](/layout/div)

### 08-3.[아이프레임](/layout/iframe)


## 09.HTML5

### 09-1.새로운 HTML5 요소

### 09-2.[멀티미디어](multimedia)
html5에서 다양한 멀티미디어 테그를 지원합니다.
* embed
* object, param

### 09-3.오디오 태그
오디오 태그는 웹 브라우저에서 플러그인의 도움 없이 음악을 재생할 수 있게 만들어주는 HTML5 
태그입니다. 
* audio

### 09-4.비디오 태그
비디오 태그는 웹 페이지에서 동영상을 볼 수 있게 만들어줍니다.
* video
* track : 동영상 화면에 자막 추가하기

### 09-5.캔버스 요소

### 09-6.로컬 스토리지

## 10.접근성
* [접근성 이해](/basic/accessibility)
* 접근 가능한 마크업 만들기
* ARIA 역할 및 속성

## 11.SEO 기본 사항
* 검색엔진최적화의 이해
* SEO 친화적인 마크업 생성
* 메타 태그 및 설명

## 12.반응형 웹 디자인
* RWD 소개
* 미디어 쿼리 사용
* 모바일 우선 디자인
* 프레임워크와 라이브러리

## 13.웹 표준 및 모범 사례
* 유효한 HTML 작성
* 웹 표준 및 검증
* 웹 개발 모범 사례


## 포트폴리오
* 추가 리소스 및 학습 기회
* 포트폴리오 만들기
* 개인 웹사이트 또는 블로그 만들기.

## CSS 디자인 적용
초창기 웹은 단순한 정보의 전달만을 목적으로 했습니다. 기존에 HTML 문서 마크업 만으로도 충분한 정보를 전달 할 수 있었으나, 최근에는 UI를 고려하여 보기 좋은 화면을 꾸며 표시를 하는 것이 더욱더 중요해 졌습니다.  

HTML도 UI를 꾸밀수 있는 몇개의 태그와 속성들을 가지고 있지만, 이는 충분하지 않습니다. 과거에는 이러한 UI 디자인인을 작은 이미지들을 중간에 삽입을 하면서 해결을 하였지만, 이제는 CSS를 통하여 UI의 화면을 꾸며지게 되어 있습니다. 이제는 HTML 과 CSS는 하나의 세트로 같이 학습하여 웹사이트를 만드는 것이 추세입니다. CSS 학습은 별도의 사이트로 정리해 두었습니다. [css 학습하기](css.jiny.dev)

## DOM 요소와 제어하기
[javascript 학습하기](javascript.jiny.dev)


## 참고도서
본 사이트는 HTML에 대한 간단한 정보들만을 요약하였습니다. 보다 더 상세한 HTML학습을 위해서는 다음과 같은 참고 도서를 이용하여 깊이있는 학습을 하는 것이 좋습니다.

* 모던웹을 위한 HTML5 + CSS3 바이블 3판(한빛미디어)  
[유튜브 동영상](https://www.youtube.com/playlist?list=PLBXuLgInP-5kgzJZRGhpHZINPu-K90jbM)

* Do it! HTML5 + CSS (이지스퍼블리싱)  
[유튜브 동영상](https://www.youtube.com/playlist?list=PLG7te9eYUi7uvROuVChYgAL5pMK7gnWSp)

* T아카데미 : HTML5 + CSS  
[유튜브 동영상](https://www.youtube.com/playlist?list=PL9mhQYIlKEhdTdvqzohqVs3RTVHzWPu79)

* [W3schools](https://www.w3schools.com/html/default.asp)
