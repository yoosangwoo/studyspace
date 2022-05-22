# Structure

## 웹페이지의 레이아웃을 구성하기 위해 공간을 분할하는 태그

웹페이지의 레이아웃을 구성하기 위해서 공간을 분할한 필요가 있다.

<img src="https://poiemaweb.com/img/html-layout.png">

공간을 분할할 수 있는 태그는 div, span, table 등이 있는데, 과거에는 table 태그를 사용하여 레이아웃을 구성하기도 하였으나 모던 웹에서는 주로 div를 사용하여 레이아웃을 구성한다.

그런데 div 태그는 의미론적으로 어떠한 의미도 가지고 있지 않기 때문에 아래와 같이 HTML5에서 새롭게 추가된 시맨틱 태그를 사용하는 것이 더 나은 방법이나 IE에서 작동하지 않기 떄문에 주의가 필요하다

<table>
<tr>
<th>tag</th>
<th>Description</th>
</tr>
<tr>
<td>header</td>
<td>헤더를 의미한다</td>
</tr>
<tr>
<td>nav</td>
<td>내비게이션을 의미한다</td>
</tr>
<tr>
<td>aside</td>
<td>사이드에 위치하는 공간을 의미한다</td>
</tr>
<tr>
<td>section</td>
<td>본문의 여러 내용(article)을 포함하는 공간을 의미한다</td>
</tr>
<tr>
<td>article</td>
<td>본문의 주내용이 들어가는 공간을 의미한다</td>
</tr>
<tr>
<td>footer</td>
<td>푸터를 의미한다</td>
</tr>
</table>

<img src="https://poiemaweb.com/img/building-structure.png">

이와 같은 공간 분할 태그는 일반적으로 다른 요소를 포함하는 컨테이너 역할을 하게된다.

div 와 span의 차이는 block 레벨 요소와 inline 레벨 요소를 이해하여야 한다.

이에 대한 자세한 내용은 display 프로퍼티를 참조하기 바란다.





