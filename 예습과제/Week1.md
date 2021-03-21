### 1. Computer Vision의 역사
##### Biological Vision의 역사
* 과거 고대 생물에게 시력은 존재하지 않았다가 시력이 생기면서 아주 짧은 기간동안 생물의 종이 폭발적으로 증가 (Evolution’s Big Bang)
* 시력은 거의 모든 지적 동물들의 가장 큰 감각 체계로 발전

##### Mechanical Vision의 역사
* Pinhole camera 이론에 근거한 카메라 Obscura  
        - 동물들이 구멍을 통해 빛을 모으는 초기 눈과 유사  
        - 카메라 뒤쪽에 있는 plane에서 정보와 영상을 수집  
* Hubel & Wiesel, 1959. Electrophysiology 연구  
        - 고양이 뇌에 전극을 꽂아서 어떤 자극이 고양이 뇌의 신경세포를 흥분시키는지 관찰  
        - 고양이 뇌의 1차 시각 피질 부분에는 많은 종류의 세포가 있지만, 가장 중요한 세포는 Edge에 반응하는 Simple cell  

##### Computer Vision의 역사
* Block world, 1963 : 눈에 보이는 사물들을 기하학적 모양으로 단순화
* “The Summer Vision Project”, 1966 : 대부분의 시각 체계를 구현하려는 시도
* <Vision>, David Marr, 1982 : 책에서는 눈으로 받아들인 정보를 우리가 생각하는 완전한 3D 형태
로 만들려면 다음과 같은 과정이 필요하다고 주장  
        - “Primal Sketch” - “2.5-D Sketch” - “3-D Model Representation”  
* ‘Generalized Cylinder’, ‘Pictorial Structure’ : 복잡한 사물을 단순하게 표현
* David Lowe, 1987 : 면도기를 단순한 선분과 곡선으로 이루어진 정보로 인식  
* 60s 70s 80s의 컴퓨터 비전 연구에서는 현실에 존재하는 일반적인 사물들을 대상으로 하는 것이 아닌, 그저 몇 가지 예시나 토이 프로젝트의 결과물만 낳는 것에 그침  
        - 이에 따라 객체 분할(Object Segmentation)을 해야 한다는 생각에 도달  
        - 객체 분할(Object Segmentation) : 이미지를 촬영하고 픽셀을 의미 있는 영역으로 그룹화하는 작업  
* 얼굴인식, 2001 : Using AdaBoost algorithm to do real-time face detection by Paul Viola
* SIFT feature, David Lowe : 불변하는 특징을 찾아 특징점끼리 매칭시키는 것이 이 알고리즘의 main idea
* Spatial Pyramid Matching, HOG algorithm
* ILSVRC(ImageNet Large Scale Visual Recognition Challenge)  
       - ImageNet은 22K의 C짐ategories와 14M 개의 이미지가 들어있는 엄청난 Dataset  
       - 2012년에 이 대회에서 Image Classification의 오차율이 급격히 감소  
       - 2012년 대회에서 우승한 혁신적인 알고리즘이 바로 CNN 구조를 기반으로 한 AlexNet  

### 2. Convolutional Neural Networks (CNN)
* Convolutional Neural Networks(CNN) have become an important tool for object recognition.
* 2012년에 CNN idea가 처음으로 나온 건 아님
* 그렇다면 2012년에 CNN이 유행하게 된 이유는?  
       - 연산 속도가 빨라짐(Increasing Computation)  
       - 데이터의 양이 많아짐  
