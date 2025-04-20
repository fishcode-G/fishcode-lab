# Fishcode LLM Bounty Lab

**Language:** [English](#fishcode-llm-bounty-lab) | [한국어](#피쉬코드-llm-바운티-연구실)

---

## Fishcode LLM Bounty Lab

Welcome to the LLM Bounty Lab section of the Fishcode repository.

This space is dedicated to the research, experimentation, and documentation of real-world LLM security vulnerabilities across public platforms. All activities here are strictly educational and aligned with responsible disclosure practices.

---

## 🎯 Objective

To identify, simulate, and document filter evasion, prompt injection, and role manipulation techniques that may expose weaknesses in deployed Large Language Models (LLMs).

---

## 🔍 Target Platforms

We focus on platforms that expose LLM services via public API or UI:

- OpenAI (ChatGPT API)
- Anthropic Claude
- HuggingFace Spaces (open-source models)
- Perplexity AI
- Others added dynamically

---

## 🧪 Techniques Covered

| Technique | Description |
|----------|-------------|
| Prompt Injection | Embedding hidden or layered instructions in user input |
| Role Manipulation | Exploiting internal system/user roles to bypass restrictions |
| Filter Bypass | Rephrasing or chaining requests to defeat moderation filters |
| AI-to-AI Relay | Using multi-agent systems to proxy prompts indirectly |

---

## 📁 File Structure

```
/llm/
├── README.md                    ← This file
├── prompt-injection-scenarios.md
├── filter-bypass-chaining.md
├── role-inversion-tests.md
└── findings-log.md
```

Each file contains:
- Realistic scenarios
- Step-by-step execution logs
- Observations and ethical conclusions

---

## 🛡️ Ethics & Disclosure

Fishcode does not support the misuse of AI or unauthorized system access. All findings are intended for collaborative research and responsible vulnerability disclosure.

---

Crafted with precision by:  
**G · BK · OC**  
*Team Fishcode – Strategic AI Red Teaming*

---

## 피쉬코드 LLM 바운티 연구실

**언어:** [English](#fishcode-llm-bounty-lab) | [한국어](#피쉬코드-llm-바운티-연구실)

---

## 🎯 목표

운영 중인 대형 언어 모델(LLM)에서 발생할 수 있는 필터 우회, 프롬프트 인젝션, 역할 조작 기법을 식별하고 시뮬레이션하며 문서화하는 것을 목표로 합니다.

---

## 🔍 타깃 플랫폼

다음과 같이 LLM 서비스를 공개 API나 사용자 인터페이스(UI)로 제공하는 플랫폼을 주요 대상으로 합니다:

- OpenAI (ChatGPT API)
- Anthropic Claude
- HuggingFace Spaces (오픈소스 모델)
- Perplexity AI
- 그 외 추가 예정 플랫폼들

---

## 🧪 실험 기법

| 기법 | 설명 |
|------|------|
| 프롬프트 인젝션 | 사용자 입력에 숨겨진 명령어 삽입 |
| 역할 조작 | 시스템/사용자 역할 간섭을 통한 권한 우회 |
| 필터 우회 | 우회적 표현이나 체이닝으로 필터 회피 |
| AI 간 릴레이 | 다중 에이전트를 활용한 간접 프롬프트 전달 |

---

## 📁 파일 구조

```
/llm/
├── README.md                    ← 본 문서
├── prompt-injection-scenarios.md
├── filter-bypass-chaining.md
├── role-inversion-tests.md
└── findings-log.md
```

각 문서에는 다음 내용이 포함됩니다:
- 실제 가능한 시나리오
- 실행 로그
- 관찰 및 윤리적 결론

---

## 🛡️ 윤리 원칙 및 공개 정책

피쉬코드는 AI 악용이나 무단 시스템 접근을 지지하지 않으며, 모든 실험 결과는 공동 연구 및 책임감 있는 보안 취약점 공개를 위한 것입니다.

---

정확하게 기록한 팀:  
**G · BK · OC**  
*전략형 AI 레드팀 피쉬코드*