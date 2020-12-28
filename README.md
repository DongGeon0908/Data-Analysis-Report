# 경기도 시ㆍ군별 학군에 따른 오락ㆍ유흥업소 형성과 재정자립도간의 관계성 
<hr />

#### Relationship between Formation of Entertainment Establishments and Degree of Financial Independence according to School Districts by City in Gyeonggi-do
<hr />

#### Donggeon Kim
#### Department of Computer Engineering, Hanshin University
<hr />

#### 요   약
  본 논문에서는 전국적으로 과열된 학군 현상이 오락ㆍ유흥업소 형성에 미치는 영향에 대해 상호 관계성을 데이터 모델링과 분석을 통해 도식화한 모형으로 제시한다. 도식화된 모형과 각 시ㆍ군별 재정자립비율을 분석해 상대적 연관성과 관계성에 대해 살펴보고자 한다.
<hr />

#### 주요 라이브러리
  - pandas as pd
  - numpy as np
  - plotly.express as px
  - matplotlib.pyplot as plt
<hr />

#### 개발환경
  - colab
  - pycharm
<hr />

#### 데이터셋
  - 경기도 공공데이터드림을 통해 받은 2018 ~ 2019년도 공공데이터
    + 게임시설
    + 당구장
    + 어린이집및유치원현황
    + 재정자립도
    + 청소년게임제공업체
    + 초중고등학교현황
    + 학원및교습소현황
    + 휴게음식점
<hr />

#### 결론

본 논문에서는 학군이 밀집되어 형성된 지역일수록 면적당 인구수가 증가하고, 결과적으로 오락 및 유흥업소가 형성됨을 확인했다. 또한 오락 및 유흥업소가 교육기관에 비해 상대적으로 높은 비율을 갖고 밀집되어 형성된 지자체의 경우에는 재정자립비율이 상대적으로 다른 지자체에 비해 낮음을 확인할 수 있다.


면적대비 학군과 오락 및 유흥업소가 밀집되어 형성된 지역일수록 재정자립비율이 낮으며, 시간이 경과함에 따라 교육기관보다 더 높은 수의 오락 및 유흥업소가 분포됨을 확인할 수 있다.



![pdf](https://github.com/DongGeon0908/Data-Analysis-Report/blob/master/%EA%B2%BD%EA%B8%B0%EB%8F%84%20%EC%8B%9C%E3%86%8D%EA%B5%B0%EB%B3%84%20%ED%95%99%EA%B5%B0%EC%97%90%20%EB%94%B0%EB%A5%B8%20%EC%98%A4%EB%9D%BD%E3%86%8D%EC%9C%A0%ED%9D%A5%EC%97%85%EC%86%8C%20%ED%98%95%EC%84%B1%EA%B3%BC%20%EC%9E%AC%EC%A0%95%EC%9E%90%EB%A6%BD%EB%8F%84%EA%B0%84%EC%9D%98%20%EA%B4%80%EA%B3%84%EC%84%B1.pdf)