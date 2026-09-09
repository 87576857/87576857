### 이주혁 | Backend Developer

건축학을 전공하다 개발로 전향했습니다.
기능을 동작시키는 것에서 멈추지 않고, 보안 취약점을 직접 검증하고 외부 연동 장애까지 설계에 반영하는 것을 중요하게 생각합니다.

📧 lomu990524@gmail.com

---

### Tech Stack

`Java 11 / 21` `Spring Boot 4` `Spring MVC (Legacy)` `MyBatis` `MySQL` `JSP / JSTL` `Python` `FastAPI` `Git`

---

### Projects

**[앙사모 ERP](https://github.com/angsamo/angsamo)** · 4인 팀 · 2026.07 ~
> 통합 ERP의 인증·권한 인프라를 구축하고, 그 위에 안전관리 모듈을 단독 개발했습니다.

- `HttpSession` 기반 자체 인증과 커스텀 인터셉터 2종으로 부서별 접근 제어 구현
- YOLO11n 모델을 FastAPI로 서빙해 안전모 착용 여부를 자동 판정, AI 서버 장애 시 폴백 경로 구성
- 요청 바디가 유실되는 문제를 raw socket 패킷 캡처로 추적해 HTTP/2 h2c 업그레이드가 원인임을 규명

**[FictionHub](https://github.com/87576857/Fiction-Hub-Novel)** · 개인 개발 · 2026.06 ~ 2026.07
> Spring MVC 3-Tier 구조의 웹소설 리뷰·커뮤니티 플랫폼. 46개 엔드포인트를 혼자 설계하고 구현했습니다.

- 자동화 스크립트로 저장형 XSS를 직접 검증하고 20개 파일 일괄 수정, CKEditor 게시판은 화이트리스트 새니타이저를 작성해 대응
- 관리자 권한 오남용을 막기 위해 role을 3단계로 재설계하고 정책을 단일 클래스로 일원화
