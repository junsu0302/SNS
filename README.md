# SNS

링크 : [https://blog-b74e6.web.app](https://blog-b74e6.web.app)

## 기술 스택
1. React-router-dom : 라우팅
2. Firebase auth : 사용자 인증
3. Firebase Firestore : CRUD
4. Media Query, scss : 반응형 스타일링
5. Recoil : 상태관리 및 다국어 처리
6. Vercel CLI : 배포

## 프로젝트 구조
```
src
├─ atom : 다국어 처
├─ components : 공통 컴포넌트
│  ├─ comments : 이미지 슬라이드 관리
│  │  ├─ Comment.module.scss : 댓글 스타일링 관리
│  │  ├─ CommentBox.tsx : 댓글 리스트 관리
│  │  └─ CommentForm.tsx : 댓글 작성 관리
│  ├─ following : 팔로잉 관리
│  │  └─ followingBox.tsx : 팔로잉 관리
│  ├─ loader : 로딩 화면 관리
│  │  ├─ Loader.module.scss : 로딩 스타일링 관리
│  │  └─ Loader.tsx : 로딩 관리
│  ├─ notifications : 예외 상황 관리
│  │  ├─ Notification.module.scss : 예외 상황 스타일링 관리
│  │  └─ NotificationBox.tsx : 예외 상황 관리
│  ├─ posts : 포스팅 관리
│  │  ├─ PostBox.tsx : 게시글 작성 관리
│  │  ├─ PostEditForm.tsx : 게시글 수정 페이지 관리
│  │  ├─ PostForm.scss : 게시글 작성 페이지 관리
│  │  └─ PostHeader.tsx : 게시글 작성 페이지 헤더 관리
│  ├─ users : 유저 상태 관리
│  │  ├─ LoginForm.tsx : 로그인 페이지 관리
│  │  └─ SignupForm.tsx : 회원가입 페이지 관리
│  ├─ Layouts.tsx: 레이아웃 관리
│  ├─ Menu.tsx : 메뉴 관리
│  └─ Router : 라우팅 관리
├─ constants : 다국어 처리 정보 관리
│  └─ language.ts : 다국어 관리
├─ context : 사용자 인증
│  └─ AuthContext.tsx : 사용자 인증 상태 관리
├─ hooks : 다국어 처리 관련 훅
│  └─ useTranslation.tsx : 다국어 처리 지원
├─ pages
│  ├─ home.tsx : 메인 페이지
│  ├─ notifications.tsx : 예외 상황 페이지
│  ├─ posts
│  │  ├─ detail.tsx : 상세 계시글 페이지
│  │  ├─ edit.tsx : 게시글 수정 페이지
│  │  ├─ new.tsx : 개사글 작성 페이지
│  │  └─ posts.tsx : 게시글 리스트 페이지
│  ├─ profile : 사용자 프로필 페이지
│  │  ├─ edit.tsx : 프로필 수정 페이지
│  │  └─ profile.tsx : 프로필 페이지
│  ├─ search.tsx : 검색 페이지
│  ├─ users : 사용자 프로필 페이지
│  │  ├─ login.tsx : 로그인 페이지
│  └─ └─ signup.tsx : 회원가입 페이지
├─ App.tsx : Contexts 설정
├─ index.tsx : 메인 페이지
├─ index.scss : 전체 스타일링
├─ _utils.scss : 반응형 스타일링
└─ firebaseApp.tsx : Firebase 설정
```
