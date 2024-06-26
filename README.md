# SKT FLY AI 4기(열정 5조)
![image](https://github.com/ktde24/SKT-FLY-AI-4th/assets/118182432/87008b46-e02b-4332-87d5-d93e6d9072eb)



### Team😄
- 기간 : 2023.12.28 ~ 2024.2.28
- 임태규(팀장) : Back-end, AI
- 김시원 : Front-end, AI
- 김선아 : Back-end, AI
- 오서영 : Front-end, AI
- 우정아 : Back-end, AI
- 주동근 : Planning, AI

### SKT FLY AI 코코박사 - 분리 수면 도우미💤
- MediaPipe의 Face landemark, Pose landemark로 아이의 수면 여부 및 뒤집 여부 판단
- CatBoostClassifier 모델 사용


### SKT FLY AI 코코박사 - COCOCHAT💬
- openai API 사용(gpt-3.5-turbo, gpt-4-turbo-preview, DALLE)
- 임베딩 모델: KoBERT(모델명: jhgan/sbert-nli)
- Vector DB: FAISS 라이브러
- LangChain & RAG
- UI 및 배포: streamlit

### Requirements💻
- openai
- streamlit
- langchain
- tiktoken
- sentence-transformers==2.3.1
- faiss-gpu==1.7.2

### Project Introduction📂
✔️ 와이파이 캠으로 입력된 영상에 대한 복합적 분석을 통해 수면 상황을 부모에게 알려, 아이의 수면 시간 동안 편안한 휴식이 가능하게 합니다. 

✔️ 기 학습된 의학 자료와 우리 아기만의 육아 정보를 추가로 학습하여, 연령 및 상황별 적절한 육아 지식을 공부해야 할 수고로움을 줄여줍니다.

![image](https://github.com/ktde24/SKT-FLY-AI-4th/assets/118182432/10951e5c-e44a-4296-9c41-768857ac9e8d)


✔️ 영상에서 아기의 수면과 뒤집음 여부 판단
-  움직임과 눈감음 정도로 수면 여부를 파악하고, Mediapipe의 Pose Landmark로 뒤집음 여부를 판단합니다. 판단한 것을 바탕으로 아이가 뒤집거나 잠에서 깨어났을 때, 부모의 폰으로 알림이 갑니다.

✔️ 육아 전문 챗봇과 육아 용품 추천 챗봇
- 육아전문가 챗봇 : 6개의 카테고리 중 하나를 선택 후, 육아 관련 질문을 하면 답변과 이미지가 나옵니다.
- 육아 용품 추천 챗봇: 사용자가 추천을 해달라고 입력하면, 11번가에 있는 제품들을 추천해줍니다.

✔️ 수면 레포트 
- 주간 수면 분석 결과, 평균 수면 시간, 또래와의 수면 시간 비교, 코코박사의 조언을 확인할 수 있습니다.
- 코코박사의 조언은 아이의 수면 데이터로 챗봇에 질문하여 나온 결과입니다.

### Result📌
| 수면 판단1 | 수면 판단2 |
|------------|------------|
| <img src="https://github.com/ktde24/SKT-FLY-AI-4th/assets/118182432/68f66e98-1d40-4aa8-a91c-16deac0edb38" width="300px"> | <img src="https://github.com/ktde24/SKT-FLY-AI-4th/assets/118182432/0481f91c-5627-4976-996e-5dbd98f689d1" width="300px"> |


| 육아 챗봇1 | 육아 챗봇2 | 수면 Report |
|------------|------------|------------|
| <img src="https://github.com/ktde24/SKT-FLY-AI-4th/assets/118182432/62b99592-a57a-4302-95ec-7a9d1c4206cf" width="300px"> | <img src="https://github.com/ktde24/SKT-FLY-AI-4th/assets/118182432/f34df8e0-034f-4dfa-b479-087f65b817d7" width="300px"> | <img src="https://github.com/ktde24/SKT-FLY-AI-4th/assets/118182432/19f95282-fb30-4299-a5d3-6baab53adcf3" width="300px"> |

### 수업 내용 정리
https://velog.io/@ktde24/series/SKT-FLY-AI-4%EA%B8%B0

