# API Conventions

## 한국어

- REST 스타일을 기본으로 합니다.
- 복수형 리소스 경로를 사용합니다.
- 예시:
  - `POST /api/auth/login`
  - `GET /api/services`
  - `POST /api/incidents`
- 응답은 JSON을 사용합니다.
- 에러 응답은 `code`, `message`, `timestamp` 필드를 기본으로 둡니다.

## English

- Use REST-style APIs as the default.
- Use plural resource paths.
- Examples:
  - `POST /api/auth/login`
  - `GET /api/services`
  - `POST /api/incidents`
- Use JSON responses.
- Error responses should include `code`, `message`, and `timestamp` by default.
