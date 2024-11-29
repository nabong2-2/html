# html 
## html 기초
* 'title' 제목태그
* 'meta' 문서정보태그
* 'Markup' HTML을 의미적으로 작성한다 == 마크업
* 'Debugging' 오류 확인


## vs code 주요 단축키
* 'shift + alt + a' 블록 주석
* 'shift + ctrl + 방향키' 블록 
* 'ctrl + d' 다중 선택
* 'ctrl + \ ' 화면 분할
* 'ctrl + k 누르고 역슬래쉬 ' 밑으로 화면 분할
* 'alt+ z ' 자동 줄바꿈
* 'shift + \' = |
* tab = 문장 깔끔히



## html 기본 작성법
* '<시작태그></닫기태그>'
* '<시작태그 속성="값" 속성="값"> </>'
* '<빈태그>'


## 타이틀 작성법
* 웹 페이지 특성에 맞춰 작성해야해
* 메인 페이지 > 사이트명
* 서브 페이지 > 페이지명 | 사이트명

## HTML 공부 시 주의사항
* HTML 의미적 구조를 <!--  css 디자인 역할에 따라 HTML 공부 시 --> 시각적 형태로 공부 X 
ex) h1은 대제목이다.(0) , h1은 글자가 크고 굵다 (x)
* 

## HTMl 문장 태그
* 'h' 제목태그 - h3까지만 쓰는 게 좋음/ block
* 'p' = 단락태그 - block 
* 'br' = 줄바꿈 태그 -inline
* 'strong' = 경고 등 심각성이 있는 강조 태그 - inline/ 제목에 사용 X
* 'em' = 문맥 내 강조 표시 태그 (1순위) - inline / 제목에 사용 X
* 'blockquote' = 인용
* 'q' = 문단 내 인용/ inline
* 'sup', 'sub'= 제곱 위 아래
* 'code' = &lt 랑 같이 쓰는 거
* 'mark'= 형광펜
* '&lt', '&gt', '&copy;' = < > c
* 'hr'= 경계선
* 'address' = 자사 주소/ 연락처
* 'del' = 글자 삭제 빗금


## 하이퍼링크태그 a
* 'a 태그의 target="_blank"' 는 새창으로 띄울때만 !
* 새 창의 기준은 외부 사이트 이동 여부
* 예) 네이버 메인 -> 네이커 카페 - 같은 페이지
* 예) 네이버 메인 -> 구글 이동 - 새창으로 변경

## a태그 작성 순서
1. '<a href=""></a>'
2. '<a href="">클릭대상</a>'
3. '<a href="연결경로">클릭대상</a>'

## div 태그 작성 순서
1. '<div></div>'
1. '<div>그룹대상</div>'
1. '<div class="이름">그룹대상</div>'
상황에 따라...

## 특정 위치로 바로가기 링크
* 다른 웹 페이지가 아닌 같은 페이지 내에 다른 위치로 스크롤되는 바로가기 기능

### 바로가기링크 제작 순서
1. 클릭대상, 이동대상 먼저 제작하기 
2. 각 이동 대상의 첫번째 요소에 id 설정하기
3. 위 2번으로 이동 시 클릭해야하는 대상에 href 속성으로 #아이디명 입력하기


# css
## 디자인 속성 순서
0. (선택자 모두 작성 후)
1. 그룹 또는 큰 박스 요소에 배경색을 적용(영역 구분) <!-- 임시임 -->
* 위 배경색 지정 시 밝은 영문색상 적용(헥사코드, rgb x)
* 테스트 영문색상으로 자주 이용하는 색상 : aqua, lime, yellow 등
2. 레이아웃 위치, 크기 속성 적용
3. 글자, 이미지, 비디오 등 내용 요소들 크기, 여백, 색상 등 적용
4. 모든 속성 작업 완료 후 1번에서 적용한 임시 배경색 제거
5. 완료

## block 특징
* 화면 너비 100%를 가진다.
* 가로, 세로 크기와 여백 값을 가질 수 있다.
* 블록요소를 2개 이상 만들면 각 행으로 떨어진다.
## inline 특징
* 내용 크기만큼만 가진다.
* 가로, 세로 크기와 여백 값을 가질 수 없다.
* 강제로 여백 설정 시 요소끼리 겹침현상이 발생한다. <!-- 기억하기 -->
* 인라인요소를 2개 이상 만들면 한 줄로 처리된다. 내용이 길 경우만 자동줄바꿈.
## inline-block 특징
* 가로, 세로 크기와 여백 값을 가질 수 있다.
* 인라인요소를 2개 이상 만들면 한 줄로 처리된다.

## text-align 속성 특징 및 주의사항
* inline 또는 inline-block 요소만 수평정렬할 수 있는 속성이다.
* left, center, right 값만 적용 가능하다.
* '<h1><em>text</em></h1>' 위 태그에서
* 'h1{text-align:center}'를 적용한다면?
* 해석) h1의 자식/자손 중 인라인에 해당하는 대상을 정렬하라 
* 'em{text-align:center}'를 적용한다면? 
* 해석) em의 자식/자손 중 인라인에 해당하는 대상을 정렬하라 

##블록과 인라인 정렬
## 인라인 요소 정렬할 경우
* 정렬대상 요소가 인라인태그거나 또는 블록인데 display:inlin-block; 명령으로 인라인 특징이 적용된 경우
### 블록 요소를 가운데 정렬할 경우
* 조건 : 사용자의 디바이스 너비보다 가운데 정렬하는 대상의 크기가 작아야 함
* 이 방법은 주로 데스크탑에서 사용.
* 선행조건 : 가운데정렬요소선택자 (width:1000~1400px)
* 적용방법 : 와이드형태의 데스크탑은 사이트너비 바깥쪽 여백을 고정할 수 없기 때문에 특정 값(px, %, margin)을 입력할 수 없음
* margin: 0 auto/ width: 1000px~1400px
* 컨텐츠 너비를 가지고 있는 경우에 많이 사용함

## img 태그와 background-image css 속성 차이
* img 태그는 이미지만으로 구성된 인라인태그로 크기를 입력하지 않아도 자동으로 원본크기를 유지하며 추가적으로 모든 css 입력이 가능하다. 예) width, height, padding,  margin, border 등등...
* background-image 속성은 태그가 아닌 꾸미가 속성이기 때문에 img태그와 다르게 자동으로 원본크기가 나타나지 않으며 배경이미지가 들어간 요소의 크기 안에서만 나타난다. 또한 추가적인 css속성을 주려면 background- 로 시작하는 속성만 가능하고 그 외 속성은 모두 불가능하다.

## background 통합속성은 background적용 선택자가 1개일 때 사용한다.
## background 개별속성은 적용선택자가 2개 이상일 때(nth등 포함) 사용한다.