---
name: Enterprise
colors:
  primary: "#0C5CAB"
  secondary: "#0a4a8a"
  success: "#10b981"
  warning: "#f59e0b"
  danger: "#ef4444"
  surface: "#09090b"
  text: "#fafafa"
  neutral: "#09090b"
typography:
  h1:
    fontFamily: "IBM Plex Sans"
    fontSize: 2rem
  body-md:
    fontFamily: "IBM Plex Sans"
    fontSize: 1rem
  label-caps:
    fontFamily: "IBM Plex Sans"
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

Dark-themed cloud-platform aesthetic with modular grids, glass-like panels, and strong data hierarchy for productivity dashboards.

## Style Foundations

- **Visual style:** modern, clean, cloud-platform aesthetic (Heroku/Vercel/GitHub inspired), dark theme, subtle gradients, soft shadows, glass-like panels, rounded components
- **Typography scale:** 12/14/16/20/24/32
- **Typography fonts:** primary=IBM Plex Sans, display=IBM Plex Sans, mono=IBM Plex Sans
- **Typography weights:** 100, 200, 300, 400, 500, 600, 700, 800, 900
- **Color palette:** primary, neutral, success, warning, danger
- **Spacing scale:** 8pt baseline grid

## Colors

- **Primary (#0C5CAB):** Token from style foundations.
- **Secondary (#0a4a8a):** Token from style foundations.
- **Success (#10b981):** Token from style foundations.
- **Warning (#f59e0b):** Token from style foundations.
- **Danger (#ef4444):** Token from style foundations.
- **Surface (#09090b):** Token from style foundations.
- **Text (#fafafa):** Token from style foundations.
- **Neutral (#09090b):** Derived from the surface token for official format compatibility.

## 한글 글꼴 (스마택트 추가)

위 설정의 영문 글꼴은 한글을 표시하지 못한다. 이 템플릿은 한글용 글꼴을 따로 쓴다(`index.html` 머리의 글꼴 `<link>` 와 `style.css`).
- 제목 글꼴: "IBM Plex Sans KR"
- 본문 글꼴: "IBM Plex Sans KR"
- 새 칸·새 섹션을 만들 때도 이 두 글꼴을 쓴다. 영문 글꼴로 바꾸지 않는다.
- 이탤릭(기울임)은 쓰지 않는다.
- 색은 `style.css` 맨 위 `--main` 과 그 아래 색 변수를 쓴다.
