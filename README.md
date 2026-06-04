![header](https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=200&section=header&fontSize=50&fontColor=ffffff&animation=fadeIn)

<div align="center">
<h1>Dohyun's GitHub</h1>
                     
[![Static Badge](https://img.shields.io/badge/GitHub-%23181717?style=plastic&logo=GitHub&logoColor=ffffff)](https://github.com/ehtm01)
[![Static Badge](https://img.shields.io/badge/instagram-%23FF0069?style=plastic&logo=instagram&logoColor=ffffff)](https://www.instagram.com/d___ohyun/)
[![https://solved.ac/profile/ehtm75](http://mazassumnida.wtf/api/mini/generate_badge?boj=ehtm75)](https://solved.ac/ehtm75)

</div>

---

## 👋 About Me

> 프론트엔드와 백엔드를 두루 경험한 풀스택 지향 개발자입니다.
> 
> 반도체 제조 현장에서 쌓은 데이터 분석 습관을 소프트웨어 설계로 이어가고 있으며,
> 
> **금융권 IT 개발**을 목표로 성장하고 있습니다.

- 🔭 현재 **SSAFY 14기** 과정에서 실전 프로젝트를 진행하고 있습니다.
- 🤖 **Claude Code · MCP · Jira 자동화** 등 AI 에이전트를 실무에 적극 활용합니다.
- 🌱 새로운 기술을 빠르게 학습하고, 팀에서 리더 역할을 맡아 협업합니다.

---

## 🏆 Awards

| 수상 | 대회 | 프로젝트 |
|:---:|:---|:---|
| 🥇 최우수상 (1등) | SSAFY 자율 프로젝트 경진대회 | **GluCoach** |
| 🥈 우수상 (2등) | SSAFY 특화 프로젝트 경진대회 | **GGulJob** |
| 🏅 우수상 | SSAFY 공통 프로젝트 경진대회 | **HearO** |

---

## 🚀 Projects

### 🩺 GluCoach — 당뇨 환자 혈당·식단 관리 앱 (Android)
> CGM 데이터와 AI를 결합한 능동형 혈당 코칭 서비스
> (AI 코칭 에이전트 · 혈당 예측 LSTM · 음식 인식 · RAG)
- **Role**: Backend 리더 / Git 버전 관리
- **Stack**: `Spring Boot 3.5` `Java 21` `Spring Security / JWT` `PostgreSQL` `Redis` `FastAPI 연동`
- AI 음식 인식 파이프라인(BE ↔ AI 서버 연동) 구현
- 혈당 예측 외부 호출을 DB 트랜잭션 밖으로 분리 (`@Async` + `CompletableFuture`)
- Refresh Token SHA-256 해시 등 인증·보안 체계 설계

### 💼 GGulJob — AI 채용 로드맵 플랫폼
> 팀 빌딩 + Neo4j 기반 팀원 추천 + Claude API 커리어 챗봇
- **Role**: Frontend 리더
- **Stack**: `React 19` `TypeScript` `Zustand` `Vite` `Tailwind CSS` `Axios`
- 채용공고 필터·정렬·페이지네이션을 `useMemo`로 캐싱해 불필요한 재계산 제거
- 백엔드 일부(ProjectService, GitHub PR 동기화)도 직접 구현

### 🎙️ HearO — 실시간 음성 상담 시스템
> WebRTC 기반 콜센터 상담원 보호 서비스 (AI 음성 마스킹)
- **Role**: Frontend 리더
- **Stack**: `Vue 3` `Pinia` `LiveKit` `STOMP.js` `TailwindCSS`
- LiveKit Composable(`useLiveKit`) 설계로 역할별 오디오 파이프라인 분기
- WebSocket 자동 재연결 로직으로 실시간 대기열 안정성 확보

---

## 🛠️ Tech Stack

### Languages
![Java](https://img.shields.io/badge/Java-%23ED8B00?style=plastic&logo=openjdk&logoColor=ffffff)
![Python](https://img.shields.io/badge/Python-%233776AB?style=plastic&logo=Python&logoColor=ffffff)
![TypeScript](https://img.shields.io/badge/TypeScript-%233178C6?style=plastic&logo=TypeScript&logoColor=ffffff)
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E?style=plastic&logo=javascript&logoColor=%23000000)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26?style=plastic&logo=HTML5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%23663399?style=plastic&logo=CSS&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-%2361DAFB?style=plastic&logo=React&logoColor=black)
![Vue.js](https://img.shields.io/badge/Vue.js-%234FC08D?style=plastic&logo=Vue.js&logoColor=%23ffffff)
![Zustand](https://img.shields.io/badge/Zustand-%23433e38?style=plastic&logoColor=%23ffffff)
![Pinia](https://img.shields.io/badge/Pinia-%23FFD859?style=plastic&logoColor=%23000000)
![Vite](https://img.shields.io/badge/Vite-%23646CFF?style=plastic&logo=Vite&logoColor=%23ffffff)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-%2306B6D4?style=plastic&logo=tailwindcss&logoColor=%23ffffff)

### Backend
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-%236DB33F?style=plastic&logo=SpringBoot&logoColor=%23ffffff)
![Spring Security](https://img.shields.io/badge/Spring%20Security-%236DB33F?style=plastic&logo=SpringSecurity&logoColor=%23ffffff)
![Django](https://img.shields.io/badge/Django-%23092E20?style=plastic&logo=Django&logoColor=%23ffffff)

### Database
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%234169E1?style=plastic&logo=PostgreSQL&logoColor=%23ffffff)
![MySQL](https://img.shields.io/badge/MySQL-%234479A1?style=plastic&logo=MySQL&logoColor=%23ffffff)
![Redis](https://img.shields.io/badge/Redis-%23FF4438?style=plastic&logo=Redis&logoColor=%23ffffff)
![SQLite](https://img.shields.io/badge/SQLite-%23003B57?style=plastic&logo=SQLite&logoColor=%23ffffff)

### Tools & Collaboration
![Git](https://img.shields.io/badge/Git-%23F05032?style=plastic&logo=Git&logoColor=%23ffffff)
![GitLab](https://img.shields.io/badge/GitLab-%23FC6D26?style=plastic&logo=GitLab&logoColor=%23ffffff)
![Docker](https://img.shields.io/badge/Docker-%232496ED?style=plastic&logo=Docker&logoColor=%23ffffff)
![Jira](https://img.shields.io/badge/Jira-%230052CC?style=plastic&logo=jira&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-%23FF6C37?style=plastic&logo=postman&logoColor=%23ffffff)
![VSCode](https://img.shields.io/badge/VSCode-%230078d7?style=plastic&logo=visualstudiocode&logoColor=%23ffffff)
![Claude](https://img.shields.io/badge/Claude-%23D97757?style=plastic&logo=anthropic&logoColor=%23ffffff)

---

## 📜 Certificates

![SQLD](https://img.shields.io/badge/SQLD-%23003B57?style=flat-square&logoColor=white)
![컴퓨터활용능력 1급](https://img.shields.io/badge/컴퓨터활용능력%201급-blue?style=flat-square)
![TOEIC Speaking IH](https://img.shields.io/badge/TOEIC%20Speaking-IH-orange?style=flat-square)

---

## 📊 GitHub Stats

<div align="center">

![Dohyun's GitHub stats](https://github-readme-stats-two-eta-pnbbmttmcc.vercel.app/api?username=ehtm01&show_icons=true&theme=radical&count_private=true)

</div>

---

<details>
<summary>👔 Where Am I 👔</summary>
<div markdown="1">

- **2017.03 ~ 2024.02** &nbsp; **PKNU** — Display & Semiconductor Engineering
- **2024.04 ~ 2024.12** &nbsp; **Maryalo** — 반도체 부품 제조
- **2025.07 ~ ing** &nbsp; **SSAFY** 14기

</div>
</details>

![footer](https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=180&section=footer)
