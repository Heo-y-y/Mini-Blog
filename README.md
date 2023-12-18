# Mini Project

## 미니 블로그 프로젝트

![스크린샷 2023-12-18 오후 2.28.52.png](https://github.com/Heo-y-y/development-blog/assets/112863029/29650203-c15e-4411-a27e-2fccf4afe38e)

### 프로젝트 실행 방법

1. 프로젝트 열기
2. `npm start` 또는 `npx serve -s build`으로 실행하여 해당 링크로 확인

### 미니 블로그에 필요한 기능

- 글 목록 보기 기능(리스트 형태)
- 글 보기 기능
- 댓글 보기 기능
- 글 작성 기능
- 댓글 작성 기능

### 전체 화면 디자인

![스크린샷 2023-12-17 오후 5.27.52.png](https://github.com/Heo-y-y/development-blog/assets/112863029/784c61c3-6754-4223-8025-c7a16e8cee6c)

### 사용한 패키지

- react-router-dom v6
- styled-components v

## 주요 컴포넌트 및 폴더 구성

### 각 기능에 필요한 Component

- 글 목록 보기 기능(리스트 형태)
    - PostList, PostListItem
- 글 보기 기능
    - Post
- 댓글 보기 기능
    - CommentList, CommentListItem
- 글 작성 기능
    - PostWrite
- 댓글 작성 기능
    - CommentWrite

### 폴더 구성

![스크린샷3 2023-12-17 오후 5 57 42](https://github.com/Heo-y-y/development-blog/assets/112863029/5dfb641b-741d-4532-a966-131b9382abef)

- **list**: 리스트와 관련된 Component들을 모아놓은 폴더
- **page**: 페이지 Component들을 모아놓은 폴더
- **ui**: UI Component들을 모아놓은 폴더
