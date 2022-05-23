# 시맨틱 웹 (Semantic Web)

검색엔진은 로봇(Robot)이라는 프로그램을 이용해 매일 전세계의 웹사이트 정보를 수집한다.<br>
(이것을 크롤링 이라 하며 검색엔진의 크롤러가 이를 수행한다.)<br>
그리고 검색 사이트 이용자가 검색할 만한 키워드를 미리 예상하여 검색 키워드에 대응하는 인덱스(색인)을 만들어 둔다.<br>
(이것을 인덱싱이라 하며 검색엔진의 인덱서가 이를 수행한다.)

아래의 코드 1행과 2행은 브라우저에서 동일한 외형을 갖는다.
이는 h1태그의 디폴트 스타일이 1행과 같기 때문이다.

<font size="6"><b>Hello</b></font>
<h1>Hello</h1>

1행의 요소는 의미론적으로 어떤 의미도 가지고 있지않다.
그러나 2행의 요소는 header(제목) 중 가장 상위 레벨이라는 의미를 내포하고 있어서 개발자가 의도한 요소의 의미가 명확히 드러나고 있다. <br>
이것은 코드의 가독성을 높이고 유지보수를 쉽게한다.

### 즉, 시맨틱 태그란 브라우저, 검색엔진, 개발자 모두에게 콘텐츠의 의미를 명확히 설명하는 역할을 한다.

- non-semantic 요소 <br>
div, span 등이 있으며 이들 태그는 content에 대하여 어떤 설명도 하지 않는다.
- semantic 요소 <br>
form, table, img 등이 있으며 이들 태그는 content의 의미를 명확히 설명한다.

<hr>
다음은 HTML5에서 새롭게 추가된 시맨틱 태그이다.

- header : 헤더를 의미
- nav : 내비게이션을 의미
- aside : 사이드에 위치하는 공간을 의미
- section : 본문의 여러 내용(article)을 포함하는 공간을 의미
- article : 본문의 주내용이 들어가는 공간을 의미
- footer : 푸터를 의미

<img src="https://poiemaweb.com/img/building-structure.png">
