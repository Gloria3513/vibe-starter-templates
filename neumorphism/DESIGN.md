---
name: Neumorphism
colors:
  primary: "#006666"
  secondary: "#F1F2F5"
  success: "#00A63D"
  warning: "#FE9900"
  danger: "#FF2157"
  surface: "#E7E5E4"
  text: "#1E2938"
  neutral: "#E7E5E4"
typography:
  h1:
    fontFamily: "Space Mono"
    fontSize: 3rem
  body-md:
    fontFamily: "Space Mono"
    fontSize: 1rem
  label-caps:
    fontFamily: "JetBrains Mono"
    fontSize: 0.75rem
  sourceScale: "desktop-first expressive scale"
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

Soft, extruded UI elements with inner and outer shadows on monochromatic surfaces for a tactile, embedded look.

## Style Foundations

- **Visual style:** minimal, clean, high-contrast, playful, matrix
- **Typography scale:** desktop-first expressive scale
- **Typography fonts:** primary=Space Mono, display=Space Mono, mono=JetBrains Mono
- **Typography weights:** 100, 200, 300, 400, 500, 600, 700, 800, 900
- **Color palette:** primary, secondary, success, warning, danger, info
- **Spacing scale:** compact density mode

## Colors

- **Primary (#006666):** Token from style foundations.
- **Secondary (#F1F2F5):** Token from style foundations.
- **Success (#00A63D):** Token from style foundations.
- **Warning (#FE9900):** Token from style foundations.
- **Danger (#FF2157):** Token from style foundations.
- **Surface (#E7E5E4):** Token from style foundations.
- **Text (#1E2938):** Token from style foundations.
- **Neutral (#E7E5E4):** Derived from the surface token for official format compatibility.

## 한글 글꼴 (스마택트 추가)

위 설정의 영문 글꼴은 한글을 표시하지 못한다. 이 템플릿은 한글용 글꼴을 따로 쓴다(`index.html` 머리의 글꼴 `<link>` 와 `style.css`).
- 제목 글꼴: "Galmuri11"
- 본문 글꼴: "IBM Plex Sans KR"
- 새 칸·새 섹션을 만들 때도 이 두 글꼴을 쓴다. 영문 글꼴로 바꾸지 않는다.
- 이탤릭(기울임)은 쓰지 않는다.
- 색은 `style.css` 맨 위 `--main` 과 그 아래 색 변수를 쓴다.
