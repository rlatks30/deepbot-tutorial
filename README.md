# 딥러닝 음성챗봇 튜토리얼

(주)한국인공지능아카데미 [딥러닝 음성챗봇] 강의 튜토리얼 강의자료 입니다. 본 튜토리얼은 아래의 5단계로 진행됩니다. 스탭을 따라가며 한단계 한단계 자신만의 챗봇으로 진화시켜 보세요.

---

## 1단계
웹기반 음성챗봇 프레임웍을 세팅하는 단계입니다. 화면 프런트앤드는 웹(HTML,CSS/JS)으로, 백앤드는 파이썬 Flask 기반으로 개발되어 있습니다. HTML5 Library 를 사용하여 음성인식(SST)과 음성합성(TTS)의 기본 기능이 구현되어 있으며, 기본적인 웹 UI가 구현되어 있습니다. 교육 목적에 맞도록 간단하게 구현되어 있지만 어느정도만 수정해도 본인의 브랜드에 맞는 음성챗봇 화면을 구현하실 수 있습니다.

```
- HTML/CSS/Javascript
- Web STT/TTS
- Flask
- DB(SQLAlchemy)
```

## 2단계
자연어의 '분석 및 전처리'를 위한 학습단계입니다. 자연어처리란 무엇을 말하는지 언제 어떠한 목적으로 사용되는지를 이해해야 합니다. 개념을 이해하고 언제 어떤 목적으로 사용하는지를 이해하고 나서 자연어 분석 및 가공을 위한 파이썬 라이브러리(nltk, konlpy) 사용법을 익히고 실습을 통해 익숙해 지도록 합니다.

인공지능 프로그래밍에서 자연어처리란 결국 자연어(한글, 영어 등등)을 컴퓨터가 이해(처리)할 수 있도록 사전에 처리(전처리)를 하기 위한 작업이라고 할 수 있습니다. 딥러닝 단계에서는 최종적으로 컴퓨터가 이해할 수 있는 숫자 형태로 변환처리 되지만 전통적으로 사용되던 통계적 기법에서는 자연어 단어 그대로를 사용하기도 합니다.

```
- NLTK
- Konlpy
- Tokenization
- Regular Expression
- One hot encoding
```


## 3단계
통계적 기법(알고리즘)을 학습하고 음성 챗봇에 응용해 보는 단계입니다. N-gram 과 TF-IDF 알고리즘을 사용하여 대화 생성 모델과 내용 추천 혹은 검색 기능을 구현해 봅니다. 전통적인 방식에는 한계가 있지만 구현 난이도가 높지 않아 현업에서도 많이 사용한다고 하는데 실제 대화 데이터를 가지고 전처리를 통해 알고리즘에 적용해보며 가능성과 한계를 경험해 보도록 합니다.

저희는 자신의 카카오 대화 데이터를 가져와서 데이터를 가공하여 알고리즘에 적용해 보며 실제 구현을 하면서 나타나는 이슈들을 처리해 나가도록 하겠습니다.

```
- Language Model
- N-gram Language Model
- TF-IDF(Term Frequency-Inverse Document Frequency)
- Cosine Similarity
- Document Recommendation
```

## 4단계
딥러닝 자연어처리 프로세스(데이터수집, 데이터전처리, 임베딩, 모델구성, 학습, 검증, 예측)를 이해하고 주요 딥러닝 자연어 처리 알고리즘을 실습해 보는 단계입니다.

대표적인 딥러닝 자연어처리 알고리즘 RNN과 LSTM 알고리즘을 사용하여 사용자의 감정분석 및 의도파악에 적용해봅니다.

```
- Embedding : Word2Vec
- RNN / LSTM
- Sentiment Analysis
- Intent Analysis
- Slot
```

## 5단계
Transformer 모델중 대표격인 BERT 알고리즘을 이해하고 음성 챗봇에 적용해 보는 단계입니다. 구글에서 제공하는 사전에 학습된(pre-trained) BERT 모델 데이터를 다운받아 우리의 목적에 맞도록 추가 학습(fine tuning)을 경험해 보도록 합니다.


```
- Transfer Model
- Pretrined Model
- Attention
- BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding
```
