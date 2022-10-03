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
![KakaoTalk_20220923_122630075](https://user-images.githubusercontent.com/89781598/193316073-a3aae336-79a8-44a6-9fa8-4394aa00db78.jpg)
- 2등, 한국서부발전(주)사장상

## 뉴스기사

https://blog.naver.com/iamkowepo/222879308481
https://n.news.naver.com/mnews/article/009/0005018070?sid=105

## 프로젝트 설명
<h3 align="center">🪄 해당 프로젝트는 3개의모델로 구성되어 있습니다! 🪄</h3>

![슬라이드4](https://user-images.githubusercontent.com/89781598/189539548-59d43959-ce0f-4185-b209-25c37fa67c11.JPG)

1. 각각의 모델에 대한 설명은 각각의 모델에 해당하는 폴더의 readme를 참고해주세요!<br>
2. 각각의 모델에 해당하는 폴더는 Data Preprocessing for solar, Solar Power Prediction, Wind Power Prediction입니다!
3. 크롤링에 대한 내용 또한 Data Preprocessing에 담겨져 있으니 참고 부탁드리겠습니다!

## 파일 구조
```
📦KOWEPO.PowerPredict
 ┣ 📂Crawling
 ┃ ┣ 📜Code.ipynb
 ┃ ┗ 📜index.xlsx
 ┣ 📂MODEL
 ┃ ┣ 📂Best Model
 ┃ ┃ ┗ 📜Best Model.json
 ┃ ┣ 📂Data Preprocessing for solar
 ┃ ┃ ┗ 📜Data Preprocessing for Solar.json
 ┃ ┣ 📂Solar Power Prediction
 ┃ ┃ ┗ 📜Solar Power Prediction.json
 ┃ ┗ 📂Wind Power Prediction
 ┃ ┃ ┗ 📜Wind Power Prediction.json
 ┣ 📜Code Explanation.docx
 ┗ 📜PT.pptx
```

## 파일 설명
- Code.ipynb
    - 기상청 API를 크롤링 하는 코드입니다.
- index.xlsx
    - 기상청 API를 크롤링하면, 열 부분이 해석할 수 없는 영어 코드명으로 나옵니다. 이를 알아볼 수 있는 한글로 변환해주기 위한 정보가 담긴 엑셀 파일입니다.
- Best Model.json
    - 해당 프로젝트에서 이용된 모든 모델이 담겨져 있습니다.
- Data Preprocessing for Solar.json
    - 일조량, 일사량, 전운량을 예측하기 위한 모델이 담겨져 있습니다.
- Solar Power Prediction.json
    - 태양광 발전량을 예측하기 위한 모델이 담겨져 있습니다.
- Wind Power Prediction.json
    - 풍력 발전량을 예측하기 위한 모델이 담겨져 있습니다.
- Code Explanation.docx
    - 코드를 설명하기 위한 워드 파일입니다.
- PT.pptx
    - PT를 위한 ppt 파일입니다. 해당 PT는 9월 15일 14시 슈피겐홀에서 진행하였습니다.

## 결과 및 결언

![슬라이드39](https://user-images.githubusercontent.com/89781598/189540503-e23b15ca-f8f6-4e32-921a-72b431cfd98a.JPG)

## 참고사항
- 데이터의 경우 대회 직후 파기해야 하므로, 깃허브에 올릴 수 없는 점 양해부탁드립니다.

## 문의사항
* email : ajc227ung@gmail.com

