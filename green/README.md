메인페이지 레이아웃 및 jquery 실습
[그린재단 메인페이지 SCM]
Software Configuration Management
형상관리 = 버전관리

1. 작업자 : 박지후
2. 작업일 : 2020년 07월 16일 (18:09)
3. 작업내용
1) 메인페이지 html 작업
2) 해당 css 작업
3) javascript jquery 이미지슬라이드쇼 드롭다운 메뉴

4. 작업 보완 정리
1) JS
(1) 이미지슬라이드쇼 보완
(2) 모달윈도우레이어팝업 구현
2)추가 작업 대상 기획
(1) 회원가입
(2) 로그인
(3) 계정 정보 수정
(4) 회원 탈퇴
(5) 휴면처리
(6) 게시판 글쓰기
(7) 반응형 웹 구현 

$slider.find('.s').first()
$secondSlide = $slider.find('.s').eq(1)
.find -> 선택한 요소의 자식 요소를 모두 선택한다.
 이때, 선택자를 인수로 전달하여, 전달받은 선택자에 해당하는
자식 요소만을 선택할 수도 있다.
.eq() -> 선택한 요소 중에서 전달받은 인덱스에 해당하는 요소를 선택함.
.first() -> 선택한 요소 중에서 첫 번째 요소를 선택함.
.last() -> 선택한 요소 중에서 마지막 요소를 선택함.
