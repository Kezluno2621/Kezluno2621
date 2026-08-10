# 👋 Hi, I'm Kangmin Kim

### 🛡️ Information Security · System Security · Reverse Engineering

정보보호 분야를 목표로 공부하고 있는 컴퓨터공학 전공자입니다.  
시스템 보안과 리버스 엔지니어링을 중심으로 공부하며,  
직접 사용할 수 있는 **보안 도구와 소프트웨어를 개발**하고 있습니다.

> Computer Engineering student interested in  
> **Information Security, Reverse Engineering, Digital Forensics and System Security.**

---

## 🛠️ Tech Stack

#### 💻 Languages

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

#### ⚙️ Frameworks

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8DB?style=flat-square&logo=tauri&logoColor=white)

#### 🔧 Tools & Environment

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

#### 🔬 Reverse Engineering & Binary Analysis

`x64dbg` · `GDB` · `NASM` · `HxD`

#### 🔍 Digital Forensics

`FTK Imager` · `Wireshark`

#### 🛡️ Security Analysis

`YARA` · `Semgrep` · `Bandit` · `Trivy` · `Gitleaks`

#### 🖥️ Lab & Infrastructure

`Kali Linux` · `Linux` · `Windows` · `Proxmox` · `Docker`

---

## 🧪 Security Lab

개인 홈랩을 활용하여 보안 실습 환경을 구축하고 있습니다.

```text
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
