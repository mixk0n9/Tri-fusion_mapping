# :office:LLM과 추천 시스템 기반의 기업 매칭 서비스:office:

<img src="./gwangingu_images/광진구청 로고.png" width="250" height="100"/>

제12회 산업통상자원부 공공데이터 활용 아이디어 공모전

:trophy:최우수상 수상

----------------------

## :book: 개요

### 주제

> 국내 기업과 해외 바이어의 텍스트 정보만으로 매칭하는 알고리즘 개발
![image](https://github.com/user-attachments/assets/d6ceed2e-4ca5-451f-841b-70ee5233237e)



### 기간
> 2024.05.20 ~ 2024.06.30
![image](https://github.com/user-attachments/assets/7676dec6-28b7-434b-b0cd-5abb7dbd6dc1)



### 참여 인원
> 3명

### 역할
> LLM 프롬프트 엔지니어링, Reranking 모델 구축


### 배경
> 텍스트 유사도만으로 매칭하는 한계를 극복하고, 매칭 정확도 향상 요구됨
> 실질적으로 바이어가 수입 가능한 품목을 추천해줘야 올바른 매칭 가능


### 목표

> LLM으로 사람의 사고방식을 모방하여 매칭을 위한 추가 정보 생성
> 정확한 매칭이 가능한 모델


### 사용 데이터
> 비식별된 해외 바이어 영문 설명 텍스트, 관세청 HS CODE 정보 데이터

### 문제 정의
> - 해외 바이어가 취급하고 있는 품목 및 산업에 대한 설명 데이터를 보고, 예상되는 품목의 HS CODE 10단위를 추천해야 함.
> - 해외 바이어 설명 데이터에는 실질적으로 수입하고자 하는 것이 드러나지 않는 문제가 있어, 사람의 추론이 필요

### 성과
> - 해외 바이어마다 수입할 만한 품목을 LLM이 자동 생성하도록 해서 효율성 극대화, 국내 기업과 매칭 정확도 개선
> - 3개의 모델을 결합하여 보수적이고 정확한 매칭 가능




---------

## :chart_with_upwards_trend:분석 과정

1. 데이터 수집
- 네이버 카페, 블로그, 인스타그램, 구청 민원 데이터, 땡겨요 앱, 놀장 앱, 뉴스기사, 구글맵
- '자양전통시장', '망원시장' 검색어 기준으로 웹크롤링
- 약 8000개의 데이터 수집

2. 데이터 가공
- content를 중심으로 분석

<img src="./gwangingu_images/광진구데이터그림.png" width="800" height="400"/>
  
3. 분석

<img src="./gwangingu_images/[광진구푸바오]결과보고서_6.png" width="800" height="400"/>

<img src="./gwangingu_images/취업 포트폴리오 최종_18.png" width="800" height="400"/>

<img src="./gwangingu_images/취업 포트폴리오 최종_19.png" width="800" height="400"/>

<img src="./gwangingu_images/취업 포트폴리오 최종_20.png" width="800" height="400"/>
