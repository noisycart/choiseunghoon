# choiseunghoon.com

최승훈 기자 개인 링크 페이지입니다.

## GitHub Pages 배포

1. GitHub에서 새 Public repository를 만듭니다.
2. 이 ZIP의 내용물을 저장소 최상위(root)에 업로드합니다.
3. `Settings → Pages`
4. `Source: Deploy from a branch`
5. `Branch: main`, `Folder: / (root)` 선택 후 저장합니다.
6. `CNAME` 파일에 이미 `choiseunghoon.com`이 입력되어 있습니다.
7. GitHub Pages의 Custom domain에 `choiseunghoon.com`을 등록합니다.
8. Porkbun DNS에서 GitHub Pages용 A/CNAME 레코드를 연결합니다.
9. DNS 확인 뒤 `Enforce HTTPS`를 켭니다.

## 구성

- `index.html` — 본문
- `styles.css` — 반응형 디자인
- `CNAME` — GitHub Pages 개인 도메인
- `assets/profile.jpg` — 원본 프로필 사진
- `assets/avatar-square.jpg` — SNS 미리보기용 이미지
- `assets/favicon.png` — 파비콘
- `robots.txt`
- `sitemap.xml`

## 링크 수정

`index.html`의 각 `href="..."` 값을 변경하면 됩니다.

외부 라이브러리나 웹폰트를 사용하지 않아 GitHub Pages에서 별도 빌드 없이 바로 동작합니다.
