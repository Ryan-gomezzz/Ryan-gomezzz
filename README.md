<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=true&repeat=true&width=700&height=80&lines=Ryan+Gomez;AI+Systems+Engineer+%7C+Founder+%40+SOYL+AI" alt="Typing SVG" />

<br>

**Building intelligent systems that ship. Not slideware.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ryan-gomez-a1a216276/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ryan-gomezzz)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ryangomez9965@gmail.com)
[![SOYL AI](https://img.shields.io/badge/SOYL_AI-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://soyl.cloud)

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:58A6FF,100:0d1117&height=120&section=header" width="100%"/>

</div>

### `$ whoami`

I'm a 20-year-old AI/ML engineer, founder of **[SOYL AI](https://soyl.cloud)**, and ECE undergraduate at Ramaiah Institute of Technology, Bengaluru. I've built **10+ production AI systems** — from sub-900ms voice agents to autonomous rescue robots — and I care about systems that work at scale, not just in notebooks.

Currently: shipping AI-native hospitality tech at SOYL AI, interning in quantum computing at **Octakaigon Bock**, and leading IEEE & MUN communities at RIT.

---

### ⚡ What I've Actually Built

<table>
<tr>
<td width="50%" valign="top">

**🏨 Butler AI — Agentic Hotel Concierge & PMS**
<br><sub>FastAPI · RAG · OpenAI · PersonaPlex-7B · Exotel · Supabase · pgvector · React/TS · Docker</sub>

Production-grade agentic backend using RAG over OpenAI APIs to resolve guest queries, reservations, and service requests in natural language — with all DB writes routed through a FastAPI bridge to keep the PMS as a single source of truth. Real-time voice layer built on NVIDIA PersonaPlex-7B, a full-duplex speech-to-speech model replacing the classic STT→LLM→TTS cascade, fine-tuned for a hospitality concierge persona and wired to Exotel for inbound/outbound SIP calls. Full stack shipped as a React/TypeScript guest PWA on FastAPI + Supabase Postgres, containerized and deployed live on Railway.

</td>
<td width="50%" valign="top">

**📡 Cognitive Radio Networks — RL for Dynamic Power Allocation**
<br><sub>Python · PyTorch · NumPy · Gymnasium · TD3</sub>

Custom reinforcement learning framework using TD3 (Twin Delayed DDPG) for dynamic transmit-power allocation — hand-engineered RL algorithm and reward shaping rather than an off-the-shelf agent. Built a bespoke Gymnasium PHY-layer simulation environment, deliberately choosing Gymnasium over OpenEnv to eliminate HTTP-induced latency in the control loop. Tuned actor-critic networks, target-policy smoothing, and delayed policy updates to stabilize convergence and maximize spectral efficiency under interference constraints.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🛒 Hush Gentle — Full-Stack E-Commerce Storefront**
<br><sub>Next.js 16 · React 18 · TypeScript · Tailwind · Supabase · Cashfree · Resend · Vercel</sub>

Production B2C skincare brand storefront covering the full purchase lifecycle, plus an admin dashboard with Supabase row-level access control. Cashfree payment gateway with webhook-based order confirmation, and Resend for automated transactional emails. Live for a real business.

</td>
<td width="50%" valign="top">

**🌊 Life Link — Autonomous Flood Rescue Robot**
<br><sub>YOLOv8 · OpenCV · ROS · GPS Navigation</sub>

Autonomous rescue robot with real-time human detection via computer vision, GPS-guided navigation fused with AI perception. **30% faster rescue response** vs. manual baselines in controlled tests. 2nd Place, IEEE Region 10 (R10) Competition — Bangalore level.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🧪 The Jellyfish — Smart Wastewater Monitoring**
<br><sub>ESP32 · C++ · Python · Flask · Isolation Forest · Random Forest · LSTM · MQTT</sub>

Dual-node ESP32 edge platform with pH/TDS/turbidity/temperature sensors detecting pharmaceutical pollutants in real time. Three-layer AI pipeline — Isolation Forest anomaly detection → Random Forest 4-class classification → LSTM time-series forecasting — driving automated UV, pump, and electrolysis remediation.

</td>
<td width="50%" valign="top">

**⚛️ Quantum Computing Research — Octakaigon Bock**
<br><sub>Python · Photonic QPU · Circuit Optimization</sub>

Optimized quantum circuit simulations across 5+ designs, achieving a **20% improvement** in execution efficiency on a scalable 100-qubit photonic QPU architecture. Contributing to a Quantum Operating System — scheduling, resource management, and hardware abstraction layers between classical control software and quantum hardware.

</td>
</tr>
</table>

---

## 🛠️ Stack

### AI/ML
[![LLMs](https://img.shields.io/badge/LLMs-42b983?logo=OpenAI&logoColor=white)]()
[![RAG](https://img.shields.io/badge/RAG-0064fa?logo=OpenAI&logoColor=white)]()
[![NLP](https://img.shields.io/badge/NLP-c93a2f?logo=OpenAI&logoColor=white)]()
[![Computer Vision](https://img.shields.io/badge/Computer_Vision-5C3EE8?logo=opencv&logoColor=white)]()
[![YOLOv8](https://img.shields.io/badge/YOLOv8-87CEEB?logo=OpenCV&logoColor=white)]()
[![LSTM](https://img.shields.io/badge/LSTM-4B0082?logo=OpenAI&logoColor=white)]()
[![Reinforcement Learning](https://img.shields.io/badge/Reinforcement_Learning-8a2be2?logo=OpenAI&logoColor=white)]()
[![TD3/DDPG](https://img.shields.io/badge/TD3%2FDDPG-6a0dad?style=flat)]()
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=PyTorch&logoColor=white)](https://pytorch.org)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=TensorFlow&logoColor=white)](https://www.tensorflow.org)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org)
[![Gymnasium](https://img.shields.io/badge/Gymnasium-00599C?style=flat)]()
[![LangChain](https://img.shields.io/badge/LangChain-21A366?logo=LangChain&logoColor=white)](https://www.langchain.com)

### Languages
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://python.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://typescriptlang.org)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://www.javascript.com)
[![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)]()
[![C](https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=white)]()
[![Java](https://img.shields.io/badge/Java-007396?logo=java&logoColor=white)]()
[![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?logo=kotlin&logoColor=white)]()

### Backend
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![REST](https://img.shields.io/badge/REST-000000?style=flat)]()
[![WebSockets](https://img.shields.io/badge/WebSockets-8048ff)]()
[![Microservices](https://img.shields.io/badge/Microservices-6DB33F?style=flat)]()
[![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)](https://flask.palletsprojects.com)

### Cloud/Infra
[![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazon-aws&logoColor=white)](https://aws.amazon.com)
[![GCP](https://img.shields.io/badge/GCP-4285F4?logo=google-cloud&logoColor=white)](https://cloud.google.com)
[![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)](https://www.docker.com)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)](https://kubernetes.io)
[![CI/CD](https://img.shields.io/badge/CI/CD-222222?logo=githubactions&logoColor=white)]()
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white)](https://supabase.com)
[![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)](https://vercel.com)
[![AWS IoT](https://img.shields.io/badge/AWS_IoT-FF9900?logo=amazon-aws&logoColor=white)]()

### Systems
[![Real-Time Processing](https://img.shields.io/badge/Real--Time_Processing-00599C?style=flat)]()
[![Distributed Systems](https://img.shields.io/badge/Distributed_Systems-9C27B0?style=flat)]()
[![Low-Latency Pipelines](https://img.shields.io/badge/Low--Latency_Pipelines-1976D2?style=flat)]()
[![Edge IoT](https://img.shields.io/badge/Edge_IoT-FF7F50?style=flat)]()
[![pgvector](https://img.shields.io/badge/pgvector-1976D2?style=flat)]()
[![MQTT](https://img.shields.io/badge/MQTT-660066?logo=MQTT&logoColor=white)](http://mqtt.org/)

### Tools
[![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)](https://git-scm.com)
[![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)](https://opencv.org)
[![Figma](https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=white)](https://figma.com)
[![Altium](https://img.shields.io/badge/Altium-BCB522?style=flat)](https://www.altium.com/)

---

### 📈 Numbers

<div align="center">

| Metric | Value |
|--------|-------|
| Production AI systems shipped | **10+** |
| Voice AI response latency | **< 900ms** |
| Quantum circuit efficiency gain | **20%** |
| Flood rescue response improvement | **30%** |
| Technical workshops coordinated (IEEE) | **40+** |
| MUN conferences organized | **3 (200+ attendees)** |

</div>

---

### 💼 Experience

**Quantum Design and Research Intern** — Octakaigon Bock *(Jun 2025 – Present)*
Optimizing quantum circuit simulations on a 100-qubit photonic QPU; contributing to Quantum OS scheduling, resource management, and hardware abstraction layers.

---

### 🏆 Achievements

- Finalist, **Chemathon** — Indian Institute of Chemical Engineers (IIChE)
- Finalist, **Meta × Scaler Hackathon (OpenEnv)** — reinforcement learning environment track
- **Best Fresher Coder**, awarded in first year of engineering
- **2nd Place, IEEE Region 10 (R10) Competition** — Bangalore level, for Life Link

---

### 🏛️ Leadership

**Vice Chair** — IEEE Student Branch, RIT *(Jan 2025 – Dec 2025)* · Coordinated 40+ workshops across 12 teams in AI, cloud, and robotics

**President** — RITMUNSOC *(Jan 2024 – Present)* · Leading a 25-member, 5-department org · 3 conferences, 200+ attendees

**IT Head** — UI/UX Club, RIT *(2025 – Present)* · Managing technical infrastructure and project pipelines

---

### 📊 GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Ryan-gomezzz&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ryan-gomezzz&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" height="165" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=Ryan-gomezzz&theme=github-dark-blue&hide_border=true&background=0D1117&stroke=58A6FF&ring=58A6FF&fire=FF6D00&currStreakLabel=58A6FF" />
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Ryan-gomezzz&theme=github-compact&bg_color=0d1117&color=58a6ff&line=58a6ff&point=c9d1d9&hide_border=true" width="95%"/>
</div>

---

### 🔭 What's Next — 2026

- Scaling SOYL AI's product portfolio across hospitality and SMB verticals
- Publishing reinforcement learning / cognitive radio research
- Contributing to major AI open-source frameworks
- Applying for MS programs in AI/ML abroad (2027 intake)

---

<div align="center">

*AI isn't about replacing intelligence. It's about engineering systems that amplify human capability.*

<br>

**If you're building something ambitious in AI, cloud, or quantum — let's talk.**

<br>

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ryan-gomez-a1a216276/)
[![Email](https://img.shields.io/badge/Send_an_Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ryangomez9965@gmail.com)

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:58A6FF&height=100&section=footer" width="100%"/>

</div>
