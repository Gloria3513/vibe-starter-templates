---
name: Glassmorphism
colors:
  primary: "#1856FF"
  secondary: "#3A344E"
  success: "#07CA6B"
  warning: "#E89558"
  danger: "#EA2143"
  surface: "#FFFFFF"
  text: "#141414"
  neutral: "#FFFFFF"
typography:
  h1:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 3rem
  body-md:
    fontFamily: "Plus Jakarta Sans"
    fontSize: 1rem
  label-caps:
    fontFamily: "JetBrains Mono"
    fontSize: 0.75rem
  sourceScale: "mobile-first compact scale"
  weights: "100, 200, 300, 400, 500, 600, 700, 800, 900"
rounded:
  sm: 4px
  md: 8px
spacing:
  sm: 8px
  md: 16px
  sourceScale: "comfortable density mode"
---

## Overview

Frosted glass effect with translucent layers, subtle blur, and luminous borders for depth and modern elegance.

## Style Foundations

- **Visual style:** clean, high-contrast, bold, enterprise, liquidglass effect, glassmorphism
- **Typography scale:** mobile-first compact scale
- **Typography fonts:** primary=Plus Jakarta Sans, display=Plus Jakarta Sans, mono=JetBrains Mono
- **Typography weights:** 100, 200, 300, 400, 500, 600, 700, 800, 900
- **Color palette:** primary, neutral, success, warning, danger, info, surface/subtle layers
- **Spacing scale:** comfortable density mode

## Colors

- **Primary (#1856FF):** Token from style foundations.
- **Secondary (#3A344E):** Token from style foundations.
- **Success (#07CA6B):** Token from style foundations.
- **Warning (#E89558):** Token from style foundations.
- **Danger (#EA2143):** Token from style foundations.
- **Surface (#FFFFFF):** Token from style foundations.
- **Text (#141414):** Token from style foundations.
- **Neutral (#FFFFFF):** Derived from the surface token for official format compatibility.

## 한글 글꼴 (스마택트 추가)

위 설정의 영문 글꼴은 한글을 표시하지 못한다. 이 템플릿은 한글용 글꼴을 따로 쓴다(`index.html` 머리의 글꼴 `<link>` 와 `style.css`).
- 제목 글꼴: "Gothic A1"
- 본문 글꼴: "Gothic A1"
- 새 칸·새 섹션을 만들 때도 이 두 글꼴을 쓴다. 영문 글꼴로 바꾸지 않는다.
- 이탤릭(기울임)은 쓰지 않는다.
- 색은 `style.css` 맨 위 `--main` 과 그 아래 색 변수를 쓴다.
