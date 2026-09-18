---
name: Fantasy
colors:
  primary: "#0250CC"
  secondary: "#FDC800"
  success: "#16A34A"
  warning: "#D97706"
  danger: "#DC2626"
  surface: "#FFFFFF"
  text: "#111827"
  neutral: "#FFFFFF"
typography:
  h1:
    fontFamily: "New Rocker"
    fontSize: 2rem
  body-md:
    fontFamily: "New Rocker"
    fontSize: 1rem
  label-caps:
    fontFamily: "IBM Plex Mono"
    fontSize: 0.75rem
  sourceScale: "12/14/16/20/24/32"
  weights: "100, 200, 300, 400, 500, 600, 700, 800, 900"
rounded:
  sm: 4px
  md: 8px
spacing:
  sm: 8px
  md: 16px
  sourceScale: "8pt baseline grid"
---

## Overview

Game-inspired fantasy aesthetic with bold, premium visuals, rich color palettes, and immersive thematic elements.

## Style Foundations

- **Visual style:** bold, premium
- **Typography scale:** 12/14/16/20/24/32
- **Typography fonts:** primary=New Rocker, display=New Rocker, mono=IBM Plex Mono
- **Typography weights:** 100, 200, 300, 400, 500, 600, 700, 800, 900
- **Color palette:** primary, secondary, success, warning, danger, info
- **Spacing scale:** 8pt baseline grid

## Colors

- **Primary (#0250CC):** Token from style foundations.
- **Secondary (#FDC800):** Token from style foundations.
- **Success (#16A34A):** Token from style foundations.
- **Warning (#D97706):** Token from style foundations.
- **Danger (#DC2626):** Token from style foundations.
- **Surface (#FFFFFF):** Token from style foundations.
- **Text (#111827):** Token from style foundations.
- **Neutral (#FFFFFF):** Derived from the surface token for official format compatibility.

## 한글 글꼴 (스마택트 추가)

위 설정의 영문 글꼴은 한글을 표시하지 못한다. 이 템플릿은 한글용 글꼴을 따로 쓴다(`index.html` 머리의 글꼴 `<link>` 와 `style.css`).
- 제목 글꼴: "Black Han Sans"
- 본문 글꼴: "Gothic A1"
- 새 칸·새 섹션을 만들 때도 이 두 글꼴을 쓴다. 영문 글꼴로 바꾸지 않는다.
- 이탤릭(기울임)은 쓰지 않는다.
- 색은 `style.css` 맨 위 `--main` 과 그 아래 색 변수를 쓴다.
