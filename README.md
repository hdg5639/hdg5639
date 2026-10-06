# 한동균

**Backend · Platform · Infrastructure**

Java / Spring 기반 백엔드를 중심으로,  
**직접 만들고 · 직접 배포하고 · 직접 운영하는 개발**을 좋아합니다.

Self-hosted cloud platform **GamjaBox**와 알고리즘 학습 플랫폼 **GamjaOJ**를 만들고 운영하고 있습니다.

[![GamjaBox](https://img.shields.io/badge/GamjaBox-Live-16A34A?style=flat-square&logo=cloudflare&logoColor=white)](https://gamjabox.cloud)
[![GamjaOJ](https://img.shields.io/badge/GamjaOJ-Live-2563EB?style=flat-square&logo=googlechrome&logoColor=white)](https://gamjaoj.gamjabox.cloud)
[![Blog](https://img.shields.io/badge/Blog-cod--ing.tistory.com-111827?style=flat-square&logo=tistory&logoColor=white)](https://cod-ing.tistory.com/)
[![Email](https://img.shields.io/badge/Email-hdg5639%40naver.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:hdg5639@naver.com)

---

## Now

- 🎓 **SSAFY** — 2026.07 ~
- ☁️ **GamjaBox** — Self-hosted IaaS + semi-PaaS 고도화
- 🥔 **GamjaOJ** — Online Judge + personalized coding training platform 개발
- 🔧 관심사 — Backend Systems · Platform Engineering · Infrastructure · Developer Tools

---

## Featured Work

### ☁️ [GamjaBox](https://github.com/hdg5639/GJ-Cloud) — Self-hosted IaaS / semi-PaaS

> 개인 Proxmox 서버 위에 직접 구축한 셀프호스팅 클라우드 플랫폼  
> **VM 생성 → 접속 → 보안 → 배포 → 운영**을 하나의 흐름으로 자동화합니다.

제가 가장 오래 만들고, 가장 애착을 가지고 운영하는 프로젝트입니다.

단순한 VM 생성기를 넘어서, **개발자가 인프라를 직접 만지지 않아도 서비스를 배포할 수 있는 환경**을 만드는 것이 목표입니다.

**Key engineering**

- **Provisioning** — Proxmox clone, cloud-init, DHCP, disk resize, SSH readiness 검증 자동화
- **Access & Security** — Cloudflare Tunnel / Zero Trust, SSH 서브도메인, audience-scoped service token
- **Deployment** — Git 저장소 기반 배포, Docker Compose / Caddy 생성·검증, 내부 네트워크 구성
- **Architecture** — Auth / User / VM / Ops를 신뢰 경계와 변경 주기에 따라 분리
- **Operations** — GitHub Actions CI/CD, PostgreSQL 성능 측정 및 인덱스·조회 구조 개선

**Stack**  
`Java` `Spring Boot` `Spring Security` `PostgreSQL` `Redis` `Next.js` `Docker` `Proxmox` `Cloudflare`

**[Repository](https://github.com/hdg5639/GJ-Cloud) · [Live](https://gamjabox.cloud)**

---

### 🥔 [GamjaOJ](https://github.com/hdg5639/GamjaOJ) — Online Judge & Coding Training Platform

> 문제를 풀고 끝나는 것이 아니라  
> **제출 → 채점 → 분석 → 약점 파악 → 다음 훈련**으로 이어지는 알고리즘 학습 플랫폼

최근 가장 크게 진행하고 있는 개인 프로젝트입니다.

**Key engineering**

- **Isolated Judge** — Java 8 / C++17 / Python 3.12 제출을 Docker 기반 Runner에서 격리 실행
- **Async Processing** — 채점·문제 생성·외부 저장을 HTTP 요청과 분리한 Worker 구조
- **AI Validation** — 생성 문제를 정답 코드, 오답 코드, 비공개 테스트로 다시 검증
- **Learning Data** — 실행 시간·메모리·풀이 기록·진단 결과를 이용한 맞춤 훈련 흐름
- **Integrations** — GitHub App / Notion OAuth 기반 AC 풀이 자동 기록
- **Operations** — PostgreSQL migration, retry, idempotency, 브라우저 비동기 경합 등 운영 이슈 대응

**Stack**  
`Java 21` `Spring Boot 3.5` `PostgreSQL` `Next.js 16` `React 19` `Python` `Docker` `Playwright`

**[Repository](https://github.com/hdg5639/GamjaOJ) · [Live](https://gamjaoj.gamjabox.cloud)**

---

## What I care about

- **Backend beyond CRUD** — 인증, 비동기 작업, 실패 복구, 데이터 일관성
- **Things that actually run** — 로컬 데모보다 실제 배포·운영 환경에서의 동작
- **Infrastructure as a product** — 반복되는 인프라 작업을 개발자 경험으로 바꾸는 것
- **Measure before optimizing** — 감이 아니라 실행 시간, 메모리, 쿼리 플랜으로 병목 확인

---

## Team & Organization Projects

- 🎪 **[Eventory](https://github.com/Likelion-13th-EGSBI)** — AI 기반 지역 맞춤형 행사 기획 서비스
- ♻️ **[새로고침 (Refresh)](https://github.com/TEAM-CP6Q/Reload_F5)** — 환경 보호와 자원 재활용을 중심으로 한 종합 플랫폼
- 🥗 **[우리동네영양사](https://github.com/dongsubnambuk/LikeLion-12th-Hackathon)** — 건강한 도시락 정기 구독 서비스
- 🦁 **[LIKELION 13th Attendance](https://github.com/dongsubnambuk/likelion_att)** — 출결·일정·교육자료 관리 플랫폼 · **Backend**

---

## Stack

**Backend**  
`Java` · `Spring Boot` · `Spring Security` · `JPA`

**Data**  
`PostgreSQL` · `MySQL` · `Redis`

**Infra / DevOps**  
`Docker` · `Proxmox` · `Cloudflare` · `GitHub Actions` · `Jenkins` · `Nginx`

**Frontend / Tools**  
`Next.js` · `React` · `Python`

---

## Experience

**SSAFY** · Trainee  
2026.07 ~ Present

**멋쟁이사자처럼 대학 13기** · 운영진  
2025.01 ~ 2025.12

**코드클럽 찾아가는 SW교육기부단 코딩가딩가팀** · 팀원  
2025.04 ~ 2025.05

**멋쟁이사자처럼 대학 12기** · 아기사자  
2024.01 ~ 2024.12

---

<details>
<summary><b>🏆 Awards & Publications</b></summary>
<br>

### Awards

- **2025 지역혁신 인재양성 연합 페스티벌** — AI · DX 산출물 부문 우수상
- **2025 코드 인사이트 챌린지** — PT 부문 우수상
- **2025 캡스톤디자인 작품발표회** — 우수상
- **AIDEA(AI+IDEA) 공모전** — 사랑상
- **한국정보기술학회 2025 하계종합학술대회 대학생논문경진대회** — 은상
- **2024 4차 산업혁명 인재양성 공유 협업 페스티벌** — ICT 솔루션(코딩) 부문 우수상
- **한국정보기술학회 2024 추계종합학술대회** — 우수논문상

### Publications

- **N-그램 및 임베딩 기반 표절 탐지 성능 비교** — 2024 한국정보기술학회 · [DBpia](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12025335)
- **대학 챗봇 활용의 인식 및 효율성 평가** — 2024 한국정보기술학회 · [DBpia](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12025346)

### Certification

- **SQLD** — SQL Developer

</details>

---

> **Build it. Ship it. Run it. Improve it.**
