# SWCON_CapstoneDesign
## Object Detection과 Classification을 활용한 Activity Recognition
    
#### 가. 과제 설계 배경 및 필요성
기존 서비스(갤럭시 사진 자동 태그 추천)는 이미지에 나타나는 객체 태그로만 활동을 나타내고 있어
무슨 활동을 하는지에 대한 정보는 제공하고 있지 않으며 그 정확도가 상당히 떨어지고 있다. 이 부분
에 대한 정확한 활동의 정의 및 분류를 위해 해당 과제를 선정했다. 또한 기존 활동 분류의 경우 3인
칭으로 사람의 동작을 보고 분류를 진행하는 경우가 많기 때문에 해당 과제는 1인칭 시점으로 객체
기반으로 활동을 분류하고자 하였다.
#### 나. 과제 주요내용
해당 과제의 주요 내용은 사진에 접근해 객체를 탐지해 사용자가 어떤 활동을 하고 있는지에 대해
분류하고 활동 시작과 활동 끝 이미지 정보를 통해 활동 시간을 파악한다. 이미지의 주된 주제를 분류
할 때 사용되는 기법은 Object Detection과 그 객체 탐지 결과 값을 토대로 주요 객체를 추출한 뒤,
해당 객체 정보를 사용해 머신 러닝 분류기를 사용해 분류 성능을 비교하고 가장 성능이 좋은 최종
분류기를 선택하여 최종 활동 분류를 진행한다.
#### 다. 최종결과물의 목표
최종적인 활동의 분류 결과의 목표로 정확도를 0.8 이상으로 결정해 과제를 진행한다. 또한 활동 시작
이미지와 활동 끝 이미지를 입력했을 때 활동의 분류 뿐만 아니라 부가적으로 총 활동 시간 정보를
반환하는 것을 목표로 한다.
