<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:0d1117&height=120&section=header&animation=fadeIn" width="100%"/>

```
╔══════════════════════════════════════════════════════════════════════╗
║                                                                      ║
║      ░█████╗░██████╗██████╗░███████╗██╗░░░░░██████╗░░█████╗░        ║
║      ██╔══██╗██╔══██╗██╔══██╗██╔════╝██║░░░░██╔══██╗██╔══██╗        ║
║      ███████║██████╦╝██║░░██║█████╗░░██║░░░░██████╔╝███████║        ║
║      ██╔══██║██╔══██╗██║░░██║██╔══╝░░██║░░░░██╔══██╗██╔══██║        ║
║      ██║░░██║██████╦╝██████╔╝███████╗███████╗██║░░██║██║░░██║        ║
║      ╚═╝░░╚═╝╚═════╝░╚═════╝░╚══════╝╚══════╝╚═╝░░╚═╝╚═╝░░╚═╝        ║
║                                                                      ║
║         Systems & Biomedical Engineering  ·  Cairo University        ║
╚══════════════════════════════════════════════════════════════════════╝
```

<br/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1200&color=58A6FF&center=true&vCenter=true&width=700&lines=Embedded+Systems+Engineer;Full-Stack+Web+Developer;Real-Time+Systems+%26+Bare-Metal+Programmer;Building+things+that+actually+work.)](https://git.io/typing-svg)

<br/>

<a href="mailto:abdlrhman.khalaf321@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-abdlrhman.khalaf321-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>
&nbsp;
<a href="https://linkedin.com/in/abdelrahman-khalaf">
  <img src="https://img.shields.io/badge/LinkedIn-abdelrahman--khalaf-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<img src="https://img.shields.io/badge/GPA-3.6%2F4.0-brightgreen?style=for-the-badge&logo=academia&logoColor=white"/>
&nbsp;
<img src="https://img.shields.io/badge/ICPC-Competitive_Programmer-F7931E?style=for-the-badge&logo=codeforces&logoColor=white"/>

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=Khalaf649&style=for-the-badge&color=0d1117&label=PROFILE+VIEWS" />

</div>

---

<div align="center">

## ⚡ The Short Version

</div>

I write code that runs on **bare metal** and code that runs in **browsers** — and I take both equally seriously.

On the embedded side: register-level STM32 programming, interrupt-driven architectures, DMA pipelines, real-time thermal control. No HAL hand-holding. On the web side: full-stack TypeScript, React/Next.js frontends wired to FastAPI/Node backends, with the kind of engineering discipline you usually only see in systems code.

Currently studying **Systems & Biomedical Engineering** at Cairo University (Expected 2027). When not in class: competitive programming, hardware, and building things that push limits.

---

<br/>

<div align="center">

# `[01]` — EMBEDDED SYSTEMS

<img src="https://img.shields.io/badge/STM32F4-Bare--Metal-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white"/>
&nbsp;
<img src="https://img.shields.io/badge/C-Register_Level-A8B9CC?style=for-the-badge&logo=c&logoColor=black"/>
&nbsp;
<img src="https://img.shields.io/badge/Real--Time-Interrupt_Driven-red?style=for-the-badge&logo=arm&logoColor=white"/>

</div>

<br/>

> *"I don't use HAL because I need to. I use register-level programming because I understand what the hardware is actually doing."*

<br/>

### 🔩 Microcontroller & Architecture

```
Platform          │ STM32F4 Series (Cortex-M4)
Programming Style │ Bare-Metal / Register-Level — No HAL abstraction layers
Execution Model   │ Interrupt-Driven Design, NVIC management, Priority configuration
Memory Strategy   │ DMA-offloaded transfers to keep CPU free for time-critical paths
Concurrency       │ Ring buffers, non-blocking IPC, flag-based state machines
```

<br/>

### 🔌 Communication Protocols — Deep Dive

| Protocol | Proficiency | What I've Built With It |
|:---:|:---:|:---|
| **SPI** | ★★★★★ | Interrupt-driven master-slave with ring-buffer queuing; register-level RXNE/TXE flag management |
| **USART** | ★★★★★ | DMA-linked UART transfers; zero CPU-blocking serial comms in distributed control systems |
| **I2C** | ★★★★☆ | Multi-device bus arbitration, clock stretching, peripheral interfacing |
| **DMA** | ★★★★★ | Memory-to-peripheral & peripheral-to-memory transfers; interrupt on transfer complete |

<br/>

### ⚙️ Peripherals & Signal Processing

<table>
<tr>
<td>

**Analog**
- ADC — Multi-channel, continuous & triggered modes
- Temperature acquisition via LM35 (analog pipeline)
- Signal conditioning and sampling timing

</td>
<td>

**Output & Control**
- Hardware PWM — Timer-linked, duty cycle control
- LCD interfacing — Real-time state visualization
- GPIO — EXTI interrupt lines, edge detection

</td>
<td>

**System Design**
- Closed-loop control systems (thermal management)
- Deterministic real-time response guarantees
- Master-slave distributed MCU architectures

</td>
</tr>
</table>

<br/>

### 🧠 Embedded Design Principles I Live By

```c
/* These aren't just buzzwords — they're how I write firmware */

1. DETERMINISM FIRST      // If timing matters, it must be guaranteed
2. CPU IS PRECIOUS        // DMA and interrupts exist for a reason — use them
3. NO ABSTRACTION LEAKS   // Know what every register bit does
4. REAL-TIME IS A CONTRACT // Missed deadlines are bugs, not warnings
5. HARDWARE SPEAKS C      // Close to metal means close to the truth
```

<br/>

**Tools:** `Proteus` for circuit simulation · `STM32CubeIDE` · Logic analyzers · Oscilloscope-driven debugging

---

<br/>

<div align="center">

# `[02]` — FULL-STACK WEB ENGINEERING

<img src="https://img.shields.io/badge/TypeScript-strict_mode-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
&nbsp;
<img src="https://img.shields.io/badge/Next.js-App_Router-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
&nbsp;
<img src="https://img.shields.io/badge/FastAPI-async_backend-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
&nbsp;
<img src="https://img.shields.io/badge/Node.js-Express-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>

</div>

<br/>

### 🖥️ Frontend Stack

<div align="center">

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

</div>

<br/>

```
React Expertise:
  ├── Component architecture — compound patterns, render props, custom hooks
  ├── State management — TanStack Query (server state), Zustand/Context (client state)
  ├── Forms — React Hook Form + Zod schema validation (end-to-end type safety)
  ├── Performance — memoization, lazy loading, bundle splitting
  └── Real-time UI — WebSocket integration, optimistic updates

Next.js Expertise:
  ├── App Router — layouts, loading states, error boundaries
  ├── Data fetching — SSR, SSG, ISR — chosen based on data volatility
  ├── API Routes — edge functions, middleware, request pipelines
  └── Deployment — Vercel, environment management, image optimization
```

<br/>

### 🔧 Backend Stack

<div align="center">

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-Auth-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-Real--Time-010101?style=flat-square&logo=socket.io&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-ORM-2D3748?style=flat-square&logo=prisma&logoColor=white)

</div>

<br/>

```
API Design:
  ├── RESTful architecture — resource-oriented, proper status codes, versioning
  ├── Authentication — JWT (access + refresh token rotation), middleware chains
  ├── Validation — schema-level input sanitization on every endpoint
  └── WebSocket — bidirectional real-time channels, room management

FastAPI (Python):
  ├── Async request handling — fully async endpoints with asyncio
  ├── Pydantic models — request/response schema validation
  ├── ML model serving — TensorFlow/OpenCV pipeline integration
  └── Background tasks — non-blocking heavy computation jobs
```

<br/>

### 🗄️ Databases

<div align="center">

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00758F?style=flat-square&logo=mysql&logoColor=white)
![AWS S3](https://img.shields.io/badge/AWS_S3-Object_Storage-FF9900?style=flat-square&logo=amazonaws&logoColor=white)

</div>

<br/>

| Database | Usage |
|:---|:---|
| **PostgreSQL** | Primary relational DB — complex queries, joins, indexing, Prisma ORM |
| **MongoDB** | Document storage — flexible schemas, aggregation pipelines |
| **MySQL** | Relational workloads, legacy system integration |
| **AWS S3** | Asset storage — file uploads, CDN-backed media delivery |

---

<br/>

<div align="center">

# `[03]` — LANGUAGES & CORE ENGINEERING

</div>

<br/>

<div align="center">

```
┌─────────────────────────────────────────────────────────────────┐
│  C          ████████████████████  Expert  (Embedded, Systems)   │
│  C++        ████████████████░░░░  Advanced (CV pipelines)       │
│  TypeScript ████████████████████  Expert  (Full-Stack)          │
│  Python     ██████████████████░░  Advanced (ML, Backend)        │
│  Java       ████████████░░░░░░░░  Intermediate (DSA, OOP)       │
│  JavaScript ████████████████████  Expert  (ES6+, async/await)   │
└─────────────────────────────────────────────────────────────────┘
```

</div>

<br/>

**Software Engineering Principles:**

```
✦ SOLID Principles          — Applied in every system design decision
✦ Design Patterns           — Observer, Factory, Strategy, Singleton (contextually)
✦ OOP                       — Encapsulation, polymorphism, inheritance where appropriate
✦ Data Structures & Algorithms — ICPC-level competitive programming background
✦ Real-Time Systems Theory  — Scheduling, determinism, resource contention
✦ Hardware Abstraction      — Knowing when to abstract and when not to
```

---

<br/>

<div align="center">

# `[04]` — RECOGNITION

</div>

<br/>

<table align="center">
<tr>
<td align="center">🏆</td>
<td><strong>1st Place — NASA Space Apps Challenge (Cairo)</strong><br/><sub>Global Nominee · Oct 2024</sub></td>
</tr>
<tr>
<td align="center">🥇</td>
<td><strong>1st Place — Robotics & AI Track, Ebdaa Festival</strong><br/><sub>Scoliosis Diagnosis System using PDEs, CNN & U-Net · May 2025</sub></td>
</tr>
<tr>
<td align="center">🥉</td>
<td><strong>3rd Place — 12th Undergraduate Engineering Mathematics Research Forum</strong><br/><sub>Cairo University · Dec 2024</sub></td>
</tr>
<tr>
<td align="center">🎯</td>
<td><strong>5th Place — ECPC (Egyptian Collegiate Programming Contest)</strong><br/><sub>Ranked among top competitive programmers nationally · Aug 2025</sub></td>
</tr>
</table>

---

<br/>

<div align="center">

# `[05]` — GITHUB STATS

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

<br/>

<div align="center">

```
┌────────────────────────────────────────────────────────────────────┐
│                                                                    │
│   "The best embedded engineers understand software.                │
│    The best software engineers understand hardware.                │
│    I intend to be both."                                           │
│                                                                    │
└────────────────────────────────────────────────────────────────────┘
```

<br/>

**Open to:** Embedded Systems roles · Full-Stack positions · Research collaborations

<br/>

<a href="mailto:abdlrhman.khalaf321@gmail.com">
  <img src="https://img.shields.io/badge/Let's_Talk-abdlrhman.khalaf321@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:0d1117&height=100&section=footer&animation=fadeIn" width="100%"/>

</div>
