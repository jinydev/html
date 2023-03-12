# Form 응용 실습

폼 양식을 통하여 사이트 내에 `구글 검색창` 기능을 삽입할 수 있습니다.



```html
<!-- Search Google -->
<form method=get action="http://www.google.co.kr/search" target="_blank" >
  <table bgcolor="#FFFFFF">
    <tr>
      <td>
          <input type=text name=q size=25 maxlength=255 value="" /> 
          <!-- 구글 검색 입력 창 -->
          <input type=submit name=btnG value="Google 검색" /> 
          <!-- 검색 버튼 -->
      </td>
    </tr>
  </table>
</form>
<!-- Search Google -->
```

   