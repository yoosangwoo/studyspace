# tabindex 속성값

### 양수
1부터의 숫자를 적어 탭의 순서를 지정합니다.
1이 제일 ㅁ너저 탭순서를 받습니다. 그 다음 번호들은 순번대로 처리됩니다.
탭순서를 지정하게 되면 탭의 흐름이 엉킬 수 있으므로 사용하지 않는 것이 좋을 듯합니다.

### 0
초점을 받을 수 없는 h1, div 등과 같은 요소들도 탭으로 초점을 받을 수 있도록 처리됩니다.
마크업 순서대로 탭순서를 자연스럽게 받게 처리됩니다.

### -1
a, button, input, select, textarea 와 같은 태그가 탭을 못받도록 처리합니다.

````
<html lang="ko">
    <head>
        <meta charset="UTF-8">
        <title>초점이동 테스트</title>
    </head>
    <body>
        <a href="#" tabindex="-1">링크태그</a>
        <h3 tabindex="0">제목태그</h3>
        <button tabindex="-1">버튼태그</button>
        <input type="text" tabindex="-1">
        <p tabindex="0">문단태그</p>
        <select tabindex="-1">
            <option>옵션1</option>
            <option>옵션2</option>
        </select>
        <textarea cols="30" rows="5" tabindex="-1"></textarea>
    </body>
</html>
````



