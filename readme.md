<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:0d1117&height=120&section=header&animation=fadeIn" width="100%"/>

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════╗
║                                                                      ║
║   ██╗  ██╗██╗  ██╗ █████╗ ██╗      █████╗ ███████╗                  ║
║   ██║ ██╔╝██║  ██║██╔══██╗██║     ██╔══██╗██╔════╝                  ║
║   █████╔╝ ███████║███████║██║     ███████║█████╗                    ║
║   ██╔═██╗ ██╔══██║██╔══██║██║     ██╔══██║██╔══╝                    ║
║   ██║  ██╗██║  ██║██║  ██║███████╗██║  ██║██║                       ║
║   ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═╝                       ║
║                                                                      ║
║          Systems & Biomedical Engineering  ·  Cairo University       ║
╚══════════════════════════════════════════════════════════════════════╝
```

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1200&color=58A6FF&center=true&vCenter=true&width=700&lines=Embedded+Systems+Engineer;Full-Stack+Web+Developer;Real-Time+%26+Bare-Metal+Programmer;Building+things+that+actually+work.)](https://git.io/typing-svg)

<br/>

<a href="mailto:abdlrhman.khalaf321@gmail.com"><img src="https://img.shields.io/badge/Gmail-abdlrhman.khalaf321-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
&nbsp;
<a href="https://www.linkedin.com/in/abdelrahman-khalaf-243a782b7/"><img src="https://img.shields.io/badge/LinkedIn-abdelrahman--khalaf-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
&nbsp;
<img src="https://img.shields.io/badge/GPA-3.6%2F4.0-brightgreen?style=for-the-badge&logo=academia&logoColor=white"/>
&nbsp;
<img src="https://img.shields.io/badge/Open_To-Embedded_%7C_Full--Stack_%7C_Research-58A6FF?style=for-the-badge"/>

</div>

---

## About

I write code that runs on **bare metal** and code that runs in **browsers** — and I take both equally seriously.

On the embedded side: register-level STM32 programming, interrupt-driven architectures, DMA pipelines, real-time thermal control. No HAL hand-holding. On the web side: full-stack TypeScript, React/Next.js frontends wired to FastAPI/Node backends, with the engineering discipline you usually only see in systems code.

Currently studying **Systems & Biomedical Engineering** at Cairo University (Expected 2027). When not in class: competitive programming, hardware, and building things that push limits.

> *"The best embedded engineers understand software. The best software engineers understand hardware. I intend to be both."*

---

## 🏆 Awards & Recognition

| | |
|:---:|:---|
| 🥇 | **1st Place — NASA Space Apps Challenge (Cairo)** · Global Nominee · Oct 2024 |
| 🥇 | **1st Place — Robotics & AI Track, Ebdaa Festival** · Scoliosis Diagnosis via PDEs, CNN & U-Net · May 2025 |
| 🥉 | **3rd Place — 12th Undergraduate Engineering Mathematics Research Forum** · Cairo University · Dec 2024 |
| 🎯 | **5th Place — ECPC (Egyptian Collegiate Programming Contest)** · Top competitive programmers nationally · Aug 2025 |

---

## 🔩 Projects

### STM32 Smart Auto-Cooler — Automotive Thermal Management
`C` `STM32F4` `ADC` `Hardware PWM` `LM35` `LCD` `Bare-Metal`

Closed-loop thermal management system directly analogous to automotive cooling control. Analog temperature acquisition via ADC, dynamic fan speed regulation via hardware PWM ensuring deterministic response without CPU polling overhead, live system-state visualization on LCD.

- Interrupt-driven pipeline — zero CPU blocking during acquisition
- Deterministic response time guaranteed by NVIC priority configuration

---

### Dual STM32F4 Elevator Control System
`C` `STM32F4` `SPI` `USART` `DMA` `Interrupts` `Bare-Metal`

Master-slave distributed control architecture using register-level programming across two microcontrollers — mirroring real-time ECU communication patterns. Interrupt-driven SPI with ring buffers for non-blocking IPC; DMA-linked USART to maintain 100% CPU availability for time-critical tasks.

- SPI ring-buffer IPC: non-blocking inter-MCU messaging at register level
- DMA-offloaded UART: CPU stays free for scheduling

---

### SignalVistaHub — Signal Intelligence Web Platform
`Next.js` `FastAPI` `Python` `TensorFlow`

Full-stack platform delivering real-time visualization and deep learning classification for ECG, EEG, Doppler, Drone, and SAR signals.

---

### ClarityCV — Computer Vision Pipeline
`Next.js` `Tailwind CSS` `C++` `OpenCV`

Responsive frontend for a C++ computer vision pipeline: face recognition, image segmentation, contour extraction, corner detection.

---

### AssetFlow — Asset Management System
`Next.js` `Tailwind CSS` `TanStack Query` `React Hook Form` `Zod`

Full-featured frontend for asset lifecycle management — inventory tracking, allocations, condition reporting, admin workflows.

---

## ⚙️ Embedded Systems

**Platform:** STM32F4 Series (Cortex-M4) · Bare-Metal / Register-Level — No HAL

| Protocol | What I've built |
|:---:|:---|
| **SPI** | Interrupt-driven master-slave with ring-buffer queuing; register-level RXNE/TXE flag management |
| **USART** | DMA-linked transfers; zero CPU-blocking serial comms in distributed control systems |
| **I2C** | Multi-device bus arbitration, clock stretching, peripheral interfacing |
| **DMA** | Memory-to-peripheral & peripheral-to-memory; interrupt on transfer complete |

**Peripherals:** ADC (multi-channel, continuous & triggered) · Hardware PWM (timer-linked) · EXTI interrupt lines · LCD · LM35 analog pipeline

**Tools:** Proteus · STM32CubeIDE · Logic analyzers · Oscilloscope-driven debugging

---

## 🌐 Full-Stack Web

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)

Component architecture · React Hook Form + Zod · TanStack Query · WebSocket · SSR/SSG/ISR

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

RESTful APIs · JWT auth (access + refresh rotation) · Async FastAPI · Pydantic · ML model serving

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00758F?style=flat-square&logo=mysql&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

---

## 💻 Languages

```
C            ████████████████████  Expert      (Embedded, Systems)
TypeScript   ████████████████████  Expert      (Full-Stack)
JavaScript   ████████████████████  Expert      (ES6+, async)
Python       ██████████████████░░  Advanced    (ML, Backend)
C++          ████████████████░░░░  Advanced    (CV pipelines)
Java         ████████████░░░░░░░░  Intermediate (DSA, OOP)
```

**Core engineering:** SOLID · Design Patterns · OOP · Real-Time Systems Theory · Data Structures & Algorithms (ICPC)

---

## 📊 GitHub Stats

<div align="center">

<br/>

<img src="https://github-readme-stats.vercel.app/api?username=Khalaf649&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&rank_icon=github" height="165"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Khalaf649&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8" height="165"/>

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Khalaf649&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff" height="165"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Khalaf649&theme=github-compact&hide_border=true&bg_color=0d1117&color=58a6ff&line=58a6ff&point=c9d1d9" width="95%"/>

</div>

---

<div align="center">

<a href="mailto:abdlrhman.khalaf321@gmail.com"><img src="https://img.shields.io/badge/Let's_Talk-abdlrhman.khalaf321@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:0d1117&height=100&section=footer&animation=fadeIn" width="100%"/>
