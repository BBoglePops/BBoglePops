# 🎤 똑부러지는 취업, 똑바른 자세부터 똑똑
<div align="center"> 
  <img width="540 alt="Instagram post - 3" src="https://github.com/user-attachments/assets/26e15ab7-d8a1-4eef-a74f-bc03377548d1" /></br> 
  <a href="#"> 
    <img src="https://komarev.com/ghpvc/?username=BBoglePops&style=for-the-badge&color=232F3E&label=++HI+THERE+👋++" alt="view counter"/> 
  </a> </div></br>


## 똑부러지는 취업, 똑바른 자세부터 똑똑

>**AI 기반 태도 분석 모의면접 서비스**</br>
>**2024.03 ~ 2024.10**

</br>

## 프로젝트 소개

**팀명 : BBoglePops(뽀글팝스)** </br>
**주제 : AI 기반 태도 분석 모의면접 서비스**</br>
**개발 기간 : 2024.03 ~ 2024.10**</br>

**'똑부러지는 취업, 똑바른 자세부터 똑똑'은 시선, 음성 분석을 활용하여 사용자의 면접 태도를 객관적으로 평가하는 AI 기반 모의면접 서비스입니다!** </br>
취업 준비 과정에서 면접은 매우 중요한 요소이지만, 자신의 면접 태도를 객관적으로 확인하기는 어렵습니다.</br>
본 프로젝트는 사용자의 웹캠 영상과 음성 데이터를 활용하여 시선 처리, 자세 유지, 답변 습관 등을 분석하고 실시간 면접 경험을 제공합니다.</br>
또한 면접 종료 후 시선 분석 결과, 자세 피드백, 음성 분석 결과 및 면접 답변 스크립트를 제공하여 사용자가 부족한 부분을 개선할 수 있도록 지원합니다.</br><br><br>

## 💁 개발팀 소개
|      김유정      |      민유빈      |      김정은      |      강이서      |
|:-------------:|:-------------:|:-------------:|:-------------:|
| [@ujjeong412](https://github.com/ujjeong412) | [@minibxx](https://github.com/minibxx) | [@wjdsilver](https://github.com/wjdsilver) |  |
|      Web Design / Unreal       |     Frontend     |     Backend / Gaze AI     |   Backend / Voice AI   |
<br>

## 서비스 구성도
<img width="9720" height="5763" alt="구성도" src="https://github.com/user-attachments/assets/3074d50d-a173-42c0-bed8-eef893b5af59" /> <br>

## 시스템 흐름도
<img width="5626" height="4583" alt="최종본" src="https://github.com/user-attachments/assets/b6c03afe-bf4e-4b89-b019-5380b833d18f" /> <br>

## 깃허브 산출물 [Repositories]
[Repository URL](https://github.com/BBoglePops/Front-Back) </br>

</br>

## 🖥️ Stack
### Used Language
<p align="left"> 
  <img src="https://img.shields.io/badge/Python-E52121?style=for-the-badge&logo=python&logoColor=white"/> 
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/> 
</p>

### Framework
<p align="left"> 
  <img src="https://img.shields.io/badge/Django%20REST%20Framework-092E20?style=for-the-badge&logo=django&logoColor=white"/> 
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/> 
</p>
  
### AI
<p align="left"> 
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/> 
  <img src="https://img.shields.io/badge/dlib-4285F4?style=for-the-badge"/> 
</p>

### Environment
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white)
![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)
![Figma](https://img.shields.io/badge/figma-F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)

### Communication
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white)
![GoogleMeet](https://img.shields.io/badge/GoogleMeet-00897B?style=for-the-badge&logo=Google%20Meet&logoColor=white)

<br>

## 프로젝트 설명
### 목적

▪️ 사용자의 면접 태도를 객관적인 데이터로 분석하여 실질적인 피드백을 제공한다.<br>
▪️ 시선, 음성 요소를 종합 분석하여 실제 면접 환경과 유사한 경험을 제공한다.<br>
▪️ 면접 태도 개선을 위한 반복 학습 환경을 구축한다.<br><br>

### ⭐ 주요기능

#### ◾ 시선 분석
>**by정은 [Gaze Tracking](https://github.com/BBoglePops/Back_AI_connect_JE)** <br/>

dlib의 Shape Predictor 68 Face Landmarks 모델을 활용하여 얼굴 랜드마크를 검출한다.<br>
초기 Calibration 과정을 통해 사용자별 눈 위치를 보정한 후 시선 방향을 추적한다.<br>
면접 진행 중 정면 응시 비율과 시선 이동 횟수를 분석하여 사용자의 집중도와 시선 안정성을 평가한다.<br>
분석 결과는 API를 통해 프론트엔드로 전달되며 면접 결과 화면에서 확인할 수 있다.<br><br>


#### ◾ 음성 분석
>**by이서 [Voice Analysis](Repository URL)** <br/>

면접 답변 음성을 분석하여 발화 특성을 측정한다.<br>
말 빠르기, 침묵 시간, 반복 표현 등을 분석하여 음성 피드백을 제공한다.<br>
답변 내용을 텍스트로 변환하여 면접 스크립트와 함께 제공한다.<br><br>

#### ◾ 면접 결과 리포트
>**by BBoglePops** <br/>

시선 분석, 음성 분석 결과를 종합하여 면접 결과 리포트를 생성한다.<br>
전체 질문 및 답변 스크립트와 함께 사용자 맞춤형 피드백을 제공한다.<br>
PDF 저장 기능을 통해 면접 결과를 지속적으로 관리할 수 있다.<br><br>

<!--
📱 화면 구성
로그인 및 메인 화면

(이미지 삽입)

면접 진행 화면

(이미지 삽입)

분석 결과 화면

(이미지 삽입)

마이페이지

(이미지 삽입)

<br><br>

### 기대 효과

▪️ 사용자가 자신의 면접 태도를 객관적으로 확인할 수 있다.<br>
▪️ 시선, 음성 데이터를 기반으로 실질적인 면접 역량 향상이 가능하다.<br>
▪️ 반복적인 모의면접을 통해 실전 면접 적응력을 높일 수 있다.<br>
▪️ AI 기반 비언어적 요소 분석을 활용하여 기존 모의면접 서비스와 차별화된 경험을 제공한다.<br>
