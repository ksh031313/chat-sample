
# RAG chat app with Azure OpenAI and Azure AI Search (Python)

이 솔루션은 RAG(검색 증강 생성, Retrieval Augmented Generation) 방식을 사용하여 여러분의 문서 위에 ChatGPT와 유사한 프론트엔드 경험을 제공합니다. Azure OpenAI Service를 통해 GPT 모델에 접근하고, Azure AI Search를 이용해 데이터 인덱싱과 검색을 수행합니다.

이 솔루션의 백엔드는 Python으로 작성되었습니다.

[📺 Watch a video overview of the app.](https://youtu.be/3acB0OWmLvM)

이 샘플은 검색 증강 생성(Retrieval Augmented Generation, RAG) 패턴을 사용하여 여러분의 데이터 위에 ChatGPT와 유사한 경험을 만드는 여러 접근 방식을 보여줍니다. Azure OpenAI Service를 통해 GPT 모델(gpt-4.1-mini)에 접근하고, Azure AI Search를 이용해 데이터 인덱싱과 검색을 수행합니다.


## Features
- 채팅(다중 턴) 및 Q&A(단일 턴) 인터페이스 제공
- 각 답변에 대한 인용 및 사고 과정을 시각적으로 표시
- UI 내에서 동작을 조정하고 다양한 옵션을 실험할 수 있는 설정 기능 포함
- Azure AI Search를 통한 문서 인덱싱 및 검색 통합, [다양한 문서 형식](/docs/data_ingestion.md#supported-document-formats)과 [통합 벡터화](/docs/data_ingestion.md#overview-of-integrated-vectorization) 지원
- 이미지가 많은 문서에 대한 추론을 위한 [GPT-4 with vision](/docs/gpt4v.md) 옵션 제공
- 접근성을 위한 [음성 입력/출력](/docs/deploy_features.md#enabling-speech-inputoutput) 기능 선택적 지원
- Microsoft Entra를 통한 [사용자 로그인 및 데이터 접근 자동화](/docs/login_and_acl.md) 옵션 제공
- Application Insights를 통한 성능 추적 및 모니터링

### Architecture Diagram

![RAG Architecture](docs/images/appcomponents.png)


## Guidance

1. [앱 설명-기초](guides/1.앱_설명(기초).md)
2. [계정 생성](guides/2.계정_생성.md)
3. [로컬 환경 설정](guides/3.로컬_환경_설정.md)
4. [저장소_소스코드_가져오기](guides/4.저장소_소스코드_가져오기.md)
5. [환경 변수 설정](guides/5.환경_변수_설정.md)
6. [앱 기본 설정](guides/6.앱_기본_설정.md)
6. [배포 하기](guides/7.배포_하기.md)
7. [앱 사용하기](guides/8.앱_사용하기.md)
8. [로컬 개발 방법](guides/9.로컬_개발_방법.md)
99. [삭제하기](guides/99.삭제하기.md)
999. [문제 해결](guides/999.문제_해결.md)
