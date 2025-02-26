# CrewDock

### 📍프로젝트 개요
프로젝트 기반 협업을 원하는 사용자들을 연결하는 플랫폼으로, 프로젝트 팀원 모집 혹은 참여를 할 수 있는 기회를 제공. 추가적으로, 프로젝트 기반 본인의 포트폴리오를 기록하여 본인의 역량을 효과적으로 제시할 수 있는 공간 제공.

### ⏲ 개발 기간
2025년 1월 7일 ~ 2025년 2월 18일 (약 40일간 진행)

### 📍ERD
<img width="621" alt="Image" src="https://github.com/user-attachments/assets/3d4a2409-f6c0-4a35-acc0-131b187d5ae8" />

### 📍흐름도 - 사용자 페이지
<img width="898" alt="스크린샷 2025-02-20 오후 3 46 13" src="https://github.com/user-attachments/assets/327f68b1-b6f9-40a9-8a76-7c5fefe05a37" />


### 📍흐름도 - 관리자 페이지
<img width="390" alt="스크린샷 2025-02-20 오후 3 46 35" src="https://github.com/user-attachments/assets/adfc4913-9f40-4742-85f6-5cd2d359c165" />


### 👥 구성원 별 파트 및 주요 기능
|구성원|맡은 파트|주요 기능|
|------|---|---|
|**장준영(팀장)**|백엔드와 프론트 시큐리티, 채팅의 백엔드, 프론트 구현,  깃액션과 도커를 이용한 CI/CD 구현, S3 설정 및 사용 메소드 구현|테스트3|
|**김민혁**|팀 프로젝트 페이지 CRUD 및 프론트, 관리자 페이지 CRUD 및 프론트, 메인 페이지 배너, 스크랩 CRUD 및 프론트|테스트3|
|**정문선**|마이페이지 백엔드 및 프론트, 포트폴리오 CRUD 및 프론트, 프로젝트 생성 백엔드 및 프론트|테스트3|
|**황예은**|게시판페이지 프로젝트 페이지 CRUD 및 프론트, 모집글 페이지 첨부파일 (프론트)|테스트3|
|**최시후**|프로젝트 이슈 페이지 CRUD 및 프론트, Full Calendar 를 사용한 마이페이지, 프로젝트 페이지 CRUD 및 프론트  |테스트3|
|**노경민**|모집글 CRUD 및 메인페이지 필터 옵션(백엔드) 모집글, 작성 모달(프론트)|테스트3|

### 📍Skills
![CrewDock Skills](https://github.com/user-attachments/assets/de795cb5-6430-4f57-82cb-45e88f5014f7)

<hr/>

### 📍클라이언트 Github 
https://github.com/wns0901/crew-dock-client

### 📍URL 규칙
- **RESTful**: 복수형 명사만 사용하기!
  - **Query String (QS)**: 어떤 자원의 모든 "조건"을 보여줌.
  - **Parameter**: 원하는 데이터의 ID값을 전달해서 해당 ID의 데이터("정보")를 보여줌.

### 📍Patch
- 요청은 **body**에 담아서 URL에 ID를 표시하지 않음.
- 단, **DELETE** 요청은 body가 없어서 URL에 ID를 표시해야 함.

### 📍커밋 메시지 컨벤션
- Struct : 빌드 업무 수정, 패키지 매니저 수정
- Feat : 새로운 기능 추가
- Fix : 버그 수정
- Docs : 문서 수정
- Style : 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우
- Refactor : 코드 리펙토링
- Test : 테스트 코드, 리펙토링 테스트 코드 추가
- Chore : 빌드 업무 수정, 패키지 매니저 수정
- Conflict: 충돌 해결
예제: Feat(#이슈번호): 커밋내용

### 📍이슈 타이틀 컨벤션
- Struct : 빌드 업무 수정, 패키지 매니저 수정
- Feat : 새로운 기능 추가
- Fix : 버그 수정
- Docs : 문서 수정
- Style : 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우
- Refactor : 코드 리펙토링
- Test : 테스트 코드, 리펙토링 테스트 코드 추가
- Chore : 빌드 업무 수정, 패키지 매니저 수정
- Conflict: 충돌 해결
예제 [Feat/Back]: 이슈 내용


### Main.
![](https://velog.velcdn.com/images/codegod/post/3682b4e3-f36b-4491-a58d-badbad670bed/image.gif)
- 관리자가 설정한 배너가 3초마다 슬라이드 되고 버튼을 통해 넘겨볼 수 있음
- 모집중인 게시글에 대하여 스크랩하는 기능으로 스크랩 이후 본인 마이페이지에서 다음과 같이 표시됨
![](https://velog.velcdn.com/images/codegod/post/0d1d1fa1-92ad-4525-919a-685f5307b6b4/image.png)


### Projects.

![](https://velog.velcdn.com/images/codegod/post/47a03449-1e92-4159-bfe1-9450eaa3dd45/image.gif)
- 프로젝트 페이지 메인에서 팀 캘린더및 공지사항을 표시함
- 이슈관리 탭을 통해 팀 이슈를 작성하고 수정할 수 있는 영역

![](https://velog.velcdn.com/images/codegod/post/8a0969bd-3f79-441b-88e4-5d8c11e7b756/image.gif)
- 깃 API를 통해 프로젝트 정보에 기입된 url 기반으로 커밋리스트, 풀리퀘스트, 이슈리스트를 표시
- 필터링을 통해 서버단, 프론트 단 레포지토리에 대하여 따로 조회 가능

![](https://velog.velcdn.com/images/codegod/post/018e315f-388a-494f-b778-fa8c1ee8e8c8/image.gif)
- 팀장 권한에 따라 프로젝트에 대한 정보 및 멤버에 대한 관리를 할 수 있는 영역

### Admin.
![](https://velog.velcdn.com/images/codegod/post/77a940cd-812f-43a0-a68d-2bff9e68f754/image.gif)
- 사용자가 사용중인 기술에 대한 통계를 표시
- 모든 항목에 대한 조회 및 수정 삭제 기능
- 새로운 스택 추가 및 배너에 대한 추가,수정,삭제,활성화 여부 업데이트

### Admin EVENT.
![](https://velog.velcdn.com/images/codegod/post/77cb0e30-245a-46e9-86f4-a80bc43b5720/image.gif)
- 관리자페이지에서 키시퀀스를 통해 커스텀 커맨드 입력시 커스텀 디자인한 LetterGlitch 표기 후 다음 주소로 이동
- 이스터에그 기능으로 타 페이지로 확대 가능하나 필요성 부족으로 인해 관리자 페이지에만 적용

[소스링크 서버](https://github.com/Minhyeok-Create/CrewDock_Server)
[소스링크 클라이언트](https://github.com/Minhyeok-Create/crew-dock-client)
[배포된 서버](http://crewdock.kro.kr/)




