<!-- Header -->
<img src="./assets/header.svg" width="100%" alt="Moon Jaewoong · Vehicle Embedded Systems · ADAS"/>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=18&duration=2800&pause=900&color=4FD1C5&center=true&vCenter=true&width=640&lines=%24+candump+can0+%E2%80%94+listening+to+the+vehicle;%24+sensor+%E2%86%92+PCB+%E2%86%92+firmware+%E2%86%92+real+car;%24+LiDAR+%2B+IMU+%E2%86%92+perception+%E2%86%92+control+(ADAS);%24+measure.+build.+validate+on+track." alt="typing"/>

</div>

<br>

## 🙋‍♂️ About Me

- 🎓 아주대학교 **기계공학과**
- 🚗 **차량용 임베디드 시스템 · ADAS** 엔지니어를 목표로 하고 있습니다
- 🏁 자작자동차 동아리 **A-FA** (BAJA · e-Formula) · 자율주행 레이싱 **ROBORACER 2026** 출전
- 👁️ LiDAR·IMU 기반 인지 → 제어를 1:10 자율주행차에 올려 실차 주행까지 해봤습니다
- 🔧 센서 선정 → 회로·PCB 설계 → MCU 펌웨어 → 실차 검증까지 **직접 끝까지** 해보는 걸 좋아합니다
- 📘 지금은 **C/C++ · Embedded C** (volatile, ISR, 링 버퍼, PID, CAN 파싱)를 기초부터 다시 다지는 중입니다

<br>

## 🛠️ Tech Stack

**Embedded / MCU**
<br>
<img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white"/>
<img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white"/>
<img src="https://img.shields.io/badge/Teensy%204.1-555555?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white"/>
<img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white"/>
<img src="https://img.shields.io/badge/Jetson%20Xavier%20NX-76B900?style=for-the-badge&logo=nvidia&logoColor=white"/>

**Protocol**
<br>
<img src="https://img.shields.io/badge/CAN-0B1220?style=for-the-badge"/>
<img src="https://img.shields.io/badge/I2C-0B1220?style=for-the-badge"/>
<img src="https://img.shields.io/badge/UART-0B1220?style=for-the-badge"/>
<img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white"/>

**Language**
<br>
<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black"/>
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>

**Hardware / CAE**
<br>
<img src="https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white"/>
<img src="https://img.shields.io/badge/SolidWorks-DA291C?style=for-the-badge&logo=dassaultsystemes&logoColor=white"/>
<img src="https://img.shields.io/badge/Altair%20Inspire-005A9C?style=for-the-badge"/>

**Robotics / Software**
<br>
<img src="https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/InfluxDB-22ADF6?style=for-the-badge&logo=influxdb&logoColor=white"/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>

<br>

## 📌 Projects

| Project | Description | Stack |
|:---|:---|:---|
| 🏁 **[A-FA BAJA 실시간 계측 시스템](https://github.com/wowowowooon/A-FA-2026-BAJA)** | 오프로드 차량 탑재형 계측 시스템 (ECU CAN·IMU·GPS·4륜 서스펜션 변위) 직접 설계·제작, 데이터 기반 서스펜션 세팅으로 **피치 변동폭 48.6% 감소** · 2026 KSAE 자작자동차대회 | `ESP32` `Teensy` `RPi` `CAN` `KiCad` `MQTT` |
| ⚡ **[A-FA e-Formula 계측 시스템 (2025)](https://github.com/A-FA-2025/monolith)** | 2025 자작자동차대회 A-FA e-Formula 차량 계측 시스템 개발 | `C` |
| 🪰 **[초파리 뇌 기반 1:10 자율주행차](https://github.com/wowowowooon/Fruit-fly-brain-reinforcement-learning)** | 초파리 커넥톰 배선 제어기 + 직접 구현한 시뮬레이터로 강화학습, **Jetson Xavier NX 실차 주행 성공** · 대회 코스 21/21 완주 · ROBORACER 2026 | `Jetson NX` `ROS2` `ESP32` `VESC` `PyTorch` |
| 🚆 **[KORAIL 연결기 높이 측정기](https://github.com/wowowowooon/KORAIL-Measuring-instrument)** | 레이저 거리센서 2개 + 궤간으로 철도차량 연결기 높이를 재는 휴대형 장치. 센서 선정·기구·PCB·펌웨어·보정 도구 전 과정 개발 | `ESP32` `UART` `KiCad` `SolidWorks` |
| 📘 **[C/C++ Study](https://github.com/wowowowooon/C-study)** | 임베디드 개발자를 목표로 C/C++ 기초 → 알고리즘(프로그래머스 Lv.3) → Embedded C 순서로 학습 기록 | `C11` `C++17` |

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
