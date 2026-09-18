---
name: Modern
colors:
  primary: "#553F83"
  secondary: "#111111"
  success: "#16A34A"
  warning: "#D97706"
  danger: "#DC2626"
  surface: "#553F83"
  text: "#ffffff"
  neutral: "#553F83"
typography:
  h1:
    fontFamily: "IBM Plex Serif"
    fontSize: 2rem
  body-md:
    fontFamily: "IBM Plex Serif"
    fontSize: 1rem
  label-caps:
    fontFamily: "JetBrains Mono"
    fontSize: 0.75rem
  sourceScale: "12/14/16/20/24/32"
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

Contemporary editorial style with serif typography, minimal palettes, and clean layouts for polished digital products.

## Style Foundations

- **Visual style:** modern, minimal, clean, editorial
- **Typography scale:** 12/14/16/20/24/32
- **Typography fonts:** primary=IBM Plex Serif, display=IBM Plex Serif, mono=JetBrains Mono
- **Typography weights:** 100, 200, 300, 400, 500, 600, 700, 800, 900
- **Color palette:** primary, secondary
- **Spacing scale:** 4/8/12/16/24/32

## Colors

- **Primary (#553F83):** Token from style foundations.
- **Secondary (#111111):** Token from style foundations.
- **Success (#16A34A):** Token from style foundations.
- **Warning (#D97706):** Token from style foundations.
- **Danger (#DC2626):** Token from style foundations.
- **Surface (#553F83):** Token from style foundations.
- **Text (#ffffff):** Token from style foundations.
- **Neutral (#553F83):** Derived from the surface token for official format compatibility.

## 한글 글꼴 (스마택트 추가)

위 설정의 영문 글꼴은 한글을 표시하지 못한다. 이 템플릿은 한글용 글꼴을 따로 쓴다(`index.html` 머리의 글꼴 `<link>` 와 `style.css`).
- 제목 글꼴: "Noto Serif KR"
- 본문 글꼴: "Noto Serif KR"
- 새 칸·새 섹션을 만들 때도 이 두 글꼴을 쓴다. 영문 글꼴로 바꾸지 않는다.
- 이탤릭(기울임)은 쓰지 않는다.
- 색은 `style.css` 맨 위 `--main` 과 그 아래 색 변수를 쓴다.
