# eye_blink_DeepLearning
안구건조증 예방 딥러닝 프로젝트
=============

### 1 프로젝트 설명
-------------

    딥러닝으로 눈 깜빡임을 인지하여, 컴퓨터 화면을 보는 사용자가 눈을 많이 깜빡이도록 도와줍니다.
    1분에 20회 미만으로 깜빡이면 경고음과 함께 경고창이 생성됩니다.
    경고창을 닫으면 깜빡임 횟수가 자동으로 초기화되며 처음부터 다시 시작됩니다.
    1분에 20회 이상 깜빡이면 자동으로 초기화되며 처음부터 다시 시작됩니다.


### 2 딥러닝 환경 설정
-------------
  #### 1) Install Anaconda
  
  #### 2) Create virtual environment
  ```
  conda activate (name of your virtual environment)
  ```

  #### 3) Install Keras (version 2.4.3)
  ```
  pip install keras==2.4.3
  ```
  #### 4) Install TensorFlow (version 2.2)
  ```
  pip install tensorflow==2.2
  ```
  #### 5) Execute jupyter notebook
  ```
  jupyter notebook
  ```



### 3 Dataset 취득
-------------
   왼쪽 눈 뜬 사진(jpg) 300개, 왼쪽 눈 감은 사진(jpg) 300개 총 600개의 dataset 사용
   
   ![image](https://user-images.githubusercontent.com/77608922/158016847-2656b80f-f3ea-48b0-b992-4d941b9979fe.png)

 
 
 
### 4 전체 코드 흐름
-------------
![image](https://user-images.githubusercontent.com/77608922/158016821-4f6b1eac-0ee6-435b-8266-5617aeac21b5.png)


### 5 preprocess.py
-------------
    The number of train dataset : The number of test dataset = 480 : 120 = 8 : 2


### 6 train.py
-------------
   #### 1) Data Augmentation
    
   #### 2) Build Model
  
<img src="https://user-images.githubusercontent.com/77608922/158017061-93995a66-bf7a-4ad7-936c-53b65a755418.png" width="50%" height="50%">
   
   #### 3) Train
   
<img src="https://user-images.githubusercontent.com/77608922/158017100-7d3b4ce6-adc4-4f6d-8021-4d37abac8a04.png" width="80%" height=80%>
<img src="https://user-images.githubusercontent.com/77608922/158017143-2f18cb0a-6d5c-4c93-9fcb-7f2d960fe5f4.png" width="80%" height="80%">



### 7 test.py
-------------

Execute the program!

<img src="https://user-images.githubusercontent.com/77608922/158047811-5cca0532-9a8c-4a0e-b2c9-a6954ebaa6aa.png" width="40%" height="40%">

실행화면 캡쳐 이미지
