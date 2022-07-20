### 레스토랑 방문자 수 예측 대회

<

**팀원 : 김경준, 차수연, 류제성**
- 김경준 : data preprocessing, model selection
- 차수연 : feature engineering, Data Visualization and EDA
- 류제성 : Model Selection, Presentation

</br>

1. Kaggle 대회명 [Recruit Restaurant Visitor Forecasting](https://www.kaggle.com/c/recruit-restaurant-visitor-forecasting)
2. 목적: 주어진 time series data를 이용하여 방문자 수를 예측하는 데이터분석 및 머신러닝 대회
3. Loss funtion : RMSLE
Ideation :

### Description

1. Data Structure:
![image](https://user-images.githubusercontent.com/84028683/179916875-036f3d74-4249-4789-b8f0-358f254fa33e.png)
- air, hpg 두 지점의 가게와 예약정보
- 이외에 레스토랑의 지점 id, 날짜 정보 등

2. Type of features:
![image](https://user-images.githubusercontent.com/84028683/179916917-8907bc4a-f059-4d2b-a1db-d621cdd4e4eb.png)
- feature engineering 수행: 예측 정확도 개선을 위해 기존에 feature로부터 새로운 feature들 생성

3. Modelling:
![image](https://user-images.githubusercontent.com/84028683/179917016-905fea35-8eff-4fb7-857d-6c898628e2fc.png)
- XGBoost 모델 사용하여 결과 최적화
