<div align="center">

# 🎭 cs_java

### Spring Boot 기반 공연 예매 웹 서비스

공연 조회부터 좌석 예매, 결제, 관리자 기능까지 제공하는 팀 프로젝트입니다.

<br>

![Java](https://img.shields.io/badge/Java-21-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)

</div>

---

## 📌 프로젝트 소개

- **개발 기간**: 2026.10.01 ~ 2026.12.00
- **주요 기능**: 공연 예매 / 결제 / 회원·관리자 권한 관리
- **목표**: Spring Boot와 Git 협업 방식을 익히고 실제 서비스 흐름을 구현

<br>

## 👥 팀원 소개

| 이름 | 역할 | 담당 기능 | GitHub |
|:---:|:---:|:---:|:---:|
| 홍길동 | 팀장 / BE | 예매, 결제 | [@acet09](https://github.com/acet09) |
| 김철수 | BE | 회원, 권한 | [@id](https://github.com/id) |
| 이영희 | FE | 화면 설계 | [@id](https://github.com/id) |

<br>

## ✨ 주요 기능

### 🎫 공연 예매
- 공연 목록 및 상세 조회
- 날짜·회차 선택, 좌석 선택

### 💳 결제
- 예매 내역 확인 후 결제
- 결제 취소 및 환불

### 🔐 권한 관리
- **USER**: 공연 조회, 예매, 결제
- **ADMIN**: 공연 등록·수정·삭제, 예매 현황 관리

<br>

## 🛠 기술 스택

| 구분 | 기술 |
|---|---|
| Language | Java 21 |
| Framework | Spring Boot, Spring Data JPA, Spring Security |
| View | Thymeleaf, HTML, CSS |
| Database | MySQL 8.0 |
| Build | Gradle |
| Tool | IntelliJ IDEA, Git, GitHub, Notion |

<br>

## 📂 프로젝트 구조

```
src/main/java/com/team/csjava
├── controller
├── service
├── repository
├── entity
├── dto
├── config
└── exception
```

<br>

## ▶️ 실행 방법

```bash
# 1. 저장소 clone
git clone https://github.com/acet09/cs_java.git

# 2. IntelliJ로 열기 후 Gradle 로딩 대기

# 3. src/main/resources/application-local.yml 작성 (DB 정보)

# 4. 실행 후 접속
http://localhost:8080
```

<br>

## 📏 협업 규칙

<details>
<summary><b>브랜치 전략</b></summary>

| 브랜치 | 용도 |
|---|---|
| `main` | 배포 가능한 최종 코드 |
| `feature/기능명` | 기능 개발 |
| `fix/버그명` | 버그 수정 |

</details>

<details>
<summary><b>커밋 컨벤션</b></summary>

| 태그 | 의미 |
|---|---|
| `feat` | 새로운 기능 |
| `fix` | 버그 수정 |
| `refactor` | 코드 개선 |
| `docs` | 문서 수정 |
| `style` | 포맷 변경 |
| `chore` | 설정, 빌드 |

예시: `feat: 좌석 선택 기능 추가`

</details>

<br>

## 📸 화면

| 메인 | 예매 |
|:---:|:---:|
| <img src="docs/main.png" width="400"> | <img src="docs/reserve.png" width="400"> |

<br>

## 📝 개발 기록

| 날짜 | 내용 |
|---|---|
| 2026.10.01 | 저장소 생성, 개발 환경 세팅 |
| | |
