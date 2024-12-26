# 👋 안녕하세요, 저는 장성민입니다!

[간단한 자기소개 및 현재 활동 내용]

## 📚 프로젝트 포트폴리오

아래는 제가 진행한 주요 프로젝트들입니다. 각 프로젝트의 제목을 클릭하시면 상세한 내용을 확인하실 수 있습니다.

### 1. [Smart Carrier Project]([프로젝트 GitHub 링크](https://github.com/jsamez/05-tailer-swift))
- **설명**: 현대의 객체 인식 기술은 다양한 환경에서 사람의 위치를 추적하고 그 거리를 정확하게 측정하는 데에 어려움이 있습니다. 특히, 사람들이 밀집된 환경이나 불규칙한 조명 아래에서 신뢰할 수 있는 정보를 제공하는 것이 중요하며, 사용자가 이동 방향을 실시간으로 확인할 수 있는 시스템이 필요합니다.
- **주요 기능**:
  - 카메라를 통해 객체인식 후 인식된 사람의 진행방향에 따라 진행방향을 결정
  - IoU기술을 통해 다음 프레임에서도 사용자를 인식
  - monodepth모델을 통한 상대적 거리측정
  - 이미지 전처리를 통한 인식률 증가
- **사용 기술**: python, Yolo, MonoDepth, OpenCV, MediaPipe, Gstream, Bluetooth
- **사용한 하드웨어** : Camera, RaspberryPi4, Computer,MotorDriver
- **시연 영상**:
  ([시연 영상](https://youtu.be/09_n7xEd-p4))

### 2. [특징 추출을 통한 사용자 인식]([프로젝트 GitHub 링크](https://github.com/jsamez/suit))
- **설명**: 화면에서 인물이 잠시 사라졌다가 다시 나타날 때, 동일 인물로 인식할 수 있는지 확인하는 프로그램입니다. OpenVINO ZOO의 Pre-Trained 모델만을 활용하여 특정 인물만 인식하도록 하고, 다른 인물의 사진을 저장하는 기능을 구현했습니다.
- **주요 기능**:
  - 처음 찍힌 사람의 특징을 추출해서 사용자로 지정
  - 다음프레임에 인식된 사람과 추출한 벡터를 Scipy의 Cosine 함수를 활용해 특징 벡터 간의 유사도를 측정
- **운영 체제(OS):** Ubuntu 18.04
- **사용 언어:** Python
- **주요 라이브러리:** OpenVINO, Scipy (Cosine Similarity)
- **시연 영상**:
  ([시연 영상](https://youtu.be/R1ZEraahKhw))

### 3. [레시피 추천 프로그]([프로젝트 GitHub 링크](https://github.com/jsamez/ARR))
- **설명**:
- **주요 기능**:
...

## 🛠️ 기술 스택

- **프로그래밍 언어**: Python, JavaScript, C, C++, verilog,VHDL.
- **프레임워크 및 라이브러리**: [예: React, Django, etc.]
- **도구**: Git, Docker, etc.

## 📫 연락처

- **이메일**: jsamez0125@naver.com

