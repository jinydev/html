---
layout: home
---

# HTML 폼테그

웹2.0 시대를 접어들면서 서버와의 데이터를 주고 받는 상호 관계를 가지게 됩니다.

이를 위하여 정보를 입력하고 전달하기 위해서 폼을 사용합니다.



## 입력양식 테그

form 테그
입력 양식을 만드는 기본 외각 양식을 말합니다.

input
입력값을 가지는 폼양식 입니다.



## form 테그
사용자의 입력을 받을 수 있는 폼을 작업합니다.  

### form
입력 요소들을 묽어서 서버와 상호 작용할 수 있도록 폼요소로 처리를 합니다.  



### fieldset
입력 요소들을 정보를 그룹화 하여 관리를 할때, `<fieldset></fieldset>`로 묽어서 처리 합니다.  

#### legend
fieldset의 제목을 작성할때 사용합니다.



## 입력요소 : input
가장 일반적인 데이터 입력 입니다. 

### label
입력요소에 제목을 지정할때 사용합니다.
> `for`속성을 이용하여 클릭했을때, 동일한 값의 id 요소를 자동으로 포커스 할 수 있는 장점을 가지고 있습니다.  



### input의 종류
입력되는 데이터에 따라서 다양한 타입의 필터링이 가능해 집니다.

* text
* hidden
* search
* tel
* url
* email
* password
* number
* rnge
* color
* checkbox
* radio
* datetime
* datetime-local
* date
* month
* week
* time
* button
* submit
* image
* reset



### input의 속성
입력 요소에도 속성을 통하여 다양한 설정을 지정할 수 있습니다. 지원되는 속성 설정은 다음과 같습니다.


#### readonly
#### [PlaceHolder](placeHolder)

#### autofocus
#### autocomplete
#### min, max, maxLength, step
#### require



## Select : 목록 나열하기

* select
* opion
* optgroup



### 멀티선택

multiple 속성



### selected 속성



### datalist

* datalist, option





## Textarea





## Button



## 기타

* output
* progress
* meter
* 





## 응용실습

* [폼을 이용한 구글 검색 기능 삽입](google)
