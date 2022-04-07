# [정책연구] 인공지능 활용 감염병 유행예측 알고리즘 개발
- 발주기관: 정보통신산업진흥원
- 수행기관: 가천대 길병원 가천의생명융합연구원 인공지능빅데이터융합센터
- 수행역할: 데이터 수집 및 구축, 구획모형(compartmental model) 활용 우리나라 코로나19 유행 예측 알고리즘 개발, 분석 보고서 작성
- 구획모형을 활용해 우리나라 코로나19 유행 예측 알고리즘을 개발하고 일 확진자 수 예측(projection)을 수행합니다.

## 분석 방법론
- Deterministic compartmental model
  - [스터디 노트](https://github.com/be-favorite/Tutorials_SIR-models)
<p align="center">
<img src = "./Figure for portfolio/flowchart_SVEIR.png" width = 500>
</p>

## 분석 툴
### R
- 주요 라이브러리: tidyverse, lubridate, vroom, Xml, RCurl, rlist, deSolve, skimR

## 데이터
- [보건복지부 코로나19 감염 현황 OPEN API](https://www.data.go.kr/tcs/dss/selectApiDataDetailView.do?publicDataPk=15043376)

## 분석 결과 예시
- Deterministic compartmental model을 기반으로 개발한 SVEIR 모형 예측 결과 예시

<p align="center">
<img src = "./Figure for portfolio/Example.png" width = 500>
</p>

- [대외 분석보고서](https://g-abcwork.github.io/COVID_projection/)
