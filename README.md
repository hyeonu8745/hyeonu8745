<div align="center">

# 👋 Hi, I'm Jihyeonu · 지현우

### 임베디드 펌웨어부터 분산 시스템까지, 시스템 전 계층을 다루는 엔지니어 지망생

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:jihyeonu910@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/hyeonu8745)
[![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)](https://alkaline-spike-6ba.notion.site/GateMate-26ef71f2d01e80faac8ad06b203a604e)
</div>

---

## 🙋‍♂️ About Me

- 🎓 **인하공업전문대학 컴퓨터시스템공학과** 재학 중
- 🔧 **IoT 임베디드(ESP32)** → **풀스택(Web+Android)** → **클라우드(AWS)** → **온프레미스 고가용성 인프라**까지 매 학기 새 영역에 도전
- 🎯 관심 분야: **시스템 엔지니어링 · 고가용성 아키텍처 · 인프라 최적화**
- 📊 JMeter 1만 동시 요청 환경에서 **Zero-Overbooking 100% · Latency 5~8ms** 달성

---

## 🛠 Tech Stack

**Backend & Language**
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)

**Frontend & Mobile**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)

**Database & Cache**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Infra & DevOps**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**IoT & Embedded**
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberry-pi&logoColor=white)
![TensorFlow Lite](https://img.shields.io/badge/TFLite_MoveNet-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

---

## 🚀 Projects

### 🎫 DEAR TICKET — 고가용성 실시간 티켓팅 시스템
> **2026 · 3학년 1학기 · 졸업작품 진행 중**

**JMeter 1만 동시 요청 환경에서 Zero-Overbooking 100% · Latency 5~8ms 달성**

대규모 트래픽 상황에서 무중단·무오버부킹을 보장하는 온프레미스 기반 티켓팅 플랫폼.
Redisson 분산 락으로 동시성을 제어하고, AI 마이크로서비스 4종을 통합해 지능형 플랫폼으로 확장.

`Spring Boot` `React` `MySQL` `Redis/Redisson` `Docker` `Nginx` `Prometheus` `Grafana` `FastAPI` `GraphSAGE` `Lag-Llama`

- Redisson 분산 락 기반 좌석 동시성 제어 — CPU 100% 환경에서 데드락 0건, 정확히 100석만 선점
- Cloudflare Tunnel 외부 도메인 노출 + Nginx 로드밸런싱 (8080/8081 이중화)
- AI 마이크로서비스 3종 (봇 탐지 GraphSAGE / 수요 예측 Lag-Llama / 추천 RALLRec) Fail-Open 격리
- Prometheus + Grafana 실시간 관측성 환경 (JVM · HTTP · Tomcat 메트릭 시각화)
- KOPIS Open API 연동, Canvas API 배너 동적 색상 추출 등 프론트엔드 리뉴얼

---

### 🛡️ GateMate — AI 기반 스마트 안전 울타리
> **2025 · 2학년 1학기 · 팀 프로젝트 2인 · 전시회 출품**

**ESP32 펌웨어부터 Flutter 앱까지 — IoT 분산 시스템 전 계층 직접 구현**

Raspberry Pi 4(센서부)와 ESP32-CAM(게이트부)을 Wi-Fi로 연동해 사람 접근을 AI로 감지하고 게이트를 자동 제어하는 스마트 안전 울타리 시스템.

`ESP32-CAM (C++)` `Raspberry Pi 4` `Python/Flask` `TFLite MoveNet` `Flutter`

- **담당**: 게이트부 펌웨어 전체 + Wi-Fi 통신 연동 + Flutter 앱 개발
- ISR(인터럽트) 기반 충격 감지 + Ticker 비동기 서보 제어 (1도씩 부드러운 이동)
- 닫히는 중 충격 감지 시 자동 재개방 + 센서부 자동 OFF (장애 복구 로직)
- Flutter 앱: 자동 모드 전환 / 수동 게이트 제어 / Flask 로그 조회

🔗 [Notion 프로젝트 페이지](https://alkaline-spike-6ba.notion.site/GateMate-26ef71f2d01e80faac8ad06b203a604e)

---

### ✈️ Travel Sphere — 풀스택 여행 플랫폼
> **2025 · 2학년 2학기 · AWS 배포까지 직접 수행**

**Web + Android 통합, Socket.IO 실시간 채팅, AWS EC2/RDS 배포**

여행 계획·실시간 채팅·후기 공유 기능을 갖춘 풀스택 여행 플랫폼.
Web(React)과 Android(MVVM) 통합 계정을 구현하고, AWS EC2 + RDS + Nginx + PM2로 직접 배포.

`Node.js` `Express` `Socket.IO` `React` `Android (MVVM)` `MySQL` `JWT` `AWS EC2/RDS` `Nginx` `PM2`

- Socket.IO 실시간 그룹 채팅, Google Maps 여행 일정 시각화
- JWT 인증, multipart 파일 업로드, Web ↔ Android 계정/데이터 연동
- AWS EC2 + RDS(MySQL) + Nginx 리버스 프록시 + PM2 클러스터 운영

🔗 [Local Repo](https://github.com/hyeonu8745/travel-platform) · [AWS 배포판](https://github.com/hyeonu8745/travel-platform-aws)

---

### 🎬 Movie Info System — TMDB 영화 정보 관리
> **2025 · 2학년 1학기 · 팀 프로젝트 3인**

TMDB API를 활용한 영화 정보 검색·즐겨찾기·리뷰 관리 시스템.

`Java` `Swing GUI` `MySQL` `JDBC` `TMDB API`

- **담당**: DB 연동(DAO 계층 전체) + GUI 이벤트 처리 + 비즈니스 로직 구현

🔗 [Repository](https://github.com/hyeonu8745/movie_info_system)

---

## 🏆 Key Achievements

| 지표 | 수치 |
|---|---|
| JMeter 부하 테스트 동시 유저 | **10,000명** |
| Zero-Overbooking 성공률 | **100%** |
| 평균 응답 속도 (부하 환경) | **5~8ms** |
| 통합 AI 마이크로서비스 | **4종** (봇 탐지 · 수요 예측 · 추천 · 챗봇) |

---

<div align="center">

📧 jihyeonu910@gmail.com · 🔗 [github.com/hyeonu8745](https://github.com/hyeonu8745)

</div>
