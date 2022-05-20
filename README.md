# coinbuying

완성된 GIF 파일 및 배포 링크 :
+ 

프로젝트 실행 방법 :
+ 

사용한 스택 목록 : 
+ spring webflux
+ MSA(Spring cloud)
+ Mysql
+ AWS
+ JS

구현한 기능 목록 (Software Requirement Specification) :
+ 일반회원은 회원가입을 할 수 있다
+ 일반회원은 가입된 아이디와 비밀번호로 로그인 할 수 있다
+ 일반회원은 로그아웃 할 수 있다
+ 일반회원은 개인정보를 변경할 수 있다
+ 관리자는 특정회원을 조회할 수 있다
+ 관리자는 공지사항/리포트에 게시글을 등록/수정/숨김 할 수 있다. (타이틀/ 컨텐츠)
+ 관리자는 게시판에 게시글 작성시 파일업로드(pdf)가 가능하다.
+ 관리자와 일반회원은 공지사항/리포트 게시글을 조회 할 수 있다.
+ 관리자와 일반회원은 공지사항/리포트의 파일 다운로드가 가능하다.
+ 게시글 조회 시 게시글 조회 수가 카운트 된다. ( 관리자는 카운트되지 않는다.)
+ 조회수를 기준으로 인기글 10개 조회 목록이 있다.
+ 보유자산 조회할 수 있다
+ 자산을 파이차트로 표시하여 준다

구현 방법 및 구현하면서 어려웠던 점 
+ 자산 조회기능을 구현할때 Flux 두개를 합치는 방법에 어려움을 느꼈습니다.
+ CORS를 WebFlux로 처리하는데 많이 어려움을 겪었습니다.
+ 팀원의 변동이 있었고 짧은 시간 안에 미숙한 스택으로 퇴근 후 온라인으로 개발하는 과정이 힘들었습니다.
+ 서버 개발량에 비해 프론트 개발작업이 많은데 공수가 부족했던 점이 어렵게 느껴졌습니다.
