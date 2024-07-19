# 2021-BigContest
통계적 검증과 앙상블을 활용한 댐 유입량 예측 모형

<br>

## 1. 배경 & 목적

- 댐 주변 강우량과 수위 분석 등을 통해 댐의 유입량을 예측해 홍수를 예방할 수 있는 모델 구축하고 이를 통해 댐 운영을 효율화

<br>

## 2. 주최/주관 & 참가 대상 & 성과

- 주최: 과학기술정보통신부, NIA 한국지능정보사회진흥원
- 주관: KDX 한국데이터거래소, 농식품빅데이터거래소, 예술의 전당, 한국수자원공사 등
- 후원: KBD 빅데이터포럼
- 참가 대상: 전국 대학(원)생(휴학생 포함) - 전일제 대학(원)생만 해당
- 성과: **2021 빅콘테스트 데이터 분석분야 퓨처스 리그 장려상 수상**

![KakaoTalk_20211227_183905123](https://github.com/user-attachments/assets/78bd371c-192e-4969-8453-ba106d735513)

<br>

## 3. 대회 기간

- 제출마감: 2021년 9월 15일
- 1차 서류 심사 결과: 2021년 10월 22일
- 2차 PT 발표 심사 결과: 2021년 11월 21일
- 시상식: 2021년 12월 15일 

<br>

## 4. 내용

<img src="https://github.com/user-attachments/assets/1e8bb641-bf5f-405d-9e4a-5a6f674874f0"  width="400"/><img src="https://github.com/user-attachments/assets/abc8f4cc-b15f-4ebf-923f-d2d5155a231b"  width="400"/>
<br>
&nbsp;&nbsp;&nbsp;&nbsp; 한국수력자원공사에서 제공한 다목적 댐 관리 현황 데이터를 바탕으로 분석을 진행함. 해당 데이터가 대부분 비슷한 값을 가지고, 7,8월 데이터만 제공되어 데이터 양이 부족했음. 이를 해결하고자 교 수위량, 강수량과 같은 총 39개의 다양한 외부 데이터를 수집함. 해당 데이터를 중심으로 EDA와 Feature Engineering을 통해 총 25개의 Feature를 선정함.
<br>
<img src="https://github.com/user-attachments/assets/8ad6a8b9-fdc9-46d7-a2a0-160968908b22"  width="400"/><img src="https://github.com/user-attachments/assets/9551052d-3598-4c83-a0ab-5fcf548820de"  width="400"/>
<br>
&nbsp;&nbsp;&nbsp;&nbsp; 생성된 Feature를 바탕으로 Catboost, LGBM, XGB와 같은 여러 ML모델을 중심으로 학습을 진행함. 이후 Ensemble을 통해 최종 Output을 생성함. 해당 Output을 중심으로 SHAP을 활용하여 여러 인사이트 도출 및 홍수 탐지에 대해 제안함.

<br>

## 5. Process

### ch.1 Data Preparation

- 기상 데이터
- 유입량 & 방류량 데이터
- 수위, 수량 데이터

---

### ch.2 EDA&Preprocessing

- EDA
- Data Preprocessing
- Feature Engineering

---

### ch.3 Modeling

- LGBM
- Catboost
- ExtraTree
- XCB

---

### ch.4 Ensemble

- Averasing Ensemble

---

### ch.5 SHAP
- SHAP

<br>

## 6. 프로젝트 담당 역할

- PM
- 피쳐 엔지니어링
- 머신러닝 모델링
- Ensemble
- SHAP

<br>

## 7. 참고자료

[2021 빅콘테스트 발표 자료](https://github.com/yugwangyeol/2021-BigContes/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B6%84%EC%84%9D%EB%B6%84%EC%95%BC_%ED%93%A8%EC%B2%98%EC%8A%A4%EB%A6%AC%EA%B7%B8_%ED%99%8D%EC%88%98ZERO_%EA%B2%BD%ED%86%B5%EB%93%9C%EB%A6%BC%ED%8C%80_%EA%B2%B0%EA%B3%BC%EB%B3%B4%EA%B3%A0%EC%84%9C.pdf)  
[2021 빅콘테스트 보고서](https://github.com/yugwangyeol/2021-BigContes/blob/main/%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B6%84%EC%84%9D%EB%B6%84%EC%95%BC_%ED%93%A8%EC%B2%98%EC%8A%A4%EB%A6%AC%EA%B7%B8_%ED%99%8D%EC%88%98ZERO_%EA%B2%BD%ED%86%B5%EB%93%9C%EB%A6%BC%ED%8C%80_%EB%B6%84%EC%84%9D%EB%B3%B4%EA%B3%A0%EC%84%9C.pdf)

<br>

## 8. 증빙자료

[빅콘테스트 수상 홈페이지]https://www.bigcontest.or.kr/introduce/history2021.php)
