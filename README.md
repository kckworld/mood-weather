# 오늘의 기분 날씨 ☁️

> 이모지 3개로 오늘의 기분을 날씨 예보로 확인해보세요.

<br>

[![바로 사용하기](https://img.shields.io/badge/☁️%20바로%20사용하기-오늘의%20기분%20날씨-7c3aed?style=for-the-badge)](https://kckworld.github.io/mood-weather)

<br>

---

## 📸 미리보기

<!-- 스크린샷 또는 GIF를 여기에 넣어주세요 -->
<!-- 예: ![preview](./preview.gif) -->

> 📷 ScreenToGif 등으로 짧게 녹화 후 이 레포에 업로드하면 자동으로 표시됩니다.

---

## 🌈 어떻게 쓰나요?

**딱 세 단계예요.**

```
1️⃣  이모지 3개 고르기
        ↓
2️⃣  나만의 기분 날씨 예보 확인
        ↓
3️⃣  저장하거나 카카오로 공유
```

- 📸 **저장하기** — 9:16 인스타 스토리 비율로 PNG 다운로드 (iOS는 사진 앱에 바로 저장)
- 💛 **카카오 공유** — 친구한테 내 기분 날씨 공유

---

## ⛅ 날씨 케이스 (26가지)

| 조합 | 날씨 |
|------|------|
| 😍 + 🥹 | 💕 핑크빛 설렘 |
| 🥳 + 🤩 | 🎆 파티 폭발 |
| 🤯 + 😵 | 🌪️ 정신 태풍 |
| 🔥 포함 | ☀️ 폭염 주의보 |
| 💸 포함 | 🌧️ 돈벼락 예보 |
| 🍕 포함 | 🍕 피자 소나기 |
| 🍜 포함 | 🍜 라면 특보 |
| 🍦 포함 | 🍦 아이스크림 고기압 |
| 🍺 포함 | 🍺 맥주 한 캔 바람 |
| 🍔 포함 | 🍔 햄버거 폭식 소나기 |
| 🍕 + 🍺 | 🍻 치맥 최강 조합 |
| 🍜 + 😴/💤/🥱 | 🌙 라면 먹고 취침 |
| 🍦 + 🔥 | 🌡️ 아이스로 열식히기 |
| 졸음 이모지 2개+ | 🌫️ 수면 안개 |
| 😤 + 😬 | 🌩️ 황사 짜증 특보 |
| 😂 + 🥳 | 🌈 폭소 소나기 |
| 🫡 + 😎 | ⚡ 각오의 맑음 |
| 😬 + 🤔 | 🌁 어색한 흐림 |
| 😡 + 😭 | ⛈️ 분노 집중호우 |
| 😭 포함 | 🌧️ 감성 장마 |
| 😡 포함 | ⚡ 낙뢰 주의보 |
| 🫠 포함 | 🌊 녹아내리는 중 |
| 😎 포함 | 😎 쿨한 맑음 |
| 🤗 포함 | 🌸 포근한 봄날 |
| 😏 포함 | 🌤️ 알 수 없는 맑음 |
| 🤔 + 😶 | 🌫️ 철학적 안개 |
| 긍정 3개 | ☀️ 완벽한 맑음 |
| 부정 3개 | ⛈️ 폭풍우 |
| 기타 | ⛅ 구름 많음 |

> 같은 조합도 매번 다른 멘트가 나와요. (케이스마다 2~3가지 변형)

---

## 💛 카카오 공유 설정

카카오 공유 버튼을 활성화하려면:

1. [Kakao Developers](https://developers.kakao.com) 접속 → 앱 등록
2. **JavaScript 키** 복사
3. `index.html` 상단 아래 부분에 키 입력:
   ```js
   const KAKAO_JS_KEY = 'YOUR_KAKAO_JS_KEY'; // ← 여기에 입력
   ```
4. 앱 설정 → **플랫폼** → Web 도메인에 `kckworld.github.io` 추가

---

<details>
<summary>🛠️ 기술 스택 / 로컬 실행</summary>

<br>

**기술 스택**

| 항목 | 내용 |
|------|------|
| 언어 | Vanilla HTML / CSS / JavaScript |
| 저장 | [html2canvas](https://html2canvas.hertzen.com/) CDN |
| 폰트 | Google Fonts (Gowun Dodum, Noto Serif KR) |
| 공유 | Kakao JavaScript SDK |
| 배포 | GitHub Pages |

**로컬 실행**

서버 없이 파일 하나로 동작합니다.

```bash
# 클론
git clone https://github.com/kckworld/mood-weather.git
cd mood-weather

# 브라우저로 바로 열기
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

**GitHub Pages 재배포**

```bash
git add .
git commit -m "update"
git push origin main
```

`main` 브랜치 루트에서 자동 배포됩니다.

</details>
