<picture> <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg"> <img src="assets/header-light.svg" alt="Kyeonghun Kim — AI Agent Engineer" width="100%"> </picture> <br/>
무엇을 만드나
LLM이 여러 단계를 스스로 밟아 일을 끝내는 애플리케이션을 만듭니다. 질문에 답하는 챗봇이 아니라, 툴을 골라 쓰고 중간에 틀리면 되돌아오는 쪽입니다.

에이전트 설계 — 툴 경계 나누기, 멀티스텝 플래닝, 상태 관리
서빙 — FastAPI 위에서 스트리밍 응답과 비동기 툴 실행
관측 — 에이전트가 왜 그 선택을 했는지 나중에 추적할 수 있게
<br/>
어떻게 접근하나
에이전트의 성패는 프롬프트보다 그 주변 구조에서 갈린다고 봅니다. 툴을 어디서 끊을지, 실패했을 때 어디로 돌아갈지, 컨텍스트에 무엇을 남길지 — 데모와 서비스의 차이는 대부분 여기서 생깁니다.

<br/>
스택
Python  ·  FastAPI  ·  LangGraph  ·  PostgreSQL  ·  Docker

<!-- 공개 리포가 생기면 아래 섹션을 살리세요. 프로필에서 가장 힘이 센 자리입니다. ### 만든 것 | 프로젝트 | 설명 | 스택 | | :-- | :-- | :-- | | **[repo-name](https://github.com/kyeonghun-kim/repo-name)** | 어떤 문제를 어떻게 풀었는지 한 줄 | `Python` `FastAPI` | --> <br/>
<p align="center"> <a href="mailto:kyeonghun.dev@gmail.com">kyeonghun.dev@gmail.com</a> </p>
