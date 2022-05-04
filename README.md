# 고객 데이터 분석을 통한 비지니스 인사이트 도출 프로젝트

### 데이터 출처
https://console.cloud.google.com/marketplace/product/bigquery-public-data/thelook-ecommerce?hl=ko&project=hip-fusion-340315

### 가설 검정
- 광고를 통한 신규고객 유입이 검색의 경우보다 많다. → TRUE
- 광고를 통해 유입된 고객의 활성화정도는 그렇지 않은 고객에 비해 낮다. → FALSE
- 시즌별 구매 특징이 존재한다. → FALSE
- 리턴이 많은 제품의 특징이 존재한다. → TRUE
- 국가별 유입경로의 트렌드가 존재한다. → TRUE

### 마케팅 전략
- 유료 검색 엔진을 통한 신규가입고객 유입이 많음 → 광고 활성화 필요 有
- 봄, 겨울의 주문량이 다른 계절보다 높음 → thelook의 상품이 봄, 겨울에 초점이 맞춰져 있는지 확인 필요 有, 만약 사계절 모두에 중점을 둔다면 여름, 가을의 광고가 미약한 것은 아닌지 확인 필요 有
- 광고를 통해 유입되어 구입한 고객의 리턴량이 가장 많음 → 광고에 포함된 내용이 과장되거나 중요한 내용이 빠져있어 구매확정까지 이어지는데 에러사항이 되는 것은 아닌지 확인할 필요 有
- 이메일을 통한 유입이 가장 많음 → 신규 가입고객 유인 전략 필요 有

### 시각화
https://datastudio.google.com/s/kIU_ckJEsdg

---
### 사용 기술
- Bigquery
- SQL
- Google data studio
