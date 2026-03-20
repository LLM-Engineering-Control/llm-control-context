# Backend Conventions

## 한국어

- 패키지는 기능보다 계층 우선으로 시작합니다.
- `controller`, `service`, `domain`, `repository`, `dto` 패키지를 기본으로 사용합니다.
- 엔티티와 요청/응답 DTO를 분리합니다.
- 예외 응답 형식은 일관되게 유지합니다.
- 검증은 Bean Validation을 우선 사용합니다.
- 비즈니스 규칙은 컨트롤러가 아니라 서비스 계층에 둡니다.

## English

- Start with layered packages rather than feature packages.
- Use `controller`, `service`, `domain`, `repository`, and `dto` as the baseline package set.
- Separate entities from request and response DTOs.
- Keep error response format consistent.
- Prefer Bean Validation for input validation.
- Place business rules in the service layer, not controllers.
