
<div align="center">

### 백엔드 개발과 운영 인프라를 함께 경험하고 있습니다.

Java와 Spring 기반의 백엔드 개발을 중심으로 공부하며  
구현한 서비스를 AWS에 배포하고 백업·모니터링·장애 알림까지 검증했습니다.

기능 구현뿐만 아니라 **애플리케이션부터 서버·네트워크까지  
전체 흐름을 이해하고 문제를 해결하는 개발자**를 목표로 하고 있습니다.

[![Email](https://img.shields.io/badge/Email-addicto1122%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:addicto1122@gmail.com)

</div>

---

## 🛠 Tech Stack

### Backend

![Java](https://img.shields.io/badge/Java_21-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring MVC](https://img.shields.io/badge/Spring_MVC-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=flat-square)
![MyBatis](https://img.shields.io/badge/MyBatis-BE3939?style=flat-square)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=flat-square)
![STOMP](https://img.shields.io/badge/STOMP-6A5ACD?style=flat-square)

- Java·Spring 기반 REST API 및 웹 애플리케이션 구현
- Spring Security·JWT HttpOnly 쿠키 인증 및 CSRF 보호
- Refresh Token Rotation, 세션 무효화 및 인증 재발급 처리
- JPA·MyBatis 기반 데이터 접근 및 트랜잭션 처리
- Transactional Outbox를 활용한 데이터 정합성 개선
- WebSocket·STOMP 실시간 기능 및 외부 API 연동 경험

### Database

![MySQL](https://img.shields.io/badge/MySQL_8-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)

- 관계형 데이터 모델링 및 SQL·JOIN·Dynamic SQL 활용
- Flyway 기반 스키마 버전 관리와 DB 마이그레이션
- MongoDB 기반 추천 로그 저장 및 관리
- MySQL·MongoDB 간 삭제 정합성을 고려한 Outbox 처리
- 외부 API 결과 저장·재사용 및 변경 데이터 부분 갱신

### Infrastructure

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

- AWS EC2 기반 WEB·WAS·MySQL·MongoDB 분리 배포
- VPC·Private Subnet·NAT Gateway 기반 네트워크 구성
- Docker·Caddy·Nginx 기반 HTTPS Reverse Proxy 구성
- GitHub Actions·GHCR·AWS Systems Manager 기반 CI/CD
- S3 백업·복원 검증 및 Grafana Cloud 장애 모니터링

### Frontend

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-22B5BF?style=flat-square)

- React·React Router·Hooks 기반 반응형 화면 구현
- Recharts 기반 월간 통계 시각화
- 공통 Fetch 함수를 통한 인증 재발급·CSRF 처리
- jQuery·AJAX·Bootstrap 및 Naver Maps API 활용 경험

---

## 📂 Portfolio

- 💻 **Development** · [Development Portfolio](https://lying-sauce-1dc.notion.site/3e1a87937d55813d8edafd73f05f27ea)

---

## 🚀 Main Projects

<h3>
  <img src="https://raw.githubusercontent.com/addicto1122-lab/mood-and-move/main/frontend/public/favicon.png" width="32" height="32" alt="Mood&Move" align="absmiddle">
  <a href="https://github.com/addicto1122-lab/mood-and-move">Mood&Move｜감정 기록·AI 행동 추천 서비스</a>
</h3>

> 사용자의 감정과 상황을 기록하고 AI가 실천 가능한 행동을 추천하며,  
> 행동 전후의 기분 변화를 월간 통계와 캘린더로 확인할 수 있는 서비스입니다.

**프로젝트 기간:** 2026.09.29 ~ 2026.10.17  
**수행 인원:** 3명  
**운영 상태:** 2026.10.20 운영 종료 (AWS 배포 환경 정리)  
**시연 영상:** [Mood&Move Demo](https://youtu.be/KhvVEx4mxlc)  
**담당 역할:** JWT 쿠키 인증·CSRF 보호·회원/계정 복구·온보딩·통계 UI·회원 탈퇴 데이터 정합성·AWS 인프라

#### 주요 기능

- 감정·일기 기록과 Gemini 기반 행동 추천
- 행동 실천 후 기분 재측정 및 개인화 통계
- 이메일 인증·카카오 OAuth 로그인·비밀번호 재설정
- JWT HttpOnly 쿠키 인증 및 Access/Refresh Token 관리
- 월간 통계·캘린더·마이페이지·계정 복구
- AWS 기반 HTTPS 배포 및 CI/CD·백업·모니터링

#### 개인 구현

**인증·회원 관리**

- 이메일 가입 인증·비밀번호 재설정·카카오 OAuth·계정 복구 구현
- Refresh Token SHA-256 해시 저장·Rotation·폐기
- `tokenVersion` 기반 세션 무효화 처리
- Spring Security CSRF 보호 및 프론트 공통 `csrfFetch()` 구현
- 동시 401 요청의 토큰 재발급 중복 방지 및 원 요청 재시도

**데이터·사용자 기능**

- 취미·활동 선호 온보딩 및 마이페이지 구현
- 월간 감정 통계와 캘린더 UI 개발
- 회원 탈퇴 시 MySQL·MongoDB 정합성을 위한 Transactional Outbox 구성
- 삭제 실패 시 재시도 및 지수 백오프 처리

**배포·운영**

- AWS EC2 4대 기반 WEB·WAS·DB 분리 배포
- GitHub Actions·GHCR·SSM 기반 배포 자동화
- MySQL·MongoDB S3 백업 및 별도 DB 복원 검증
- Grafana Cloud 지표 수집과 Synthetic Monitoring 장애 알림 검증

#### 기술 스택

![Java](https://img.shields.io/badge/Java_21-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_4.1.1-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL_8-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS_EC2-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

<details>
<summary><strong>🔧 주요 설계·운영 경험 펼쳐보기</strong></summary>

<br>

#### 1. JWT 쿠키 인증과 CSRF 보호

**문제**

- HttpOnly 쿠키는 JavaScript의 토큰 접근을 제한하지만, 브라우저의 자동 쿠키 전송 특성으로 인해 CSRF 방어가 필요했습니다.

**해결**

- Spring Security CSRF 보호 적용
- `/api/csrf`에서 `XSRF-TOKEN` 쿠키 발급
- 프론트 공통 `csrfFetch()`에서 `X-XSRF-TOKEN` 헤더 자동 첨부
- 로그인·로그아웃·토큰 재발급 흐름 검증

**결과**

- JWT 쿠키 인증을 유지하면서 상태 변경 요청에 대한 CSRF 검증을 적용했습니다.

---

#### 2. MySQL·MongoDB 회원 탈퇴 데이터 정합성

**문제**

- 서로 다른 데이터베이스의 삭제를 하나의 트랜잭션으로 처리하기 어려워 일부 데이터만 삭제될 위험이 있었습니다.

**해결**

- MySQL 트랜잭션 내에 Outbox 삭제 작업 기록
- 별도 스케줄러에서 MongoDB 삭제 수행
- 삭제 실패 시 지수 백오프 기반 재시도

**결과**

- 외부 저장소 오류가 발생하더라도 삭제 작업을 유실하지 않고 재처리할 수 있도록 구성했습니다.

---

#### 3. AWS 배포·백업·모니터링

**구현**

- WEB·WAS·MySQL·MongoDB를 EC2 4대로 분리
- VPC·Private Subnet·NAT Gateway 구성
- Caddy·Nginx·Docker 기반 HTTPS 서비스 배포
- GitHub Actions·GHCR·SSM 기반 CI/CD
- MySQL·MongoDB S3 자동 백업
- Grafana Cloud 모니터링 및 장애 알림

**검증**

- GitHub Actions 자동 배포 성공
- 별도 테스트 DB에서 백업 복원 및 원본 비교
- Synthetic Monitoring의 Firing → 이메일 수신 → URL 복구 → Normal 확인

</details>

**상세 문서:** [Mood&Move 포트폴리오](https://app.notion.com/p/3faa87937d5581bd929be033523a59c6)

---

<h3>
  <img src="https://raw.githubusercontent.com/addicto1122-lab/meetback/main/src/main/resources/static/images/meetback-logo.svg" width="32" height="32" alt="MeetBack" align="absmiddle">
  <a href="https://github.com/addicto1122-lab/meetback">MeetBack｜안전한 귀가를 고려한 모임 장소 추천 서비스</a>
</h3>

> 여러 참가자의 귀가 시간과 대중교통 막차 정보를 분석해  
> 모두가 안전하게 귀가할 수 있는 모임 장소를 추천하는 서비스입니다.

**프로젝트 기간:** 2026.08.18 ~ 2026.09.02  
**수행 인원:** 4명  
**담당 역할:** 귀가·추천 로직, 외부 API 연동, 지도 시각화, API 호출 최적화

#### 주요 기능

- Kakao Local API 기반 장소·주소 검색
- ODsay API 기반 대중교통 경로 및 막차 조회
- 참가자별 안전 귀가 가능 여부 계산
- 평균 귀가시간·편차 기반 장소 추천
- MyBatis·MySQL 기반 경로·계산 결과 저장 및 재사용
- Naver Maps 기반 이동 경로 시각화
- WebSocket·STOMP 기반 실시간 기능

#### 개인 구현

- 참가자별 귀가 가능 여부 및 막차 계산 로직 구현
- 자정 이후 날짜 보정과 마지막 안전 출발 시각 계산
- 평균 귀가시간·이동시간 편차를 반영한 장소 추천
- 외부 API 조회 결과 저장·재사용 및 부분 재계산
- ODsay 호출 제한 대응을 위한 프록시 요청 제어
- Naver Maps 기반 대중교통 이동 경로 시각화
- 주요 UI 및 다크/라이트 테마 전환 기능 구현

#### 기술 스택

![Java](https://img.shields.io/badge/Java_17-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-BE3939?style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL_8-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

<details>
<summary><strong>🔧 주요 트러블슈팅 펼쳐보기</strong></summary>

<br>

#### 1. ODsay 연속 호출 오류와 긴 대기시간

**문제**

- ODsay API를 연속 호출하면 오류가 발생했습니다.
- 요청마다 1.1초 간격을 적용하는 직렬 방식은 전체 계산 시간이 길어졌습니다.

**해결**

- 애플리케이션과 ODsay 사이에 사설 프록시 서버 구성
- 프록시 내부에서 최대 5개 요청 병렬 처리
- 외부 API로 전달되는 요청에 1.1초 간격 적용

**결과**

- 호출 안정성을 유지하면서 완전 직렬 처리보다 대기시간을 줄였습니다.

---

#### 2. 일일 API 호출 한도 축소 대응

**문제**

- ODsay 일일 호출 한도가 1,000건에서 30건으로 축소되어 기존 전체 재계산 방식의 유지가 어려웠습니다.

**해결**

- 기존 API 응답을 DB에 저장·재사용
- 동일한 계산 조건의 재호출 생략
- 변경된 참가자·장소에 대해서만 부분 재계산

**결과**

- 불필요한 호출을 줄이고 제한된 API 호출량을 효율적으로 사용했습니다.

---

#### 3. 주소 형식에 따른 좌표 조회 오류

**문제**

- 일부 주소에서 의도한 위치와 다른 x·y 좌표가 반환되어 경로 계산에 영향을 주었습니다.

**해결**

- 도로명 주소를 기준으로 Kakao Local API에 좌표 요청
- 반환된 좌표를 거리 계산과 대중교통 경로 조회에 활용

**결과**

- 주소 형식 차이로 발생하던 좌표 오류를 줄였습니다.

---

#### 4. 700m 미만 경로의 ODsay 오류

**문제**

- 출발지와 목적지 사이의 거리가 700m 미만일 때 정상적인 대중교통 경로가 반환되지 않는 문제가 있었습니다.

**해결**

- API 호출 전 좌표 기반 직선거리 계산
- 700m 미만 경로는 대중교통 조회 없이 도보 처리
- 평균 도보 이동시간 10분 적용

**결과**

- 단거리 경로 오류를 방지하고 불필요한 API 호출을 줄였습니다.

---

#### 5. 자정 이후 막차 시간 계산 오류

**문제**

- 자정 이후 막차 시간이 이전 날짜 기준으로 해석되어 귀가 가능 여부가 잘못 판정되었습니다.

**해결**

- ODsay 응답 시간과 서버 날짜 계산 흐름 확인
- 자정을 넘기는 시간에 날짜 보정 적용
- 안전 여유 시간을 반영한 마지막 출발 가능 시각 계산

**결과**

- 날짜 경계에서 발생하는 귀가 가능 여부 오판정을 개선했습니다.

</details>

**상세 문서:** [MeetBack 포트폴리오](https://app.notion.com/p/3e1a87937d5581e3a635ebdcd708133a)

---

## 🖥 Infrastructure Experience

### Service Operation

Mood&Move 프로젝트에서 실제 구축하고 검증한 환경입니다.

- AWS EC2 4대 기반 WEB·WAS·MySQL·MongoDB 역할 분리
- VPC·Public/Private Subnet·NAT Gateway 구성
- Docker·Caddy·Nginx 기반 HTTPS Reverse Proxy
- GitHub Actions·GHCR·SSM 기반 자동 배포
- S3 DB 백업·복원 검증
- Grafana Cloud 지표 수집 및 장애 알림 검증

> 2026.10.20 프로젝트 종료 후 AWS 배포 환경을 정리했습니다.

<details>
<summary><strong>📘 Lab & Training</strong></summary>

<br>

### Server & Virtualization

- WEB·WAS·DB 3-Tier 환경 구성
- VMware Workstation Pro·ESXi·vSphere
- Rocky Linux·CentOS 기반 서버 실습
- TrueNAS iSCSI 기반 Datastore 구성
- vMotion을 이용한 VM 호스트 간 마이그레이션

### Network

- BIND DNS 및 Master/Secondary DNS 구성
- DNS Zone Transfer 실습
- VyOS·CentOS Router 기반 NAT·Firewall·Routing
- GNS3 기반 네트워크 토폴로지 구성
- DHCP·RIP·OSPF·HSRP·VLAN 실습
- UTM 및 VPN 구성

### Container & Orchestration

- Docker Compose 기반 멀티 컨테이너 구성
- Docker Swarm 클러스터 구축
- Kubernetes 3-Node 클러스터 구축
- kubeadm 기반 Control Plane·Worker Node 구성
- Calico CNI 설치 및 Node·Pod 트러블슈팅

### AWS Practice

- VPC·Subnet·Route Table 구성
- EC2·ELB·S3 실습
- 보안 그룹 및 네트워크 접근 제어

</details>

---

## 📜 Certifications

- **리눅스마스터 2급** — KAIT, 2026.10
- **네트워크관리사 2급** — 한국정보통신자격협회, 2025.08
- **PC정비사 2급** — 한국정보통신자격협회, 2025.01
- **전자계산기기능사** — 한국산업인력공단, 2022.12
- **전자기능사** — 한국산업인력공단, 2022.07

---

## 📫 Contact

- **Email:** [addicto1122@gmail.com](mailto:addicto1122@gmail.com)
- **Portfolio:** [Notion Portfolio](https://lying-sauce-1dc.notion.site/3e1a87937d55813d8edafd73f05f27ea)

