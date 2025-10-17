
---

## ⚙️ 주요 기술 스택
- **Java 21**, **Spring Boot 3.x**
- **Gradle** 기반 빌드
- **JWT(Json Web Token)** 인증
- **JPA (Hibernate)** CRUD 구현
- **Swagger (springdoc-openapi)** API 문서화
- **H2 / PostgreSQL** 지원
- **Docker Compose** 실행 환경 포함

---

## 🧾 기본 제공 기능

| 구분 | 내용 |
|------|------|
| 🔐 **JWT 로그인/회원 인증** | 회원가입, 로그인, 토큰 발급 및 검증 |
| 👤 **User CRUD API** | 사용자 등록, 조회, 수정, 삭제 |
| 🧩 **Swagger 문서화** | API 테스트 및 문서 자동 생성 |
| ⚙️ **환경 구성 파일** | `application.yml`, `Dockerfile`, `docker-compose.yml` 제공 |
| 💾 **H2 내장 DB 샘플** | 별도 DB 설치 없이 즉시 실행 가능 |

---

## 🔧 요청 시 확장 개발 가능 항목

| 구분 | 내용 | 추가 비용(예시) |
|------|------|----------------|
| 🧠 **Role/권한 관리 기능** | ADMIN/USER 권한 기반 접근 제어 | +10만원 |
| 🗂️ **맞춤형 도메인 CRUD 추가** | 예: 게시판, 상품, 주문 등 고객 요청에 따라 신규 API 구현 | +10만원 |
| 🗄️ **DB 교체 지원** | MySQL, PostgreSQL 등 환경 맞춤 세팅 | +5만원 |
| ☁️ **서버 배포 지원** | Docker 기반 클라우드 배포 (AWS/Naver 등) | +10~20만원 |
| 🔄 **API 통합** | 외부 서비스 연동 (결제, 인증, 이메일 등) | 협의 |

> 💡 맞춤형 CRUD 추가는 **하나의 도메인(엔티티)** 기준으로 제공됩니다.  
> 예: 게시판(Post) 1개, 상품(Product) 1개 단위로 산정합니다.  
> 추가적인 기능(댓글, 검색, 업로드 등)은 별도 협의로 진행됩니다.

---

## 📄 API 예시

| Method | Endpoint | Description |
|--------|-----------|--------------|
| `POST` | `/api/v1/auth/signup` | 회원가입 |
| `POST` | `/api/v1/auth/login` | 로그인 (JWT 발급) |
| `GET` | `/api/v1/users` | 사용자 목록 조회 |
| `GET` | `/api/v1/users/{id}` | 사용자 상세 조회 |
| `PUT` | `/api/v1/users/{id}` | 사용자 정보 수정 |
| `DELETE` | `/api/v1/users/{id}` | 사용자 삭제 |

---

## 🧱 구조 예시
```

src/
├─ main/
│   ├─ java/com/codehymm/jwtcrud/
│   │   ├─ controller/
│   │   ├─ service/
│   │   ├─ entity/
│   │   └─ security/
│   └─ resources/
│       ├─ application.yml
│       └─ schema.sql
└─ build.gradle

```

---

## 💰 제공 및 가격 안내

| 구분 | 내용 | 가격 |
|------|------|------|
| ✅ **기본형** | JWT 로그인 + User CRUD + Swagger + Docker 환경 구성 | **10만원** |
| ⚙️ **확장형 (옵션)** | Role/권한 기능, DB 교체, 추가 CRUD 개발 | +5~20만원 |
| 🚀 **프리미엄형 (옵션)** | 서버 배포, 외부 API 통합, 맞춤형 확장 지원 | 협의 |

> 본 템플릿은 **완성된 백엔드 모듈(소스코드)** 을 제공하는 서비스입니다.  
> 고객의 프로젝트에 직접 참여하거나, 시스템에 접속하여 설치를 대행하지 않습니다.

---

## 💬 문의
> 📧 **CodeHymm**  
> 본 템플릿은 완성된 소스코드와 실행 가이드가 포함된 형태로 제공됩니다.  
> 구매 후 즉시 실행 가능한 환경이 제공되며, 추가 개발이 필요한 경우 아래 경로로 문의해 주세요.  
>  
> - 📩 **문의 방법:** [크몽 프로필](https://kmong.com) / [GitHub Issue](https://github.com/CodeHymm/codehymm-jwt-crud/issues)  
> - ⚙️ **추가 요청 예시:** Role/권한 기능, CRUD 확장, DB 교체, 배포 설정 등  
>
> CodeHymm은 귀하의 서비스 환경에 맞는 **실용적이고 안정적인 백엔드 솔루션**을 제공합니다.  
>  
> © 2025 CodeHymm. All rights reserved.
```

---


