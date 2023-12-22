# YOLOX 논문 리뷰 및 드론 트레픽 항공뷰 객체인식 프로젝트  
YOLOX 논문을 팀원들과 스터디 형식으로 공부하고, 공부한 내용을 토대로 드론 항공뷰 객체인식 프로젝트를 진행하며 Google Colab 환경에서 직접 코드에 적용시켜 보는 프로젝트 입니다.

프로젝트의 목적은 Camera based Object Detection 기법 중 하나인 YOLO에 대한 추가 학습, 인공지능 분야 논문 읽기 및 코드 리뷰를 통해 논문 읽기 역량 향상, 그리고 모두가 간편하게 코드를 실행해 볼 수 있도록 Google Colab 환경에서 코딩하는 것 입니다.

리뷰 논문 : <a href="https://arxiv.org/abs/2107.08430">YOLOX: Exceeding YOLO Series in 2021</a>

프로젝트 진행기간 : 23.10.23 ~ 23.11.14

------

## 프로젝트 구조
1. YOLOX github repository 복사
2. Python 환경 set up
3. Install Requirements
4. 사전 학습된 YOLOX 모델 다운로드
5. Kaggle Dataset 다운로드
6. Data split
7. Class modification
8. Training Parameters Definition
9. Inference

------

## 사용기술 및 환경
Google Colab, Python, Pytorch

------

## 테스트
<a href="https://github.com/yuzy1022/YOLOX-drone-traffic-object-detection/blob/main/src/%5BMSAI%5DYOLO_X_Drontraffic__kaggledataset_Final.ipynb">[MSAI]YOLO_X_Drontraffic__kaggledataset_Final.ipynb</a> 파일을 다운로드 받아 Google Colab (GPU 사용) 혹은 (컴퓨터 자원이 충분하다면) Local PC에서 Jupyter Notebook을 사용해 실행합니다.


<a href="https://github.com/yuzy1022/YOLOX-drone-traffic-object-detection/blob/main/src/YOLOX%20thesis%20review.pdf">YOLOX thesis review.pdf</a> 파일은 팀원 <a href="https://github.com/yuzy1022">박상원</a>이 논문을 리뷰하며 공부했던 내용을 논문 PDF파일에 주석으로 정리한 것입니다.  
해당 파일을 다운로드 받아 PDF뷰어로 실행하면 주석을 확인할 수 있습니다.

<a href="https://github.com/yuzy1022/YOLOX-drone-traffic-object-detection/blob/main/src/YOLOX%20%EB%B0%8F%20%EA%B4%80%EB%A0%A8%20%EA%B0%9C%EB%85%90%20%EC%A0%95%EB%A6%AC.pdf">YOLOX 및 관련 개념 정리.pdf</a> 파일은 팀원들끼리 YOLOX에 대해 공부한 내용과 관련 개념들을 간략하게 정리한 것입니다.

------

## 팀원
MicroSoft AI School 3기 9팀 : 전수형, 지이현, <a href="https://github.com/ICHBINLUCASKIM">김루카스</a>, <a href="https://github.com/yuzy1022">박상원</a>

------

## 결과 영상
<img src="https://github.com/yuzy1022/YOLOX-drone-traffic-object-detection-/blob/main/inference.gif">
드론 항공뷰로 차량들을 인식합니다.


좌측 상단에서는 차량의 숫자에 따라 교통 혼잡도를 확인할 수 있습니다.
