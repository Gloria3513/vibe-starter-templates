---
name: Vintage
colors:
  primary: "#008080"
  secondary: "#C0C0C0"
  success: "#16A34A"
  warning: "#D97706"
  danger: "#DC2626"
  surface: "#C0C0C0"
  text: "#000000"
  neutral: "#C0C0C0"
typography:
  h1:
    fontFamily: "Silkscreen"
    fontSize: 2rem
  body-md:
    fontFamily: "Silkscreen"
    fontSize: 1rem
  label-caps:
    fontFamily: "JetBrains Mono"
    fontSize: 0.75rem
  sourceScale: "12/14/16/20/24/32"
  weights: "400, 700"
rounded:
  sm: 4px
  md: 8px
spacing:
  sm: 4px
  md: 8px
  sourceScale: "4/8/12/16/24/32"
---

## Overview

1950s-1990s nostalgia with skeuomorphic touches, grainy textures, retro color palettes, and pixel-style typography.

## Style Foundations

- **Visual style:** clean, vintage, retro
- **Typography scale:** 12/14/16/20/24/32
- **Typography fonts:** primary=Silkscreen, display=Silkscreen, mono=JetBrains Mono
- **Typography weights:** 400, 700
- **Color palette:** primary, neutral, success, warning, danger
- **Spacing scale:** 4/8/12/16/24/32

## Colors

- **Primary (#008080):** Token from style foundations.
- **Secondary (#C0C0C0):** Token from style foundations.
- **Success (#16A34A):** Token from style foundations.
- **Warning (#D97706):** Token from style foundations.
- **Danger (#DC2626):** Token from style foundations.
- **Surface (#C0C0C0):** Token from style foundations.
- **Text (#000000):** Token from style foundations.
- **Neutral (#C0C0C0):** Derived from the surface token for official format compatibility.

## 한글 글꼴 (스마택트 추가)

위 설정의 영문 글꼴은 한글을 표시하지 못한다. 이 템플릿은 한글용 글꼴을 따로 쓴다(`index.html` 머리의 글꼴 `<link>` 와 `style.css`).
- 제목 글꼴: "Galmuri11"
- 본문 글꼴: "Gothic A1"
- 새 칸·새 섹션을 만들 때도 이 두 글꼴을 쓴다. 영문 글꼴로 바꾸지 않는다.
- 이탤릭(기울임)은 쓰지 않는다.
- 색은 `style.css` 맨 위 `--main` 과 그 아래 색 변수를 쓴다.
