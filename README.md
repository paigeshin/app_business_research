# app_business_research

### Value Per Daily Active User

- 평균 유저 conversion rate 1% ~ 2%, 100명 중에 1명 2명이 유료서비스를 등록함. 
- 연 구독료 $12 ~ $15, 구독 유저 1명의 한 달 가치 =>  $0.83
- 광고 수익 한 달 1명의 가치 => $0.3 
- conversion rate 1% 유저 100명의 가치 => $30.52 
- conversion rate 2% 유저 100명의 가치 => $31.06
```jsx
    const subscribedUserValue = 0.83 
    const nonPayingDAUUserValue = 0.3 
    subscribedUserValue * 1 + nonPayingDAUUserValue * 99
    subscribedUserValue * 2 + nonPayingDAUUserValue * 98
```

### KPI 

-나의 광고 125% KPI
        
    - 월 1000 모델
    
        - 사업이득 1,000만원
        
        - DAU 163,934명 ⇒ 사업이득 1,000만원

### 앱비지니스 계산 공식

- 구체적인 계산
    1. 연구독료 $12 ~ $15 ⇒ 순수익 $10 
    2. $10 / 12개월 = $0.83 ⇒  월에 유저 한 명당 가치 $0.83
    3. $100,000 / $0.83 = 120,000명 ⇒ 월 구독 유저가 12만명은 나와야 함.
    4. 예상 광고 수익, 유저 10명당 $3, 
        1. $3 * (120,000 / 10)  = $36,000 
- 앱비지니스 성공 모델
    - 평균 conversion rate ⇒ 1% ~ 2%
    - 구독 유저 1명 ⇒ $0.83
    - 광고 수익 1명 ⇒ $0.3
- 광고성과 125%
    - 광고 성과 목표 125% ⇒ $100를 써서 $125를 벌어야 함
    - DAU 100명 ⇒  $30.52, 예상 광고 비용 $24.42 ⇒ 순이익 $6
- 광고성과 150%
    - 광고 성과 목표 150% ⇒ $100를 써서 $150를 벌어야 함
    - DAU 100명 ⇒ $30.52,  예상 광고 비용 $20.34 ⇒ 순이익 $10.18
- 광고성과 175%
    - 광고 성과 목표 175% ⇒ $100를 써서 $175를 벌어야 함
    - DAU 100명 ⇒ $30.52, 예상 광고 비용 $17.44 ⇒ 순이익 $13.08
- 광고성과 200%
    - 광고 성과 목표 200% ⇒ $100를 써서 $200를 벌어야 함
    - DAU 100명 ⇒ $30.52, 예상 광고 비용 $15.26 ⇒ 순이익 $15.26
- 광고 성과 225%
    - 광고 성과 목표 225% ⇒ $100 써서 $225를 벌어야 함
    - DAU 100명 ⇒ $30.52, 예상 광고 비용 $13.56
- 광고 비율 구하는 공식
    - (100 * 30.52) / 광고성과,
    - ex) 광고성과 150%, 100 달러 써서 150 달러 범 = (100 * 30.52 ) / 150
    
    ```jsx
    let adPerformance = 150;
    let expectedAdExpense = (100 * 30.52) / adPerformance;
    console.log(expectedAdExpense);
    ```
