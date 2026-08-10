# 👋 Hi, I'm Kangmin Kim

### 🛡️ Information Security · System Security · Reverse Engineering

정보보호 분야를 목표로 공부하고 있는 컴퓨터공학 전공자입니다.  
시스템 보안과 리버스 엔지니어링을 중심으로 공부하며,  
직접 사용할 수 있는 **보안 도구와 소프트웨어를 개발**하고 있습니다.

> Computer Engineering student interested in  
> **Information Security, Reverse Engineering, Digital Forensics and System Security.**

---

## 🛠️ Tech Stack

### 💻 Languages

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

### ⚙️ Frameworks

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=white)

### 🔧 Tools & Environment

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

---

# 🛡️ Cybersecurity

## 🔍 Security Interests

`Reverse Engineering` · `System Security` · `Digital Forensics`  
`Malware Analysis` · `Binary Analysis` · `Network Security` · `CTF`

특히 **Low-Level / System Security** 분야에 관심을 가지고 공부하고 있습니다.

---

## 🔧 Security Tools

### 🔬 Reverse Engineering & Binary Analysis

`x64dbg` · `GDB` · `NASM` · `HxD`

### 🔍 Digital Forensics

`FTK Imager` · `Wireshark`

### 🛡️ Security Analysis

`YARA` · `Semgrep` · `Bandit` · `Trivy` · `Gitleaks`

### 🖥️ Lab & Infrastructure

`Kali Linux` · `Linux` · `Windows` · `Proxmox` · `Docker`

---

## 🧪 Security Lab

개인 홈랩을 활용하여 시스템 보안, 리버스 엔지니어링 및 악성코드 분석을 위한 실습 환경을 구축하고 있습니다.

<pre>
                    ┌──────────────────┐
                    │     Proxmox      │
                    │   Homelab Host   │
                    └────────┬─────────┘
                             │
             ┌───────────────┼───────────────┐
             │               │               │
        Malware Lab       Web Lab        Dev / Infra
             │               │               │
       ┌─────┴─────┐     Vulnerable      Code Server
       │           │      Services         Docker
     Kali       Windows
    Linux       Victim VM
       │           │
       └─────┬─────┘
             │
       Isolated Network
</pre>

### 🐉 Kali Linux

- Security testing
- Analysis environment
- Jump host

### 🪟 Windows Analysis VM

- Reverse engineering
- Binary analysis
- Malware analysis practice

### 🔒 Isolated Malware Network

- Separated virtual network
- Controlled malware analysis environment
- Internet-isolated victim environment

### 📸 Snapshot & Recovery

- Clean VM baseline
- Snapshot-based recovery
- Repeatable security experiments

### 🐧 Linux Environment

- System programming
- Security tooling
- Low-level experiments

---

# 🔬 Security Study

## ⚙️ Reverse Engineering

- C / C++ → x86-64 Assembly
- Registers & CPU Flags
- Stack & Memory
- Calling Convention
- Function Analysis
- Static Analysis
- Dynamic Analysis
- GDB / x64dbg / NASM

## 🧠 System Security

- Process & Memory
- Pointer / Buffer
- Stack & Heap
- Linux System Programming
- ELF / PE Binary Structure
- Memory Vulnerabilities

## 🔍 Digital Forensics

- Disk Image Analysis
- File System Analysis
- Windows Artifacts
- Network Packet Analysis
- Memory Forensics

## 🦠 Malware Analysis

- Static Analysis
- Dynamic Analysis
- PE Structure
- Behavioral Analysis
- YARA Rules

---

# 🚀 Projects

## 🛡️ Security Projects

### 🔎 Yara Studio

YARA rule creation and security analysis workflow management tool.

보안 분석 과정에서 YARA 규칙과 관련 작업을 보다 편리하게 관리하기 위한 프로젝트입니다.

**Tech**

`TypeScript` `YARA` `Security Analysis`

📦 [kezulno/yara_studio](https://github.com/kezulno/yara_studio)

---

### 🛡️ VibeGuard

Automated security analysis platform for source code and applications.

여러 보안 분석 도구를 하나의 파이프라인으로 통합하여  
소스 코드의 취약점과 민감정보를 자동으로 분석하는 프로젝트입니다.

**Security Tools**

`Semgrep` · `Bandit` · `Trivy` · `Gitleaks`

**Tech**

`Python` `Security Automation`

📦 [kezulno/vibeguard-worker](https://github.com/kezulno/vibeguard-worker)

---

### 🧪 Vulnerability Test

Security testing environment containing vulnerable code samples.

취약점의 발생 원리를 직접 확인하고 분석하기 위한 테스트 프로젝트입니다.

**Tech**

`Python` `Vulnerability Analysis`

📦 [kezulno/vulnerability_test](https://github.com/kezulno/vulnerability_test)

---

## 💻 Software Projects

### 📱 JustCheck

Mobile application for managing outing checklists, reminders and daily routines.

**Tech**

`React Native` `Expo` `TypeScript`

📦 [kezulno/JustCheck](https://github.com/kezulno/JustCheck)

---

### ✅ TaskDesk

Desktop productivity application for managing tasks and workflows.

**Tech**

`TypeScript`

📦 [kezulno/TaskDesk](https://github.com/kezulno/TaskDesk)

---

### 🐛 Territory-Worm

3D turn-based strategy game built with Unity.

Players move across a cube-based map while using trails, items and movement strategies to trap opponents.

**Tech**

`Unity` `C#`

📦 [kezulno/Territory-Worm](https://github.com/kezulno/Territory-Worm)

---

# 🌱 Currently Learning

## 🔬 Reverse Engineering

- x86-64 Assembly
- C / C++ → Assembly
- GDB
- x64dbg
- NASM
- Binary Structure

## 🐧 System Security

- Linux System Programming
- Process & Memory
- Stack / Heap
- Memory Vulnerabilities

## 🔍 Digital Forensics

- Disk Forensics
- Windows Artifacts
- Memory Forensics
- Network Forensics

## 🦠 Malware Analysis

- Static Analysis
- Dynamic Analysis
- Windows Internals
- YARA

## 🧠 Computer Science

- Computer Architecture
- Operating Systems
- Computer Networks
- Algorithms

---

# 🎯 Security Roadmap

- [x] C / C++ Fundamentals
- [x] Python Fundamentals
- [x] Linux Fundamentals
- [x] Assembly Fundamentals
- [x] Basic Reverse Engineering
- [x] Basic Digital Forensics
- [ ] Advanced x86-64 Reverse Engineering
- [ ] Windows Internals
- [ ] PE / ELF Analysis
- [ ] Malware Static Analysis
- [ ] Malware Dynamic Analysis
- [ ] Memory Forensics
- [ ] Binary Exploitation
- [ ] CTF Write-ups
- [ ] Security Research

---

# 🚩 Security Practice

보안 학습 내용과 실습 결과를 GitHub에 지속적으로 기록하고 있습니다.

<pre>
security-study/
│
├── reverse-engineering/
│   ├── x86-64/
│   ├── gdb/
│   ├── x64dbg/
│   └── writeups/
│
├── system-security/
│   ├── linux/
│   ├── memory/
│   └── binary/
│
├── malware-analysis/
│   ├── static-analysis/
│   ├── dynamic-analysis/
│   └── yara/
│
├── digital-forensics/
│   ├── disk/
│   ├── memory/
│   └── network/
│
└── README.md
</pre>

📦 [kezulno/security-study](https://github.com/kezulno/security-study)

---

# 📫 Contact

- 📧 **Email:** [kim051902@naver.com](mailto:kim051902@naver.com)
- 📝 **Naver Blog:** [blog.naver.com/revrow2621](https://blog.naver.com/revrow2621)

---

# 👨‍💻 About Me

- 🎓 Computer Engineering
- 🛡️ Career Goal: **Information Security**
- 🔐 Main Interests: **System Security / Reverse Engineering / Digital Forensics**
- ✈️ ROK Air Force CERT (`2024.11.18 ~ 2026.08.17`)
- 🎮 Games
- 📚 Reading
- ✈️ Travel
- 🎧 J-Pop
- ⭐ Favorite Artist: **Hoshimachi Suisei / 星街すいせい**

---

<p align="center">
  <b>Security · Development · Research</b>
</p>
