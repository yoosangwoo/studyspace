# 텍스트 관련 태그

### 1. 제목(Headings) 태그
Heading 태그는 제목을 나타낼 때 사용하며 h1에서 h6까지의 태그가 있다.<br>
h1이 가장 중요한 제목을 의미하며 글자의 크기도 가장 크다.<br>

시맨틱 웹의 의미를 살려서 제목 이외에는 사용하지 않는것이 좋다.<br>
검색엔진은 제목 태그를 중요한 의미로 받아들일 가능성이 크다.


### 2. 글자 형태 (Text Formatting) 태그

2.1 b <br>
bold체를 지정한다. 제목 태그와 같이 의미론적(Semantic) 중요성의 의미는 없다.

2.2 strong <br>
b 태그와 동일하게 bold체를 지정한다. 하지만 의미론적(Semantic) 중요성의 의미를 갖는다.<br>
표현되는 외양은 b 태그와 동일하지만 웹 표준을 준수하고자 한다면 strong을 사용하는 것이 바람직하다.

2.3 i
Italic체를 지정한다. 의미론적(Semantic) 중요성의 의미는 없다.

2.4 em
emphasized(강조, 중요한) text를 지정한다. i 태그와 동일하기 Italic체로 표현된다. 의미론적(Semantic) 중요성의 의미를 갖는다.

2.5 small
small text를 지정한다

2.6 mark
highlighted text를 지정한다.

2.7 del
deleted (removed) text를 지정한다.

2.8 ins
inserted (added) text를 지정한다.

2.9 sub / sup
sub 태그는 subscripted (아래에 쓰인) text를 sup 태그는 superscripted (위에 쓰인) text를 지정한다



### 3. 본문 태그

3.1 p
단란 (Paragraphs)을 지정한다.

3.2 br
br 태그는 (강제)개행 (line break)을 지정한다. br 태그는 빈 요소(empty element)로 종료 태그가 없다.<br>
html에서는 1개 이상의 연속된 공백(space)을 삽입하여도 1개의 공백으로 표시된다.<br>
1개 이상의 연속된 줄바꿈(enter)도 1개의 공백으로 표시된다.

3.3 pre
형식화된 (preformatted) text를 지정한다. pre 태그 내의 content는 작성된 그대로 브라우저에 표시된다.

3.4 hr
수평줄을 삽입한다.

3.5 q
짧은 인용문(quotation)을 지정한다. 브라우저는 인용부호(큰 따욤표/ quotation marks)로 q요소를 감싼다.

3.6 blockquote
긴 인용문 블록을 지정한다. 브라우저는 blockquote요소를 들여쓰기한다. css를 이용하여 다양한 style을 적용할 수 있다.
