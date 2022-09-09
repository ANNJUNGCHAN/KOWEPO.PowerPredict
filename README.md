# 지속가능한 에너지 활용을 위한 인공지능 경진대회

## 개요
* 본 대회는 한국전자기술연구원, 한국생산기술연구원이 주최/주관하고, 삼성SDS(주), 한국서부발전(주), (주)아미텍이 후원하는 대회입니다.
* KETI의 연구개발 및 한국서부발전(주)의 신재생 에너지 발전 실증 데이터에 기반한 인공지능 경진대회 운영을 통해 지속 가능한 인공지능 에너지 활용 모델 및 실용 아이디어를 도출하고자 하는 대회였습니다.
* 대회는 Track 1과 Track 2로 나누어져 있었고, 저희 팀은 Track 1만 참가하였습니다.(팀명 : AIVLE)

## Track 1 : 에너지 인공지능(Energy AI) 경진대회
* 본 대회는 리더보드를 통하여 정량평가로 진행되었습니다.
* 재생에너지 발전량을 예측하는 문제입니다.
* 전력 거래소는 재생에너지 확대에 따른 출력 변동성 대응을 위해 재생에너지 발전량 예측제도를 도입하였습니다.
* 재생에너지 발전량 예측제도란, 재생에너지 발전량을 하루 전에 미리 예측하여 제출하고, 당일날 일정 오차율 이내로 이행할 경우 정산금을 지급하는 제도입니다.
* 재생에너지 발전량 예측제도로 인해, 발전 사업자들의 정확한 재생 에너지 예측 기술에 대한 필요성이 증가하게 되었으며, 이를 잘 예측하는 모델을 개발해야합니다.
* 매일 17시 이전에 생성된 예보/실제 관측 데이터를 이용하여 익일 발전량을 예측하는 것이 과제의 실제 목표입니다.(실제로 익일 예측은 매일 17시까지 수행해야하므로, 17시 데이터는 사용 불가)

## 개발환경

<p align="center">
  <img src="https://img.shields.io/badge/Brightics Studio-1428A0?style=flat-square&logo=Samsung&logoColor=white"/></a>&nbsp
</p>

- 삼성 SDS의 Brightics Studio 플랫폼 사용이 대회의 원칙

## 프로젝트 결과
![image](https://user-images.githubusercontent.com/89781598/189381041-bfd51ac9-5c10-49f9-9b48-a3dba3f9a2fc.png)
- 2등, 한국서부발전(주)시장상

## 프로젝트 설명
<h3 align="center">🪄 추후 추가될 예정입니다! 🪄</h3>

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

