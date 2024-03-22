## 10일차 학습
- 빅데이터 분석 실습
    - 통계 분석 리뷰
    - 머신러닝 실습

### 빅데이터 실습

#### 통계 분석 리뷰
- 그래프를 사용한 기술 통계 분석
- 히트맵을 사용한 상관 분석

##### 와인 품질 분석
- [캘리포니아 어바인 대학 연구소](https://archive.ics.uci.edu/dataset/186/wine+quality)
- 기술통계, 기존방식의 분석 사용
- 회귀분석, 기존의 데이터만으로 선형회귀를 도출

    ![회귀분석 시각화](https://github.com/vinca0224/bigdata-analysis-2024/blob/main/day10/ba011.png)

##### 타이타닉 생존자 상관분석
- seaborn 모듈 내 샘플 데이터 셋
- 생존자 상관분석 : 두 변수간에 상관관계를 유추하는 작업, 상관관계있는 변수들로 더 자세한 분석을 할 수 있는 지표
- 0.0 ~ 1.0 사이의 상관계수 값
- 0.5 ~ 0.9 의 결과가 나오는 변수들끼리 재분석
- 결측치 검색, 제거

    ![파이그래프](https://github.com/vinca0224/bigdata-analysis-2024/blob/main/day10/ba012.png)

    ![상관계수 그래프](https://github.com/vinca0224/bigdata-analysis-2024/blob/main/day10/ba014.png)

    ![상관분석 히트맵](https://github.com/vinca0224/bigdata-analysis-2024/blob/main/day10/ba015.png)
    
