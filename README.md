## ✏️ KUBIG 크롤링 및 텍스트마이닝 스터디
- **기간** : 2021.03~2021.06
- [DataCamp](https://www.datacamp.com)에서 제공하는 크롤링 및 텍스트마이닝 강의 중심으로 스터디 진행
- **주차별 스터디**

**주차**|**학습 주제**
|------|---|
|**1주차**|Web Scraping in Python|
|**2주차**|Introduction to Importing Data in Python|
|**3주차**|Intermediate Importing Data in Python|
|**4주차**|Analyzing Social Media Data in Python|
|**5주차**|Cleaning Data in Python|
|**6주차**|Introduction to Natural Language Processing in Python|
|**7주차**|Sentiment Analysis in Python|
|**8주차**|Advanced NLP with spaCy|

-----------------------------------------------------------------------------------

### 💻 Crawling Project
- **주제** : [KLUE](https://klue.kr/) 강의평 만족도 예측 모델
- **내용** : Selenium을 이용해 KLUE 강의평 데이터를 크롤링하고 모델을 구축해 새로운 강의평 텍스트에 대한 만족도를 예측한다.

1️⃣ **Crawling**
- Selenium과 BeautifulSoup 패키지 이용
- 2020년 2학기 전공수업 강의평 약 5500개 데이터 수집

2️⃣ **Tokenization**
- 한국어 처리 패키지 KoNLPy 중 Okt 형태소 분석기 사용

3️⃣ **Modeling**
- 정수 인코딩 및 패딩
- RNN, LSTM, GRU, Bi-LSTM, CNN 모델에 대해 모델링 실시
- **결과**

모델|Accuracy
|------|---|
|RNN|0.7130|
|LSTM|0.7478|
|GRU|0.7366|
|Bi-LSTM|0.7419|
|CNN(1D)|0.7614|
|Bi-LSTM+Attention|0.7394|

