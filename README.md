# Self_Learning_Data_Science

### 스스로 배우는 데이터 사이언스

#### 수업 일시
- 2020.11.23 ~ 2021.01.17 (8주)

#### 사용 언어 및 프로그램 
- Python
- jupyter notebook, google colab 
- Notion : 학습 리뷰 및 커리큘럼 확인
- Slack : 학습 공지사항 및 질문

#### 수업 방식
- 커리큘럼 기반 선 학습 후 노션에 소감 작성
- 복습 강의
- 라이브 코딩 강의
- 가이드 강의
- 데이터분석 초보반 강의


**1주차**
- Python 실습 환경 
    - idle, google colab, anaconda, vscode, jupyter notebook, jupyter lab, atom, pycham
- Python 문자열 포맷팅 방법, 기본 자료형
- <https://www.youtube.com/watch?v=kWiCuklohdY> 수강
- **1주차 복습 강의**
    - 강의 진행 후, 클래스에 대해 어려워하는 학생들이 많음
    - 클래스 기초 개념부터 객체, init메소드 등 전반적인 개념과 활용 대한 설명

**2주차**
- 평균, 중앙값, 표준편차 등 기술 통계의 기초적인 개념 이해
- Python을 활용하여 CSV, Json, Excel파일 읽고 저장
- Openpyxl 설치 및 튜토리얼 학습
- Pandas 학습
- **2주차 복습 강의**
    - 통계적 기초에 대한 니즈와 아쉬움, 그리고 코딩의 어려움을 겪는 학생들이 많음
    - 통계적 사고의 필요성과 통계학 원론의 구성, 그리고 활용 사례
    - 몇 가지 알고리즘 연습 사이트와 코테에 관한 궁금증 해결


**3주차**
- 선형대수학을 사용하는 이유
    - 머신러닝 알고리즘의 결과를 객관적으로 이해하기 위하여
- 데이터 분석에 사용하는 선형대수학의 핵심 개념 이해
- 선형 대수를 사용하여 데이터를 분석하는 테크닉 이해
- NumPy의 사용법을 이해하고 데이터를 사용해 간단한 선형대수 계산을 수행
- **라이브 코딩 강의1**
    - 데이콘 상점 신용카드 매출 예측 경진대회
    - 데이터 확인, 베이스라인 구축, 랜덤포레스트 적용
- **3주차 복습 강의**
    - 선형대수학을 사용하는 이유에 대한 궁금증이 많음
    - 텐서 실습



**4주차**
- 시각화 라이브러리
- 올바르게 데이터를 전처리하는 과정의 중요성을 이해하고 기법들에 대해 학습
- 데이터 탐색을 위해 필요한 시각화의 필요성을 이해하고, 구체적인 시각화 기법들에 대해 학습
- Matplotlib을 사용하여 데이터 처리 과정을 살펴보고 구체적인 시각화 기법들에 대해 실습
- **라이브 코딩 강의2**
    - 우수멘티 코드리뷰
    - 피처엔지니어링

- **4주차 복습 강의**
    - 수 많은 시각화 라이브러리를 어떻게 기억하고 사용하는가에 대한 궁금증 해결
    - 노션을 통한 코드 정리
    - 깃허브 사용법(커밋, 푸시)

**5주차**
- 프로젝트에 주어진 데이터에서 살펴봐야 할 핵심 검토 요소들을 이해
- 원하는 목적에 맞는 분석을 위해 필요한 구체적인 절차에 대해 정의
- 학습한 내용을 바탕으로 목적을 달성하기 위한전체 데이터 분석과정 연습

- **라이브 코딩 강의3**
    - 추천시스템



**6주차 (easydeep사용)**

- **6주차 가이드 강의** 
- 머신러닝 개념, 이론 배경
- 선형회귀 개념, loss개념
- 선형회귀 학습 과정, Gradient Descent
- 선형회귀 관련 중고차가격 예측
- 데이터 전처리 잘하는 방법
    - 데이터에 대한 이해가 필요함
    - 데이터가 어떻게 구성되어있고, 어떻게 설계가 되어있는지 알아야 함, 목표가 무엇인지
    - 도메인이 중요
    - 전처리 방법을 여러개 아는 것보다 데이터를 이해하는 것이 더 중요함
    
    - 데이터에 대한 이해가 중요
    - 데이터 정규화를 해야될지는 경험치
    - 코드만 가져다 쓰니까 전처리 방법 정리해야 함
    - 어떤 점이 좋았는지
    - 한가지 전처리를 여러 데이터에 적용시키는게 중요함
- 모델이 어떻게 동작하는지 알아볼 것
    - 코드가져다가 결과보고 끝나는 것이 아니라 구현과정을 알아보는 것이 중요함
    - 왜 이런 결과물이 나왔는지 알아야 그 모델을 쓸 수 있음
    - 모델을 꼭 이해하고 사용해야 의미있음
- 카테고리형은 꼭 숫자로 치환해줘야 하나?
    - 문자열은 학습에 사용하지 못하므로 무조건 숫자로 치환해줘야 하며 숫자로 치환하는 과정은 여러개
- 데이터 사이언티스트와 머신러닝 엔지니어 포지션이 따로 있는경우 하는 업무가 많이 다른가?
    - r : 리서치 (코드 10 연구 90), 논문 읽고 연구
    - re : 리서치 엔지니어 (코드 50 연구 50), 머신러닝 엔지니어
    - se :  소프트 엔지니어 (코드 100), 데이터 사이언티스트
    - r-re-se순 :  연구를 통해 계획 및 방향을 알려주고, 엔지니어가 이해하기 쉽게 개발하고, 앱에 실제로 구현
- 카테고리형에 숫자로 치환할 때, 순차적인 값을 주나?
    - 설계하기에 따라 다름
- 카테고리가 보유한 종류가 10개가 넘어가면 보통 다운사이징(개수를 줄이는)을 하게 될거라고 예상하는데 개수를 줄이는 기준이 있나?
    - 모델이 분류해야할 종류가 많다면 다운사이징 꼭 하지 않음
    - 딥러닝연구에서는 안 줄임, 그대로 데이터 활용함
    - 줄이는데 기준 없음
    - 상황에 따라 줄이면 안될수 있고
    - 즉, 데이터의 목적에 따라 다름- 날자의 연속성은 중요하지만 날짜자체는 의미없어서 날릴수도 있고









**7주차 (easydeep사용)**
- 단순 회귀, 다중 회귀, 차원 축소 등 회귀모델을 만드는 데 필요한 개념 및 알고리즘 학습
- 분류 모델에 사용하는 다양한 학습 알고리즘과활용에 대해 이해
- scikit-learn을 사용해 다양한 회귀, 분류 모델을 실제로 구현
- 실제 데이터에 예측 모델을 적용해 유의미한 결과를 도출하는 과정 이해

**8주차**
- 데이터의 구조를 이해하고, 이를 바탕으로 분석 목적에 맞게 데이터 분석 프로젝트를 기획
- 프로젝트 수행을 위해 필요한 구체적인 절차를 계획하고 이를 바탕으로 분석 실습을 실행
- 분석 결과에 대해 평가하고, 이를 바탕으로 결과의 의미를 설명할 수 있는 프로젝트 보고서 완성
