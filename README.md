<div align="center">

# Yeeun Shin · 신예은

**상상한 것을 직접 기획하고, 디자인하고, 개발해 현실로 만듭니다.**<br/>
<sub>I plan, design, and build what I imagine — and turn it into something real.</sub>

<br/>

[![Email](https://img.shields.io/badge/Email-1f2328?style=flat-square&logo=gmail&logoColor=white)](mailto:bliass9050@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-1f2328?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yeeun-shin-437b57250)

</div>

<br/>

## About

백엔드 개발자를 꿈꾸며, AI와 함께 빠르게 변하는 시대에 발맞춰 성장하고 있는 학생입니다.
한 가지 역할에 머무르기보다 AI를 활용해 지식의 폭을 넓히고, 문제를 발견해 해결책을 만드는 일을 좋아합니다.

- 팀에서는 **방향을 잡고 프로젝트를 꾸준히 정리**하는 역할을 주로 맡습니다.
- 각자의 장점이 살아날 때 팀이 가장 잘 움직인다고 믿기에, **소통과 배려**를 중요하게 생각합니다.
- 비전 — *내가 만든 서비스로 사람들에게 즐거움과 행복을 주는 것.*

<details>
<summary><sub>English</sub></summary>
<br/>

A student aspiring to be a backend developer, growing alongside AI in a fast-changing world.
Rather than staying in a single role, I use AI to broaden what I know, and I enjoy finding problems and building solutions for them.

- On teams, I usually **set direction and keep the project organized** from start to finish.
- I believe a team works best when everyone's strengths come alive, so I value **communication and consideration** for my teammates.
- Vision — *to bring joy and happiness to people through the services I build.*

</details>

<br/>

## Tech Stack

**Backend**<br/>
![Java](https://img.shields.io/badge/Java-1f2328?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-1f2328?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-1f2328?style=flat-square&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/Spring_Data_JPA-1f2328?style=flat-square&logo=hibernate&logoColor=white)

**Database · Infra**<br/>
![MySQL](https://img.shields.io/badge/MySQL-1f2328?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-1f2328?style=flat-square&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_EC2_·_RDS_·_S3-1f2328?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-1f2328?style=flat-square&logo=docker&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-1f2328?style=flat-square&logo=nginx&logoColor=white)

**Learning**<br/>
![React Native](https://img.shields.io/badge/React_Native-f6f8fa?style=flat-square&logo=react&logoColor=1f2328)
![TypeScript](https://img.shields.io/badge/TypeScript-f6f8fa?style=flat-square&logo=typescript&logoColor=1f2328)
![React](https://img.shields.io/badge/React-f6f8fa?style=flat-square&logo=react&logoColor=1f2328)

<br/>

## Projects

### 🏠 dormapp &nbsp;<sub>Full-stack · 기획 · 디자인 · 개발</sub> &nbsp;![Private](https://img.shields.io/badge/공개_예정-f6f8fa?style=flat-square)
숭실대 기숙사생을 위한 통합 앱 — 공동구매와 기숙사 생활을 한곳에서.<br/>
<sub>An all-in-one app for Soongsil University dorm residents: group buying + dorm life.</sub>

- 카카오 소셜 로그인 (Spring Security + JWT)
- WebSocket(STOMP) 기반 1:1 채팅, Redis로 마지막 메시지 캐싱 (장애 시 DB 폴백)
- Jsoup으로 숭실대 기숙사 사이트 연동 — HTML 파싱 및 폼 자동 제출
- AWS EC2 · RDS · S3 배포, Swagger로 API 문서화

<sub>`Java 21` `Spring Boot 3` `JPA` `MySQL 8` `Redis` `WebSocket` `AWS` · `Expo` `React Native` `React Navigation 7` `axios`</sub>

---

### 📑 [문서반장](https://github.com/UNITHON-iguana/web_backend) &nbsp;<sub>Backend</sub>
건설 현장의 사진대지 작성·엑셀 정리 업무를 AI로 자동화하는 서비스.<br/>
<sub>Automates construction-site photo reports and Excel paperwork with AI.</sub>

- 현장 사진 업로드 → AI OCR·정형화 결과를 표준 데이터로 저장·검수·집계·문서화
- Apache POI로 수식이 포함된 엑셀 문서 자동 생성
- WebFlux(WebClient) 기반 비동기 병렬 HTTP 통신으로 외부 AI 서버 연동
- AWS EC2 + nginx 리버스 프록시 + systemd 배포

<sub>`Java 21` `Spring Boot 4` `Spring Security` `JWT` `JPA` `MySQL` `AWS S3` `Apache POI` `WebFlux`</sub>

---

### 📚 [ReadMate](https://github.com/database-7/backend) &nbsp;<sub>Backend</sub>
독서 모임 플랫폼 — 책 교환 릴레이, 독서 모임, 게시글 공유.<br/>
<sub>A book club platform with book-exchange relays, reading groups, and post sharing.</sub>

- 개인 독서 카드(도서 · 후기 · 읽은 날짜 · 평점 · 읽기 상태) 목록 조회 API 구현
- 도서 API 연동 메인 페이지 (신간 · 베스트셀러 · 관련 기사)
- Firebase(FCM) 푸시 알림, Docker 배포

<sub>`Java 17` `Spring Boot 3.2` `JPA` `MySQL` `JWT` `FCM` `Docker`</sub>

---

### 🛒 [Soongpal](https://github.com/soongpal/backend) &nbsp;<sub>Backend</sub>
숭실대 기숙사생 공동구매 서비스. dormapp의 출발점이 된 프로젝트입니다.<br/>
<sub>A group-buying service for Soongsil dorm residents — the project that became dormapp.</sub>

<sub>`Java` `Spring Boot`</sub>

<br/>

<div align="center">

<sub>Seoul, Korea · 보고, 듣고, 경험한 것에서 좋은 기획이 시작된다고 믿습니다.</sub>

</div>
