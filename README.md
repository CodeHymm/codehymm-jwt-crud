# codehymm-jwt-crud
Spring Boot 기반 JWT 로그인 및 CRUD API 템플릿

## 🧾 기본 제공 기능

| 구분                   | 내용                                                       |
| -------------------- | -------------------------------------------------------- |
| 🔐 **JWT 로그인/회원 인증** | 회원가입, 로그인, 토큰 발급 및 검증                                    |
| 👤 **User CRUD API** | 사용자 등록, 조회, 수정, 삭제                                       |
| 🧩 **Swagger 문서화**   | API 테스트 및 문서 자동 생성                                       |
| ⚙️ **환경 구성 파일**      | `application.yml`, `Dockerfile`, `docker-compose.yml` 제공 |
| 💾 **H2 내장 DB 샘플**   | 별도 DB 설치 없이 즉시 실행 가능                                     |

---

## 🔧 요청 시 확장 개발 가능 항목

| 구분                     | 내용                              | 추가 비용(예시) |
| ---------------------- | ------------------------------- | --------- |
| 🧠 **Role/권한 관리 기능**   | ADMIN/USER 권한 기반 접근 제어          | +10만원     |
| 🗂️ **다른 도메인 CRUD 추가** | 예: 게시판, 상품, 주문 등                | +10만원     |
| 🗄️ **DB 교체 지원**       | MySQL, PostgreSQL 등 환경 맞춤 세팅    | +5만원      |
| ☁️ **서버 배포 지원**        | Docker 기반 클라우드 배포 (AWS/Naver 등) | +10~20만원  |
| 🔄 **API 통합**          | 외부 서비스 연동 (결제, 인증, 이메일 등)       | 협의        |

> 💬 **추가 기능이 필요하시면 문의주세요.**
> CodeHymm이 귀하의 서비스 환경에 맞게 빠르고 안정적으로 확장해드립니다.

---

## 📄 API 예시

| Method   | Endpoint              | Description  |
| -------- | --------------------- | ------------ |
| `POST`   | `/api/v1/auth/signup` | 회원가입         |
| `POST`   | `/api/v1/auth/login`  | 로그인 (JWT 발급) |
| `GET`    | `/api/v1/users`       | 사용자 목록 조회    |
| `GET`    | `/api/v1/users/{id}`  | 사용자 상세 조회    |
| `PUT`    | `/api/v1/users/{id}`  | 사용자 정보 수정    |
| `DELETE` | `/api/v1/users/{id}`  | 사용자 삭제       |

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

## 💬 문의

> 📧 **CodeHymm**
> 빠르고 안정적인 백엔드 구축이 필요하신가요?
> [크몽 프로필](https://kmong.com) 또는 GitHub 이슈를 통해 문의주세요.

