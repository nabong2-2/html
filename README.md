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