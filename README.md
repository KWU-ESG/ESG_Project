# LOVESG

알기쉬운 ESG 정보 제공 및 사용자 관심 키워드를 통한 맞춤 기업 추천 웹 서비스  
<br><br>

## 😘 커밋 기록

### 1️⃣ 7/29

- 현재까지 구현된 피그마를 구현한 첫번째 데모버전

### 2️⃣ 8/10

#### 수정 사항

1. src 폴더 구조 수정
2. 삽입되는 이미지의 변경
3. 피그마 수정에 따른 컴포넌트 수정
4. 로그인 폼 수정
5. 헤더 변경

#### 추가적인 학습 내용

- Postman을 이용하여 서버와의 통신 연결 학습
- JavaScript와 React의 이벤트 및 이벤트 처리 과정

### 3️⃣ 8/14

#### 수정 사항

- 프로젝트의 폴더 구조 수정
- postman을 통하여 서버와의 통신 테스트
- 로그인 버튼을 누를 시에 postman의 데이터를 가져와 id, password 정보 비교
- 각각에 맞는 알림창 출력

#### 추가적인 학습 내용

- post 방식에 대한 학습
- post를 통하여 회원가입 내용을 서버로 전송하는 방법

### 3️⃣ 8/16

#### 수정 사항

- post 방법 테스트
- jsonplaceholder에 post 성공 유무 확인

#### 추가적인 학습 내용

- 회원가입 내용이 서버에 존재하는지 확인
- redux 학습

### 4️⃣ 8/24

#### 수정 사항

- Login 코드 수정 및 test (XAMPP db 이용한 post)
- SignIn 코드 수정 및 test (XAMPP db 이용한 post)
- LoginValidation.js 생성, 로그인 입력 제약 조건 생성
- SignInValidation.js 생성, 회원가입 입력 제약 조건 생성

### 5️⃣ 9/2

#### 수정 사항

- MainPage 내부 컴포넌트 쪼개기, 디자인 변경
- style 폴더 생성하여 폴더 구조 재정비
- S-dot naming 사용하여 각각의 스타일을 별도 파일로 관리
- 반응형을 위해 rem 단위 적용
- [노션](https://www.notion.so/chaerim0626/PR-2-5c90bf113d1a42b0b452af98a0b09147) 참조

### 6️⃣ 9/4

#### 수정 사항

- 화면 크기 조절 시, 깨지는 UI 수정
- 모바일 미디어쿼리 480px로 수정
- [노션](https://www.notion.so/chaerim0626/PR-3-cd8e7d20fcae4c8dbac01a5b809020c0) 참조
### 7️⃣ 9/5

#### 수정 사항

- 버튼, 폼 디자인 수정
- 로그인 페이지 하단 체크박스 및 비밀번호 찾기 문구 생성
- Banner 하단 여백 수정
- 노션 추후 업데이트

### 8️⃣ 9/16

#### 수정 사항

- ErrorPage의 grid 디자인 수정
- IntroducePage grid 디자인 수정
- IntroducePage 상단 텍스트 추가
- 화면 크기가 줄어들었을 때 사진 비율이 깨지는 현상 수정
- 한 줄에 나타나는 사진의 개수를 줄어들도록 수정 
### 9️⃣ 9/19

#### 수정 사항

- LearningPage 수정
- 개념, 중요성, 퀴즈 각각의 페이지를 Route와 Outlet을 통해 구현
- 반응형에 맞게 Sidebar 위치 수정
### 9/19

#### 수정 사항

- SideMain.js 레이아웃 생성
- 기존의 LearningPage의 레이아웃을 포럼에도 사용하기 위해 별도로 레이아웃 파일 생성
- props.children을 사용하여 Sidebar 구현
- Outlet을 사용하여 Main 구현
### 9/26

#### 수정 사항

- ForumPage 제작
- 데이터 배열에서 정보를 가져와 화면에 흩뿌리기
- Sidebar 메뉴 선택 시 보여지는 화면 구현 필요
- 카드 클릭시 보여지는 화면 구현 필요