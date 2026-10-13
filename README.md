# 이호준 · AI Engineer

LLM으로 공공기관 서비스를 만들고 운영합니다.
모델 서빙과 부하 테스트, 에이전트 오케스트레이션, 비동기 작업 파이프라인처럼 LLM을 실제 서비스로 굴리는 데 필요한 백엔드를 주로 다룹니다.

## Now

- 공공기관 대상 LLM 서비스 개발 및 운영
- 오픈 모델 서빙(vLLM) 성능 비교와 동시 접속 부하 테스트
- 에이전트 오케스트레이션 루프와 대화 메모리 설계

## Featured work

| 저장소 | 내용 |
|---|---|
| [model_benchmark_test](https://github.com/comaserious/model_benchmark_test) | 단일 GPU에서 오픈 LLM을 동시 사용자 1~50명 단계로 부하 테스트하고 TTFT 등을 비교한 벤치마크 |
| [orchestrator_loop_v2](https://github.com/comaserious/orchestrator_loop_v2) | FastAPI와 Redis로 만든 에이전트 오케스트레이션 루프 챗봇 서버 |
| [batch_api_scheduler](https://github.com/comaserious/batch_api_scheduler) | OpenAI Batch API 제출, 지수 백오프 폴링, 콜백 전송을 자동화하는 FastAPI 서버 |
| [celery-basic](https://github.com/comaserious/celery-basic) | Celery 분산 작업 처리를 모듈 구조로 정리한 예제 |
| [short_term_memory_with_redisvl](https://github.com/comaserious/short_term_memory_with_redisvl) | RedisVL과 임베딩으로 대화 스레드별 단기 기억을 관리하는 챗봇 메모리 |
| [elasticsearch-bm25](https://github.com/comaserious/elasticsearch-bm25) | Elasticsearch와 Nori로 구현한 한국어 BM25 검색 API |
| [terminal_commu](https://github.com/comaserious/terminal_commu) | 커뮤니티 공개 게시글을 터미널에서 읽는 read-only TUI |

## Stack

- **LLM**: Python · LangGraph · LangChain · vLLM · Ollama · MCP
- **Backend**: FastAPI · Celery · RabbitMQ · Redis · PostgreSQL
- **Search**: Milvus · Elasticsearch · Chroma
- **Infra**: Docker · Kubernetes
