# paper-notes

이 리포지토리는 제가 읽은 논문들에 대한 개인 노트를 모아둔 공간입니다.

이 리포의 목적은 논문 내용을 “정리/요약”하는 데 있지 않고, 아래를 남기는 데 있습니다.

- 논문이 실제로 풀려고 하는 문제는 무엇인지
- 어떤 가정 위에서 성립하는지
- 실무/시스템에서 어디서 깨지는지(실패 모드)
- 시스템 설계 관점에서 어떤 시사점이 있는지

대부분의 노트는 **Applied / Systems 관점**으로 작성하며, 주로 다음 주제를 다룹니다.

- Retrieval-Augmented Generation (RAG)
- LLM의 한계, 컨텍스트 활용 특성
- retrieval / ranking / evaluation
- 실무에서의 failure modes

## What this repo is NOT

- 논문 PDF를 모아두는 아카이브가 아닙니다. (PDF 원문은 저장하지 않습니다)
- 논문 내용을 그대로 재현하는 공간이 아닙니다.

원문은 링크로 남깁니다.

## Structure

```text
notes/
├── rag/         # RAG 관련 논문/분석
├── retrieval/   # 검색/랭킹/리트리벌
├── llm/         # LLM 특성, scaling, evaluation
└── _template.md # 논문 노트 템플릿
