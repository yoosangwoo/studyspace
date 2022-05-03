# 툴팁 Tooltip

툴팁은 Jason Frame 이 만든 jQuery.tipsy 이라는 훌륭한 플러그인에서 영감을 받아, 이미지에 의존하지 않고, 애니메이션에 CSS3 를 사용하고, title 속성을 사용하는 부분이 업데이트된 버전입니다. <br>
0 길이의 제목의 툴팁은 절대 보여지지 않습니다.

팻말 같은 것

### 정적 툴팁
4가지 옵션이 가능합니다 : 위 아래 오른쪽 왼쪽 정렬

### 4가지 방향
<button type="button" class="btn btn-default" data-toggle="tooltip" data-placement="left" title="Tooltip on left">Tooltip on left</button>

<button type="button" class="btn btn-default" data-toggle="tooltip" data-placement="top" title="Tooltip on top">Tooltip on top</button>

<button type="button" class="btn btn-default" data-toggle="tooltip" data-placement="bottom" title="Tooltip on bottom">Tooltip on bottom</button>

<button type="button" class="btn btn-default" data-toggle="tooltip" data-placement="right" title="Tooltip on right">Tooltip on right</button>

### 사용법
툴팁 플러그인은 주문에 의해 콘텐츠와 마크업을 생성합니다. 그리고 기본적으로 트리거 요소 다음에 놓여집니다.
자바스크립트로 툴팁 실행합니다.


````
$('#example').tooltip(options)
````

###마크업 (= 태그)
툴팁을 위해 필요한 마크업은 오직 툴팁을 가지고 싶은 요소에 data 속성과 title 입니다. 만들어진 툴팁의 마크업이 간단하긴 하지만, 그것은 위치가 필요합니다. (기본적으로, 플러그인에 의해 top 으로 설정됨)