# Example Patterns

## 한국어

기본 패턴은 다음과 같습니다.

- 컨트롤러는 요청 수신과 응답 반환만 담당
- 서비스는 비즈니스 규칙과 상태 전이를 담당
- DTO는 입력과 출력 계약을 담당
- 프론트 페이지는 데이터 조회와 조합을 담당
- 공용 타입은 `packages/contracts`에 정리

## English

Use the following baseline patterns.

- controllers handle request and response flow
- services handle business rules and state transitions
- DTOs define input and output contracts
- frontend pages assemble fetched data and UI
- shared types belong in `packages/contracts`
