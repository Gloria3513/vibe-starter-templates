---
name: Cafe
colors:
  primary: "#5D4432"
  secondary: "#E9E3DD"
  success: "#16A34A"
  warning: "#D97706"
  danger: "#DC2626"
  surface: "#F9F7F5"
  text: "#3E2B1E"
  neutral: "#F9F7F5"
typography:
  h1:
    fontFamily: "Poppins"
    fontSize: 3rem
  body-md:
    fontFamily: "Poppins"
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
  sm: 2px
  md: 4px
  sourceScale: "2/4/8/12/16/24/32/48"
---

## Overview

Cozy cafe-inspired interface with warm tones, soft typography, and clean layouts for a relaxed browsing experience.

## Style Foundations

- **Visual style:** minimal, clean
- **Typography scale:** desktop-first expressive scale
- **Typography fonts:** primary=Poppins, display=Poppins, mono=JetBrains Mono
- **Typography weights:** 100, 200, 300, 400, 500, 600, 700, 800, 900
- **Color palette:** primary, neutral, success, warning, danger
- **Spacing scale:** 2/4/8/12/16/24/32/48

## Colors

- **Primary (#5D4432):** Token from style foundations.
- **Secondary (#E9E3DD):** Token from style foundations.
- **Success (#16A34A):** Token from style foundations.
- **Warning (#D97706):** Token from style foundations.
- **Danger (#DC2626):** Token from style foundations.
- **Surface (#F9F7F5):** Token from style foundations.
- **Text (#3E2B1E):** Token from style foundations.
- **Neutral (#F9F7F5):** Derived from the surface token for official format compatibility.

## 한글 글꼴 (스마택트 추가)

위 설정의 영문 글꼴은 한글을 표시하지 못한다. 이 템플릿은 한글을 위해 제목에 "Gowun Batang", 본문에 "Gothic A1" 를 쓴다(`index.html` 머리의 글꼴 `<link>` 와 `style.css`).
- 새 칸·새 섹션을 만들 때도 이 두 글꼴을 쓴다. 영문 글꼴로 바꾸지 않는다.
- 이탤릭(기울임)은 쓰지 않는다.
- 색은 `style.css` 맨 위 `--main` 과 그 아래 색 변수를 쓴다.
