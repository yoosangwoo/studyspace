# 반응형을 위한 css 단위 이해하기
### %, em, rem, vw, vh

<hr>

### %
말 그대로 전체크기의 %의 크기

### em, rem
em : 상위 요소의 폰트 사이즈의 몇배인가를 정하는 
<br>
rem : 최상위 요소의 폰트 사이즈의 몇배인가를 정하는
<br>
<br>
example) 상위(최상위) 요소 폰트 사이즈가 20일때, <br>
1em = 20px;
20em = 20 * 20px = 400px;

### vw, vh
vw, vh 의  v 는 viewport (윈도우 창의 크기)
<br>
% 와 비슷하다 


### Summary
- px : 폰트의 크기를 고정시키고 싶을 때 씁니다.
- em : 앞서 적용된 폰트 크기의 배수로 적용됩니다.
- rem : em과 비슷하다. 웹 브라우저 기본크기(16px)의 배수의 입니다.
- vw : 1vw는 가로(Width)의 1/100, 너비 사이즈 변화에 따라 변합니다.
- vh : 1vh는 세로(Height)의 1/100, 높이 사이즈 변화에 따라변합니다.