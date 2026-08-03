<div align="center">

# Donghwan Yun

### Machine Learning Engineer · Autonomous Systems

센서 데이터를 학습 기반 의사결정과 경로 계획으로 연결해  
**재현 가능하고 검증 가능한 지능형 시스템**을 구현합니다.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest">
</p>

`Reinforcement Learning` · `Path Planning` · `Sensor Intelligence` · `Edge AI`

</div>

---

## Featured Project

### [UAV Signal Search & RSSI Localization](https://github.com/raccoon297/UAV_Signal_Search_Localization)

PPO 탐색, LiDAR 장애물 회피, A* 편대 배치와 RSSI 위치 추정을  
하나의 재현 가능한 UAV 시뮬레이션 파이프라인으로 통합했습니다.

<p align="center">
  <a href="https://github.com/raccoon297/UAV_Signal_Search_Localization">
    <img src="https://raw.githubusercontent.com/raccoon297/UAV_Signal_Search_Localization/main/results/animations/full_pipeline.gif" width="900" alt="UAV signal search and localization pipeline">
  </a>
</p>

<table>
  <tr>
    <td align="center" width="25%"><b>84.17%</b><br>Search Success<br><sub>3,000 episodes</sub></td>
    <td align="center" width="25%"><b>2.337 m</b><br>Mean Localization Error<br><sub>500 scenarios</sub></td>
    <td align="center" width="25%"><b>87.0%</b><br>Error Reduction<br><sub>vs. baseline</sub></td>
    <td align="center" width="25%"><b>0.0187 ms</b><br>ANN Inference<br><sub>mean latency</sub></td>
  </tr>
</table>

**What I built**

- Continuous-action PPO policy with a `3 × 3` belief map and 16-direction LiDAR
- Collision-aware triangular deployment of three UAVs using A*
- LOS·PNLOS·NLOS RSSI sampling from measured data
- Kalman filtering, a compact ANN and least-squares trilateration
- Reproducible evaluation scripts, pretrained weights and unit tests

<p align="right"><a href="https://github.com/raccoon297/UAV_Signal_Search_Localization"><b>View repository →</b></a></p>

---

## Selected Work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/raccoon297/Image_Processing/tree/main/Automatic_Modulation_Classification">Edge-Efficient AMC</a></h3>
      <a href="https://github.com/raccoon297/Image_Processing/tree/main/Automatic_Modulation_Classification">
        <img src="https://raw.githubusercontent.com/raccoon297/Image_Processing/main/Automatic_Modulation_Classification/results/model_dashboard.png" width="100%" alt="Automatic modulation classification model dashboard">
      </a>
      <p>
        RadioML I/Q 신호를 성상도 이미지로 변환하고 MobileNetV3와 ResNet-18의 정확도·연산 효율을 비교했습니다.
      </p>
      <p>
        <b>253× fewer FLOPs</b><br>
        <b>7.3× smaller model</b><br>
        <b>1.64 ms CPU inference</b>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/raccoon297/Path_Planning_Practice/tree/main/03_Reinforcement_Learning">3D RL Path Planning</a></h3>
      <a href="https://github.com/raccoon297/Path_Planning_Practice/tree/main/03_Reinforcement_Learning">
        <img src="https://raw.githubusercontent.com/raccoon297/Path_Planning_Practice/main/03_Reinforcement_Learning/results/comparison/navigation_comparison.gif" width="100%" alt="DQN and PPO 3D navigation comparison">
      </a>
      <p>
        동일한 3차원 도시 환경에서 DQN의 이산 위치 제어와 PPO의 연속 가속도 제어가 만드는 경로 특성을 비교했습니다.
      </p>
      <p>
        <b>15.9% shorter trajectory</b><br>
        <b>98.1% lower roughness</b><br>
        <b>74 steps to goal</b>
      </p>
    </td>
  </tr>
</table>

---

## Project Collections

| Repository | Focus | Highlights |
|---|---|---|
| [**UAV Signal Search & Localization**](https://github.com/raccoon297/UAV_Signal_Search_Localization) | RL · Sensor Fusion · Localization | PPO, LiDAR, A*, RSSI, Kalman+ANN |
| [**Path Planning Laboratory**](https://github.com/raccoon297/Path_Planning_Practice) | Planning · Optimization · RL | A*, RRT, D* Lite, ACO, GA, GWO, PSO, DQN, PPO |
| [**Image & Signal Intelligence**](https://github.com/raccoon297/Image_Processing) | Edge AI · Computer Vision | AMC benchmark, image enhancement, hand-gesture game |

---

## Engineering Focus

- 문제 정의부터 데이터 처리, 모델 학습, 정량 평가와 시각화까지 하나의 실행 흐름으로 구성합니다.
- 평균 성능만 제시하지 않고 실패 사례, 제약 조건과 해석상의 한계를 함께 기록합니다.
- VS Code에서 바로 실행할 수 있는 Python 프로젝트 구조와 재현 가능한 명령형 스크립트를 선호합니다.

### Currently Building

**Predictive Maintenance Early Warning** — 고장 발생 여부만 분류하는 대신, 고장을 몇 단계 앞서 감지하는 조기경보 문제를 구현하고 있습니다.

---

<div align="center">
  <b>Kwangwoon University · Seoul, Korea</b><br>
  <sub>Building reliable ML systems for sensing, decision-making and autonomous navigation.</sub>
</div>
