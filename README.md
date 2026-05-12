# 오늘의 기분 날씨 ☁️

이모지 3개로 오늘의 기분을 날씨 예보 형식으로 브리핑해주는 단일 HTML 웹앱.

## 기능

- 24개 이모지 중 3개 선택
- 이모지 조합에 따라 21가지 날씨 케이스 분기
- 인스타 스토리 비율(9:16) 날씨 카드 생성
- PNG 이미지로 갤러리 저장 (html2canvas)
- 모바일 최적화 (max-width 390px)
- 서버 없이 파일 하나로 동작

## 날씨 케이스 (21가지)

| 조합 | 날씨 |
|------|------|
| 😍 + 🥹 | 💕 핑크빛 설렘 |
| 🥳 + 🤩 | 🎆 파티 폭발 |
| 🤯 + 😵 | 🌪️ 정신 태풍 |
| 🔥 포함 | ☀️ 폭염 주의보 |
| 💸 포함 | 🌧️ 돈벼락 예보 |
| 🍕 포함 | 🍗 치킨 소나기 |
| 졸음 이모지 2개+ | 🌫️ 수면 안개 |
| 😡 + 😭 | ⛈️ 분노 집중호우 |
| 😭 포함 | 🌧️ 감성 장마 |
| 😡 포함 | ⚡ 낙뢰 주의보 |
| 🫠 포함 | 🌊 녹아내리는 중 |
| 😎 포함 | 😎 쿨한 맑음 |
| 🤗 포함 | 🌸 포근한 봄날 |
| 😏 포함 | 🌤️ 알 수 없는 맑음 |
| 🤔 + 😶 | 🌫️ 철학적 안개 |
| 긍정 3개 | ☀️ 완벽한 맑음 |
| 긍정 2개 | 🌤️ 대체로 맑음 |
| 긍정+부정 혼합 | 🌦️ 변덕스러운 날씨 |
| 부정 2개 | 🌧️ 흐리고 비 |
| 부정 3개 | ⛈️ 폭풍우 |
| 중립 2개+ | 🌫️ 짙은 안개 |

## 로컬 실행

```bash
# 파일을 브라우저로 바로 열기
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

## GitHub Pages 배포

### 1. 저장소 생성 및 push

```bash
git init
git add .
git commit -m "init: 오늘의 기분 날씨 앱"
gh repo create mood-weather --public --source=. --remote=origin --push
```

### 2. GitHub Pages 활성화

1. 저장소 → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / `/ (root)`
4. **Save** 클릭

### 3. 접속

```
https://{username}.github.io/mood-weather/
```

몇 분 후 자동 배포됩니다.

## 기술 스택

- Vanilla HTML/CSS/JS (외부 의존성 없음)
- [html2canvas](https://html2canvas.hertzen.com/) — 카드 PNG 저장용 CDN
- [Google Fonts](https://fonts.google.com/) — Gowun Dodum, Noto Serif KR
