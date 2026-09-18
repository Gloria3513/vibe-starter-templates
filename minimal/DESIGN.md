---
name: Minimal
colors:
  primary: "#0C0C09"
  secondary: "#312C85"
  success: "#16A34A"
  warning: "#D97706"
  danger: "#DC2626"
  surface: "#F4F4F1"
  text: "#0C0C09"
  neutral: "#F4F4F1"
typography:
  h1:
    fontFamily: "Inter"
    fontSize: 3rem
  body-md:
    fontFamily: "Open Sans"
    fontSize: 1rem
  label-caps:
    fontFamily: "Inconsolata"
    fontSize: 0.75rem
  sourceScale: "desktop-first expressive scale"
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

Stripped-back design emphasizing whitespace, clean typography, and restrained color for maximum clarity and focus.

## Style Foundations

- **Visual style:** minimal, clean, bold
- **Typography scale:** desktop-first expressive scale
- **Typography fonts:** primary=Open Sans, display=Inter, mono=Inconsolata
- **Typography weights:** 100, 200, 300, 400, 500, 600, 700, 800, 900
- **Color palette:** primary, neutral, success, warning, danger
- **Spacing scale:** 4/8/12/16/24/32

## Colors

- **Primary (#0C0C09):** Token from style foundations.
- **Secondary (#312C85):** Token from style foundations.
- **Success (#16A34A):** Token from style foundations.
- **Warning (#D97706):** Token from style foundations.
- **Danger (#DC2626):** Token from style foundations.
- **Surface (#F4F4F1):** Token from style foundations.
- **Text (#0C0C09):** Token from style foundations.
- **Neutral (#F4F4F1):** Derived from the surface token for official format compatibility.

## 한글 글꼴 (스마택트 추가)

위 설정의 영문 글꼴은 한글을 표시하지 못한다. 이 템플릿은 한글용 글꼴을 따로 쓴다(`index.html` 머리의 글꼴 `<link>` 와 `style.css`).
- 제목 글꼴: "IBM Plex Sans KR"
- 본문 글꼴: "IBM Plex Sans KR"
- 새 칸·새 섹션을 만들 때도 이 두 글꼴을 쓴다. 영문 글꼴로 바꾸지 않는다.
- 이탤릭(기울임)은 쓰지 않는다.
- 색은 `style.css` 맨 위 `--main` 과 그 아래 색 변수를 쓴다.
