![001](https://github.com/DS-21-DL-Project/Trash-classification/assets/83691399/e55d08c5-d7c2-40f6-9eb1-17f23f966679)

<h3 align="center" dir="auto"><a id="user-content--tech-stack-" class="anchor" aria-hidden="true" tabindex="-1" href="#-tech-stack-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a>📚 Tech Stack 📚</h3>



<p align="center">Language
<p align="center"><img src="https://img.shields.io/badge/python-3776AB?style=flat-square&logo=python&logoColor=white"/>

<p align="center">Library
<p align="center"><img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<p align="center">Other
<p align="center"><img src="https://img.shields.io/badge/Colab-F9AB00?style=for-the-badge&logo=googlecolab&color=525252"/><img src="https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white"/><img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"/>

---
## Introduction
- 쓰레기

---

## Contents
- [1. 프로젝트 소개](#1-프로젝트-소개)
  * [배경](#배경)
  * [프로젝트 개요](#프로젝트-개요)
- [2. 데이터 수집](#2-데이터_수집)
  * [진행 과정](#진행_과정)
  * [나무위키 데이터](#나무위키-데이터)
  * [유튜브 데이터](#유튜브-데이터)
  * [직접 입력 데이터](#직접-입력-데이터)
- [3.데이터 분석 & 시각화](#3-데이터-전처리)
  * [EDA](#EDA)
- [4. 모델링](#4-모델링)
  * [시청률 예측](#시청률-예측)
  * [조회수 예측](#조회수-예측)
  * [모델 활용](#모델-활용)
- [5. 프로젝트 한계 및 과제](#5-프로젝트-한계-및-과제)
  * [한계점](#한계점)
  * [향후 과제](#향후-과제)
- [6. 참고 문헌](#6-참고-문헌)

---

## 1. 프로젝트 소개
### 배경
- 콘텐츠 과포화 시장 속 차별화된 주제와 인물 선정이 조회수 & 시청률 성과에 직결되는 추세임
- 유퀴즈온더블럭은 시대 상황에 따른 다양한 주제와 인물을 초청하여 토크쇼를 진행하고 있지만 회차가 계속될수록 차별화된 콘텐츠의 고갈이 예상됨
- 이에 기획/제작자의 의사결정 지원을 위해 기존 출연진의 다양한 정보(나이, 직업, 성별, 인지도 등)를 수집 및  분석 후 인사이트 도출을 통해 콘텐츠 기획(출연진 선정)의 최대 효율을 기대하고자 함

### 프로젝트 개요
1. 프로젝트명: **EcoSort : Yolo를 활용한 분리 수거 시스템**
2. 수행자: 강수정, 강호진
3. 수행 기간: 3주 (2024.3.04 \~ 4.03)
4. 목표: YOLO를 활용한 쓰레기 데이터 "객체 탐지 및 분류" 

---

## 2. 데이터 수집
### 진행 과정

유퀴즈 채널의 데이터는 캐글이나 데이콘과 같은 사이트에 존재하는 데이터가 아니다 보니 나무위키와 유튜브 API를 사용하여 수집하였고 직업군이나 나이, 성별 데이터는 수집할 방법이 없어 직접 데이터를 입력하는 방식으로 진행하였습니다. 

### 캐글 데이터
![002](https://github.com/DS-21-DL-Project/Trash-classification/assets/83691399/d301fc49-6189-4c4f-ac40-e7b33971d3f3)
 
- 일반쓰레기
- 종이
- 플라스틱
- 고철
- 비닐
  
### 직접 수집 데이터
![003](https://github.com/DS-21-DL-Project/Trash-classification/assets/83691399/564e2e5e-b3c4-4e06-b5da-90f669b2323f)

-
-
-
-
-

### 직접 입력 데이터
![004](https://github.com/hojimint/Zero_Base/assets/83691399/05861a81-e16c-4f9e-9b0b-8fc60fea7914)

직업군, 성별, 나이 데이터 수집

---
## 3. 데이터 분석 & 시각화

![제목을 입력해주세요_-005 (2)](https://github.com/DS-21-DL-project/youquiz/assets/83691399/c8f1545b-1462-4cee-806f-9d8a7a66e773)

### EDA

✅ **Feature별 분포도 확인**

![image](https://github.com/DS-21-DL-project/youquiz/assets/155232890/bc755360-8c98-4287-8563-78abb5f804b4)

- **Youtube API 컬럼 전체 분포:** 조회수에서 상대적으로 특정 데이터가 다른 데이터에 비해 훨씬 높은 조회수를 가지고 있습니다.
- **성별에 따른 조회수 분포:** 남성과 여성 간에는 조회수 분포에서 큰 차이가 나타나지 않았으며, 두 그룹 간에는 유사한 조회수를 가진 데이터가 많은 것으로 보입니다.
- **나이에 따른 조회수 분포:** 대체로 여러 나이 그룹에서 유사한 조회수를 가진 데이터들이 분포되어 있습니다.
- **직업에 따른 조회수 분포:** 직업에 따라 조회수에 차이가 있음을 알 수 있습니다.

</br></br>

✅ **이상치(Outliers) 확인 & 처리**

- **이상치 확인**
    
    조회수, 좋아요 수, 댓글수의 경우 상위 이상치 값이 나타나 있음. 이는 다른 동영상들보다 훨씬 많은 조회수를 가지고 있음을 알 수 있습니다.
    
    ![image](https://github.com/DS-21-DL-project/youquiz/assets/155232890/781f477b-714b-4ba6-a98d-ca202d2815c1)


</br></br>

- **이상치 처리**
    
    **상위 5개의 이상치 출력 후** 타 값에 비해 상당히 높은 값을 갖고 있는 **281번 인덱스 행 제거**
    
    - 281번 인덱스 정보 : 출연자(BTS), 직업(연예인), 성별(M), 연령(청년), 시청률(6.74%)
  ![image](https://github.com/DS-21-DL-project/youquiz/assets/155232890/4ab3d45b-e536-41cb-a604-c3382609b862)


</br></br>

📊 **이상치 전후 Feature 확인**

각 변수에 대한 이상치 처리 전과 후의 subplots을 통해 아래와 같은 결과를 확인할 수 있었습니다.

- 이상치 처리 전
    
    조회수에 상당한 편차가 있으며 특정 데이터가 매우 높은 조회수를 가지고 있었습니다.
    
- 이상치 처리 후
    
    이상치가 제거되어 분포가 더 균일해짐을 확인할 수 있습니다.
    

---

![image](https://github.com/DS-21-DL-project/youquiz/assets/155232890/e313f89d-ea76-4ba4-ad6a-46c2c1916fc4)

![image](https://github.com/DS-21-DL-project/youquiz/assets/155232890/ee986fec-57f3-4003-aa8e-7be6786b3f85)

---

![image](https://github.com/DS-21-DL-project/youquiz/assets/155232890/81e68b3d-b25d-4433-81f5-0c401e048416)

![image](https://github.com/DS-21-DL-project/youquiz/assets/155232890/49a5dfab-bd8a-4997-a2e0-c9bcb689d106)

---

</br></br>

📊 **Feature별 히트맵**

상관 행렬을 통해 변수들 간의 관계를 파악하여 ‘유퀴즈’의 특성에 대해 알아보고자 했습니다.

![image](https://github.com/DS-21-DL-project/youquiz/assets/155232890/9b809906-6a53-489a-8624-362150d815f5)

</br></br>

📊 **시청률 Feature 분포도**

이상치를 제거 후 시청률의 히스토그램과 분포도를 확인했습니다.

정규 분포에 가까운 형태의 히스토그램과 QQ-plot은 '시청률'이 정규 분포에 가깝게 분포되어 있음을 시사하고 있습니다.

![image](https://github.com/DS-21-DL-project/youquiz/assets/155232890/c3a78f56-55bb-4de5-9e55-b138e886fe0d)

</br></br>

📊 **회차 & 직업별 시청률 분포**

매 회차 방영에 따른 시청률은 보편적으로 증가하는 추세를 보이고 있으며, 출연자의 직업이 **운동선수, 연예인, 전문기술 순으로 시청률이 가장 높게 분포**되어 있는 것을 확인할 수 있습니다.

![image](https://github.com/DS-21-DL-project/youquiz/assets/155232890/86cf8b49-b9b1-4dd1-9124-95b499074cfe)

![image](https://github.com/DS-21-DL-project/youquiz/assets/155232890/d645c16b-b3ca-464b-bda4-161eaf39f998)

</br></br>

📊 **출연자의 직업별 데이터 확인**

여러 직업군에서 수상 여부와 성별에 따라 어떻게 분포하는지를 시각적으로 나타냈습니다.

- 조회수, 좋아요, 댓글 수가 가장 많은 직업군은 연예인입니다.
- 그러나 직업별 **평균 시청률 1위는 운동선수**로 연예인이 2위, 전문 기술이 3위로 확인됩니다.
- **‘일반 학생’이 출연 시 가장 높은 재생시간**을 기록하고 있으며 연예인, 운동선수, 예술인 순으로 순위가 확인됩니다.

![image](https://github.com/DS-21-DL-project/youquiz/assets/155232890/6421889f-4b4b-45e2-8a34-df88925baa5f)

![image](https://github.com/DS-21-DL-project/youquiz/assets/155232890/100b4142-9f43-41ea-8d1b-4f97087ee22a)

</br></br>

📊 **좋아요수 별 subplot**

첫 번째 서브플롯에서는 '좋아요수'와 '조회수' 간의 관계를 직업군에 따라 산점도로 나타내었습니다. 두 번째 서브플롯에서는 '좋아요수'와 '댓글수' 간의 관계를 성별에 따라 산점도로 나타내었습니다.

- 특정 성별과 직업군에서 좋아요를 많이 받으면 조회수도 증가하는 경향을 확인할 수 있었습니다.

![image](https://github.com/DS-21-DL-project/youquiz/assets/155232890/2b4052d2-69e0-41d6-aee2-49c300496540)

</br></br>

📊 **댓글-조회수 별 subplot**

댓글-조회수 간의 관계와 특성을 확인하고자 했습니다.

- 댓글수-조회수별 직업군
    - 연예인의 경우 댓글이 많으면서 조회수가 높은 경향을 보이는 반면, 운동선수의 경우 댓글이 많더라도 조회수가 높지 않은 경우가 있는 것을 확인됩니다.
- 댓글수-조회수별 인지도
    
    대체로 인지도가 없는 경우(N) 낮은 조회수를 기록하는 것이 확인됩니다.
    

![image](https://github.com/DS-21-DL-project/youquiz/assets/155232890/1a5fee6c-c2a6-4b51-a338-4e5980e3c6b2)

</br></br>

📊 **계절적 변화에 따른 시청률 확인**

외부 활동하기 좋은 봄과 가을에 따른 평균 시청률 하락하는 추세를 보입니다.

- 2023년부터 실내 마스크 착용 의무가 권고 사항으로 변경됨에 따라, 코로나19에 대한 경계심이 낮아지면서 사람들의 외부 활동이 증가했습니다. 이 변화는 우상향하던 시청률의 증가세가 둔화되거나 멈추는 원인이 되었을 수 있습니다.
- 22년 5 월 야외 마스크 해제
- 22년 9 월 26일 실외 마스크 전면 해제
- 23년 1 월 30일 실내 마스크 의무에서 권고
- 23년 6 월 실내 마스크 해제

![image](https://github.com/DS-21-DL-project/youquiz/assets/155232890/b2a8945f-ab21-4b15-9ba0-7da5c9baf7c3)





## 4. 모델링

### 시청률 예측
![제목을 입력해주세요_-005 (1)](https://github.com/DS-21-DL-project/youquiz/assets/83691399/bc218c68-9a6a-4ec1-944e-ea524c58b0a5)


</br></br>
#### 첫번째 시도

X = df[['직업', '성별', '나이', '구독자수', '수상여부', '인지도']]

y = df[['시청률']]

X, y 컬럼을 다음과 같이 지정하여 

GradientBoostingRegressor, XGBRegressor, RandomForestRegressor 모델들을 GridSearchCV를 사용하여 최적의 하이퍼 파라메터값을 적용해 주었습니다.

이후 MAE, MAPE를 구하여 지표를 확인해 보았습니다.

![중간-발표-019](https://github.com/DS-21-DL-project/youquiz/assets/83691399/8c775030-2632-485f-b43f-3d79df8b40cb)

| 모델                      | MAE  | MAPE   |
|---------------------------|------|--------|
| GradientBoostingRegressor | 0.28 | 6.38%  |
| XGBRegressor              | 0.30 | 7.17%  |
| RandomForestRegressor     | 0.45 | 10.39% |

#### 참고
```
MAE :  예측값과 실제값 간의 평균적인 절대 오차를 나타냅니다.
       MAE가 0에 가까울수록 모델의 예측이 좋다고 평가할 수 있습니다.

MAPE : 예측값과 실제값 간의 평균적인 백분율 오차를 나타냅니다.
       MAPE가 0에 가까울수록 모델의 예측이 좋다고 평가할 수 있습니다.
```
</br></br>


#### 두번째 시도

첫번째 시도에서는 생각하지 못했던 방법들을 추가하여 보완하였습니다.
1. 날짜 데이터를 사인과 코사인으로 변환하여 새로운 컬럼으로 추가
2. RobustScaler, StandardScaler, MinMaxScaler 스케일링을 시도하여 최적의 하이퍼 파라메터 찾아보기
3. SVR 모델을 추가로 시도해 보기

날짜 컬럼을 년, 월, 일 컬럼으로 분리하고 해당 데이터들을 sin, cos으로 변환해 데이터의 주기성을 학습하고, 주기적인 패턴을 잡아내기 쉬워도 록 하였습니다.

![image](https://github.com/DS-21-DL-project/youquiz/assets/83691399/8bd8c855-3466-439e-8232-d28a6d306692)

3종류의 스케일링 기법을 총 4가지의 모델에 최적의 하이퍼 파라메터 값을 구하여 총 12가지의 경우의 수에 대해서 시도하여 어떤 경우에 가장 최적의 모델이 나오는지를 확인해 보았습니다.

![image](https://github.com/DS-21-DL-project/youquiz/assets/83691399/3b3020b9-691f-4294-aeab-4e1b3b8d51d7)

</br></br>


- StandardScaler

| 모델                | MAE  | MAPE   |
|---------------------|------|--------|
| Random Forest       | 0.23 | 0.05%  |
| Gradient Boosting   | 0.15 | 0.03%  |
| XGBoost             | 0.8  | 0.2%   |
| SVN                 | 0.46 | 0.1%   |

- MinMaxScaler

| 모델                | MAE  | MAPE   |
|---------------------|------|--------|
| Random Forest       | 0.23 | 0.05%  |
| Gradient Boosting   | 0.17 | 0.04%  |
| XGBoost             | 0.79 | 0.2%   |
| SVN                 | 0.48 | 0.11%  |

- RobustScaler

| 모델                | MAE  | MAPE   |
|---------------------|------|--------|
| Random Forest       | 0.2  | 0.04%  |
| Gradient Boosting   | 0.16 | 0.04%  |
| XGBoost             | 0.79 | 0.2%   |
| SVN                 | 0.47 | 0.1%   |


</br></br>
가장 좋은 결과를 보여준 StandardScaler와 Gradient Boosting의 모델의 예측값과 실제 값을 시각화 해보면 다음과 같은 그래프가 그려지게 되는데

![image](https://github.com/DS-21-DL-project/youquiz/assets/83691399/2237ab09-c7e2-454f-96da-beaa93db6789)

여기서 눈에 띄게 예측을 벗어난 2개의 데이터를 추적해 보도록 해보았습니다.

![image](https://github.com/DS-21-DL-project/youquiz/assets/83691399/7abe1dad-3491-461a-8b83-138b27b9f6dc)
</br></br>

가장 큰 에러를 가진 데이터 포인트의 에러 값: [1.0684939 1.484873 ]

```
     출연자  조회수  좋아요수  댓글수  재생시간(초)   구독자수  term  시청률    직업 성별  나이 수상여부 인지도    날짜  
22   김현지   68     0    0      185      0  1290  2.5    기타  F  청년    N   N   22   2019-11-26  
104  홍동규   38     0    0      208  60000  1271  2.3  사회복지  M  중년    N   N   104 2019-11-05  
```

#### high_error_points
도메인 & EDA 기반 분석 :
- 직업 특성 : 기타, 사회복지 직군은 '직업에 따른 시청률 EDA' 결과에서 하위 순위에 분포돼있습니다.
- 회차/시청률 특성 : 해당 프로그램의 평균 시청률은 4.3%로 '2.5, 2.3'의 값을 갖는 2개의 데이터는 평균 시청률의 50%도 미치지 못하는 값으로 예측이 어려웠을 것입니다.
- 인지도 특성 : 인지도는 총 3개의 피쳐(시청률, 직업, 조회수)와 연관성이 높습니다. 조회수를 예로 들어 2개의 에러 포인트는 평균 조회수의 50%(109,740)에도 미치지 못하는 38, 68로 현저히 작은 값을 갖고 있어 정확한 예측이 어려웠을 것으로 예상됩니다.
- 일부 Feature에 대한 정보 실측값 0  :  '좋아요수'와 '댓글수'의 실제 확인된 값이 모두 0으로 정확한 예측이 어려웠을 것으로 예상됩니다.

</br></br>

### 조회수 예측
![제목을 입력해주세요_-006](https://github.com/DS-21-DL-project/youquiz/assets/83691399/6cc8c1a9-c400-4bbd-8d5d-01b38e5d8503)

</br></br>


#### 첫번째 시도

X = df[['직업', '성별', '나이', '구독자수', '수상여부', '인지도']]
y = df[['조회수']]
X, y 컬럼을 다음과 같이 지정하여 

GradientBoostingRegressor, XGBRegressor, RandomForestRegressor 모델들을 GridSearchCV를 사용하여 최적의 하이퍼 파라메터값을 적용해 주었습니다.

이후 MAE, MAPE를 구하여 지표를 확인해 보았습니다.

![중간-발표-020 (1)](https://github.com/DS-21-DL-project/youquiz/assets/83691399/63332f6e-69bc-45c3-a4e6-0d925a043ecb)


| 모델                      | MAE        | MAPE      |
|---------------------------|------------|-----------|
| GradientBoostingRegressor | 351,866.50 | 2,282.54% |
| XGBRegressor              | 323,278.39 | 3,079.86% |
| RandomForestRegressor     | 321,701.03 | 3,403.23% |

오차 범위가 보다 싶이 굉장히 많이 나서 개선이 많이 필요해 보입니다.

</br></br>
#### 두번째 시도

조회수 데이터의 분포를 확인해 본 결과 다음과 같이 정규 분포와 거리가 먼 형태의 히스토그램이 나오게 됩니다.

![image](https://github.com/DS-21-DL-project/youquiz/assets/83691399/de840203-203e-4c4c-9d5c-726d67dd972f)

머신러닝은 일반적으로 가우시안 분포 형태의 데이터들로 학습을 시켰을 때 좋은 모델을 뽑아낸다고 합니다. 

따라서 조회수 데이터를 가우시안 분포에 가까운 형태로 바꿔주기 위해 numpy의 log 기능을 사용하여 조회수 컬럼을 로그 변환을 진행해 주어  **정규 분포에 더 가까운** 형태로 바꿔주었습니다.

![image](https://github.com/DS-21-DL-project/youquiz/assets/155232890/81275b84-78ca-49a3-8847-e390493acd44)

데이터 세트를 변경하여 다시 한번 머신러닝을 돌려 보았습니다.

![중간-발표-023](https://github.com/DS-21-DL-project/youquiz/assets/83691399/2acaf9bf-d6c5-489f-8531-0f3d4d8adfc9)

데이터의 값들이 보다 조밀하게 모여 오차 범위가 줄어들어 위에서 시도한것보다 좋은 모델이 나왔습니다.

</br></br>

#### 세번째 시도

두 번째 시도에서는 생각하지 못했던 방법들을 추가하여 보완하였습니다.

1. 날짜 데이터를 사인과 코사인으로 변환하여 새로운 컬럼으로 추가
2. 이상치에 강한 RobustScaler 스케일링을 시도하여 최적의 하이퍼 파라메터 찾아보기
3. SVR 모델을 추가로 시도해 보기
4. 조회수와 많은 상관관계를 가지고 있는 좋아요 수 와 댓글 수 데이터를 추가해보기


날짜 컬럼을 년, 월, 일 컬럼으로 분리하고 해당 데이터들을 sin, cos으로 변환해 데이터의 주기성을 학습하고, 주기적인 패턴을 잡아내기 쉬워도 록 하였습니다.

![image](https://github.com/DS-21-DL-project/youquiz/assets/83691399/8bd8c855-3466-439e-8232-d28a6d306692)

조회수 데이터의 경우 이상치라고 부를 만큼 편차가 큰 데이터 셋이여서 이상치에 강한 RobustScaler 스케일러를 사용하였습니다.

![image](https://github.com/DS-21-DL-project/youquiz/assets/83691399/f6f88f21-7c3c-4783-9166-ac954be0372e)


좋아요 수와 댓글 수를 포함하여 진행한 결과 다음과 같이 예측 성능이 극적으로 올라간 것을 확인할 수 있었습니다.

![image](https://github.com/DS-21-DL-project/youquiz/assets/83691399/40586fb3-6d5d-44cd-8ee8-e90547b8abf6)


| 모델               | MAE  | MAPE   |
|---------------------|------|--------|
| Random Forest       | 0.33 | 0.03%  |
| Gradient Boosting   | 0.3  | 0.03%  |
| XGBoost             | 1.67 | 0.19%  |
| SVN                 | 0.51 | 0.06%  |

### 모델 활용

지금까지 만든 모델을 사용하여 '현직 데이터사이언티스트 교수님이 지난달에 유퀴즈에 나왔다면?'이라고 가정하고 조회수와 시청율을 예측해 보도록 하였습니다

![image](https://github.com/DS-21-DL-project/youquiz/assets/83691399/85b62ba5-afba-408e-8b26-afcfde8427e9)

※ 좋아요 수와 댓글 수는 최근 1년간의 평균값으로 하였고 재생시간은 302초로 임의값으로 하였습니다.

#### 시청률

![image](https://github.com/DS-21-DL-project/youquiz/assets/83691399/8b0e0a4e-b0ca-46be-9727-a82151e1dd7b)

![image](https://github.com/DS-21-DL-project/youquiz/assets/83691399/feefa278-073c-4201-8371-5de4ff3a7884)


민형기 교수님의 데이터를 StandardScaler를 사용하여 시청률을 예측해 보면 

| 모델               | 시청율  |
|---------------------|------|
| Random Forest       | 4.70% |
| Gradient Boosting   | 4.48%  |
| XGBoost             | 4.33% |
| SVN                 | 5.34% |

다음과 같이 4.7% 정도의 시청율이 나온다고 예측해 볼 수 있었습니다.

#### 조회수

![image](https://github.com/DS-21-DL-project/youquiz/assets/83691399/a0ecf087-ff45-461b-9e52-ee30589bfcaa)\

시청률과 마찬가지로 조회수 데이터도 위에서 구한 가장 우수햇던 기법으로 예측해 보았습니다.

| 모델               | 조회수 |
|---------------------|------|
| Random Forest       | 94178|
| Gradient Boosting   | 94877 |
| XGBoost             | 70820 |
| SVN                 | 50682 |

조회수의 1년동안 평균치가 40만 정도 인데 결과 수치를 보면 뭔가 잘못된 것을 알 수 있었습니다.

데이터 수에 비해서 여러가지 기법을 사용하여 만들다보니 모델이 심하게 과적합이 일어 났다고 가정하고 이전에 log까지만 취한 상태로 다시한번 더 측정 해 보았습니다.


| 모델               | 조회수 |
|---------------------|------|
| Random Forest       | 488805|
| Gradient Boosting   | 555650 |

MAE 값은 위 모델 보다는 떨어지지만 예측 성능은 이 쪽이 더 뛰어나다는 결론이 나왔습니다.


#### 결론
민형기 교수님이 출연하게 된다면 시청율은 대략 4.7% 대가 나오며 조회수는 4~50만 정도가 나온다고 볼 수 있겠습니다.

---

## 5. 프로젝트 한계 및 과제
### 한계점
- 모델을 충분히 학습시키고 더 좋은 성과를 내기에는 데이터가 조금 부족했었습니다. 만약 시간과 데이터가 더 주어진다면, 더 좋은 모델을 만들어 정확한 예측을 할 수 있을 거라 생각합니다. 
- 직업군 분류 작업이 잘 진행되지 않았던 거 같습니다. 직접 크롤링을 하여 얻은 데이터를 3명이서 분류를 진행하다 보니 기준이 저마다 다르거나 애매한 경우가 있어 직업군별 분류가 좋지 못한 결과가 나온거 같습니다.
- 최대한 정보를 모아 데이터를 이해해 모델을 학습시켰지만, 아쉽게도 버려야 하는 컬럼들이 존재했습니다. 활용하지 못한 변수도 포함해 적용해 본다면, 더 나은 성과를 내지 않았을까 생각됩니다.
- 예측했을 때의 그래프만 보았을 때는 좋은 결과를 나타냈지만 실제로 적용해 보았을 때 엄청난 과적합이 발생하여 실제로 활용하기에는 어려움이 있다는 결론이 나와 많이 아쉬웠습니다.

### 향후 과제
- 현재는 229화까지의 데이터 셋을 사용하여 진행하였지만 몇 년 뒤에 유퀴즈 프로그램이 남아있다면 더 많은 데이터를 사용하여 더 좋은 모델을 만들 수 있지 않았을까 싶습니다.
- 하이퍼파라메터를 다루는 방법에 대해 미숙했습니다. 아직 하이퍼파라메터의 기능이 무엇인지를 정확이 인지하지 못해 모든 경우를 돌려야 하는 점이 최적의 값을 찾는 데 오랜 시간을 걸리게 하였고 일부 모델에서는 몇몇 조건을 제외하여 진행하였습니다.

---
## 6. 참고 문헌
- [나무위키 - 1](https://namu.wiki/w/%EC%9C%A0%20%ED%80%B4%EC%A6%88%20%EC%98%A8%20%EB%8D%94%20%EB%B8%94%EB%9F%AD/%EB%B6%80%EC%A0%9C%20%EB%B0%8F%20%EC%8B%9C%EC%B2%AD%EB%A5%A0)
- [나무위키 - 2](https://namu.wiki/w/%EC%9C%A0%20%ED%80%B4%EC%A6%88%20%EC%98%A8%20%EB%8D%94%20%EB%B8%94%EB%9F%AD/%EC%83%81%EA%B8%88%20%EC%88%98%EB%A0%B9%EC%9E%90)
- [유튜브 api v3](https://console.cloud.google.com/apis/library/youtube.googleapis.com?hl=ko&project=braided-city-312905)
- [캐글](https://ko.wikipedia.org/wiki/%EB%8B%B9%EB%87%A8%EB%B3%91](https://www.kaggle.com/code/serigne/stacked-regressions-top-4-on-leaderboard)https://www.kaggle.com/code/serigne/stacked-regressions-top-4-on-leaderboard)
