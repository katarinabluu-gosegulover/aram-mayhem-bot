# GitHub Pages 사이트

이 폴더는 세구 봇의 공개 소개, 개인정보 처리방침, 이용 약관을 위한 정적 웹사이트입니다. 별도 빌드 도구나 서버가 필요하지 않습니다.

## 포함 페이지

- `index.html`: 봇 소개와 기능 범위
- `privacy.html`: 개인정보 처리방침
- `terms.html`: 이용 약관

## GitHub Pages 게시 방법

1. GitHub에서 공개 저장소를 만들고 이 `site` 폴더 **안의 파일들**을 저장소 최상위에 올립니다.
2. 저장소의 **Settings → Pages**로 이동합니다.
3. **Build and deployment**에서 `Deploy from a branch`, 브랜치 `main`, 폴더 `/(root)`를 선택하고 저장합니다.
4. 게시가 완료되면 `https://<GitHub-사용자명>.github.io/<저장소-이름>/` 형태의 주소가 생성됩니다.
5. 생성된 주소를 Riot Developer Portal의 Product URL에 입력합니다.

저장소가 `username.github.io`라는 이름이면 주소는 `https://<GitHub-사용자명>.github.io/`가 됩니다.

## 게시 전 확인

- 운영자 연락처를 공개할 방법이 필요하면 `privacy.html`과 `terms.html`의 “Discord 서버 운영자” 문구를 서버 초대 링크 또는 전용 연락처로 바꿉니다.
- 실제로 처리하는 데이터나 보관 기간이 바뀌면 개인정보 처리방침도 같은 배포에서 갱신합니다.
- API 키, Discord 봇 토큰, SQLite DB, `.env` 파일은 이 사이트나 Git 저장소에 올리지 않습니다.

## 로컬 미리보기

HTML 파일을 브라우저에서 직접 열면 됩니다. 상대 경로만 사용하므로 GitHub Pages 하위 경로에서도 동작합니다.
