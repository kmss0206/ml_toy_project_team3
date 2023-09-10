# Analysis_Domestic_Travel_Region_Interest
# 국내 여행 지역 선호도 분석

## Original Data(원본 데이터)
https://www.bigdata-culture.kr/bigdata/user/data_market/detail.do?id=359f0000-4129-11ec-a107-3b8bd6a15b10<br>
https://www.bigdata-culture.kr/bigdata/user/data_market/detail.do?id=b44da660-5892-11ec-8ee4-95f65f846b27<br>
Original data is not pre-processed

## EDA (탐색적 데이터 분석)
EDA_interest_final.ipynb, EDA_lodgment_final.ipynb에 진행과정이 나와있습니다.
1. 숙박 여행 유형 데이터
![l_chi](https://github.com/khuda-4th/ml_toy_project_team3/assets/70475010/50c2aa48-f381-4cc0-9717-630ce18e147e)
![l_pvalue](https://github.com/khuda-4th/ml_toy_project_team3/assets/70475010/65f462bd-7f05-4e8b-9616-e09e02346641)
![l_crammerV](https://github.com/khuda-4th/ml_toy_project_team3/assets/70475010/c5d2709b-2e47-4424-a674-bfb0c46ebdcc)

2. 국내 여행지역 관심도 데이터
![카이제곱검정](https://github.com/khuda-4th/ml_toy_project_team3/assets/70475010/8144535a-7257-4bf9-8dd2-e593dbb6ba8d)
![p-value](https://github.com/khuda-4th/ml_toy_project_team3/assets/70475010/c45e9176-af4f-41f7-bf7e-b3eff64bd137)
![cramerv](https://github.com/khuda-4th/ml_toy_project_team3/assets/70475010/b4481892-690a-4f15-99c3-0eed11457d92)

## Data Pre-processing(데이터 전처리)
1. Feature's name is modified<br>
특성의 이름이 수정되어 있습니다<br>
2. Degree of Interest of Region is quantificated for Regression.(Pre-processing is not included)<br>
회귀를 위해 여행 지역 선호 정도를 수치화하였습니다<br>
original data: '많이 작아졌다', '약간 작아졌다', '예전과 비슷하다', '약간 커졌다', '많이 커졌다'<br>
pre-processed data: 0, 1, 2, 3, 4

## Modeling(모델링)
1. 숙박 여행 유형 데이터
DecisionTree, GradientBoostingClassifier 이용하여 분석을 진행함 <br>
2. 국내 여행지역 관심도 데이터 <br>
K-Means Clustering, Deicision Tree, RandomForest, XGBoost 이용하여 분석을 진행함 <br>
   
## Overview
To analyze about region in Korea, we launched this project!
