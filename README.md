# :office:LLM과 추천 시스템 기반의 기업 매칭 서비스:office:

<img src="./tri-fusion_images/산업통상자원부 로고.jpg" width="280" height="90"/>

**제12회 산업통상자원부 공공데이터 활용 아이디어 공모전**

**:trophy:최우수상 수상:trophy:**

  Tri-Fusion mapping 알고리즘 출품

  (LLM, 언어 모델, 추천 시스템에 기반한 HS CODE 10단위 매핑)

----------------------

## :book: 개요

### :dart:주제

국내 기업과 해외 바이어의 텍스트 정보만으로 매칭하는 알고리즘 개발



### :calendar:기간
2024.05.20 ~ 2024.06.30



### :busts_in_silhouette:참여 인원
3명

### :memo:역할
HS code 번역 및 전처리, Reranking 모델 구축


### :chart_with_upwards_trend: 배경

- 텍스트 유사도만으로 매칭하는 한계를 극복하고, 매칭 정확도 향상 요구됨
- 실질적으로 바이어가 수입 가능한 품목을 추천해줘야 올바른 매칭 가능


### :triangular_flag_on_post:목표

- LLM으로 사람의 사고방식을 모방하여 매칭을 위한 추가 정보 생성
- 정확한 매칭이 가능한 모델


### :open_file_folder: 사용 데이터

비식별된 해외 바이어 영문 설명 텍스트, 관세청 HS CODE 정보 데이터

### :bulb: 문제 정의
- 해외 바이어가 취급하고 있는 품목 및 산업에 대한 설명 데이터를 보고, 예상되는 품목의 HS CODE 10단위를 추천해야 함.
- 해외 바이어 설명 데이터에는 실질적으로 수입하고자 하는 것이 드러나지 않는 문제가 있어, 사람의 추론이 필요

### :crown:성과
- 해외 바이어마다 수입할 만한 품목을 LLM이 자동 생성하도록 해서 효율성 극대화, 국내 기업과 매칭 정확도 개선
- 3개의 모델을 결합하여 보수적이고 정확한 매칭 가능



---------

## :chart_with_upwards_trend:분석 과정

<img src="./tri-fusion_images/취업 포트폴리오 최종_12.png" width="800" height="400"/>

<img src="./tri-fusion_images/취업 포트폴리오 최종_13.png" width="800" height="400"/>
