# Airline-satisfaction
Airline satisfaction data analysis
# 사용된 Data Set
https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction/data

# 1. 서론
## 배경 및 분석 목표
승객의 연령대, 비행 거리, 여행 목적(개인/비즈니스) 및 클래스(이코노미/비즈니스)에 따른 만족도 패턴을 분석하여, 장거리 승객을 위한 주요 서비스 항목을 도출하고,  만족도에 가장 큰 영향을 미치는 요인을 파악한다. 
또한 만족도 중 중복 및 같은 부류의 경향성을 보이는 지표들을 상관관계 분석을 통해 정리하여 한쪽 분야에 치우치는걸 막고, 모델에도 역시 적용한다.
이를 기반으로 만족도를 예측하는 모델을 설계하여,  맞춤형 서비스 제공 및 마케팅 전략을 제시하는 것을 목표로 한다.

## 진행 방향
- 최종적인 만족여부에 기여하는 요인들을 분석하기위해 EDA 진행
  1. 기본적인 EDA를 통해 다양한 만족도 컬럼들의 경향성을 확인
  2. 상관관계 분석을 통해 기여하는정도, 중복되는 정도등 다각도에서의 탐색
  3. 발견한 인사이트를 통한 결론 도출

- 분석 결론을 활용한 예측 모델 개발
  1. 분석 결론을 통해  feature enginnering 와 컬럼 가감을 진행
  2. logistic regression, XGBoost , RandomForest 을 진행
  3. Ensemble 기법을 적용해 F1score 를 끌어올리는 방법 선택

## 사용 된 도구
- 언어 : Python
- 라이브러리 : pandas, scikit-learn, matplotlib등
- 팀원 : 김선우, 백준원, 조혜진  

## 보고서

