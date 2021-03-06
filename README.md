<img src="https://user-images.githubusercontent.com/22374750/90978874-f01f0100-e58b-11ea-9b35-ec1d4529ee57.png" width="128" height="128">

# Burnout Challenge 🧯

[![Android11](https://img.shields.io/badge/Android11-📱-green.svg)](https://developer.android.com/preview)
[![Wiki](https://img.shields.io/badge/Wiki-📚-pink.svg)](https://github.com/hakzzang/Burnout/wiki)
![Last Commit](https://img.shields.io/github/last-commit/hakzzang/Burnout)

번아웃을 재미있게 해결해보고자, 멘탈을 건강하게 하는 `Health`를 주제로 프로젝트를 진행합니다.<br/>
<a href="https://festa.io/events/1111" target="_blank">안드로이드11 끝장개발대회</a> 참여 프로젝트입니다.

<br/>

<p align="center">
    <img src="https://user-images.githubusercontent.com/25583321/91629470-5bd9f180-ea04-11ea-9cbb-b986cf77605b.png"  
     width="520px" height="292.5px" href="https://github.com/ggujangi/ggu.system.ui/files/4094927/System.UI.Visibility.ppt.pptx"/>
</p>
<p align="center">
    👆👆
  <br/> <br/>
    <a href="https://github.com/hakzzang/Burnout/files/5144815/BURNOUT_._._.pptx" target="_blank">번아웃_챌린지 발표자료</a>
</p>




# About

### 🔥 팀 HBS
- 문병학<br/>
    ✔️ AAC, Jetpack, Coroutine, Material Design <br/>
    ✔️ 채팅 UI, 기능 개발
    
- 조희영<br/>
    ✔️ TF Lite, CameraX, Sketch Library <br/>
    ✔️ 미션 화면 UI, 기능 개발

- 이홍주<br/>
    ✔️ ScopedStorage,  <br/>
    ✔️ 미션 결과 UI, 기능 개발


### 💡 특징

- 프로젝트는 다크테마와 가로모드를 고려했습니다 🌗
- 프로젝트는 머터리얼 트랜지션을 고려했고, 머터리얼 디자인 뷰를 사용했습니다 ✏️
- 프로젝트는 Dagger2-Hilt를 사용했습니다 🗡️


### 🌱 Android 11

- 안드로이드 Bubble을 통한 채팅 시스템을 고려하고 있습니다 🧼
- 안드로이드에서 제공하는 최신 Jetpack Library를 사용하고 있습니다 🚄

### ⚽ 목표
- 인공지능을 통한 새판별기를 구현하려고 합니다 🐤
- 채팅 UI 기반의 게임을 구현하려고 합니다 💬
- SNS 챌린지를 만드는 앱을 구현하려고 합니다 💪




# Schedule

![date](https://user-images.githubusercontent.com/22374750/89760983-694c3c00-db28-11ea-98d1-9ec6bd0ace47.png)

## Week 1

### 0. 프로젝트 개요

이 앱은 좋아하는 유튜브 bj가 어느날 삶이 정말 재미없어졌을 때, 문득 색안경을 사러 안경점에 갔다고 합니다. 안경점에서 색안경을 사고 난 후에, 색안경을 끼고 이곳 저곳 돌아다니다보니, 뭔가 다른 시야를 얻게 되었다는 경험을 했습니다. 이러한 경험을 앱을 통해서 제공하면 의미있을 것이라고 생각을 했습니다. 그래서 저희는 멘탈케어를 할 수 있는 번아웃 챌린지 앱을 생각하게 되었습니다. 번아웃 챌린지 앱은 ‘아무 의미 없는 미션’(사진 찍기, 그림 그리기) 등의 미션을 수행하고, 이것을 클리어 함을 통해서 특별한 의미를 제공해주고자 했고, 앱은 대화형 UI/UX 의 구조를 갖고 있으며, 카메라, 지도 등을 사용합니다.

### 1. 프로젝트 소개

실제 앱에서는 10개, version 1.0을 기준으로 제출할 때는 3개의 미션을 기준으로 합니다.
모든 미션을 클리어했다는 내용과 함께 ‘앱의 마지막’을 보여줌을 통해서, 번아웃과 관련된 멘탈치료를 할 수 있도록 돕고자 하는 취지가 있습니다.

메인 화면 : 미션 실행 -> 미션 진행(대화형 UI/UX 구조)
미션 화면 : 미션은 그림 그리기, 옆 사람 때리기, 새 사진 찍기 등의 미션으로 되어 있음->  
미션을 클리어 하게 되면, 미션을 완료했다는 것을 SNS에 공유하는 기능이 있어야 함 
카메라 미션 화면 : 카메라 미션은 사진을 인식하는 기능이 있음

### 2. 러프한 화면

![image](https://user-images.githubusercontent.com/22374750/89758160-1f605780-db22-11ea-8880-5b9ed04093ff.png)

![image](https://user-images.githubusercontent.com/22374750/89758212-3acb6280-db22-11ea-8e5d-e8a979664eec.png)


## Week 2
### 채팅 프로젝트 만들기

![image](https://user-images.githubusercontent.com/22374750/90979282-0b3f4000-e58f-11ea-91f3-57298ba9601f.png)

### 이미지 인식 기능
#### 사용된 Android 기능 및 기술
- CameraX: https://developer.android.com/training/camerax
 -- 카메라 priview와 캡쳐 기능 사용
- Navigation: https://developer.android.com/guide/navigation
 -- 카메라의 프리뷰와 캡쳐 결과 화면, 퍼미션 화면간 이동에 사용
- TensorFlow Lite: https://developer.android.com/ml
 -- 사용된 tf lite 용 모델 및 예제
  1. 새 이미지 인식 (TF 허브) :https://tfhub.dev/google/aiy/vision/classifier/birds_V1/1
  2. 이미지 인식 (TF 허브) :https://tfhub.dev/tensorflow/lite-model/efficientnet/lite4/fp32/1
  3. 스케치 인식 : https://github.com/jtheiner/SketchRecognition/
- ML binding: https://developer.android.com/studio/preview/features?hl=fr#tensor-flow-lite-models
 -- tflite 모델 바인딩에 사용
 
## Week 3
### 스테이지 & 뱃지함 리스트 추가

![image](https://user-images.githubusercontent.com/22374750/91059945-4f9d0f80-e665-11ea-902f-347f73792a88.png)
