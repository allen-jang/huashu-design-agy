<sub><b>🌐 한글</b> · <a href="README.en.md">English</a> · <a href="README.zh.md">中文</a></sub>

<div align="center">

# Huashu Design - Antigravity Edition

> *"타이핑하고 엔터를 누르세요. 완성된 고품질 디자인이 눈앞에 펼쳐집니다."*
> *「打字。回车。一份能交付的设计。」*

[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Agent-Agnostic](https://img.shields.io/badge/Agent-Antigravity-blueviolet)](https://github.com/allen-jang/huashu-design-agy)
[![Skills](https://img.shields.io/badge/Antigravity-Compatible-green)](https://github.com/allen-jang/huashu-design-agy)

<br>

**안티그라비티(Antigravity)에게 한 문장만 말해보세요. 3분에서 30분 만에 완벽한 디자인 결과물이 완성됩니다.**

<br>

**제품 런칭 애니메이션**, 클릭 가능한 **App 프로토타입**, 편집 가능한 **PPT 덱**, 인쇄용 **인포그래픽**까지.

"AI가 만든 것치곤 괜찮네" 수준이 아닙니다. 실제 전문 디자인 팀이 작업한 듯한 퀄리티를 보여줍니다. 스킬에 브랜드 에셋(로고, 색상, UI 스크린샷 등)을 제공하면 브랜드 고유의 아이덴티티를 읽어내어 적용하며, 아무것도 제공하지 않더라도 내장된 20가지 전문 디자인 어휘를 바탕으로 AI 특유의 뻔한 디자인('AI Slop')을 철저히 배제합니다.

**이 README에 포함된 모든 애니메이션과 데모는 huashu-design 스킬이 직접 제작한 결과물입니다.** Figma나 After Effects 없이 오직 자연어 지시와 스킬 실행만으로 완성되었습니다. 다음 제품 출시 프로모션 비디오가 필요하신가요? 직접 만들어 보세요.

```bash
# 안티그라비티 스킬로 설치하기
npx skills add allen-jang/huashu-design-agy
```

> 📣 **MIT 라이선스로 공개되었습니다.** 본 스킬은 [MIT 라이선스](LICENSE)에 따라 개인 및 상업적 목적으로 무료로 사용할 수 있으며, 별도의 승인이 필요하지 않습니다.

[데모 보기](#데모-갤러리) · [설치 및 사용법](#설치-및-사용법) · [핵심 기능](#핵심-기능) · [작동 원리](#작동-원리) · [vs. Claude Design](#vs-claude-design)

</div>

---

<p align="center">
  <video src="https://github.com/alchaincyf/huashu-design/releases/download/v2.0/hero-animation-v10-en.mp4" autoplay muted loop playsinline width="100%">
    브라우저가 비디오 태그를 지원하지 않습니다. <a href="https://github.com/alchaincyf/huashu-design/releases/download/v2.0/hero-animation-v10-en.mp4">MP4 다운로드</a>.
  </video>
</p>

<p align="center"><sub>▲ huashu-design이 할 수 있는 일을 보여주는 10초짜리 히어로 애니메이션</sub></p>

---

## 설치 및 사용법

```bash
npx skills add allen-jang/huashu-design-agy
```

설치한 후, **안티그라비티(Antigravity)** 에이전트에게 자연어로 지시해 보세요:

```text
"사용자 심리학을 주제로 한 키노트 발표 자료를 만들어줘. 선택할 수 있는 3가지 스타일 방향을 추천해줘."
"뽀모도로 앱을 위한 iOS 프로토타입을 만들어줘. 4개의 화면으로 구성하고 실제로 클릭이 가능해야 해."
"이 로직을 60초짜리 애니메이션으로 만들어줘. MP4와 GIF로 내보내줘."
"이 디자인에 대해 5가지 차원으로 전문가 리뷰를 진행해줘."
```

별도의 그래픽 툴 플러그인이나 복잡한 설정이 필요하지 않습니다. 에이전트 친화적인 설계로 안티그라비티(Antigravity)를 지원하는 모든 AI 에이전트 환경에서 자연스럽게 작동합니다.

---

## 핵심 기능

| 기능 | 산출물 | 일반적인 소요 시간 |
|---|---|---|
| **인터랙티브 프로토타입 (App / Web)** | 단일 파일 HTML · 실제 iPhone 베젤 적용 · 실시간 클릭 및 네비게이션 · Playwright 자가 검증 | 10–15분 |
| **프레젠테이션 슬라이드 덱** | 브라우저 발표용 HTML 덱 + 실제 PPTX 편집 가능한 오브젝트 변환 (텍스트 프레임 유지) | 15–25분 |
| **모션 디자인 / 비디오** | MP4 (25fps / 60fps 보간 인코딩) + GIF (팔레트 최적화) + 배경음악(BGM) 믹싱 | 8–12분 |
| **디자인 변체 및 실시간 튜닝** | 3개 이상의 시각적 변체 나란히 비교 · 실시간 파라미터(Tweak) 조정용 프론트엔드 패널 제공 | 10분 |
| **인포그래픽 / 데이터 시각화** | 매거진 품질의 정교한 타이포그래피 · 벡터 PDF / 300dpi PNG / SVG 출력 | 10분 |
| **디자인 방향성 어드바이저** | 5대 디자인 학파 × 20가지 디자인 철학 매칭 · 최적의 3가지 방향 추천 및 실시간 병렬 데모 생성 | 5분 |
| **5차원 전문가 디자인 비평** | 비주얼 위계, 디테일, 철학적 일관성 등 5개 기준 채점 (방사형 차트 시각화) + 개선 리스트 | 3분 |

---

## 데모 갤러리

### 1. 디자인 방향성 어드바이저 (Design Direction Advisor)
요구사항이 다소 모호할 때 작동하는 폴백 모드입니다. 5개 학파 × 20개 철학 중 3개의 고유한 디자인 방향을 제안하고, 3가지 시각적 데모를 병렬로 생성하여 사용자가 직접 선택하도록 돕습니다.

<p align="center"><img src="https://github.com/alchaincyf/huashu-design/releases/download/v2.0/w3-fallback-advisor-en.gif" width="100%"></p>

### 2. iOS 앱 프로토타입 (iOS App Prototype)
아이폰 15 프로 베젤(다이내믹 아일랜드, 상태 표시줄, 홈 인디케이터 포함)을 픽셀 단위로 정확하게 재현합니다. 상태 기반 멀티 스크린 네비게이션을 포함하며 Wikimedia, Unsplash 등에서 실제 고품질 이미지를 동적으로 불러옵니다. 전달 전 Playwright 기반 자동 클릭 테스트를 실행하여 깨짐이 없는지 검증합니다.

<p align="center"><img src="https://github.com/alchaincyf/huashu-design/releases/download/v2.0/c1-ios-prototype-en.gif" width="100%"></p>

### 3. 모션 디자인 엔진 (Motion Design Engine)
Stage + Sprite 시간 슬라이스 모델을 기반으로 하며 `useTime`, `useSprite`, `interpolate`, `Easing` API를 통해 정교한 웹 애니메이션을 생성합니다. 명령 한 줄로 MP4, 고성능 60fps 보간 비디오, 팔레트 최적화 GIF 및 사운드트랙이 병합된 최종본을 렌더링합니다.

<p align="center"><img src="https://github.com/alchaincyf/huashu-design/releases/download/v2.0/c3-motion-design-en.gif" width="100%"></p>

### 4. HTML 슬라이드 → 편집 가능한 PPTX
웹 브라우저 프레젠테이션용 HTML 덱을 `html2pptx.js` 변환기가 분석하여 실제 PowerPoint 오브젝트로 일대일 번역합니다. 단순 캡처 이미지를 얹은 가짜 PPT가 아닌, **실제 텍스트 편집이 가능한 오리지널 텍스트 박스 형태**로 내보냅니다.

<p align="center"><img src="https://github.com/alchaincyf/huashu-design/releases/download/v2.0/c2-slides-pptx-en.gif" width="100%"></p>

### 5. 실시간 디자인 튜닝 (Tweaks)
디자인의 컬러 테마, 폰트, 정보 밀도 등을 파라미터화하여 화면 우측에 실시간 제어 패널을 생성합니다. 브라우저 새로고침을 하더라도 `localStorage`에 설정 값이 유지됩니다.

<p align="center"><img src="https://github.com/alchaincyf/huashu-design/releases/download/v2.0/c4-tweaks-en.gif" width="100%"></p>

### 6. 인포그래픽 및 데이터 시각화
세련된 타이포그래피와 CSS Grid 기반의 레이아웃, `text-wrap: pretty`와 같은 웹 표준 속성을 결합하여 잡지 인쇄물 수준의 데이터 가독성을 제공합니다. 벡터 PDF와 300dpi 고해상도 PNG/SVG 출력을 지원합니다.

<p align="center"><img src="https://github.com/alchaincyf/huashu-design/releases/download/v2.0/c5-infographic-en.gif" width="100%"></p>

### 7. 5차원 전문가 비평 (Expert Critique)
디자인 결과물의 철학적 일관성, 시각적 계층 구조, 실행 완성도, 기능성, 혁신성의 5가지 차원을 0-10점으로 정밀 채점하여 방사형 차트로 보여주며, 즉시 개선해야 할 체크리스트(Keep / Fix / Quick Wins)를 제공합니다.

<p align="center"><img src="https://github.com/alchaincyf/huashu-design/releases/download/v2.0/c6-expert-review-en.gif" width="100%"></p>

### 8. 점진적 설계 워크플로우 (Junior Designer Workflow)
한 번에 완벽한 결과물을 내려 하지 않습니다. 가설 수립 및 와이어프레임(gray blocks) 단계에서 미리 사용자 피드백을 수집하여 논리적 불일치를 예방합니다. 오해를 일찍 해결하는 것은 완성 후 수정하는 것보다 100배 더 경제적입니다.

<p align="center"><img src="https://github.com/alchaincyf/huashu-design/releases/download/v2.0/w2-junior-designer-en.gif" width="100%"></p>

### 9. 핵심 에셋 프로토콜 (Core Asset Protocol)
특정 브랜드의 디자인 태스크를 진행할 때 작동하는 5단계 강제 프로세스입니다. 로고, 실제 제품 샷, UI 스크린샷, 컬러 값, 폰트 등을 찾기 위해 공식 채널 수집 및 웹서칭을 우선하여 브랜드 왜곡을 차단합니다.

<p align="center"><img src="https://github.com/alchaincyf/huashu-design/releases/download/v2.0/w1-brand-protocol-en.gif" width="100%"></p>

---

## 작동 원리 (Core Mechanics)

### 1. 브랜드 핵심 에셋 프로토콜 (Core Asset Protocol)
특정 브랜드(예: Stripe, Linear, Anthropic, DJI 등)와 관련된 작업이 수행될 때, 스킬은 아래 5단계 프로세스를 완벽하게 수행합니다.

| 단계 | 행동 | 목적 |
|---|---|---|
| **1. 질문 (Ask)** | 로고, 제품 샷, UI 스크린샷, 색상 팔레트, 폰트, 가이드라인 등 6대 핵심 에셋 목록 확인 | 유저가 보유한 기존 리소스 수집 및 존중 |
| **2. 공식 채널 탐색** | `<brand>.com/brand`, `/press`, `brand.<brand>.com` 등의 제품 소개 및 미디어 키트 서칭 | 신뢰성 높은 공식 자료 수집 |
| **3. 에셋 다운로드** | 고해상도 로고(SVG 우선), 대표 제품 이미지, 고화질 UI 캡처본 획득 | 대체 가능한 3중의 다운로드 패스 보장 |
| **4. 검증 및 추출** | 이미지 해상도 검증 및 실제 리소스 파일에서 정확한 컬러 Hex 코드 추출 | **기억에 의존하지 않는 팩트 기반 설계** |
| **5. 스펙 동결 (Freeze)** | 추출된 로고 경로, 이미지, CSS 변수 등을 `brand-spec.md` 파일에 기록 보존 | 에이전트의 컨텍스트 휘발 방지 |

### 2. 디자인 방향성 어드바이저 (Fallback)
유저의 요구사항이 너무 막연할 때 실행되는 지능형 백업 모드입니다.
- 단편적인 직관으로 구현을 서두르지 않고 Fallback 모드로 즉시 전환합니다.
- 서로 다른 5대 학파에서 추출한 고유한 3가지 디자인 철학적 방향을 구체적인 예시와 벤치마크 키워드로 제안합니다.
- 각 방향에 맞는 시각적 데모를 병렬로 생성하여 유저에게 검토를 요청하며, 선택된 시각 자산을 바탕으로 세부 설계를 이어나갑니다.

### 3. 주니어 디자이너 워크플로우 (Junior Designer Workflow)
안티그라비티 에이전트가 디자인 설계를 시작할 때 따르는 기본 실무 구조입니다.
- 불명확한 점이 있을 때는 개별 질문을 쏟아내지 않고, 고도로 구조화된 질문 리스트를 한 번에 발송하여 완벽하게 논의를 마칩니다.
- 초기 단계에서는 핵심 배치와 레이아웃 구조를 HTML 주석(가설, 설계 이정표) 및 더미 영역으로 미리 작성해 유저의 의도와 싱크를 맞춥니다.
- 컬러 구현, 파라미터 패널 튜닝 등 점진적인 개선 단계를 거칠 때마다 시각적으로 피드백을 요구합니다.
- 결과물을 제출하기 전에 백그라운드 환경에서 Playwright 등으로 모의 브라우징 테스트를 수행해 오류를 최종 검토합니다.

### 4. 사실 검증 최우선 원칙 (Principle #0)
실제 제품, 브랜드 혹은 기술 스펙(예: "DJI Pocket 4", "Gemini 3 Pro" 등)을 다룰 때, 에이전트는 결코 사전 학습 데이터에만 의존하지 않습니다. 가장 먼저 `WebSearch` 도구를 실행해 실시간 릴리즈 여부, 렌더링 스펙 및 공식 정보 일치 여부를 파악합니다.

### 5. 안티 AI-slop 규칙 (Anti AI-slop Rules)
AI 생성물 특유의 단조롭고 양식화된 디자인 양식(자주빛 그라데이션, 유치한 이모지 아이콘, 둥근 모서리 디자인 남용, SVG 실루엣 대체, Inter 폰트의 무조건적인 본문 남용 등)을 강력하게 지양합니다. `text-wrap: pretty`, CSS Grid, 엄선된 Serif/Display 서체 조합, 정교한 oklch 테마 컬러 체계를 적용하여 사람 디자이너가 공들여 작성한 듯한 느낌을 줍니다.

---

## vs. Claude Design

핵심 에셋 프로토콜의 설계 철학은 Anthropic이 Claude Design에 작성했던 훌륭한 아이디어에서 영감을 받았습니다. **뛰어난 고해상도 디자인은 빈 페이지에서 시작하는 것이 아니라, 이미 존재하는 브랜드 고유의 맥락에서 출발한다**는 단순하고도 강력한 신조가 평범한 디자인과 90점짜리 명품 디자인의 차이를 만듭니다.

`huashu-design`과 Claude Design의 지향점 차이는 다음과 같습니다:

| 비교 항목 | Claude Design | huashu-design (Antigravity Edition) |
|---|---|---|
| **제공 형태** | 브라우저 전용 웹 프로덕트 | 터미널 및 에이전트용 스킬 (Skill) |
| **작동 환경** | Claude.ai 공식 웹 인터페이스 | **Antigravity (안티그라비티)**, Claude Code, Cursor, Trae 등 |
| **산출물** | 그래픽 캔버스 및 Figma 익스포트 | HTML(단일 파일), MP4 비디오, GIF, 편집 가능 PPTX, PDF 벡터 등 |
| **조작 방식** | GUI 기반 클릭, 드래그 및 에디터 수정 | 에이전트와의 자연어 대화 및 자동 빌드 |
| **모션 그래픽** | 간단한 화면 전환 및 모션 | Stage + Sprite 타임라인 컨트롤, 60fps 렌더링 지원 |

Claude Design이 훌륭한 **그래픽 저작 도구**라면, `huashu-design`은 **복잡한 그래픽 저작 도구 레이어 자체를 생략해주는 파트너**에 가깝습니다. 마우스 조작 없이 오직 안티그라비티와의 대화만으로 훌륭한 결과물을 직접 얻을 수 있습니다.

---

## 제한 사항 (Limitations)
- **Figma와의 양방향 동기화 미지원**: 결과물은 순수 HTML 및 최종 미디어 파일(PPTX, MP4 등)로 내보내집니다. PPTX의 경우 Keynote나 PowerPoint에서 텍스트 상자를 자유롭게 드래그해 편집하는 것은 완벽히 지원하지만, 피그마 레이어로 직접 가져오는 구조는 제공하지 않습니다.
- **초고도 3D/물리 시뮬레이션의 범위 초과**: WebGL이나 복잡한 3D 파티클 물리엔진(Framer Motion 3D 등)을 연동한 무거운 인터랙티브 3D 디자인은 본 스킬의 주된 범위가 아닙니다.
- **완전 무에서 유를 창조할 때의 한계**: 브랜드 로고나 가이드가 아예 존재하지 않는 빈 바탕 상태에서 즉흥적으로 그릴 경우 퀄리티 편차가 발생할 수 있습니다. 가능한 한 최소한의 디자인 맥락이나 브랜드 에셋을 공급해 주는 것이 훨씬 더 큰 감동을 선사합니다.

---

## 저장소 구조 (Repository Structure)

```text
huashu-design-agy/
├── SKILL.md                 # 안티그라비티가 읽고 실행하는 메인 지침 (한국어 번역/최적화)
├── README.md                # 한국어 README (본 파일)
├── README.en.md             # 영문 README (Original English)
├── README.zh.md             # 중문 README (Original Chinese)
├── assets/                  # 프로젝트 스타터 컴포넌트 라이브러리
│   ├── animations.jsx       # Stage + Sprite + Easing + interpolate 프레임워크
│   ├── ios_frame.jsx        # iPhone 15 Pro 디바이스 프레임
│   ├── android_frame.jsx
│   ├── macos_window.jsx
│   ├── browser_window.jsx
│   ├── deck_stage.js        # HTML 프레젠테이션 엔진
│   ├── deck_index.html      # 멀티 파일 프레젠테이션 빌더
│   ├── design_canvas.jsx    # 변체(Tweaks) 실시간 캔버스 패널
│   ├── showcases/           # prebuilt 디자인 예시 (8개 씬 × 3가지 스타일)
│   └── bgm-*.mp3            # 6종의 고품질 배경 음악 사운드 트랙
├── references/              # 태스크별 지식 아카이브 및 세부 규칙서
│   ├── animation-pitfalls.md
│   ├── design-styles.md     # 20가지 디자인 철학의 구체적 명세
│   ├── slide-decks.md
│   ├── editable-pptx.md
│   ├── critique-guide.md
│   ├── video-export.md
│   └── ...
├── scripts/                 # 미디어 내보내기 툴체인
│   ├── render-video.js      # HTML 애니메이션 → MP4 렌더러 (Playwright)
│   ├── convert-formats.sh   # MP4 → 60fps 보간 비디오 및 용량 최적화 GIF 변환 스크립트
│   ├── add-music.sh         # MP4 + BGM 음원 믹싱 자동화
│   ├── export_deck_pdf.mjs
│   ├── export_deck_pptx.mjs
│   ├── html2pptx.js         # DOM CSS 연산 기반 PPTX 인코더
│   └── verify.py
└── demos/                   # 기능 소개용 로컬 데모 모음
```

---

## 라이선스
MIT 라이선스(LICENSE)에 의해 보호됩니다. 자유로운 수정, 회사 내부 활용, 상업용 클라이언트 작업 인도 및 유료 서비스 내 번들이 완전 무상으로 허용됩니다.

---

## 원작자 소개 및 연결
`huashu-design`은 독립 개발자이자 AI 크리에이터인 화수(Huasheng, @AlchainHust)가 제작하였습니다. 한국어 포팅 및 안티그라비티 최적화(Antigravity Edition)는 [allen-jang](https://github.com/allen-jang)에 의해 구성되었습니다.

- **원작자 X (Twitter)**: [@AlchainHust](https://x.com/AlchainHust)
- **원작자 WeChat**: 花叔
- **원작자 YouTube**: [花叔](https://www.youtube.com/@Alchain)
- **공식 사이트**: [huasheng.ai](https://www.huasheng.ai/)
---
