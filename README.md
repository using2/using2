<div align="center">

# 강유진 · Frontend Developer

<br>

[![Tech Blog](https://img.shields.io/badge/📝_개발_로그-000000?style=for-the-badge&logo=notion&logoColor=white)](https://www.notion.so/using2/2621b5b802128019a974f37fdb951b95)
[![Boostcamp](https://img.shields.io/badge/💻_부스트캠프_활동-000000?style=for-the-badge&logo=notion&logoColor=white)](https://www.notion.so/using2/c47a0e1baf104a3ab536605c4337fd9f)

</div>

<br>

## 🎓 Education & Experience

| 기간 | 활동 | 비고 |
|------|------|------|
| 2022.03 ~ 2026.02 | 인하대학교 컴퓨터공학과 졸업 | |
| 2024.03 ~ 2024.12 | 인하대학교 컴퓨터공학과 42대 학생회 학술국장 | |
| 2024.08 ~ 2024.12 | 네이버 부스트캠프 웹·모바일 9기 멤버십 | |
| 2025.06.26 ~ 2025.06.27 | 2025 INHA SW NET-ZERO 공통 해커톤 | 🥈 우수상 |
| 2025.12 ~ 2026.02 | 현대자동차그룹 소프티어 부트캠프 7기 | |

<br>

## 🗂️ Projects

### Narratix — 장기 취준생을 위한 자기소개서 아카이빙·작성·첨삭 플랫폼

> 2026.01 ~ 2026.02 · 현대자동차 소프티어 부트캠프 7기  
> **[GitHub](https://github.com/softeerbootcamp-7th/WEB-Team7-Jackpot)** · **[narratix.site](https://narratix.site)**

> 일반적인 CRUD 서비스가 아닌,  
> **브라우저 입력 시스템(contentEditable), React 렌더링,  
> 실시간 WebSocket 동기화가 동시에 충돌하는 문제를 다룬 프로젝트**

**역할** Frontend — 실시간 텍스트 에디터 및 협업 첨삭 기능 구현

**기술 스택**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwind-css&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket/STOMP-010101?style=flat-square)

**주요 구현**
- `contentEditable` 기반 커스텀 에디터 설계 및 구현  
  → 한글 IME(composition), 일반 입력(input), 복사·붙여넣기, Enter·Delete, Undo·Redo를
    브라우저 기본 DOM 조작과 분리하여 직접 제어  
  → React state를 단일 진실 원천으로 유지하며,
    리뷰(첨삭) 영역을 포함한 복잡한 DOM 구조에서도
    커서 안정성·입력 동기화·실시간 소켓 이벤트 처리 보장
- Lighthouse 성능 개선 (Performance 56 → 98, **실서비스 기준**)

**기술 블로그 포스트**
- **[Vite + Rollup 번들 최적화로 Lighthouse 성능 56 → 98 개선](https://www.notion.so/using2/Softeer-bootcamp-7-Vite-Rollup-Lighthouse-56-98-3121b5b80212806394f8c48262e06c02)**  
  → 초기 번들 구조 분석, 불필요한 의존성 제거, 코드 스플리팅 전략을 통해 실제 Lighthouse 성능 지표를 개선한 과정 정리
- **[실시간 협업 텍스트 에디터: 동작 흐름 완전 분석](https://www.notion.so/using2/Softeer-bootcamp-7-3131b5b8021280c79fd5c233270cb9e9)**  
  → WebSocket 기반 실시간 입력 처리 흐름, 이벤트 전파 구조, 동시 편집 시 상태 동기화 방식 분석
- **[React + contentEditable에서 Enter·Delete·Undo·Redo 구현과 트러블슈팅](https://www.notion.so/using2/Softeer-bootcamp-7-React-contentEditable-Enter-Delete-Undo-Redo-3091b5b8021280f087e5fbcbd85f2e0d)**  
  → 브라우저 기본 동작 제어, Selection/Range API를 활용한 커스텀 입력 처리 구현 경험

**추가 기술 블로그 포스트**
- **[실시간 텍스트 에디터 버그 고치기](https://www.notion.so/using2/Softeer-bootcamp-7-3121b5b8021280f29fc2db17180386ad)**  
  → 커서 위치 불일치, 입력 누락 등 실제 사용자 환경에서 발생한 버그 원인 추적 및 수정 과정
- **[실시간 협업 자소서 첨삭 서비스의 프론트엔드 데이터 구조 조사](https://www.notion.so/using2/Softeer-bootcamp-7-2fd1b5b802128019bfd5c36a2185cf45)**  
  → 첨삭 코멘트, 문단 단위 상태 관리, 실시간 협업을 고려한 데이터 구조 설계 과정 정리
- **[WebSocket 이벤트 상태 반영 설계](https://www.notion.so/using2/Softeer-bootcamp-7-WebSocket-30b1b5b8021280e48bacd7320e849482)**  
  → 수신 이벤트를 UI 상태로 변환하는 흐름 설계와 컴포넌트 책임 분리 전략
- **[WebSocket 수신 후 컴포넌트 미업데이트 트러블슈팅](https://www.notion.so/using2/Softeer-bootcamp-7-WebSocket-30c1b5b802128064ab1cf7e42ace2118)**  
  → 상태 변경은 되었지만 UI가 갱신되지 않던 문제를 추적하며 React 렌더링 특성을 점검한 사례

<br>

## 💻 Tech Stack

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

**Tools**

![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)

<br>

## 🧠 What I Care About

- React 렌더링과 상태 업데이트의 실제 동작 원리
- 복잡한 UI를 구조로 해결하는 설계
- 성능 저하의 원인을 추적하고 수치로 개선하는 과정
- “왜 이렇게 구현했는지” 설명 가능한 코드
