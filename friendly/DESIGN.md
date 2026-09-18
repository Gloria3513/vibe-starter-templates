---
name: Friendly
colors:
  primary: "#F2D9DC"
  secondary: "#D9F2D8"
  success: "#16A34A"
  warning: "#D97706"
  danger: "#DC2626"
  surface: "#FFFFFF"
  text: "#111827"
  neutral: "#FFFFFF"
typography:
  h1:
    fontFamily: "Noto Serif Display"
    fontSize: 2.5rem
  body-md:
    fontFamily: "Noto Serif Display"
    fontSize: 1rem
  label-caps:
    fontFamily: "Space Mono"
    fontSize: 0.875rem
  sourceScale: "14/16/18/24/32/40"
  weights: "100, 200, 300, 400, 500, 600, 700, 800, 900"
rounded:
  sm: 4px
  md: 8px
spacing:
  sm: 4px
  md: 8px
  sourceScale: "compact density mode"
---

## Overview

Approachable, intuitive design with rounded elements, ample whitespace, and soft pastel color palettes.

## Style Foundations

- **Visual style:** bold, playful, premium
- **Typography scale:** 14/16/18/24/32/40
- **Typography fonts:** primary=Noto Serif Display, display=Noto Serif Display, mono=Space Mono
- **Typography weights:** 100, 200, 300, 400, 500, 600, 700, 800, 900
- **Color palette:** primary, secondary, neutral
- **Spacing scale:** compact density mode

## Colors

- **Primary (#F2D9DC):** Token from style foundations.
- **Secondary (#D9F2D8):** Token from style foundations.
- **Success (#16A34A):** Token from style foundations.
- **Warning (#D97706):** Token from style foundations.
- **Danger (#DC2626):** Token from style foundations.
- **Surface (#FFFFFF):** Token from style foundations.
- **Text (#111827):** Token from style foundations.
- **Neutral (#FFFFFF):** Derived from the surface token for official format compatibility.

## 한글 글꼴 (스마택트 추가)

위 설정의 영문 글꼴은 한글을 표시하지 못한다. 이 템플릿은 한글용 글꼴을 따로 쓴다(`index.html` 머리의 글꼴 `<link>` 와 `style.css`).
- 제목 글꼴: "Gowun Batang"
- 본문 글꼴: "Gothic A1"
- 새 칸·새 섹션을 만들 때도 이 두 글꼴을 쓴다. 영문 글꼴로 바꾸지 않는다.
- 이탤릭(기울임)은 쓰지 않는다.
- 색은 `style.css` 맨 위 `--main` 과 그 아래 색 변수를 쓴다.
