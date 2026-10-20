<img src="./assets/banner.svg" width="100%" alt="Eunpyeong Yoon — Software Engineer"/>

<p>
  <a href="mailto:yooneunpyeong@gmail.com"><img src="https://img.shields.io/badge/Email-0a0d14?style=flat-square&logo=gmail&logoColor=white"/></a>
  <a href="https://github.com/peyoon"><img src="https://img.shields.io/badge/GitHub-0a0d14?style=flat-square&logo=github&logoColor=white"/></a>
</p>

### About

실시간 데이터를 받아 **화면에 보여주고, 명령을 다시 내려보내는 HMI 소프트웨어**를 만듭니다.
패킷 한 줄, 보드 콘솔 한 줄처럼 소프트웨어와 하드웨어가 맞닿는 지점을 좋아하고, **국방 · 항공우주 SW**를 향해 가고 있습니다.

<img src="./assets/divider.svg" width="100%"/>

### Tech Stack

<p>
  <img src="https://img.shields.io/badge/C%23-512BD4?style=flat&logo=csharp&logoColor=white"/>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/WPF-0C54C2?style=flat&logo=windows&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TCP%2FUDP-005571?style=flat"/>
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=flat&logo=wireshark&logoColor=white"/>
  <br/>
  <img src="https://img.shields.io/badge/FPGA-0071C5?style=flat&logo=intel&logoColor=white"/>
  <img src="https://img.shields.io/badge/Embedded%20Linux-FCC624?style=flat&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white"/>
  <img src="https://img.shields.io/badge/ONNX-005CED?style=flat&logo=onnx&logoColor=white"/>
  <img src="https://img.shields.io/badge/Visual%20Studio-5C2D91?style=flat&logo=visualstudio&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"/>
</p>

<img src="./assets/divider.svg" width="100%"/>

### Projects

**ADIS** · 방공 요격 시뮬레이션  
SIM이 UDP(10Hz)로 표적 데이터를 보내면 GCS가 전술 레이더 화면에 실시간으로 그리고, TCP로 요격 명령을 내려보냅니다. 12바이트 공통 헤더로 패킷을 설계하고 Heartbeat로 통신 상태를 감시합니다.  
<sub>`C# WPF` `C++ DLL` `P/Invoke` `UDP/TCP`</sub>

**Gamma Spectrum HMI** · 감마 스펙트럼 핵종 판별  
CNN 모델을 ONNX로 내보내 C#에서 추론하고, 실시간 스펙트럼 차트와 핵종별 확률을 보여줍니다. Python과 C#의 전처리 결과를 대조하는 검증 기능을 넣었습니다.  
<sub>`C# WPF` `ONNX Runtime` `PyTorch`</sub>

**Radar Simulator** · 레이더 시뮬레이터  
DMS ↔ Decimal, Degree ↔ Mil 좌표 변환, INI 기반 설정 저장, 여러 창 간 데이터 공유를 구현했습니다.  
<sub>`C# WPF`</sub>

**Club Management System** · 동호회 일정 관리  
회사 동호회 일정을 등록하고 조회 · 관리하는 데스크톱 앱입니다.  
<sub>`C# WPF`</sub>

<p>
  <a href="https://github.com/peyoon/-Project-SIMSW"><img height="120" src="https://github-readme-stats.vercel.app/api/pin/?username=peyoon&repo=-Project-SIMSW&bg_color=0a0d14&title_color=f8fafc&text_color=94a3b8&icon_color=22d3ee&hide_border=true&border_radius=12"/></a>
  <a href="https://github.com/peyoon/-Project-Club-management-system"><img height="120" src="https://github-readme-stats.vercel.app/api/pin/?username=peyoon&repo=-Project-Club-management-system&bg_color=0a0d14&title_color=f8fafc&text_color=94a3b8&icon_color=22d3ee&hide_border=true&border_radius=12"/></a>
</p>

<img src="./assets/divider.svg" width="100%"/>

### Experience

**올제텍** · 소프트웨어 엔지니어 인턴 <sub>약 7개월</sub>
- 실시간 데이터 분석 시스템(DAS)의 사후 분석 화면(주기 · 응답 · 교전반응 분석) 개발
- Wireshark와 CSV 대조로 패킷 무결성을 검증하고, Pcap 데이터의 포트 역전 문제를 추적해 해결
- 사용자가 설정한 개수만큼 생성되는 동적 게이지 패널 UI 개발

<img src="./assets/divider.svg" width="100%"/>

### Stats

<p>
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=peyoon&show_icons=true&hide_rank=true&count_private=true&bg_color=0a0d14&title_color=f8fafc&text_color=94a3b8&icon_color=22d3ee&hide_border=true&border_radius=12"/>
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=peyoon&layout=compact&hide=jupyter%20notebook,html,css,javascript&bg_color=0a0d14&title_color=f8fafc&text_color=94a3b8&icon_color=22d3ee&hide_border=true&border_radius=12"/>
</p>
<p>
  <img height="150" src="https://streak-stats.demolab.com?user=peyoon&background=0a0d14&border=0a0d14&stroke=1e293b&ring=22d3ee&fire=3b82f6&currStreakNum=f8fafc&sideNums=f8fafc&currStreakLabel=22d3ee&sideLabels=94a3b8&dates=64748b&border_radius=12"/>
</p>
