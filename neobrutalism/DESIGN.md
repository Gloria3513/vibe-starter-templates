---
name: Neobrutalism
colors:
  primary: "#FDC800"
  secondary: "#432DD7"
  success: "#16A34A"
  warning: "#D97706"
  danger: "#DC2626"
  surface: "#FBFBF9"
  text: "#1C293C"
  neutral: "#FBFBF9"
typography:
  h1:
    fontFamily: "Inter"
    fontSize: 2.1875rem
  body-md:
    fontFamily: "Inter"
    fontSize: 0.9375rem
  label-caps:
    fontFamily: "JetBrains Mono"
    fontSize: 0.8125rem
  sourceScale: "13/15/17/21/27/35"
  weights: "100, 200, 300, 400, 500, 600, 700, 800, 900"
rounded:
  sm: 4px
  md: 8px
spacing:
  sm: 4px
  md: 8px
  sourceScale: "4/8/12/16/24/32"
---

## Overview

Modern take on brutalism with bold borders, vivid accent colors, and raw, high-contrast layouts on warm surfaces.

## Style Foundations

- **Visual style:** modern, clean, high-contrast
- **Typography scale:** 13/15/17/21/27/35
- **Typography fonts:** primary=Inter, display=Inter, mono=JetBrains Mono
- **Typography weights:** 100, 200, 300, 400, 500, 600, 700, 800, 900
- **Color palette:** primary, neutral, success, warning, danger
- **Spacing scale:** 4/8/12/16/24/32

## Colors

- **Primary (#FDC800):** Token from style foundations.
- **Secondary (#432DD7):** Token from style foundations.
- **Success (#16A34A):** Token from style foundations.
- **Warning (#D97706):** Token from style foundations.
- **Danger (#DC2626):** Token from style foundations.
- **Surface (#FBFBF9):** Token from style foundations.
- **Text (#1C293C):** Token from style foundations.
- **Neutral (#FBFBF9):** Derived from the surface token for official format compatibility.

## 한글 글꼴 (스마택트 추가)

위 설정의 영문 글꼴은 한글을 표시하지 못한다. 이 템플릿은 한글용 글꼴을 따로 쓴다(`index.html` 머리의 글꼴 `<link>` 와 `style.css`).
- 제목 글꼴: "Black Han Sans"
- 본문 글꼴: "IBM Plex Sans KR"
- 새 칸·새 섹션을 만들 때도 이 두 글꼴을 쓴다. 영문 글꼴로 바꾸지 않는다.
- 이탤릭(기울임)은 쓰지 않는다.
- 색은 `style.css` 맨 위 `--main` 과 그 아래 색 변수를 쓴다.
