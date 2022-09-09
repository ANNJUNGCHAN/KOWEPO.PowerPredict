# 지속가능한 에너지 활용을 위한 인공지능 경진대회

## 개요
* 본 대회는 한국전자기술연구원, 한국생산기술연구원이 주최/주관하고, 삼성SDS(주), 한국서부발전(주), (주)아미텍이 후원하는 대회입니다.
* KETI의 연구개발 및 한국서부발전(주)의 신재생 에너지 발전 실증 데이터에 기반한 인공지능 경진대회 운영을 통해 지속 가능한 인공지능 에너지 활용 모델 및 실용 아이디어를 도출하고자 하는 대회였습니다.
* 대회는 Track 1과 Track 2로 나누어져 있었고, 저희 팀은 Track 1만 참가하였습니다.

## Track 1 : 에너지 인공지능(Energy AI) 경진대회
* 본 대회는 리더보드를 통하여 정량평가로 진행되었스빈다.
* 재생에너지 발전량을 예측하는 문제입니다.
* 전력 거래소는 재생에너지 확대에 따른 출력 변동성 대응을 위해 재생에너지 발전량 예측제도를 도입하였다.
* 재생에너지 발전량 예측제도란, 재생에너지 발전량을 하루 전에 미리 예측하여 제출하고, 당일날 일정 오차율 이내로 이행할 경우 정산금을 지급하는 제도이다.
* 재생에너지 발전량 예측제도로 인해, 발전 사업자들의 정확한 재생 에너지 예측 기술에 대한 필요성이 증가하게 되었으며, 이를 잘 예측하는 모델을 개발해야한다.

## 개발환경

<p align="center">
  <img src="https://img.shields.io/badge/Brightics Studio-1428A0?style=flat-square&logo=Samsung&logoColor=white"/></a>&nbsp
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=NumPy&logoColor=white"/></a>&nbsp
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=SciPy&logoColor=white"/></a>&nbsp
  <img src="https://img.shields.io/badge/scikit-learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/></a>&nbsp
  <br>
    <img src="https://img.shields.io/badge/-statsmodel-green"/></a>&nbsp
    <img src="https://img.shields.io/badge/-itertools-black"/></a>&nbsp
    <img src="https://img.shields.io/badge/-catboost-yellow"/></a>&nbsp
    <img src="https://img.shields.io/badge/-byes_opt-blueviolet"/></a>&nbsp
    
</p

## 프로젝트 결과
![result](https://user-images.githubusercontent.com/89781598/189193337-bbb43766-7221-4daa-af4c-3eb80bcd83be.png)
- AIVLE SCHOOL 2기 AI과정 169명중 1등
<p align="center">
  <a href="https://www.kaggle.com/competitions/aivle-school-2nd-miniproject-competition/leaderboard"><img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=Kaggle&logoColor=white&link=https://www.kaggle.com/competitions/aivle-school-2nd-miniproject-competition/leaderboard"/></a>&nbsp
</p>

## 프로젝트 설명
<h3 align="center">🪄 프로젝트에 대한 설명은 아래의 네이버 블로그를 참고해주세요! 🪄</h3>

- [1편] 프로젝트 소개 : https://blog.naver.com/j227ung/222868866219
- [2편] EDA : https://blog.naver.com/j227ung/222868890634
- [3편] Config to Select, 통계 기법을 제어하다. : https://blog.naver.com/j227ung/222868893036
- [4편] 베이지안 옵티마이제이션(Bayesian Optimization) : https://blog.naver.com/j227ung/222869791893
- [5편] SUBMIT : https://blog.naver.com/j227ung/222870620816


## 패키지 사용

<p align="center">
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/></a>&nbsp
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=NumPy&logoColor=white"/></a>&nbsp
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=SciPy&logoColor=white"/></a>&nbsp
  <img src="https://img.shields.io/badge/scikit-learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/></a>&nbsp
  <br>
    <img src="https://img.shields.io/badge/-statsmodel-green"/></a>&nbsp
    <img src="https://img.shields.io/badge/-itertools-black"/></a>&nbsp
    <img src="https://img.shields.io/badge/-catboost-yellow"/></a>&nbsp
    <img src="https://img.shields.io/badge/-byes_opt-blueviolet"/></a>&nbsp
    
</p>

## 파일 구조
```
📦KT.BAD_WEB
 ┣ 📂CSV
 ┃ ┣ 📜cat_esb_best2.csv
 ┃ ┣ 📜CONFIG_RESULT.csv
 ┃ ┗ 📜logistic_result.csv
 ┣ 📂PT
 ┃ ┣ 📜부산경남_안중찬.pdf
 ┃ ┗ 📜부산경남_안중찬.pptx
 ┣ 📜01.EDA.ipynb
 ┣ 📜02.CONFIG.ipynb
 ┣ 📜03.Bayesian-Optimization.ipynb
 ┗ 📜04.SUBMIT.ipynb
```

## 파일 설명
- EDA.ipynb
    - EDA에 관련된 코드들이 담겨져있습니다.
- CONFIG.ipynb
    - CONFIG To Select에 대한 코드가 담겨져있습니다.(자세한 내용은 위의 불로그 참조)
- Bayesian-Optimization.ipynb
    - Bayesian-Optimization으로 하이퍼 파라미터 튜닝을 한 코드들이 담겨져 있습니다.
- SUBMIT.ipynb
    - 최종 제출된 모델의 코드가 담겨져 있습니다.
- 부산경남_안중찬.pdf,pptx
    - 모델에 대한 설명이 담겨져 있습니다. AIVLE SCHOOL에서 프레젠테이션을 진행하였습니다.
- cat_esb_best2.csv
    - 성능이 가장 좋은 모델이 예측한 값입니다.
- CONFIG_RESULT.csv
    - Config to Select의 결과입니다.
- logistic_result.csv
    - logistic 검정의 결과입니다.

## 문의사항
* email : ajc227ung@gmail.com

