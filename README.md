<!-- 상단 배너 -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Eunpyeong%20Yoon&fontSize=46&fontColor=ffffff&fontAlignY=38&desc=Real-time%20HMI%20%7C%20C%23%20%2F%20C%2B%2B%20Developer&descAlignY=58&descSize=18" width="100%"/>

<div align="center">

<!-- 타이핑 애니메이션 -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=4FC3F7&center=true&vCenter=true&width=600&lines=%EC%95%88%EB%85%95%ED%95%98%EC%84%B8%EC%9A%94%2C+%EC%9C%A4%EC%9D%80%ED%8F%89%EC%9E%85%EB%8B%88%EB%8B%A4+%F0%9F%91%8B;Real-time+Data+%C2%B7+HMI+%C2%B7+Embedded;C%23+%7C+C%2B%2B+%7C+TCP%2FUDP+%7C+FPGA" />

<br/>

<a href="mailto:yooneunpyeong@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
<a href="https://github.com/peyoon"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/></a>

</div>

---

## 🙋‍♂️ About Me

- 💻 실시간 데이터를 받아 **화면에 보여주고, 명령을 내려보내는 HMI 소프트웨어**를 만드는 주니어 개발자입니다
- 📡 패킷 한 줄, 보드 콘솔 한 줄처럼 **소프트웨어와 하드웨어가 맞닿는 지점**을 좋아합니다
- 🛰️ 장기적으로 **국방 · 항공우주 SW** 분야를 목표로 하고 있습니다
- 📜 정보처리기사 · 한남대학교 컴퓨터공학과 졸업

<br/>

## 🛠️ Tech Stack

### Language
<img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white"/> <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>

### Desktop / HMI
<img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/> <img src="https://img.shields.io/badge/WPF-0C54C2?style=for-the-badge&logo=windows&logoColor=white"/> <img src="https://img.shields.io/badge/MVVM-6E40C9?style=for-the-badge"/> <img src="https://img.shields.io/badge/P%2FInvoke%20(C%23%E2%86%94C%2B%2B)-00599C?style=for-the-badge"/>

### Network / Protocol
<img src="https://img.shields.io/badge/TCP-005571?style=for-the-badge"/> <img src="https://img.shields.io/badge/UDP-005571?style=for-the-badge"/> <img src="https://img.shields.io/badge/Socket-2C5364?style=for-the-badge"/> <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white"/> <img src="https://img.shields.io/badge/Pcap-1679A7?style=for-the-badge"/> <img src="https://img.shields.io/badge/ICD%20%2F%20Packet%20Design-203A43?style=for-the-badge"/>

### Embedded / Board
<img src="https://img.shields.io/badge/FPGA%20(Cyclone%20V%20SoC)-0071C5?style=for-the-badge&logo=intel&logoColor=white"/> <img src="https://img.shields.io/badge/Embedded%20Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/> <img src="https://img.shields.io/badge/UART%20Serial-4B5563?style=for-the-badge"/> <img src="https://img.shields.io/badge/SSH%20%2F%20Ethernet-4B5563?style=for-the-badge"/>

### AI
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/ONNX%20Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white"/>

### Tools
<img src="https://img.shields.io/badge/Visual%20Studio-5C2D91?style=for-the-badge&logo=visualstudio&logoColor=white"/> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/PuTTY-2C5364?style=for-the-badge"/> <img src="https://img.shields.io/badge/MobaXterm-2C5364?style=for-the-badge"/>

<br/>

## 🚀 Projects

| Project | Description | Stack |
|:--|:--|:--|
| 🎯 **ADIS** | 방공 요격 시뮬레이션 시스템 — SIM이 UDP(10Hz)로 표적 데이터를 송신하고, GCS가 전술 레이더 화면에 실시간 표시 · TCP로 요격 명령 전송. 12바이트 공통 헤더(SYNC · MSG_ID · SEQ · CHECKSUM) 패킷 설계, Heartbeat 기반 통신 상태 감시 | C# WPF · C++ DLL (P/Invoke) · UDP/TCP |
| 📡 **[Radar Simulator (OJT)](https://github.com/peyoon/-Project-SIMSW)** | 레이더 시뮬레이터 — DMS↔Decimal, Degree↔Mil 좌표 변환, INI 기반 설정 저장, 멀티 윈도우 간 데이터 공유 | C# WPF |
| ☢️ **Gamma Spectrum HMI** | 감마 스펙트럼 기반 핵종 판별 HMI — CNN 모델을 ONNX로 내보내 C#에서 추론, 실시간 스펙트럼 차트 · 핵종별 확률 표시 · Python↔C# 전처리 검증 | C# WPF · ONNX Runtime · PyTorch |
| 🗓️ **[Club Management System](https://github.com/peyoon/-Project-Club-management-system)** | 회사 동호회 일정 관리 시스템 — 동호회 일정 등록 · 조회 · 관리 | C# WPF |

<br/>

## 💼 Experience

**올제텍** · 인턴 (약 7개월)
- 실시간 데이터 분석 시스템(DAS) 개발 참여 — 사후 분석 화면(주기 · 응답 · 교전반응 분석) 구현
- Wireshark · CSV 대조를 통한 패킷 무결성 검증, Pcap 데이터 이상(포트 역전) 원인 추적 및 해결
- 사용자 설정 개수만큼 동적으로 생성되는 게이지 패널 UI 개발

<br/>

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=peyoon&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&hide_rank=true"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=peyoon&layout=compact&hide=jupyter%20notebook,html,css,javascript&theme=tokyonight&hide_border=true"/>

<img src="https://streak-stats.demolab.com?user=peyoon&theme=tokyonight&hide_border=true" />

</div>

<!-- 하단 배너 -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" width="100%"/>
