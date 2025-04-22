# 민성재

안녕하세요, 컴퓨터 비전과 딥러닝을 연구한 **민성재**입니다. 지능형 모빌리티 시스템을 위한 차량 도메인에서 혁신적인 AI에 열정을 가지고 있습니다.

- **학력:**
    - 국민대학교 자동차모빌리티대학원 석사 졸업 (자동차IT융합전공, AI 연구 중심) | 2023.03 - 2025.02
    - 국민대학교 자동차공학과 학사 졸업 | 2017.03 - 2023.02
- **석사 논문:** "실시간 얼굴 이미지 및 PPG 기반 운전자 감정 판단 딥러닝 알고리즘 개발"
- **주요 관심 분야:** Deep Learning, Computer Vision, Autonomous Driving Perception, Sensor Fusion, AI for Automotive Applications
- **연락처:** [mugun19@gmail.com](mailto:mugun19@gmail.com)

---

## 기술 스택 (Technical Skills)

* **Languages:** **Python** (상), C++ (중)
* **ML/DL Frameworks:** **PyTorch** (상), **TensorFlow** (상), Pytorch Lightning (중)
* **Computer Vision:** OpenCV (중)
* **Libraries & Tools:** NumPy (중), PCL (Point Cloud Library) (중), Git (중), Blender (하)
* **Robotics/Simulation:** ROS (중), CarMaker (중), Matlab (중)
* **OS:** Ubuntu (중)

*(숙련도: 상 - 깊은 이해 및 다수 실무 경험 / 중 - 문서 참고하여 복잡 문제 해결 가능 / 하 - 기본 개념 이해 및 간단 구현 가능)*

---

## 주요 프로젝트 및 연구 (Featured Projects & Research)

### 1. HMD 착용자 얼굴 복원 딥러닝 모델 개발 (Project Lead)
* **개요:** HMD 착용 시 가려진 얼굴 영역을 Unet + AdaIN 기반 모델로 복원하여 신원 정보 유지
* **역할:** Blender를 활용한 3D 모델 기반 합성 데이터 생성 및 모델 아키텍처 설계/학습 주도
* **성과:** FID 9.86, 신원 정보 코사인 유사도 0.63 달성, **KCC 2024 우수논문상 수상**
* **기술:** Python, PyTorch, Pytorch Lightning, UNet, GAN, AdaIN, Blender
* **논문:** [합성 데이터를 활용한 HMD 착용자의 얼굴 복원 (KCC 2024)](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11862045)

### 2. 실시간 운전자 감정 인식 모델 개발 (Project Lead)
* **개요:** Jetson Nano 환경에서 실시간 구동을 목표로 SCRFD 얼굴 검출 + PPG 센서 데이터를 융합한 감정 인식 모델 개발 (MobileNetV3 기반)
* **역할:** 이미지 특징 추출 모듈 개발 담당
* **성과:** 기존 모델 대비 FPS 약 5배, 정확도 약 19% 향상
* **기술:** Python, PyTorch, SCRFD, MobileNetV3, Supervised Learning
* **논문:** [실시간성을 고려한 얼굴 이미지 기반의 운전자 감정 인식 (KSAE 2024)](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12047679)

### 3. In-the-Wild 환경 감정 인식 모델 개발 (CVPR ABAW Challenge, Project Lead)
* **개요:** ViT (Vision Transformer) 및 Transformer 기반 네트워크를 설계하여 다양한 환경에서의 감정 인식 성능 향상 목표
* **역할:** 모델 아키텍처 설계, 구현 및 학습 주도
* **성과:** Valence Arousal 부문 baseline 대비 성능 약 33.53% 향상
* **기술:** Python, PyTorch, Vision Transformer (ViT), Transformer
* **논문:** [Emotion Recognition Using Transformers with Random Masking (CVPRW 2024)](https://ieeexplore.ieee.org/document/10678303)

### 4. AI 기반 EV 토크벡터링 제어 연구 (현대자동차 산학과제)
* **개요:** 센서 데이터 기반 차량 미래 움직임 예측 알고리즘 개발 (1D CNN 활용)
* **성과:** 예측 정확도 75% 달성 (기존 대비 25%↑), 목표 움직임 재현 오차 15%↓
* **기술:** Python, TensorFlow/PyTorch, Matlab, CarMaker, 1D CNN

### 5. 자율주행 차량 경진대회 (인식 담당)
* **개요:** LiDAR-카메라 센서 융합 알고리즘 설계
* **성과:** 팀 최종 2위, 주행 중 장애물 충돌 0회
* **기술:** Python, OpenCV, PCL, NumPy, Sensor Fusion

---

## 수상 및 발표 (Awards & Publications)

* **우수논문상:** 한국정보과학회 한국컴퓨터종합학술대회 (KCC 2024)
* **Publications:**
    * [S. Min, J. Yang and S. Lim, "Emotion Recognition Using Transformers with Random Masking," CVPRW 2024](https://ieeexplore.ieee.org/document/10678303)
    * [민성재, 양준석, 임세준. (2024). 합성 데이터를 활용한 HMD 착용자의 얼굴 복원. KCC 2024](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11862045)
    * [민성재, 정병진, 양준석, 임세준. (2024). 실시간성을 고려한 얼굴 이미지 기반의 운전자 감정 인식. KSAE 2024 추계학술대회](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12047679)

---
