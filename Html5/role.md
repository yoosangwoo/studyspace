# role 속성

role은 웹 접근성을 위해 생겨났으며 위젯, 구조 및 동작에 대한 의미 정보를 올바르게 전달하기 위해 생겼다.<br>
elements의 확장 개념을 좀 더 명확한 구조와 의미를 부여하는 역할

### role은 아래의 카테고리를 따른다.
- Abstract Roles
- Widget Roles
- Document Structure Roles
- Landmark Roles
- Live Region Roles
- Window Roles   <br>

각각의 Role 속성에 대한 의미와 종류에 대해 알아볼 것이고, role-attribute는 해당 role속성에 맞게 사용하면 된다

### Abstract Roles
일반적인 역할 개념을 정의할 목적으로 사용
- command	입력 데이터를 수신하지 않는 위젯 형식
- composite	위젯 탐색 또는 자식을 포함하는 형식
- input	사용자 입력을 허용하는 위젯형식
- range	사용자가 설정할 수 있는 값 범위
- roletype	역할이 할당 된 개체에 구조적, 기능적 목적을 설명
- sectionhead	section의 주제를 표시하거나 요악하는 구조
- section	문서 또는 응용 프로그램에서 렌더링 가능한 구조 단위
- select	사용자가 선택 항목 집합에서 선택을 할 수 있게 하는 위젯
- tructure	문서의 구조 요소
- widget	GUI 사용자 인터페이스
- window	브라우저 또는 응용 프로그램 창
  
### Widget Roles
독립형 사용자 인터페이스 위젯 또는 더 큰 복합 위젯의 일부로 작동
- button	버튼을 누르거나 사용자 트리거 동작을 허용하는 입력
- checkbox	체크가 확인 됐는지, 확인 되지 않은지, 다중 체크가 되었는지 확인하는 란
- link	내부 또는 외부 링크로 이동
- menuitem	메뉴 또는 선택 세트 옵력
- option	select 목록에서 선택 가능한 항목
- progressbar	작업의 상태를 표시하는 요소
- radio	역할이 동일한 요소 그룹의 확인 가능한 입력으로 한 번에 하나만 확인 가능
- scrollbar	내용 스크롤을 제어하는 그래픽 객체
- searchbox	검색 기준을 지정하기 위한 텍스트 상자 유형
- slider	슬리어다의 크기와 가능한 값의 현재 값가 범위를 나타냄
- switch	체크 또는 체크되지 않은 값 (on 또는 off)
- tab	탭 내용을 선택하기 위한 그룹화 레이블
- textbox	자유 형식의 텍스트를 값으로 사용할 수 있는 입력 유형
- treeitem	하나의 요소로 하위 레벨의 트리 항목 요소 그룹을 포함하는 경우 확장이나 축소 가능
- grid	하나 이상의 셀이 있는 하나 이상의 행 컬렉션을 포함하는 그룹
- listbox	사용자가 선택의 목록에서 하나 이상의 항목을 선택할 수 있음
- menu	사용자에게 선택 목록을 제공하는 위젯 유형

### Document Structure Roles
- 페이지에서 컨텐츠를 구성하는 구조를 설명
- article	문서, 페이지 또는 사이트의 독립적인 부분을 구성하는 페이지 섹션
- cell	테이블 컨테이너의 셀
- columnheader	열에 대한 헤더 정보가 들어있는 셀
- definition	용어 또는 개념의 정의
- directory	목차와 같은 그룹 구성원에 대한 참조 목록
- document	컨텐츠가 포함된 요소
- figure	그래픽 문서, 이미지, 예제 텍스트를 포함하는 인식 가능한 컨텐츠
- group	페이지 요약 또는 목차에서 포함되지 않는 일련의 사용자 인터페이스
- heading	페이지 섹션의 제목
- img	이미지를 구성하는 요소
- list	listitem을 소유하고 있는 section
- listitem	목록 또는 디렉토리 단일 항목
- row	테이블 형식 컨테이너의 셀 행
- rowgroup	테이블 형식 컨테이너에 하나 이상의 행 요소를 포함하는 구조
- rowheader	격자의 행에 대한 헤더 정보가 들어있는 셀
- table	section 데이터가 행과 열로 정렬
- term	해당 정의가 있는 단어 또는 구문
- toolbar	시각적 형태로 표현되는 기능 버튼 또는 컨트롤 모음
- tooltip	요소에 대한 설명을 표시하는 상황별 팝업

### Landmark Roles
Landmark 기본 유형에서 상속되며 각 역할 속성에서 모두 가져옴
- banner	페이지별 콘텐츠가 아닌 사이트 중심 콘텐츠를 주로 포함하는 영역
- contentinfo	상위 문서에 대한 정보를 포함한 인식이 가능한 큰 영역
- form	양식을 만들 결합, 항목 및 개체의 컬렉션을 포한한 지역
- main	문서의 주요 내용
- navigation	문서 또는 관련 문서를 탐색하기 위한 탐색 요소 모음
- region	의도한 목적에 사용자가 쉽게 섹션을 이동하고 요약된 내용을 통해 요소로 빠르게 탐색 할 수 있게 하는 역할
- search	전체, 검색 기능을 만들 결합, 항목 및 개체의 컬렉션을 포함한 지역

### Live Region Roles
라이브 영역 특성에 의해 수정
- alert	경고 메세지를 전달하여 사용자에게 경고 표시(알람)
- log	새로운 정보가 의미있는 순서로 추가되고, 오래된 정보가 사라지는 라이브 영역
- marquee	중요하지 않은 정보가 자주 변경되는 라이브 영역
- status	사용자를 위한 자문 정보를 위한 라이브 영역
- timer	시작 지점에서 경과된 시간 또는 종료 지점까지 남은 시간을 나타내는 숫자 카운터 라이브 영역

### Window Roles
브라우저 또는 응용 프로그램 내에서 창 역할을 함
- alertdialog	초기 포커싱 시, 대화 상자의 요소로 이동하는 경고 메세지가 포함된 대화 상자 유형
- dialog	웹 애플리케이션의 기본 하위 창
