# WalkingMate

> 나의 일상 속 워킹 메이트  
> 한이음 드림업(ICT 멘토링) 프로젝트  
> 진행 기간: 2024.04.01 ~ 2024.10.31

WalkingMate는 걷기 기록, 메이트 모집, 피드, 채팅을 한 앱에서 제공하는 Android 서비스입니다.

## 주요 기능
- 산책 기록(거리/시간/경로)
- 메이트 모집 글 작성 및 신청/수락 관리
- 피드 업로드 및 조회
- 1:1 및 그룹 채팅
- 지도 기반 경로 표시
- 음악 추천/재생 기능

## 화면 및 기능 설명
### 인증
로그인/회원가입과 네이버 간편 로그인을 통해 빠르게 앱에 진입합니다.

| 화면 | 설명 | 캡처 |
|---|---|---|
| 로그인 화면 | 일반 로그인, 회원가입 이동, 네이버 간편 로그인을 제공하는 시작 화면 | <img src="./assets/screens/login-screen.jpg" width="130" /> |
| 회원가입 화면 | 아이디/비밀번호/연령대/성별을 입력해 계정을 생성하는 화면 | <img src="./assets/screens/signup-screen.jpg" width="130" /> |

### 메인 탭
홈, 게시판, 기록, 채팅/랭킹 탭으로 핵심 기능을 빠르게 탐색합니다.

| 화면 | 설명 | 캡처 |
|---|---|---|
| 워킹 홈 대시보드 | 오늘의 걸음 수, 목표, 포인트/칼로리, 주간 캘린더를 확인하는 메인 화면 | <img src="./assets/screens/screen01.jpg" width="130" /> |
| 메이트 게시판 목록 | 모집글 조회, 검색/필터, 페이징, 글 작성 진입을 제공하는 게시판 화면 | <img src="./assets/screens/screen02.jpg" width="130" /> |
| 기록 캘린더 | 날짜별 산책 기록 확인과 기록 조회/작성 진입을 제공하는 캘린더 화면 | <img src="./assets/screens/screen03.jpg" width="130" /> |
| 채팅 탭 | 참여 중인 채팅방 목록을 확인하고 대화방으로 이동하는 화면 | <img src="./assets/screens/screen04.jpg" width="130" /> |
| 랭킹 탭 | 주간 걸음 수 기준 사용자 랭킹을 확인하는 화면 | <img src="./assets/screens/screen05.jpg" width="130" /> |

### 트래킹/메이트
실시간 산책 기록부터 메이트 신청/관리까지 하나의 흐름으로 연결됩니다.

| 화면 | 설명 | 캡처 |
|---|---|---|
| 산책 트래킹 지도 | 실시간 걸음 수/거리/시간 측정과 경로 표시를 제공하는 트래킹 화면 | <img src="./assets/screens/screen06.jpg" width="130" /> |
| 산책 종료 다이얼로그 | 저장 후 종료/저장 없이 종료/계속 걷기 선택을 제공하는 종료 확인 UI | <img src="./assets/screens/screen07.jpg" width="130" /> |
| 메이트 게시글 상세 | 경로/일정/작성자 정보를 확인하고 신청하는 상세 화면 | <img src="./assets/screens/screen08.jpg" width="130" /> |
| 피드 목록 | 저장된 산책 기록 기반 피드를 리스트로 확인하는 화면 | <img src="./assets/screens/screen09.jpg" width="130" /> |
| 신청 목록 관리 | 대기/수락 신청자 관리, 채팅 연결, 게시물 삭제를 처리하는 화면 | <img src="./assets/screens/screen10.jpg" width="130" /> |

### 채팅/프로필
메이트 사용자와의 대화와 프로필 기반 상호작용을 지원합니다.

| 화면 | 설명 | 캡처 |
|---|---|---|
| 1:1 채팅 화면 | 메시지 송수신과 실시간 대화를 제공하는 채팅 화면 | <img src="./assets/screens/screen11.jpg" width="130" /> |
| 채팅 참가자 목록 | 채팅방 참여자 확인과 방장 권한 정보를 제공하는 패널 | <img src="./assets/screens/screen12.jpg" width="130" /> |
| 사용자 프로필 | 사용자 정보 조회, 신고/차단, 피드 보기 기능을 제공하는 화면 | <img src="./assets/screens/screen13.jpg" width="130" /> |

### 음악 추천/템포 워킹
음악 유사도 추천과 인터벌 기반 템포 재생으로 걷기 페이스를 조절합니다.

| 화면 | 설명 | 캡처 |
|---|---|---|
| 목표 걸음 설정 | 목표 걸음 수 프리셋/직접 입력을 지원하는 설정 다이얼로그 | <img src="./assets/screens/screen14.jpg" width="130" /> |
| 음악 추천 메인 | 내 음악 업로드 후 유사도 기반 추천 목록을 확인하는 화면 | <img src="./assets/screens/screen15.jpg" width="130" /> |
| 추천 상세 분석 | 템포/에너지/리듬 등 세부 유사도 지표를 보여주는 상세 화면 | <img src="./assets/screens/screen16.jpg" width="130" /> |
| 인터벌 트레이닝 | BPM/인터벌 시간(30초, 1분, 1분30초) 기반 재생 제어 화면 | <img src="./assets/screens/screen17.jpg" width="130" /> |
| LOW 템포 재생 | 천천히 걷는 페이스용 곡 재생 화면 | <img src="./assets/screens/screen18.jpg" width="130" /> |
| MAX 템포 재생 | 고강도 파워 워킹용 곡 재생 화면 | <img src="./assets/screens/screen21.jpg" width="130" /> |

## 기술 스택
- Language: Java
- Platform: Android
- Build: Gradle
- Backend/DB: Firebase (Firestore, Realtime Database, Storage)
- Map: Naver Maps SDK
- Network: Retrofit, Volley

## 프로젝트 구조
```text
WalkingMate/
  app/
  assets/
    screens/
  gradle/
  build.gradle
  settings.gradle
  gradlew
```
