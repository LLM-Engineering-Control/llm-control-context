# Experiment Rules

## 한국어

### 목적

동일한 제품을 두 저장소에서 구현하면서 Codex 사용 방식의 차이를 비교합니다.

- `llm-control-context`: 컨텍스트 엔지니어링
- `llm-control-prompt`: 프롬프트 엔지니어링

### 고정 조건

- 동일한 기능 범위
- 동일한 이슈 번호
- 동일한 완료 조건
- 동일한 기술 스택
- 동일한 브랜치 전략
- 동일한 테스트 기준

### 비교 변수

- Codex에 전달되는 지식의 형태
  - 지속 문서 기반 컨텍스트
  - 이슈 단위 프롬프트 기반 유도

### 완료 기준

- 구현 완료
- 빌드 성공
- 관련 테스트 통과
- 리뷰 가능 상태
- 메트릭 기록 완료

### 주요 측정 항목

- hallucination count
- convention violation count
- input tokens
- output tokens
- rework cycles
- human intervention count

## English

### Objective

Compare how two Codex guidance methods perform while implementing the same product in two repositories.

### Fixed Conditions

- same feature scope
- same issue ids
- same acceptance criteria
- same tech stack
- same branch strategy
- same validation standard

### Variable Under Test

- how knowledge is delivered to Codex
  - persistent document context
  - issue-scoped prompting

### Done Criteria

- implementation completed
- build succeeds
- relevant tests pass
- code is reviewable
- metrics are recorded
