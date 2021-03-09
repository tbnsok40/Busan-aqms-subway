🎆
# Busan-aqms-subway

## 논문 링크 
- http://jekosae.or.kr/xml/26062/26062.pdf

## Describtion
- 2015 ~ 2020년 부산시 미세먼지(지하철(내기) / AQMS(외기) 데이터 분석
- 사이킷런 라이브러리 활용하여 내기와 외기의 상관관계 분석

## Stack
- Python, Pandas, Matplotlib, Seaborn, Sickit-learn
- Excel


### challenged
- 정제되지 않은 데이터 처리 -> 모든 전처리 과정 경험
- 하나의 그래프에 2가지 Linear Regression line 그려 비교
- 노이즈 데이터와 공백 데이터 처리

### preprocessing
#### 전처리 함수
> - 0값 제거 후 평균, 분산, 최소, 최대값 구한다.
> - 최솟값 검사 시 음수값 있는지 필히 확인 => 제거(row)


#### 이전 논문에서 op, nonop 분리 구현 

- two linear regression, 변수 구분 안됐을때 발생하는 오류 : negative r-squared
