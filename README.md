# ☄️ 최범규(Bumku Choi) ㅣ AI 개발자

[📄최범규 CV](https://github.com/choibumku00/choibumku00/blob/main/%EC%B5%9C%EB%B2%94%EA%B7%9C_CV.pdf)  

안녕하세요. 어렵다고 포기하지 않는 최범규입니다.  
지식 그래프를 활용한 추천 시스템 연구를 주로 하고 있습니다.  
팀원들과 협업을 통해 연구 및 프로젝트 하기를 즐깁니다.  
IT 분야에 관심이 많아, 컴퓨터, 모바일, 인공지능, 자연 과학 등 다양한 분야의 최신 동향을 매일 찾아보고 있습니다.  
또한 취미로 수영을 즐기고 있습니다.  

## 📞 연락처

📧 choirony00@gmail.com  
<br>

# 🔎사용 기술

### 💻Coding
- 파이썬
- Deep Learning(Pytorch, Tensorflow)
- Recommendation System
- Neo4j
- C, C++

### 🎨Design
- Photoshop
- AfterEffects
- Vegas
<br>

# 🌟주요 기술
## **Python**
- 메인 프로그래밍 언어
- AI 및 데이터 분석에 활용
- 주요 라이브러리: PyTorch, TensorFlow, Pandas, NumPy 등

## **Recommendation System**
- 유사도 기반 및 행렬 분해 학습
- MLP, NLP, GNN을 활용한 딥러닝 기반 추천 시스템 연구
- 개인화된 맞춤형 추천 시스템 개발

## **GNN (Graph Neural Network)**
- 그래프 구조 및 특징 학습
- POI(Point Of Interest) 추천 시스템에 적용
- GCN, GAT 등 다양한 모델 공부 및 실습

## **NLP (Natural Language Processing)**
- Word2vec을 통한 단어 벡터화
- BERT를 Fine-tuning 및 Embedding 추출 경험
- 감성 분석, 텍스트 분류 등 다양한 NLP 기술 경험
- RNN, Transformer, RAG 모델 공부
<br>

# 📈프로젝트 경험
**프로젝트 제목을 눌러 Github로 이동 가능합니다.**
## [**POISON**](https://github.com/DAU-FAIRDAY-TEAM6/POISON_Models) (2024-03 ~ 2024-12)

**Yelp(사용자-위치 방문 데이터) 데이터셋을 이용한 개인화 POI 추천 시스템 연구**

- **목표**: 다양한 컨텐츠 정보(방문, 리뷰, 지리)를 적극 활용
    - 개개인의 특성을 반영하기 위해 BERT로 리뷰 텍스트 임베딩 추출
    - Global/Local Relation을 추출하기 위한 지리 정보와 LightGCN 사용
- **역할**: 팀원 (AI모델 설계 및 개발, 리뷰 텍스트 임베딩 추출, Hyperparameter tuning)
- **기술**: LightGCN, BPR, BERT, Pytorch
- **성과**: 한국정보처리학회 논문 제출, 졸업작품 우수상

## [**VoiceWizards Deepfake Detection**](https://github.com/choibumku00/VoiceWizards_deepfake_detectione) (2024-06 ~ 2024-07)

**실제 음성과 생성된 가짜 음성을 탐지하는 경진대회**

- **목표**: 일반화 성능 향상과 과적합 방지
    - Train 데이터을 Test 데이터와 최대한 비슷하게 만들어 성능 향상
    - 가짜 음성 탐지에서 높은 성능을 보이는 AASIST 사용
    - 잡음을 제거하기 위한 CleanUNet 사용
- **역할**: 팀장 (AI모델 설계 및 개발, Data augment, Hyperparameter tuning)
- **기술**: Data augment, CleanUNet, AASIST, Label smoothing
- **성과**: 9등 기업후원상 (총 212팀)

## [**Improve Smart Crossroads**](https://github.com/choibumku00/Improve_Smart_Crossroads) (2023-09 ~ 2024-06)

**교차로의 신호를 최적화하는 프레임워크 개발**

- **목표**: 교통량과 속도를 예측하여 최적의 신호 도출
    - 이전 교통량을 통해 향후 교통량 예측에 LSTM사용
    - 교통량과 신호 값을 통한 MLP 사용
    - 여러 신호 중 최적의 신호를 찾기 위해 유전 알고리즘 사용
    - 파이프라인을 설계하여 유기적으로 작동
- **역할**: 팀장 (MLP모델 개발, 유전 알고리즘 설계,  파이프라인 설계)
- **기술**: LSTM, MLP, 유전 알고리즘, Keras Tuner
- **성과**: 2024 대학생 아이디어 경진대회 최우수상, 교내 개발대회 DevDay2023 최우수상, 대한교통학회 2024춘계학술대회 논문 제출, 한국ITS학회 2024춘계학술대회 장려상

## [**Hands-on-GNN**](https://github.com/choibumku00/Hands-on-GNN) (2023-12 ~ 2024-02)

**생성형 GNN을 공부하고 실습**

- **목표**: 다양한 GNN 모델을 통해 그래프를 생성
    - 다양한 생성형 GNN모델 학습 및 실습
- **기술**: Graph variational autoencoders, Autoregressive models, Generative adversarial networks, Temporal Graph Neural Networks

## [**Tear_Translator**](https://github.com/hyeyeoung/Tear_Translator) (2024-01 ~ 2024-02)

**아기의 울음 소리를 분석하여 아기가 왜 우는지 원인을 분류하는 AI 개발**

- **목표**: 아기의 울음 소리를 받아와 CNN이 특성을 추출하고, MLP를 통한 클래스 분류
    - Kaggle의 아기 울음소리 데이터로 AI모델 학습
    - 울음소리를 MFCC 변환 후 CNN으로 특징 추출
    - MLP로 우는 원인을 분류
    - 앱으로 제작하여, 일반인이 사용 가능하도록 제작
- **역할**: 팀장 (MFCC 변환, CNN/MLP로 분류 모델 개발)
- **기술**: MFCC, CNN, MLP, Flutter

## [**꼬리에 꼬리를 무는 단어**](https://github.com/Daanyong/cocodan) (2023-10 ~ 2023-11)

**단어 간 유사도를 통해 오늘의 단어를 유추하며 맞추는 게임**

- **목표**: 사용자가 영어 단어를 재밌게 습득할 수 있도록 제공
    - Word2vec 기술을 사용하여 토익 영단어를 임베딩
    - 아무 단어나 입력하며 유사도를 통해 어떤 단어일지 유추
- **역할**: 팀장 (영단어 예문을 통한 Word2vec 학습, Cosine similarity로 영단어 유사도 순위 추출)
- **기술**: Word2vec, Cosine similarity

## [**CONREC**](https://github.com/datascience-labs/conrec) (2023-06 ~ 2023-09)

**사용자가 이해한 개념을 기반으로 지속적으로 성장 가능한 강의 영상을 추천**

- **목표**: 사용자의 인지 내용을 지식그래프로 표현 및 영상 추천
    - Youtube API로 영상들을 불러와 자막 추출
    - PageRank 알고리즘을 통해 핵심 단어 추출
    - 영상의 이해한 단어를 저장하여 추후 영상 추천
- **역할**: 팀원 (영상 자막 추출 및 텍스트 전처리, 핵심 단어 추출, 추천 시스템 개발, 웹사이트 제작, 논문 작성)
- **기술**: Knowledge graph, 텍스트 전처리, PageRank, Jaccard similarity, 추천 시스템, Streamlit
- **성과**: KaRS - RecSys 2023 Workshop 논문 출판

## [**모먹을까?**](https://github.com/2023-Busan-Hackathon/Busan-Hackathon-team4-backend-MVC) (2023-06 ~ 2023-08)

**GPT API를 활용한 간단한 음식 레시피를 추천**

- **목표**: 맞벌이 부부의 자녀들에게 부모가 부재 중에 음식 레시피 추천
    - GPT Prompt-tuning 및 원하는 Output 생성 역할 수행
    - 웹사이트를 통해 사용 가능
- **역할**: 팀원 (GPT Prompt-tuning, 웹사이트 제작)
- **기술**: GPT API, Prompt-tuning, SpringBoot

## [**web-media-mix**](https://github.com/chunsejin/web-media-mix) (2022-03 ~ 2022-07)

**미디어 믹스를 온톨로지 형식으로 저장하기 위한 데이터 구조 개발**

- **목표**: 미디어 믹스를 저장할 그래프 구조 개발
    - 그래프 데이터 구조 개발
    - Neo4j를 활용하여 데이터 관리 및 DB 구축
- **역할**: 팀원 (오픈 프로젝트 방향 제시, 데이터 구조 개발)
- **기술**: Knowledge graph(지식 그래프), 온톨로지, Neo4j
<br>


# 📔학력

동아대학교 컴퓨터공학과 (졸업 예정) - 2025

내성고등학교 (졸업) - 2019

