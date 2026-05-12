<div align="center">

# 👋 Hi, I'm Jihyeonu

### 임베디드부터 분산 시스템까지, 시스템 전 계층을 다루는 엔지니어 지망생

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/hyeonu8745)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jihyeonu910@gmail.com)
[![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)](https://alkaline-spike-6ba.notion.site/GateMate-26ef71f2d01e80faac8ad06b203a604e)

</div>

---

## 🙋‍♂️ About Me

- 🎓 **인하공업전문대학 컴퓨터시스템공학과** 재학 중
- 🔧 **클라우드(AWS) · 온프레미스 · IoT 임베디드** 모두 경험
- 🎯 관심 분야: **시스템 엔지니어링 · 인프라 · 고가용성 아키텍처**
- 🌱 매 학기 새 영역에 도전하며 시스템 전 스택을 다루고 있습니다

---

## 🛠 Tech Stack

### Backend & Language
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=spring-boot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

### Frontend & Mobile
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)

### Database & Cache
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

### Infra & DevOps
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

### Embedded & IoT
![ESP32](https://img.shields.io/badge/ESP32-000000?style=flat-square&logo=espressif&logoColor=white)
![RaspberryPi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat-square&logo=raspberry-pi&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)

---

## 🚀 주요 프로젝트

### 🎫 DEAR TICKET — 고가용성 실시간 티켓팅 시스템 *(2026, 졸업작품 진행 중)*
> **JMeter 1만 동시 요청 환경에서 Zero-Overbooking 100% 달성**

- **Stack**: Spring Boot, React, MySQL, Redis(Redisson), Docker, Nginx, Prometheus, Grafana, FastAPI
- **핵심 성과**:
  - Redisson 분산 락으로 동시성 제어 → 100석 환경에서 정확히 100건 예매 보장
  - 평균 응답 속도 **5~8ms**, CPU 100% 환경에서도 데드락 0건
  - AI 마이크로서비스 4종 통합 (봇 탐지·수요 예측·추천·챗봇)
  - Prometheus + Grafana 기반 실시간 관측성 환경 구축

📂 *Repository: 비공개*

---

### 🛡️ GateMate — AI 기반 스마트 안전 울타리 *(2학년 1학기, 전시회 출품)*
> **ESP32 펌웨어부터 Flutter 앱까지 — IoT 분산 시스템 전 계층 직접 구현**

- **Stack**: ESP32-CAM (C++), Raspberry Pi 4 (Python/Flask), Flutter, MoveNet (TFLite)
- **본인 역할**: 게이트부 펌웨어 + Wi-Fi 통신 연동 + Flutter 앱 전체
- **기술 포인트**:
  - 인터럽트(ISR) 기반 충격 감지 + 비동기 Ticker 서보 제어
  - AsyncWebServer로 HTTP 양방향 통신
  - 닫히는 중 충격 발생 시 자동 재개방 + 센서부 자동 OFF (장애 복구 로직)

🔗 [Notion 프로젝트 페이지](https://alkaline-spike-6ba.notion.site/GateMate-26ef71f2d01e80faac8ad06b203a604e)

---

### ✈️ Travel Sphere — 풀스택 여행 플랫폼 *(2학년 2학기)*
> **Web + Android + Backend 통합, AWS 배포까지 직접 수행**

- **Stack**: Node.js, Express, Socket.IO, React (Vite), Android (Java, MVVM), MySQL, JWT
- **배포**: AWS EC2 + RDS(MySQL) + Nginx Reverse Proxy + PM2
- **핵심 기능**:
  - Socket.IO 기반 실시간 그룹 채팅
  - Google Maps 기반 여행 일정 시각화
  - JWT 인증 + multipart 파일 업로드
  - Web ↔ Android Cross-platform 계정/데이터 연동

🔗 [Local Repo](https://github.com/hyeonu8745/travel-platform) | 🔗 [AWS 배포판](https://github.com/hyeonu8745/travel-platform-aws)

---

### 🎬 Movie Info System — TMDB 영화 정보 관리 *(2학년 1학기, 팀 프로젝트)*
> **Java + JDBC 기반 DAO 패턴, 외부 API 연동 기초 학습**

- **Stack**: Java, Swing GUI, MySQL, JDBC, TMDB API
- **본인 역할**: DB 연동(DAO 계층) + GUI 이벤트 처리 + 비즈니스 로직

🔗 [Repository](https://github.com/hyeonu8745/movie_info_system)

---

## 📈 GitHub Stats

<div align="center">

![Jihyeonu's GitHub stats](https://github-readme-stats.vercel.app/api?username=hyeonu8745&show_icons=true&theme=tokyonight)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=hyeonu8745&layout=compact&theme=tokyonight)

</div>

---

## 📫 Contact

- 📧 Email: **jihyeonu910@gmail.com**
- 💼 GitHub: [@hyeonu8745](https://github.com/hyeonu8745)
