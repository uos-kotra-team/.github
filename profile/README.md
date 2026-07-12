# 팀 TriMax

> KOTRA 공공데이터를 활용한 **AI 기반 수출 지원 시스템** 개발

수출 기업이 실제로 쓸 수 있는 추천 시스템을 만듭니다.
B/L(선하증권) 거래 데이터와 공공 지원사업 데이터를 근거로,
"왜 이 결과인가"를 설명할 수 있는 추천을 지향합니다.

## 무엇을 만드나

| 과제 | 내용 |
|---|---|
| **AI 바이어 추천** | B/L 데이터로 국내기업에 맞는 해외 바이어를 찾고, 웹 검색으로 프로필을 보강해 근거와 함께 추천 |
| **지원사업 추천** | 공공 데이터 기반으로 수출기업 맞춤 정부 지원사업을 자연어로 추천 |

## 기술 스택

`Python` · `LangGraph` · `PostgreSQL(pgvector)` · `OpenAI` · `Streamlit`

## 레포지토리

- [`kotra-buyer-profiling-agent`](https://github.com/uos-kotra-team/kotra-buyer-profiling-agent) — AI 바이어 추천 에이전트

## 협업 방식

- 규칙은 각 레포의 `CLAUDE.md` / `_harness/` 에서 관리 (단일 출처)
- 모든 변경은 브랜치 + PR. CI(ruff · pytest) 통과 필수
- PR·이슈 양식은 이 `.github` 레포에서 조직 전체에 공통 적용
