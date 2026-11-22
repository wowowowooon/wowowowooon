<!-- Header -->
<img src="./assets/header.svg" width="100%" alt="Moon Jaewoong · Vehicle Embedded Systems · ADAS"/>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=18&duration=2800&pause=900&color=4FD1C5&center=true&vCenter=true&width=640&lines=%24+candump+can0+%E2%80%94+listening+to+the+vehicle;%24+sensor+%E2%86%92+PCB+%E2%86%92+firmware+%E2%86%92+real+car;%24+LiDAR+%2B+IMU+%E2%86%92+perception+%E2%86%92+control+(ADAS);%24+measure.+build.+validate+on+track." alt="typing"/>

</div>

<br>

## 🙋‍♂️ About Me

- 🎓 아주대학교 **기계공학과**
- 🎯 **차량용 임베디드 시스템 · ADAS** 엔지니어를 목표로 합니다
- 🏎️ **IFAC 2026 Roboracer 자율주행 레이싱** 본선 32강 · 경로 생성·추종·회피 파트 단독 담당
- 🏁 자작자동차 동아리 **A-FA** · BAJA(2026) / e-Formula(2025) 차량 계측 시스템
- 🔧 센서 선정 → 회로·PCB → MCU 펌웨어 → 실차 검증까지 **끝까지 직접** 해보는 걸 좋아합니다
- 📘 지금은 **C/C++ · Embedded C**를 기초부터 다시 다지는 중입니다

<br>

## 🗺️ Project Map

<div align="center">

| | 🏎️ 자율주행 레이싱 | 🏁 BAJA 계측 | 🪰 Fly Racer | ⚡ e-Formula | 🚆 KORAIL |
|:---|:---:|:---:|:---:|:---:|:---:|
| **ADAS · 인지/판단/제어** | ✅ | | ✅ | | |
| **차량 계측 · DAQ** | | ✅ | | ✅ | ✅ |
| **차량 통신 (CAN · UART · I2C)** | ✅ | ✅ | | ✅ | ✅ |
| **MCU 펌웨어** | | ✅ | | ✅ | ✅ |
| **회로 · PCB** | | ✅ | | | ✅ |
| **실차 검증** | ✅ | ✅ | ✅ | ✅ | |

</div>

<br>

## 📌 Projects

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/wowowowooon/Roboracer-2026"><img src="./assets/projects/roboracer.jpg" width="100%"/></a>

### 🏎️ [자율주행 레이싱카 경로 추종·회피 스택](https://github.com/wowowowooon/Roboracer-2026)
<sub>IFAC 2026 제29회 Roboracer · 아주대 A:UTO · 2025.12 – 2026.08</sub>

1/10 자율주행 레이싱카에서 **Path Following 파트를 혼자 설계·구현·튜닝**했습니다.

- 🏆 **본선 진출 · 32강**
- 📐 최소곡률 레이스라인(볼록 QP) → 예상 랩타임 **−16%**
- 🛑 속도 기반 회피 기동 + TTC **AEB** → 777개 지점 시험에서 **벽 충돌 계획 0건**
- 🧪 단위 테스트 **501개** · GitHub Actions CI

<img src="https://img.shields.io/badge/ROS%202%20Humble-22314E?style=flat-square&logo=ros&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white"/> <img src="https://img.shields.io/badge/Jetson%20Orin%20NX-76B900?style=flat-square&logo=nvidia&logoColor=white"/> <img src="https://img.shields.io/badge/LiDAR-0B1220?style=flat-square"/> <img src="https://img.shields.io/badge/Stanley-0B1220?style=flat-square"/>

</td>
<td width="50%" valign="top">

<a href="https://github.com/wowowowooon/A-FA-2026-BAJA"><img src="./assets/projects/baja.jpg" width="100%"/></a>

### 🏁 [BAJA 실시간 계측 · 서스펜션 최적화](https://github.com/wowowowooon/A-FA-2026-BAJA)
<sub>아주대 A-FA · 2026 KSAE 대학생 자작자동차대회 기술아이디어</sub>

오프로드 차량에 계측 시스템을 **직접 만들어 싣고**, 그 데이터로 서스펜션 세팅을 골랐습니다.

- 📉 실차 피치 변동폭 **10.70° → 5.50° (−48.6%)**
- 🔌 RPi + ESP32(ADC→I2C) + Teensy(ECU **CAN**) 통합 · 진동에 강한 **자체 PCB**
- 📡 MQTT → FastAPI → InfluxDB / WebSocket 실시간 대시보드
- 🛞 에어쇼바 실측 → 등가 강성식 → Altair 점프 해석

<img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white"/> <img src="https://img.shields.io/badge/Teensy%204.1-555555?style=flat-square"/> <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white"/> <img src="https://img.shields.io/badge/CAN-0B1220?style=flat-square"/> <img src="https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/wowowowooon/Fruit-fly-brain-reinforcement-learning"><img src="./assets/projects/flyracer.gif" width="100%"/></a>

### 🪰 [초파리 뇌 배선으로 달리는 1:10 자율주행차](https://github.com/wowowowooon/Fruit-fly-brain-reinforcement-learning)
<sub>커넥톰 강화학습 · Sim-to-Real · 2026.09 – 10</sub>

초파리 뉴런 871개 배선을 그대로 쓴 제어기를, **직접 구현한 시뮬레이터**로 학습시켜 실차에 올렸습니다.

- 🏁 학습에 안 쓴 대회 코스 **21/21 완주**
- 🧠 밀집망 대비 파라미터 **59배 적음**, 센서 고장·지연 등 처음 보는 조건에서 더 강건
- 🚗 **Jetson Xavier NX 실차 주행 성공** (라이다 + IMU만 사용, 지도 없음)

<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/ROS%202-22314E?style=flat-square&logo=ros&logoColor=white"/> <img src="https://img.shields.io/badge/Jetson%20Xavier%20NX-76B900?style=flat-square&logo=nvidia&logoColor=white"/> <img src="https://img.shields.io/badge/VESC-333333?style=flat-square"/> <img src="https://img.shields.io/badge/RL%20%C2%B7%20PPO-0B1220?style=flat-square"/>

</td>
<td width="50%" valign="top">

<a href="https://github.com/A-FA-2025/monolith"><img src="./assets/projects/eformula.svg" width="100%"/></a>

### ⚡ [e-Formula 차량 텔레메트리 시스템](https://github.com/A-FA-2025/monolith)
<sub>아주대 A-FA · 2025 자작자동차대회 · 팀 프로젝트</sub>

STM32F4 ECU가 받은 CAN 데이터를 **운전석 디스플레이와 원격 서버로 동시에** 보내는 계측 플랫폼입니다.

- 🖥️ RPi 5 운전석 디스플레이 (장갑 착용 고려한 저항식 터치)
- 📡 ESP32 → WSS/Socket.IO → 웹 실시간 모니터링 · 로그 리뷰
- 🧪 가상 CAN 데이터를 쏘는 **시뮬레이터**로 수신 로직 사전 검증

<img src="https://img.shields.io/badge/STM32F4-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white"/> <img src="https://img.shields.io/badge/CAN-0B1220?style=flat-square"/> <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white"/> <img src="https://img.shields.io/badge/Raspberry%20Pi%205-A22846?style=flat-square&logo=raspberrypi&logoColor=white"/> <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/wowowowooon/KORAIL-Measuring-instrument"><img src="./assets/projects/korail.jpg" width="100%"/></a>

### 🚆 [KORAIL 연결기 높이 측정기](https://github.com/wowowowooon/KORAIL-Measuring-instrument)
<sub>휴대형 측정 장치 · 기구 · PCB · 펌웨어</sub>

레이저 거리센서 2개와 궤간(1435 mm)만으로 철도차량 연결기 높이를 재는 장치를 **혼자 처음부터 끝까지** 만들었습니다.

- 📏 각도 없이 세 변으로 높이 계산 → 레이저 각도 바뀌어도 재보정 불필요
- 🔍 센서 3차 비교 → ±1 mm 성능을 약 **1/5 가격**으로
- 🛡️ 이상값 차단 · 응답 없는 센서 자동 재시작 · 최소제곱 보정 도구

<img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white"/> <img src="https://img.shields.io/badge/Arduino%20C%2B%2B-00979D?style=flat-square&logo=arduino&logoColor=white"/> <img src="https://img.shields.io/badge/UART-0B1220?style=flat-square"/> <img src="https://img.shields.io/badge/KiCad%209-314CB0?style=flat-square&logo=kicad&logoColor=white"/> <img src="https://img.shields.io/badge/SolidWorks-DA291C?style=flat-square&logo=dassaultsystemes&logoColor=white"/>

</td>
<td width="50%" valign="top">

<a href="https://github.com/wowowowooon/C-study"><img src="./assets/projects/cstudy.svg" width="100%"/></a>

### 📘 [C/C++ · Embedded C Study](https://github.com/wowowowooon/C-study)
<sub>진행 중 · C++17 / C11</sub>

하드웨어는 많이 만들어 봤지만, 펌웨어를 **AI 없이 직접 읽고 쓰는 힘**을 키우려고 처음부터 다시 쌓고 있습니다.

- 📖 언어 기초 → 알고리즘(프로그래머스 Lv.3) → 임베디드 C
- 🔧 목표: `volatile` · ISR · 링 버퍼 · 상태 머신 · PID · CAN 파싱 직접 구현

<img src="https://img.shields.io/badge/C11-A8B9CC?style=flat-square&logo=c&logoColor=black"/> <img src="https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=cplusplus&logoColor=white"/> <img src="https://img.shields.io/badge/g%2B%2B-0B1220?style=flat-square"/>

</td>
</tr>
</table>

<br>

## 🛠️ Tech Stack

| 분야 | 기술 |
|:---|:---|
| **MCU / SBC** | <img src="https://img.shields.io/badge/STM32F4-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white"/> <img src="https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white"/> <img src="https://img.shields.io/badge/Teensy%204.1-555555?style=flat-square"/> <img src="https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white"/> <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat-square&logo=raspberrypi&logoColor=white"/> <img src="https://img.shields.io/badge/Jetson%20Orin%20NX-76B900?style=flat-square&logo=nvidia&logoColor=white"/> <img src="https://img.shields.io/badge/Jetson%20Xavier%20NX-76B900?style=flat-square&logo=nvidia&logoColor=white"/> |
| **Vehicle Network** | <img src="https://img.shields.io/badge/CAN-0B1220?style=flat-square"/> <img src="https://img.shields.io/badge/I2C-0B1220?style=flat-square"/> <img src="https://img.shields.io/badge/UART-0B1220?style=flat-square"/> <img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white"/> <img src="https://img.shields.io/badge/WebSocket-12304F?style=flat-square"/> |
| **ADAS / Robotics** | <img src="https://img.shields.io/badge/ROS%202%20Humble-22314E?style=flat-square&logo=ros&logoColor=white"/> <img src="https://img.shields.io/badge/Cartographer-0B1220?style=flat-square"/> <img src="https://img.shields.io/badge/2D%20LiDAR-0B1220?style=flat-square"/> <img src="https://img.shields.io/badge/IMU-0B1220?style=flat-square"/> <img src="https://img.shields.io/badge/VESC-333333?style=flat-square"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> |
| **Control / Planning** | <img src="https://img.shields.io/badge/Stanley-12304F?style=flat-square"/> <img src="https://img.shields.io/badge/Min--curvature%20QP-12304F?style=flat-square"/> <img src="https://img.shields.io/badge/TTC%20AEB-12304F?style=flat-square"/> <img src="https://img.shields.io/badge/Follow--the--Gap-12304F?style=flat-square"/> <img src="https://img.shields.io/badge/Kalman%20Filter-12304F?style=flat-square"/> |
| **Language** | <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black"/> <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/> |
| **Hardware / CAE** | <img src="https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white"/> <img src="https://img.shields.io/badge/SolidWorks-DA291C?style=flat-square&logo=dassaultsystemes&logoColor=white"/> <img src="https://img.shields.io/badge/Altair%20Inspire-005A9C?style=flat-square"/> |
| **Data / Server** | <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/> <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white"/> <img src="https://img.shields.io/badge/InfluxDB-22ADF6?style=flat-square&logo=influxdb&logoColor=white"/> <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/> <img src="https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white"/> |
| **Dev** | <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black"/> <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white"/> <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white"/> |

<br>

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=wowowowooon&theme=tokyonight" width="100%"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=wowowowooon&theme=tokyonight" width="49%"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=wowowowooon&theme=tokyonight" width="49%"/>
</div>

<br>

## 📫 Contact

<a href="https://github.com/wowowowooon"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>


<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F4E8C,100:0B1220&height=120&section=footer" width="100%"/>
