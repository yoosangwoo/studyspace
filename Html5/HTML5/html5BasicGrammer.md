# HTML5
HTML (HyperText Markup Language)은 웹페이지를 기술하기 위한 마크업 언어이다. <br>
조금 더 자세히 말하면 웹페이지의 내용(content)과 구조(structure)을 담당하는 언어로써 HTML태그를 통해 정보를 구조화하는 것이다.

<br>
HTML5는 2014년 10월 28일 확정된 차세대 웹 표준으로 아래와 같은 기능들이 추가되었다.
<br>

- 멀티미디어 (Multimedia)
<br> 플래시와 같은 플러그인의 도움없이 비디오 및 오디오 기능을 자체적으로 지원한다.
- 그래픽 (Graphics & Effects)
<br> SVG, 캔버스를 사용한 2차원 그래픽과 CSS3, WebGL을 사용한 3차원 그래픽을 지원한다.
- 통신 (Connectivity)
<br> 지금까지의 HTML은 단방향 통신만이 가능하였으나 HTML5는 서버와의 소켓 통신을 지원하므로 서버와의 양방향 통신이 가능하다.
- 디바이스 접근 (Device acess)
<br> 카메라, 동작센서 등의 하드웨어 기능을 직접적으로 제어할 수 있다.
- 오프라인 및 저장소 (Offline & Storage)
<br> 오프라인 상태에서도 애플리케이션을 동작시킬 수 있다. 이는 HTML5가 플랫폼으로서 사용될 수 있음을 의미한다.
- 시맨틱 태그 (Semantics)
<br> HTML 요소의 의미를 명확히 설명하는 시맨틱 태그를 도입하여 브라우저, 검색엔진, 개발자 모두에게 콘텐츠의 의미를 명확히 설명할 수 있다. <br>
이를 통해 HTML 요소의 의미를 명확히 해석하고 그 데이터를 활용할 수 있는 시맨틱 웹을 실현할 수 있다.
- CSS3
<br> HTML5는 CSS3를 완벽하게 지원한다.

# HTML5의 기본 문법

### 요소 (Element)
HTML 요소는 시작 태그(start tag)와 종료 태그(end tag) 그리고 태그 사이에 위치한 content로 구성된다.
<img src="https://poiemaweb.com/img/tag.png">
HTML document는 요소(Element)들의 집합으로 이루어진다.
<br>
<hr>

### 빈 요소 (Empty Element)
content를 가질 수 없는 요소를 빈 요소(Empty element of Self-Closing element)라 한다. <br>
아래의 예와 같이 빈 요소는 content가 없으며(필요가 없다) 어트리뷰트(Attribute)만을 가질 수 있다.

빈 요소 중 대표적인 요소는 아래와 같다.
- br
- hr
- img
- input
- link
- meta

<hr>

### 어트리뷰트 (Attribute)

어트리뷰트(Attribute)이란, 요소의 성질, 특징을 정의하는 명세이다. 요소는 어트리뷰트를 가질 수 있으며 어트리뷰트는 요소에 추가적 정보(예를 들어 이미지 파일의 경로, 크기 등)를 제공한다.
어트리뷰트는 시작 태그에 위치해야 하며 이름과 값의 쌍을 이룬다. (e.g. name="value")
<img src="https://poiemaweb.com/img/html-attribute.png">

````<img src="html.jpg" width="104" height="142">````

<hr>

### 글로벌 어트리뷰트

글로벌 어트리뷰트는 모든 HTML 요소가 공통으로 사용할 수 있는 어트리뷰트다. 몇몇 요소에는 효과가 적용되지 않을 수 있지만, 글로벌 어트리뷰트는 대체로 모든 요소에 사용될 수 있다.

자주 사용되는 글로벌 어트리뷰트는 아래와 같다.

- id
<br> 유일한 식별자(id)를 요소에 지정한다. 중복 지정이 불가하다.
- class
<br> 스타일시트에 정의된 class를 요소에 지정한다. 중복 지정이 가능하다.
- hidden
<br> css의 hidden과는 다르게 의미상으로도 브라우저에 노출되지 않게 된다.
- lang
<br> 지정된 요소의 언어를 지정한다. 검색엔진의 크롤링 시 웹페이지의 언어를 인식할 수 있게 한다.
- style
<br> 요소에 인라인 스타일을 지정한다.
- tabindex
<br> 사용자가 키보드로 페이지를 내비게이션 시 이동 순서를 지정한다.
- title
<br> 요소에 관한 제목을 지정한다.

<hr>

### 주석 (Comments)

주석은 주로 개발자에게 코드를 설명하기 위해 사용되며 브라우저는 주석을 화면에 표시하지 않는다.





