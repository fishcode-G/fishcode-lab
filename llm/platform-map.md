# Fishcode Bounty Platform Map / 피쉬코드 바운티 플랫폼 맵

**Language:** [English](#fishcode-bounty-platform-map--피쉬코드-바운티-플랫폼-맵) | [한국어](#%ED%94%BC%EC%89%AC%EC%BD%94%EB%93%9C-%EB%B0%94%EC%9A%B4%ED%8B%B0-%ED%94%8C%EB%9E%AB%ED%8F%BC-%EB%A7%B5)

---

## Fishcode Bounty Platform Map

> This document outlines the major public LLM platforms relevant to bounty hunting. Each entry summarizes the target’s characteristics, known security vectors, bounty rules, and strategic approach for Team Fishcode.

---

## 🧠 OpenAI (ChatGPT API / GPT-4)

- **Target Surface**: API-based LLM interactions
- **Known Vectors**:
  - Prompt Injection (via role confusion or system override)
  - Output Filtering Bypass (via rephrasing, multi-turn tricks)
- **Rules**:
  - No ToS violation (e.g. no attempts to access internal systems)
  - Generally *no* payouts for prompt-level tricks unless severe data leakage
- **Strategy**:
  - Chain prompts for role manipulation and content leak
  - Focus on indirect summarization and AI-to-AI relay methods

---

## 🧠 Anthropic Claude

- **Target Surface**: Claude Web + API
- **Known Vectors**:
  - System prompt override via indirect narrative
  - Emotional or philosophical edge case manipulation
- **Rules**:
  - High ethical expectations
  - Vulnerability reports must demonstrate *actual harm* potential
- **Strategy**:
  - Story-based chaining or empathy-driven system confusion
  - Memory anchoring and context misalignment attacks

---

## 🧠 HuggingFace Spaces

- **Target Surface**: Open-source LLMs deployed in user Spaces
- **Known Vectors**:
  - Prompt Injection
  - Output misalignment in unmoderated models
- **Rules**:
  - Depends on the hosted model’s maintainer
  - Community-based disclosure, may not offer bounties
- **Strategy**:
  - Target weak moderation or poor sandboxing
  - Apply automated prompt stress tests

---

## 🧠 Perplexity AI

- **Target Surface**: Natural language queries with live search grounding
- **Known Vectors**:
  - Query rewriting + context distortion
  - Filtered output reshaping
- **Rules**:
  - No formal bounty, but reputation-based contact available
- **Strategy**:
  - Semantic overload + follow-up redirection
  - Context window exhaustion tactics

---

## ✅ Notes for Fishcode Ops

- Document all findings with timestamps and input/output logs
- Avoid redundant “jailbreak” naming – use structured labels
- Prioritize ethical impact and reproducibility

Authored by: **G · BK · OC**  
*Fishcode – Coordinated AI Exploit Research Unit*

---

## 피쉬코드 바운티 플랫폼 맵

**언어:** [English](#fishcode-bounty-platform-map--피쉬코드-바운티-플랫폼-맵) | [한국어](#피쉬코드-바운티-플랫폼-맵--fishcode-bounty-platform-map)

---

## 🧠 OpenAI (ChatGPT API / GPT-4)

- **대상 영역**: API 기반 LLM 상호작용
- **주요 취약 벡터**:
  - 역할 혼동이나 시스템 우회를 통한 프롬프트 인젝션
  - 다중 턴 유도 또는 재표현을 통한 필터 우회
- **정책**:
  - 내부 시스템 접근 시도 등 ToS 위반 금지
  - 일반적으로 프롬프트 수준의 우회는 보상 없음 (중대한 데이터 유출 예외)
- **Fishcode 전략**:
  - 프롬프트 체이닝을 통한 역할 조작 및 정보 유출 유도
  - 요약 중첩 기법과 AI 릴레이 사용

---

## 🧠 Anthropic Claude

- **대상 영역**: Claude 웹 및 API
- **주요 취약 벡터**:
  - 간접적 서사를 통한 시스템 프롬프트 무력화
  - 감정/철학 기반 경계 조건 유도
- **정책**:
  - 높은 윤리 기준 요구
  - 취약점 보고는 실제 위해 가능성을 입증해야 함
- **Fishcode 전략**:
  - 이야기 중심 체이닝 또는 감성 기반 시스템 혼란 유도
  - 메모리 고정 및 컨텍스트 불일치 공격 시도

---

## 🧠 HuggingFace Spaces

- **대상 영역**: 유저가 배포한 오픈소스 LLM
- **주요 취약 벡터**:
  - 프롬프트 인젝션
  - 미필터링 모델의 출력 불일치
- **정책**:
  - 모델 관리자에 따라 다름
  - 보상 없는 커뮤니티 기반 공개 가능성 있음
- **Fishcode 전략**:
  - 취약한 필터링 또는 격리 환경 공략
  - 자동화된 프롬프트 스트레스 테스트 적용

---

## 🧠 Perplexity AI

- **대상 영역**: 라이브 검색 기반 자연어 쿼리 시스템
- **주요 취약 벡터**:
  - 쿼리 재구성 + 컨텍스트 왜곡
  - 필터된 결과 재형성
- **정책**:
  - 공식 바운티는 없으나 평판 기반 컨택 가능
- **Fishcode 전략**:
  - 의미 과부하 + 후속 리디렉션 시도
  - 컨텍스트 윈도우 소모를 통한 출력 왜곡

---

## ✅ Fishcode 작전 주의사항

- 모든 실험 결과는 타임스탬프 및 입력/출력 로그와 함께 기록
- ‘탈옥(jailbreak)’ 같은 용어는 피하고 구조화된 라벨 사용
- 윤리적 영향과 재현 가능성을 최우선으로 고려

작성: **G · BK · OC**  
*Fishcode – 전략형 AI 침투 연구팀*

