# 꿈꾸지 않으면 · 합창 연습실

초등학교 합창 연습을 위한 정적 웹사이트입니다.

## 주요 기능

- 전체 / Soprano / Alto High / Alto Low / Men 파트 선택
- 노래 듣기 / MR 듣기
- 파트별 음량 조절 및 음소거
- 흐르는 벡터 악보
- 재생 위치와 악보 동기화
- A-B 반복 및 현재 구간 반복
- 재생 속도 조절
- Windows / Android / iPhone 반응형 화면
- 기본 악보 싱크 보정 적용

## 실행

별도 서버 프로그램이 필요 없는 정적 웹사이트입니다.

### 로컬 실행

저장소를 내려받은 뒤 `index.html`을 Chrome 또는 Edge에서 열면 됩니다.

### GitHub Pages 배포

이 저장소에는 `.github/workflows/deploy-pages.yml`이 포함되어 있습니다.

1. 새 GitHub 저장소를 만듭니다.
2. 이 폴더의 **내용물 전체**를 저장소 루트에 업로드합니다.
3. 기본 브랜치를 `main`으로 사용합니다.
4. GitHub 저장소의 **Settings → Pages**에서 Source를 **GitHub Actions**로 설정합니다.
5. `main` 브랜치에 push하면 자동으로 Pages에 배포됩니다.

배포 주소 예시:

`https://사용자명.github.io/저장소명/`

## 폴더 구조

```text
.
├── index.html
├── manifest.webmanifest
├── .nojekyll
├── README.md
├── .github/
│   └── workflows/
│       └── deploy-pages.yml
└── assets/
    ├── audio/
    │   ├── full.mp3
    │   ├── soprano.mp3
    │   ├── alto_high.mp3
    │   ├── alto_low.mp3
    │   ├── men.mp3
    │   └── mr/
    ├── data/
    ├── icons/
    └── score/
```

## 참고

음원과 악보 자료의 권리는 각 권리자에게 있습니다. 공개 저장소에 업로드하거나 외부에 배포할 때에는 해당 자료의 이용 범위를 확인하세요.
