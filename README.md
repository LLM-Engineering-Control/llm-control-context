# LLM Control Context

## 한국어

### 개요

이 저장소는 Codex의 컨텍스트 엔지니어링 방식 실험용 레포지토리입니다.
동일한 제품을 `llm-control-prompt`와 같은 범위로 구현하되, 구조화된 문서 컨텍스트를 지속적으로 제공하는 방식을 사용합니다.

### 목표

- 환각 감소
- 컨벤션 준수 향상
- 재작업 감소
- 큰 맥락에서의 일관성 검증

### 기술 스택

- Backend: Java 21, Spring Boot
- Frontend: React, TypeScript
- Build Layout: Monorepo

### 디렉터리 구조

```text
apps/
  backend/     Spring Boot 애플리케이션
  frontend/    React 애플리케이션
packages/
  contracts/   공용 타입 및 API 계약 문서
docs/
  context/     지속 컨텍스트 문서
  experiments/ 실험 기록 및 메트릭
```

### 브랜치 전략

- `main`
- `feature/001-auth-login`
- `feature/002-project-management`

### 운영 원칙

- 프롬프트 레포와 동일한 이슈 번호를 사용합니다.
- 완료 조건과 테스트 기준은 프롬프트 레포와 동일해야 합니다.
- 차이는 오직 Codex에 전달하는 방식이어야 합니다.

## English

### Overview

This repository is the context-engineering arm of the Codex experiment.
It implements the same product scope as `llm-control-prompt`, but uses persistent structured context as the primary guidance method.

### Goals

- reduce hallucinations
- improve convention compliance
- reduce rework
- validate consistency under growing context

### Tech Stack

- Backend: Java 21, Spring Boot
- Frontend: React, TypeScript
- Build Layout: Monorepo

### Directory Layout

```text
apps/
  backend/     Spring Boot application
  frontend/    React application
packages/
  contracts/   shared types and API contracts
docs/
  context/     persistent context documents
  experiments/ experiment records and metrics
```

### Branch Strategy

- `main`
- `feature/001-auth-login`
- `feature/002-project-management`

### Operating Rules

- Use the same issue ids as the prompt repository.
- Keep acceptance criteria and test gates aligned with the prompt repository.
- The only variable should be how Codex receives guidance.
