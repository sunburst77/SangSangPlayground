# SangSangPlayground

상상놀이터(유아 교육 앱) 랜딩 페이지 프로젝트입니다.

배포 주소: https://sunburst77.github.io/SangSangPlayground/

## 주요 구성

- 히어로 섹션 스플래시/입장 애니메이션
- 핵심 기능, 프로그램, 부모 대시보드, 후기, 요금제, FAQ
- Limited Offer, 다운로드 CTA, 플로팅 카운트다운
- SEO 메타 태그 + Open Graph/Twitter + JSON-LD 구조화 데이터

## 기술 스택

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript

## 로컬 실행

정적 페이지 프로젝트입니다.

- 간단 확인: `index.html`을 브라우저에서 직접 열기
- 권장 확인: 로컬 서버로 실행 후 확인
  - VS Code Live Server 사용 또는
  - `python -m http.server` 실행 후 브라우저 접속

## 파일 구조 (핵심)

- `index.html`: 메인 랜딩 페이지
- `master.html`: 디자인 톤앤매너 기준 레퍼런스
- `robots.txt`: 검색엔진 크롤링 정책
- `sitemap.xml`: 사이트맵
- `favicon.ico`, `favicon.svg`, `apple-touch-icon.png`: 파비콘/아이콘
- `og-image.png`: 소셜 공유 썸네일 이미지

## SEO 체크 포인트

- canonical / OG / Twitter URL 기준:
  - `https://sunburst77.github.io/SangSangPlayground/`
- 공유 이미지:
  - `og-image.png` (권장 1200x630)
- 파비콘/아이콘:
  - `favicon.ico`, `favicon.svg`, `apple-touch-icon.png`
- `robots.txt`의 Sitemap URL과 `sitemap.xml`의 `<loc>` 일치 여부 확인

## 배포 메모 (GitHub Pages)

- 리포지토리: `sunburst77/SangSangPlayground`
- Pages 활성화 후 `main` 브랜치 기준으로 배포
- 리포지토리명 또는 사용자명이 바뀌면 `index.html`의 SEO URL, `robots.txt`, `sitemap.xml` URL을 함께 수정

