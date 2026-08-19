# Jung Beauty × SUNNY AFTERDARK — Booth Brief

할로윈 부스 준비 상황판. 한국어 / English 전환 지원.
2026년 10월 30일(금) · 남산뜰, 이태원 · 3F

## 보기

`index.html` 파일 하나로 끝입니다. 브라우저로 열면 바로 보입니다.
외부 라이브러리 없음, 인터넷 없어도 작동합니다.

## 팀 공유 — GitHub Pages

```bash
# 1. GitHub에서 새 저장소 생성 (예: halloween-booth)

# 2. 이 폴더에서
git init
git add .
git commit -m "부스 브리프 초안"
git branch -M main
git remote add origin https://github.com/<계정명>/halloween-booth.git
git push -u origin main
```

3. 저장소 → **Settings** → **Pages** → Source를 `main` / `root`로 지정 → Save
4. 1~2분 뒤 `https://<계정명>.github.io/halloween-booth/` 로 접속

팀원에게는 이 주소만 보내면 됩니다. 비공개로 하려면 저장소를 Private으로 두고
팀원을 Collaborator로 추가하세요. (Private 저장소의 Pages는 유료 플랜 필요 —
무료 플랜이면 Public 저장소로 두되 민감 정보는 넣지 않는 방식이 현실적입니다.)

## 수정

`index.html` 안의 `const D = { ko: {...}, en: {...} }` 객체만 고치면 됩니다.

- `tabs` — 탭 이름
- `body` — 탭별 내용 (HTML 문자열, 배열 순서 = 탭 순서)
- `svg` — 도면 라벨

한국어와 영어를 같은 순서로 맞춰주세요.

## 구조

```
index.html      전체 (HTML + CSS + JS + SVG 도면)
README.md       이 파일
```

## 업데이트 로그

- 2026-08-19 — 초안. 백월·게임소품 발주, 레이아웃 확정, 도어기프트 갭 35개 발견
