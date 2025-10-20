# 🍱 한입만조- 배달 플랫폼 백엔드 서버


> **“배달의 민족” ㅣ  “요기요” ㅣ  “쿠팡이츠”** 와 같은 배달 앱을 목표로 개발한 프로젝트입니다.

> 해당 프로젝트에서는 **배달 라이더가 없다고 가정**하고 진행합니다.  
> 주문 요청은 `CUSTOMER` → 가게(`OWNER`)로 전달되며
> 가게가 주문을 수락하고 조리 및 완료 상태를 관리합니다.

---

<img width="300" height="300" alt="logo" src="https://github.com/user-attachments/assets/6791a94e-b523-475c-a85a-c3e2489e34b3" />
 






##  팀원 소개

| 이름 | 역할 | 주요 담당 |
|------|------|------------|
| **배원진** | 리뷰(Review) | 리뷰 작성/조회/수정/삭제, 평점 통계, 글로벌 예외처리 |
| **민송경** | 주문(Order) | 주문 요청/취소/주문 상태 관리/주문 상태 이력 관리/고객별 주문 목록 및 상세정보 조회 |
| **서지희** | 결제(Payment) | 결제 및 거래 승인, 취소 |
| **송준일** | 회원(User) | 회원가입, 로그인, JWT 인증 |
| **노희현** | 가게(Shop) | 가게 등록, 수정, 삭제 및 리뷰와 주문내역 조회 | 
| **남예준** | 상품(Item), AI, 인프라 | 상품 CRUD, AI API, AWS EC2 CI/CD 구축 |

---


##  프로젝트 개요

| 항목 | 내용 |
|------|------|
| **프로젝트명** | Just One Bite |
| **목표** | 광화문 지역 기반 배달 서비스를 위한 백엔드 API 구축 |
| **기간** | 2025.09.26 ~ 2025.10.17 |
| **개발 언어** | Java 21 |
| **프레임워크** | Spring Boot 3.5.6 |
| **데이터베이스** | PostgreSQL |
| **빌드 도구** | Gradle |
| **배포 환경** | AWS EC2, Nginx |
| **CI/CD** | GitHub Actions |
| **버전 관리** | Git & GitHub |

---




## ERD
<img width="2151" height="1232" alt="배달2" src="https://github.com/user-attachments/assets/0a27416d-a5b4-4f11-8576-48d10ca835dc" />





> - User ↔ Order ↔ Payment ↔ Review ↔ Shop ↔ Item 간 다대일 관계로 구성  
> - Soft Delete 및 Auditing 기반으로 데이터 이력 추적 가능  




---




##  기술 스택

| 구분 | 기술 |
|------|------|
| **Language** | Java 21 |
| **Framework** | Spring Boot 3.5.6 / Spring Data JPA / Spring Security / **Spring Scheduler** |
| **Database** | PostgreSQL |
| **Build Tool** | Gradle |
| **Infra** | AWS EC2 / Nginx / RDS |
| **CI/CD** | GitHub Actions |
| **Test** | JUnit 5 / Mockito |
| **Docs & Tool** | Swagger / Postman / Notion / Slack |

---
