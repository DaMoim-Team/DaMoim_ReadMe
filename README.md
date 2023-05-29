<div align="center">
  <h1>흡연자 검출 모델을 활용한
  
  "단속반 &amp; 미화원" 경로 추천 서비스</h1>
<p align="center">
  <img src="https://user-images.githubusercontent.com/90829718/241697029-2119575e-890a-4ede-b4b6-3a507f9f256c.png" width="150" />
</p>
</div>

<div align="center">
    <h2>🚬 바른흡연 🔎</h2>
 </div>

<br />

## 목차
1. [**바른흡연 프로젝트란**](#barunsmoke)
1. [**기대 효과**](#effect)
1. [**데모영상**](#DeepLearning)
1. [**기술 스택**](#tech-stack)
1. [**구조도**](#structure)
1. [**검출과정**](#detection-process)
<br />

<a name="barunsmoke"></a>

## 📚 바른흡연 프로젝트란
>프로젝트 "바른흡연"은, 흡연자의 행위패턴을 분석하여 만들어낸 흡연자 검출 모델을 활용한 경로추천 서비스입니다.  <br/>
>흡연 관련 업무를 수행하는 단속반 및 미화원 분들에게 최적의 업무 경로를 제공하는 것을 목표로 합니다
<br/>

<br />
<a name="effect"></a>

## 💡 기대 효과
>1. 흡연자 검출수 기반 히트맵을 통해 효율적인 구역관리 지원.  <br/>
>2. 사용자 맞춤형 경로 추천으로 업무 효율 향상.  
>2-1. 최소 검출수 조정으로 선택적 경유지 설정  
>2-2. '최단거리' 경로 추천 지원  
>2-3. '검출수 우선' 경로 추천 지원  
>3. 검출수 데이터 통계로 더 정확한 단속 계획 수립 지원.
>4. 구역별 검출수 초기화 기능으로 미화원간 업무 혼선 방지.
<br/>

<br/>
<a name="DeepLearning"></a>

## 🎥 데모영상
| <div align="center"/>데모 영상(DeepLearning)| <div align="center">데모 영상(Client)|
| :----------------------------------------- |:----------------------------- |
|🔗[**데모 영상(DeepLearning) //후시녹음 + 길이조절**](https://drive.google.com/file/d/1A79oRBlCQMnTHgEM9tONC2gp72HaA1xk/view?usp=share_link)|🔗[**데모 영상(Client)**](클라이언트 데모 영상 링크)|
|<img src="https://user-images.githubusercontent.com/90829718/241766271-78b0295e-8af2-4d6c-9e48-bf754b405b3e.jpg" alt="딥러닝 데모영상" width="400"/>|<img src="클라이언트 데모 영상 이미지 URL" alt="클라이언트 데모영상" width="200"/>|

<br/>
<br/>
<a name="tech-stack"></a>

## 🛠 기술 스택

![](https://img.shields.io/badge/%20OpenPose-%2300008B)
<img src="https://img.shields.io/badge/YOLOv8-F79025?style=flat&logo=YOLO&logoColor=white" /> <img src="https://img.shields.io/badge/YOLOv5-000000?style=flat&logo=YOLO&logoColor=white" /> ![](https://img.shields.io/badge/%20SORT-%234B0082)

<img src="https://img.shields.io/badge/OpenCV-v4.7.0-000000?style=flat&logo=OpenCv&logoColor=white" /> <img src="https://img.shields.io/badge/Pytorch-v2.0.0+cu117-000000?style=flat&logo=PyTorch&logoColor=white" />

<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white" /> <img src="https://img.shields.io/badge/Swift-FF4500?style=flat&logo=Swift&logoColor=white" />

<img src="https://img.shields.io/badge/raspberrypi-A22846?style=flat&logo=raspberrypi&logoColor=white" /> <img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" />
![](https://img.shields.io/badge/%20-GoormIDE-blue)
 <img src="https://img.shields.io/badge/Colab-FFDB00?style=flat&logo=Google Colab&logoColor=orange" />

<img src="https://img.shields.io/badge/Flask-98FB98?style=flat&logo=Flask&logoColor=black" /> <img src="https://img.shields.io/badge/NaverMapAPI-2E8B57?style=flat&logo=Naver&logoColor=white" /> <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=Firebase&logoColor=white" /> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white" />


<br/>
<a name="structure"></a>

## ⚙ 구조도
<p align="center">
  <img src="https://user-images.githubusercontent.com/90829718/241696820-1fe716a9-c40a-482f-9f3d-1635bcfbd2df.jpg" width="1500" />
</p>
<br/>
<br/>

<a name="detection-process"></a>

## 🔍 검출과정
<p align="center">
  <img src="https://user-images.githubusercontent.com/90829718/241695846-e4dff658-6a93-4c28-9eb6-b58db491328c.jpg" width="1500" />
</p>
<br/>
<br/>
