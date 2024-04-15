---
title: "[Portfolio] 유인재"
date: 2024-04-01 12:00:00 +0900
categories: [포트폴리오, 유인재]
tags: [포트폴리오]     # TAG names should always be lowercase
pin: true
math: false
mermaid: false
# image:
#   path: /commons/devices-mockup.png
#   lqip: data:image/webp;base64,UklGRpoAAABXRUJQVlA4WAoAAAAQAAAADwAABwAAQUxQSDIAAAARL0AmbZurmr57yyIiqE8oiG0bejIYEQTgqiDA9vqnsUSI6H+oAERp2HZ65qP/VIAWAFZQOCBCAAAA8AEAnQEqEAAIAAVAfCWkAALp8sF8rgRgAP7o9FDvMCkMde9PK7euH5M1m6VWoDXf2FkP3BqV0ZYbO6NA/VFIAAAA
#   alt: Responsive rendering of Chirpy theme on multiple devices.
---

## About ME
- Name : 유인재 (Ryou InJae)
- Univ. : Gachon University, Department of AI&SW <b>(SW Major)</b> (2019.03 ~ 2025.02)
- E-mail : sts07142@naver.com
- Link : [GitHub](https://github.com/sts07142) / [GitBlog](https://sts07142.github.io/) / [Portfolio](https://sts07142.github.io/posts/Portfolio/)

## Activity

- BDA <sup><a href="https://cafe.naver.com/officialbac">↗</a></sup> / 8기 데이터분석 전처리 적용반 학회원<sub>(2024.03 ~ )</sub>
  > 빅데이터학회 Big Data Analysis
  * 데이터 이상치 확인 및 제거
  * 데이터 시각화 EDA 및 연관성 탐색
  * NLP 불용어 처리 및 전처리

<br>

- INC Lab. <sup><a href="https://sites.google.com/gachon.ac.kr/inclab">↗</a></sup> / Undergraduate RA <sub>(2023.03 ~ )</sub>
  > 지능정보통신연구실
  * WiFi CSI를 활용한 Human Activity Recognition(HAR) 연구
    * Distributed WiFi Sensing System for Energy 

## Project

- <b>[상위 13%]</b> DACON 소득 예측 AI 해커톤<sub>2024</sub><sup><a href="https://dacon.io/competitions/official/236230/overview/description">↗</a></sup><b></b> / 개인<sub>(2024.03 ~ 2023.04)</sub>
  > 개인 특성 데이터 활용 개인 소득 수준 예측<sup><a href="https://github.com/sts07142/DACON-Income-prediction">↗</a></sup>
  
  - 데이터 전처리
    - Industry_Status : Not in universe
    - Occupation_Status : Unknown
    - Employment_Status : Not Working
    - Education_Status : Children
    - train 데이터 관측 기준, Income 값이 0인 것 확인
  
  - 예측값 후처리
    - Income 예측값 음수인 경우 0으로 처리

  - 데이터 EDA & 시각화
    - EDA를 통한 데이터 간 연관성, 분포도 시각화
    - feature_importance 기준 파생변수 생성

  - CatBoostRegressor 모델 StratifiedKFold 학습
  - Optuna 하이퍼파라미터 튜닝

<hr>

- <b>[상위 13%]</b> DACON 고객 대출등급 분류 AI 해커톤<sub>2024</sub><sup><a href="https://dacon.io/competitions/official/236214/overview/description">↗</a></sup><b></b> / 개인<sub>(2024.01 ~ 2023.02)</sub>
  > 개인 특성 데이터 활용 고객 대출등급 예측<sup><a href="https://github.com/sts07142/DACON-Customer-Loan-Rating-Classification">↗</a></sup>

  - 데이터 전처리
    - 데이터 형식 숫자+문자(금액, 기간) -> 숫자 형태로 변환
    
  - 데이터 EDA & 시각화
    - EDA를 통한 데이터 간 연관성, 분포도 시각화
    - feature_importance 기준 변수 drop
    - feature_importance 기준 파생변수 생성
  
  - CatBoostClassifier 모델 StratifiedKFold 학습
  - Wandb 하이퍼파라미터 튜닝

<hr>

- <b>[은상]</b> K-디지털 챌린지: NET 챌린지 캠프<sub>시즌10</sub><sup><a href="https://koren.kr/kor/Alram/contyView.asp?s=17&page=1">↗</a></sup> / 팀장<sub>(2023.07 ~ 2023.12)</sub>
  >  다중 객체 추적 기술을 활용한 지능형 어린이집 안전 모니터링 시스템<sup><a href="https://github.com/sts07142/senior_project">↗</a></sup>

  * MOT (ByteTrack + YoloX), 행동분석 (SlowR50) 모델 구축
  * Re-ID 완화 알고리즘 개발 
    * Re-ID : MOT과정 속에서 생기는 문제로, 동일한 객체가 새로운 객체로 오인식 되는 문제
    * 스마트워치의 블루투스 신호값과, CCTV 영상 정보 활용
    * 객체(원생)의 위치를 교차 확인하여, Re-ID 문제 완화
  * 객체(원생)의 부가정보 분석 (히트맵, 이동경로, 소비칼로리)
  * CCTV 영상 그래픽화 *(개인정보 비식별처리)*
  * 사용자 APP 개발

<hr>

- <b>[상위 25%]</b> SW중심대학 공동 AI 경진대회<sub>2023</sub><sup><a href="https://dacon.io/competitions/official/236092/overview/description">↗</a></sup><b></b> / 팀장<sub>(2023.07 ~ 2023.07)</sub>
  > 위성 이미지 기반 건물 영역 분할<sup><a href="https://github.com/sts07142/DACON-Satellite-Image-Building-Area-Segmentation">↗</a></sup>

  * 데이터 전처리
    * 학습 이미지 전처리 (rotate, brightness, RGB, CLAHE ...)
    * train data 가공 (1024<sup>2</sup> -> 224<sup>2</sup> 크기의 이미지로 분할 및 압축)

  * 예측 이미지 후처리
    * 건물 검출 영역 크기 기준 Contour Outlier 제거
    
  * U-Net, EfficientNet, VGG16, ResNet50 모델 구축
  
  

