---
name: Pulse
colors:
  primary: "#EA580B"
  secondary: "#F59E0B"
  background: "#FFEDD5"
  surface: "#FDBA74"
  text: "#EA580C"
  neutral: "#FDBA74"
typography:
  h1:
    fontFamily: "Limelight"
    fontSize: 3rem
  body-md:
    fontFamily: "Limelight"
    fontSize: 1rem
  label-caps:
    fontFamily: "JetBrains Mono"
    fontSize: 0.75rem
  sourceScale: "12/14/16/20/24/32/48"
  weights: "400"
rounded:
  sm: 4px
  md: 8px
spacing:
  sm: 4px
  md: 8px
  sourceScale: "4/8/12/16/24/32/48/64"
---

## Overview

Dynamic, vibrant style with thick borders, geometric shapes, high-contrast colors, and expressive typography conveying motion and vitality.

## Style Foundations

- **Visual style:** bold, geometric, vibrant, thick-bordered
- **Typography scale:** 12/14/16/20/24/32/48
- **Typography fonts:** primary=Limelight, display=Limelight, mono=JetBrains Mono
- **Typography weights:** 400
- **Color palette:** primary, secondary, neutral
- **Spacing scale:** 4/8/12/16/24/32/48/64

## Colors

- **Primary (#EA580B):** Token from style foundations.
- **Secondary (#F59E0B):** Token from style foundations.
- **Background (#FFEDD5):** Token from style foundations.
- **Surface (#FDBA74):** Token from style foundations.
- **Text (#EA580C):** Token from style foundations.
- **Neutral (#FDBA74):** Derived from the surface token for official format compatibility.

## 한글 글꼴 (스마택트 추가)

위 설정의 영문 글꼴은 한글을 표시하지 못한다. 이 템플릿은 한글용 글꼴을 따로 쓴다(`index.html` 머리의 글꼴 `<link>` 와 `style.css`).
- 제목 글꼴: "Black Han Sans"
- 본문 글꼴: "Gothic A1"
- 새 칸·새 섹션을 만들 때도 이 두 글꼴을 쓴다. 영문 글꼴로 바꾸지 않는다.
- 이탤릭(기울임)은 쓰지 않는다.
- 색은 `style.css` 맨 위 `--main` 과 그 아래 색 변수를 쓴다.
