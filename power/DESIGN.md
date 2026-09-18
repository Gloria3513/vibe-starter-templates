---
name: Power
colors:
  primary: "#FAFAFA"
  secondary: "#FAFAFA"
  success: "#16A34A"
  warning: "#D97706"
  danger: "#DC2626"
  surface: "#000000"
  text: "#ffffff"
  neutral: "#000000"
typography:
  h1:
    fontFamily: "Oswald"
    fontSize: 3rem
  body-md:
    fontFamily: "Oswald"
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
  sm: 8px
  md: 16px
  sourceScale: "8pt baseline grid"
---

## Overview

High-end dark aesthetic with bold headings, monochromatic palette, and premium feel for premium brand experiences.

## Style Foundations

- **Visual style:** modern, bold, big headings
- **Typography scale:** desktop-first expressive scale
- **Typography fonts:** primary=Oswald, display=Oswald, mono=JetBrains Mono
- **Typography weights:** 100, 200, 300, 400, 500, 600, 700, 800, 900
- **Color palette:** primary
- **Spacing scale:** 8pt baseline grid

## Colors

- **Primary (#FAFAFA):** Token from style foundations.
- **Secondary (#FAFAFA):** Token from style foundations.
- **Success (#16A34A):** Token from style foundations.
- **Warning (#D97706):** Token from style foundations.
- **Danger (#DC2626):** Token from style foundations.
- **Surface (#000000):** Token from style foundations.
- **Text (#ffffff):** Token from style foundations.
- **Neutral (#000000):** Derived from the surface token for official format compatibility.

## 한글 글꼴 (스마택트 추가)

위 설정의 영문 글꼴은 한글을 표시하지 못한다. 이 템플릿은 한글용 글꼴을 따로 쓴다(`index.html` 머리의 글꼴 `<link>` 와 `style.css`).
- 제목 글꼴: "Black Han Sans"
- 본문 글꼴: "Gothic A1"
- 새 칸·새 섹션을 만들 때도 이 두 글꼴을 쓴다. 영문 글꼴로 바꾸지 않는다.
- 이탤릭(기울임)은 쓰지 않는다.
- 색은 `style.css` 맨 위 `--main` 과 그 아래 색 변수를 쓴다.
