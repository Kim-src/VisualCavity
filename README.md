<!-- Introduction -->
### 🎁 Tunnel
- [VisualCavity 개발 현황 (깃허브 블로그)](https://kim-src.github.io/categories/visualcavity/)
- [링크드인 프로필 (Chang-Seong Kim)](https://www.linkedin.com/in/chang-seong-kim-7826142a0/)

<br>

## ✅ 모델 소개
> - 모델명 : VisualCavity AI
> - 모델분류 : 이미지 학습 CNN AI 모델
> - 상세내용 : 싱크홀(공동) 자동 분석 프로그램 제작을 위한 이미지 학습 AI 모델
> - 개발목적 : 3D-GPR 데이터 분석 난이도 하향
> - 주요자료 : GPR 공동 탐사 데이터 및 30만장의 이미지

<br>

## 🚀 개발 현황 : VisualCavity AI (현재 ver. 0.1.0)
> - v0.1.0 : 이미지 1장 학습 완료 (2024-01-09)
> - v0.1.3 : 이미지 1장 학습에 대한 검토 완료
> - v0.1.7 : 학습한 이미지 1장을 가지고 다른 이미지 대조 완료
> - v0.2.0 : 이미지 100장 학습 완료
> - v0.2.3 : 이미지 100장 학습에 대한 검토 완료
> - v0.2.7 : 학습한 이미지 100장을 가지고 다른 이미지를 대조한 뒤 버전 비교 완료
> - v0.3.0 : 이미지 1,000장 학습 완료
> - v0.3.3 : 이미지 1,000장 학습에 대한 검토 완료
> - v0.3.7 : 학습한 이미지 1,000장을 가지고 다른 이미지를 대조한 뒤 버전 비교 완료
> - v0.4.0 : 이미지 10,000장 학습에 대한 검토 완료
> - v0.4.3 : 이미지 10,000장 학습에 대한 검토 완료
> - v0.4.7 : 학습한 이미지 10,000장을 가지고 다른 이미지를 대조한 뒤 버전 비교 완료
> - v0.5.0 : 이미지 100,000장 학습에 대한 검토 완료
> - v0.5.3 : 이미지 100,000장 학습에 대한 검토 완료
> - v0.5.7 : 학습한 이미지 100,000장을 가지고 다른 이미지를 대조한 뒤 버전 비교 완료
> - v0.6.0 : 이미지 300,000장(보유중인 이미지 개수) 학습에 대한 검토 완료
> - v0.6.3 : 이미지 300,000장 학습에 대한 검토 완료
> - v0.6.7 : 학습한 이미지 300,000장을 가지고 다른 이미지를 대조한 뒤 버전 비교 완료
> - v0.7.0 : 이미지가 학습된 AI 모델을 이용하여 50m 길이의 탐사 데이터 분석
> - v0.7.1 : 탐사 데이터 분석 성공률 10% 달성  
> ㄴ 수많은 에러 발생 가능성 증가 예상
> - v1.0.0 : AI를 이용한 싱크홀 분석 모델 생성  
> ㄴ AI 모델을 이용한 싱크홀 분석 프로그램에 적용될 예정

<br>

***

<br>
<br>
<br>

<!-- Update Date -->
#### Date : January 9, 2024

<!-- Title -->
## ✅ 첫 이미지 학습 완료

<br>

<!-- Contents -->
### 📌 공동 분석 모델의 발전
> - 2023-12-09 공동 분석 모델 개발(CDM)이 시작되었음
> - CDM에 jpg 및 xml 파일을 하나씩 학습시킴
> - 2023-12-15 당시 에러 발생의 이유를 파악하지 못하였었음
> - 에러 발생의 이유는 Google Colab 사용 능력이 부족하였기 때문임
> - 당시 학습시킬 파일의 위치 설정을 어떻게 해야되는지 몰랐었음

<br>

### 📌 공동 분석 모델 상태 검토
> - 다음 step은 학습된 이미지의 상태를 파악하는 것임
> - 아직 이미지 학습 과정이 어떠한지에 대한 모식도가 머릿속에 그려지지 않음
> - 따라서 inspecting 과정을 거쳐 디지털 형식의 CDM을 파악해야 됨

<br>

### 🎁 References
> - 아래는 학습시킨 이미지이며 이는 맨홀을 지날 때의 GPR 신호가 가시화 된 모습임
<p align="center"><img src="https://github.com/Kim-src/Images/assets/150884526/ff1bb03b-0237-463a-b371-5421133b8383" width="360px"><p/>

<br>

***

<br>
<br>
<br>

<!-- Update Date -->
#### Date : December 15, 2023

<!-- Title -->
## ✅ Python을 활용한 이미지 학습

<br>

<!-- Contents -->
### 📌 공동 분석 모델 개발의 시작
> - 작성자는 현재 엔지니어링 서비스 업체에서 근무중임
> - 역할은 GPR 탐사 및 GPR 데이터 분석임
> - 이는 도로 하부에 있을 수 있는 cavity의 존재를 분석하는 것임
> - 관련 내용은 아래 "링크드인 프로필"의 "경력 사항"에 작성하였음

<br>

### 📌 현재의 공동 분석 상황
> - 업계에서 현재 도로 하부 cavity의 유무는 보통 인력으로 파악중임
> - Cavity의 유무는 GPR 안테나의 가시화 된 진폭 신호로 파악할 수 있음
> - 그런데 cavity의 형태를 pipe, gravel, air gap 등과 잘 구분되지 않음
> - 따라서 숙련된 GPR 신호 분석 인력이 cavity의 존재를 파악해야 되는 상황임

<br>

### 📌 공동 분석 모델 개발의 이유
> - 이러한 cavity detection이 계속 인력으로만 진행되는 것은 미래 기술에 어울리지 않음
> - 왜냐하면 비슷한 행위를 계속 반복해야되기 때문임
> - 물론 공동 분석 관련 AI model이 이미 국내에 있지만 detection 능력이 저조한 상태임
> - 따라서 꾸준한 R&D를 통해 공동 분석에 대한 정확도를 상승시켜야 됨

<br>

### 🎁 References
> - 아래는 GPR 탐사 모습이며 추후 시각화 된 GPR 신호를 공개할 예정임(공개 가능 시)
<p align="center"><img src="https://github.com/Kim-src/Images/assets/150884526/789c4aab-8955-47a6-92d1-9b845785490d" width="500px"><p/>

<br>

***

<br>
<br>
<br>
