# 🏭 4th-KAMP-Competition (제4회 제조데이터 분석 경진대회(시계열 데이터 부문))
---
### 프로젝트 주제
- 주조공정 최적화를 위한 AI 기반 솔루션 - 품질 예측 및 이상탐지

---
### 프로젝트 내용
- STL(Seasonal and Trend decomposition using Loess) 분해 및 Periodiagram 을 활용한 시계열 구조해석
- DTW(Dynamic Time Wrapping)을 적용한 전/후공정 간 품질예측 시차조정
- 데이터 전처리(이상치 탐색, 특성공학, 결측치 처리)
- EDA 분석(Heatmap, PCA, Clustering, RandomForest)을 통한 Main Facters 도출
- 시계열 전처리 : 비정상성(Non-Stational) => 정상성(Stational) - 1) Autocorelation(자기상관성), ADF 검증 2) 차분(Differential)
- 시계열 예측분석 : MA(Moving Average), AI 모델(XGBoost, Prophet, LSTM, Stacked Hybrid)
- 성능평가 및 데이터 복원

---
### 프로젝트 설명
- 데이터
![image](https://github.com/user-attachments/assets/2c4aa5e9-0ffb-4e4b-9490-366af8168b8c)


- 데이터 전처리 흐름도
![image](https://github.com/user-attachments/assets/c128ae2f-7104-4541-85bc-544b2927ed92)


- 품질평가 주요인자(Main Factors) 도출
![image](https://github.com/user-attachments/assets/97dd3265-4e73-4e6b-b716-d05ef82da704)


- 시계열 예측 모델링 
![image](https://github.com/user-attachments/assets/006d6b73-6bbc-46cb-929f-27229c7bfa30)


- 성능평가
![image](https://github.com/user-attachments/assets/6227fae0-57d2-4fc6-b657-7fae66da2e60)



---
### 활용방안 및 기대효과
- 제조공정상 전/후공정 간의 시간차(Time Shift)로 인한 품질예측 오류 해결
- 제조품 품질 부적합 원인규명
- 시계열 예측분석을 통한 이상탐지(Anomaly Detection) 모델 개발

---
### 보완 및 향후계획
- SMOTE 기법을 활용한 오버샘플링(Oversampling) - 부적합 데이터 증강 생성
- OneClassSVM을 활용한 적/부 품질데이터 Anomaly Score 예측 분류
- 데이터 생성을 통한 실시간(Real-Time) 품질 예측

---
### 발표 PPT자료
[![image](https://github.com/kwanyeong/Machine-Vision/assets/124857002/f7b2b9a4-f938-486f-82ca-6ca065e4aabd)](https://github.com/kwanyeong/Machine-Vision/files/15148029/default.pptx)



[머신비전 프로젝트 PPT](https://github.com/kwanyeong/Machine-Vision/files/15148029/default.pptx)
