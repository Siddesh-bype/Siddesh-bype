<!-- ═══════════════════════════════════════════════════════════════════════════════════ -->
<!--   SIDDESH SHIROTE · AI/ML & SYSTEMS ENGINEER                                      -->
<!-- ═══════════════════════════════════════════════════════════════════════════════════ -->

<p align="center">
  <img src="./assets/hero.svg" alt="Siddesh Shirote — AI/ML &amp; Systems Engineer" width="100%" />
</p>

<div align="center">

<!-- MONOSPACE TYPING BANNER -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&duration=2600&pause=1000&color=00D4B2&center=true&vCenter=true&random=false&width=680&lines=Hi+%2C+I'm+Siddesh+Shirote;AI%2FML+%26+Systems+Engineer;Computer+Engineering+%40+VIT+Pune;Deep+Learning+%C2%B7+LLMs+%26+ML+Systems;Adversarial+ML+%26+Cyber+Defense;Open+to+AI%2FML+%26+Software+Internships)](https://git.io/typing-svg)

<br/>

<!-- PRIMARY STATUS BADGES -->
<a href="https://www.vit.edu/"><img src="https://img.shields.io/badge/VIT_Pune-Comp_Engg_%2728-0080FF?style=flat-square" alt="VIT Pune Computer Engineering"/></a>&nbsp;
<a href="https://www.linkedin.com/in/siddeshshirote2006/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>&nbsp;
<a href="https://leetcode.com/u/Siddesh-bype"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black" alt="LeetCode"/></a>&nbsp;
<img src="https://img.shields.io/badge/Open_to_Internships-10B981?style=flat-square" alt="Open to Internships"/>&nbsp;
<a href="https://github.com/Siddesh-bype?tab=followers"><img src="https://img.shields.io/github/followers/Siddesh-bype?label=Followers&color=00D4B2&style=flat-square" alt="GitHub Followers"/></a>&nbsp;
<a href="https://github.com/Siddesh-bype?tab=repositories"><img src="https://img.shields.io/github/stars/Siddesh-bype?label=Total%20Stars&color=00D4B2&style=flat-square" alt="Total Stars"/></a>

</div>

---

## 👋 &nbsp;About Me

<img align="right" width="300" src="./assets/coding.gif" alt="Animated GIF of a penguin typing furiously on a laptop"/>

I am a Computer Engineering undergraduate at **Vishwakarma Institute of Technology (VIT Pune)** (Batch of 2028).

My engineering work is centered on **AI/ML and Systems Engineering** — building end-to-end machine learning pipelines, deep learning models, and hardened AI infrastructure across predictive modeling, adversarial AI defense, low-level network systems, and spatial computer vision.

- 🎓 **Academics:** B.Tech in Computer Engineering @ **VIT Pune** (2024–2028)
- 🧠 **Domain Focus:** Machine Learning, Deep Learning, LLM Guardrails & Intelligent Systems
- 📍 **Location:** Pune, Maharashtra, India
- 🚀 **Current Focus:** Training and evaluating robust ML/LLM pipelines, model explainability (SHAP), and adversarial defenses

---

## 📦 &nbsp;Featured Systems

<details open>
  <summary><strong>🛡️ LLM Prompt Injection Firewall</strong> · <code>group-k11</code> · <em>ML Pipeline &amp; Defense Lead</em></summary>
  <br/>

  Enterprise-grade middleware defense proxy that protects LLM applications from adversarial prompt injections, multi-turn jailbreaks, and indirect prompt poisoning. Implements a 4-component weighted scoring formula `[SVM + MiniLM Transformer + Heuristic Rules + Encoding Anomaly]`, session escalation tracking with an in-memory ring buffer, and automatic fallback from OpenRouter to local Ollama.

  - **Role:** ML Pipeline & Model Training Lead (`group-k11` SE Project @ VIT Pune).
  - **Impact:** 85%+ detection accuracy on adversarial prompt injection benchmarks with real-time attack demonstration mode.
  - **Stack:** Python · FastAPI · Scikit-Learn · Sentence-Transformers · Next.js 14 · SQLite · OpenRouter / Ollama
  - **Repo:** [group-k11/LLM-Firewall-Prompt-Injection-Detection-System](https://github.com/group-k11/LLM-Firewall-Prompt-Injection-Detection-System)
</details>

<details>
  <summary><strong>🤖 A.I.R.S — Intelligent Intrusion Response System</strong> · <code>group-k11</code> · <em>Autonomous NIDS</em></summary>
  <br/>

  Autonomous Network Intrusion Detection platform combining classical machine learning with LLM-assisted forensic triage. Ingests packet telemetry, detects malicious flows using Random Forest and Isolation Forest trained on the **CICIDS2017** dataset, generates per-prediction feature explainability via **SHAP TreeExplainer**, maps threats to **MITRE ATT&CK** techniques, and streams natural-language incident reports with recommended SOC actions.

  - **Role:** Core Collaborator @ `group-k11` (Detection Engine & Threat Explainability).
  - **Impact:** Automated threat triage and explainable anomaly alerts reducing alert fatigue for security operations.
  - **Stack:** Python · Flask · Scikit-Learn · SHAP · Anthropic Claude API · React + Vite · Recharts · CICIDS2017
  - **Repo:** [group-k11/EDI_SY](https://github.com/group-k11/EDI_SY)
</details>

<details>
  <summary><strong>☀️ SolarSense AR Platform</strong> · <code>Personal</code> · <em>Spatial Computing &amp; On-Device AI</em></summary>
  <br/>

  100% on-device spatial computing tool built with Flutter 3 and native Kotlin OpenGL ES 2.0 (`ARRenderer`). Maps rooftop dimensions in real time with ARCore plane and depth detection, routes solar arrays around rooftop obstacles using on-device **YOLOv8n TFLite**, computes real-time solar irradiance via PVGIS, applies PM Surya Ghar subsidies, and exports an audit-ready 16-page PDF report without sending photos or metrics off-device.

  - **Role:** Solo Creator & Systems Developer.
  - **Impact:** Instant augmented reality rooftop solar feasibility assessment in under 2 minutes.
  - **Stack:** Flutter · Dart · Kotlin (ARRenderer) · YOLOv8n TFLite · Google ARCore · PVGIS · OpenGL ES
</details>

<details>
  <summary><strong>⚙️ HydroX — Smart Pump Health Digital Twin</strong> · <code>Hackathon</code> · <em>Predictive Telemetry &amp; RUL</em></summary>
  <br/>

  Industrial IoT digital twin evaluating real-time vibrational, pressure, and thermal sensor streams. Extracts an 84-dimensional feature vector combining time-domain and FFT spectral descriptors, feeding an ensemble of Isolation Forest (unsupervised anomaly detection), a 5-class Random Forest (cavitation, bearing fault, dry run, misalignment, normal), and an LSTM Remaining Useful Life (RUL) predictor.

  - **Role:** ML Pipeline & Telemetry Engineer.
  - **Impact:** Early detection of impulsive degradation and mechanical drift with sub-second WebSocket broadcast.
  - **Stack:** Python · FastAPI · Scikit-Learn · PyTorch / LSTM · WebSockets · FFT Signal Analysis
  - **Repo:** [Siddesh-bype/HydroX-TESSERACT-26](https://github.com/Siddesh-bype/HydroX-TESSERACT-26)
</details>

<details>
  <summary><strong>ProbeIQ — API Health Diagnostics</strong> · <code>Personal</code> · <em>Telemetry & Playwright Verification</em></summary>
  <br/>

  Real-time API health inspection with latency tracking, deployment docs, and Playwright-verified frontend. Full-stack layout (`backend` + `frontend` + `docs` + `DEPLOYMENT.md`) with environment-template config.

  - **Role:** Solo Creator.
  - **Impact:** Reproducible latency diagnostics with deployment-ready docs.
  - **Stack:** Python · FastAPI · Telemetry · Playwright · Frontend
</details>

<details>
  <summary><strong>LinguaSwitch — Realtime Translation Platform</strong> · <code>Personal</code> · <em>Full-Stack + Docker</em></summary>
  <br/>

  Containerized realtime translation system with dedicated backend/frontend, Docker Compose deployment, test suite, and evidence log (`RIME_EVIDENCE.md`).

  - **Role:** Solo Creator.
  - **Impact:** One-command Docker deployment with verified end-to-end flow.
  - **Stack:** Python · Docker · Full-Stack · Tests
</details>

<details>
  <summary><strong>🔒 Secure Socket Chat Engine</strong> · <code>group-k11</code> · <em>C++ POSIX Sockets &amp; React</em></summary>
  <br/>

  Full-stack secure communication platform designed for Group K11's OOP project at VIT Pune. Features a custom multithreaded C++ socket server using POSIX sockets, dedicated connection handler classes, custom packet encryption, and password hashing, connected to a modern React frontend with Supabase authentication and WebSockets.

  - **Role:** Systems & Socket Architecture Collaborator (`group-k11` @ VIT Pune).
  - **Impact:** High-throughput encrypted byte streaming with zero third-party networking library dependencies.
  - **Stack:** C++ · POSIX Sockets · TCP/IP · Multithreading · React · Supabase · WebSockets
</details>

<details>
  <summary><strong>📦 Project Archive</strong> · <em>Full-Stack, Agents &amp; Telemetry</em></summary>
  <br/>

  - **[SaaS Spend-Waste Agent](https://github.com/Siddesh-bype/SaaS-Spend-Waste-Agent)** — Autonomous automation agent auditing cloud subscriptions to eliminate recurring waste `(Python · GenAI · Tooling)`.
  - **[TideTrace](https://github.com/Siddesh-bype/TideTrace)** — Trace-analysis workbench with architecture doc, demo, models, and test suite `(Python · Full-Stack · Tests)`.
  - **[SpendSmart](https://github.com/Siddesh-bype/SpendSmart)** — Expense-tracking Flutter app with platform builds and widget tests `(Flutter · Dart)`.
  - **[teachcast](https://github.com/Siddesh-bype/teachcast)** — Teaching-agent platform with backend/frontend split and docs `(Python · Full-Stack)`.
  - **[Retail POS & Inventory Engine](https://github.com/group-k11/Mobile-app-development)** — Mobile inventory tracking with barcode scanning, expiry alerts, and offline sync `(Flutter · Dart · Firebase)`.
  - **[Call-Shield](https://github.com/Siddesh-bype/call-shield)** — Collaborative fork: real-time AI voice authenticity and social-engineering defense tooling `(Python · Kotlin · Android)`.
  - **[Bias-Aware 360° Review Desk](https://github.com/Siddesh-bype/bias-aware-360-review-system)** — Collaborative fork: evidence-cited 360° review pipeline with bias checks `(Python · FastAPI · NLP)`.
</details>

## Live Repository Pins

<div align="center">

<a href="https://github.com/Siddesh-bype/SolarSense_AR">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Siddesh-bype&repo=SolarSense_AR&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" height="150" alt="SolarSense_AR pin" />
</a>
&nbsp;
<a href="https://github.com/Siddesh-bype/ProbeIQ">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Siddesh-bype&repo=ProbeIQ&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" height="150" alt="ProbeIQ pin" />
</a>

<br/>

<a href="https://github.com/Siddesh-bype/LinguaSwitch">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Siddesh-bype&repo=LinguaSwitch&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" height="150" alt="LinguaSwitch pin" />
</a>
&nbsp;
<a href="https://github.com/Siddesh-bype/OOPs-Project-K11---Socket-based-Secure-Chat-App">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=Siddesh-bype&repo=OOPs-Project-K11---Socket-based-Secure-Chat-App&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9" height="150" alt="Socket Chat pin" />
</a>

</div>

---

## 🎯 &nbsp;Availability & Opportunity Filter

| Parameter | Current Status & Preferences |
|:---|:---|
| **Academics** | B.Tech Computer Engineering (2024–2028) @ **VIT Pune** |
| **Target Roles** | AI/ML Engineer Intern · Machine Learning Research Intern · Systems / Backend Intern · AI Security Intern |
| **Availability** | Summer 2027 Internships · Off-Cycle &amp; Part-Time Research Collaborations |
| **Location &amp; Timezone** | Pune, India (IST / UTC+5:30) · Open to Remote, Hybrid, or On-site |
| **What I'm Looking For** | Teams shipping production machine learning systems, deep learning pipelines, adversarial AI robustness, low-level network systems, or resilient backends |
| **What I'm NOT Looking For** | Unpaid marketing roles, generic form-builder tasks, or crypto speculation projects |

---

## 🛠️ &nbsp;Tech Stack

### Programming Languages
<p align="left">
  <a href="https://www.python.org" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" width="38" height="38" alt="Python" title="Python"/></a>&nbsp;&nbsp;
  <a href="https://isocpp.org" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/cplusplus/cplusplus-original.svg" width="38" height="38" alt="C++" title="C++"/></a>&nbsp;&nbsp;
  <a href="https://en.wikipedia.org/wiki/C_(programming_language)" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/c/c-original.svg" width="38" height="38" alt="C" title="C"/></a>&nbsp;&nbsp;
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" width="38" height="38" alt="JavaScript" title="JavaScript"/></a>&nbsp;&nbsp;
  <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" width="38" height="38" alt="TypeScript" title="TypeScript"/></a>&nbsp;&nbsp;
  <a href="https://dart.dev" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/dart/dart-original.svg" width="38" height="38" alt="Dart" title="Dart"/></a>&nbsp;&nbsp;
  <a href="https://www.java.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" width="38" height="38" alt="Java" title="Java"/></a>&nbsp;&nbsp;
  <a href="https://kotlinlang.org" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/kotlin/kotlin-original.svg" width="38" height="38" alt="Kotlin" title="Kotlin"/></a>
</p>

### AI, Machine Learning &amp; Deep Learning
<p align="left">
  <a href="https://pytorch.org" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pytorch/pytorch-original.svg" width="38" height="38" alt="PyTorch" title="PyTorch"/></a>&nbsp;&nbsp;
  <a href="https://scikit-learn.org" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/scikitlearn/scikitlearn-original.svg" width="38" height="38" alt="Scikit-Learn" title="Scikit-Learn"/></a>&nbsp;&nbsp;
  <a href="https://opencv.org" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/opencv/opencv-original.svg" width="38" height="38" alt="OpenCV" title="OpenCV"/></a>&nbsp;&nbsp;
  <a href="https://pandas.pydata.org" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original.svg" width="38" height="38" alt="Pandas" title="Pandas"/></a>&nbsp;&nbsp;
  <a href="https://numpy.org" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original.svg" width="38" height="38" alt="NumPy" title="NumPy"/></a>
</p>

### Frameworks &amp; Web Development
<p align="left">
  <a href="https://fastapi.tiangolo.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/fastapi/fastapi-original.svg" width="38" height="38" alt="FastAPI" title="FastAPI"/></a>&nbsp;&nbsp;
  <a href="https://flask.palletsprojects.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/flask/flask-original.svg" width="38" height="38" alt="Flask" title="Flask"/></a>&nbsp;&nbsp;
  <a href="https://react.dev" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" width="38" height="38" alt="React" title="React"/></a>&nbsp;&nbsp;
  <a href="https://nextjs.org" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nextjs/nextjs-original.svg" width="38" height="38" alt="Next.js" title="Next.js"/></a>&nbsp;&nbsp;
  <a href="https://nodejs.org" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nodejs/nodejs-original.svg" width="38" height="38" alt="Node.js" title="Node.js"/></a>&nbsp;&nbsp;
  <a href="https://tailwindcss.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/tailwindcss/tailwindcss-original.svg" width="38" height="38" alt="Tailwind CSS" title="Tailwind CSS"/></a>&nbsp;&nbsp;
  <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" width="38" height="38" alt="HTML5" title="HTML5"/></a>&nbsp;&nbsp;
  <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" width="38" height="38" alt="CSS3" title="CSS3"/></a>
</p>

### Mobile, Cloud &amp; Systems
<p align="left">
  <a href="https://flutter.dev" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/flutter/flutter-original.svg" width="38" height="38" alt="Flutter" title="Flutter"/></a>&nbsp;&nbsp;
  <a href="https://firebase.google.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/firebase/firebase-original.svg" width="38" height="38" alt="Firebase" title="Firebase"/></a>&nbsp;&nbsp;
  <a href="https://www.docker.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" width="38" height="38" alt="Docker" title="Docker"/></a>&nbsp;&nbsp;
  <a href="https://www.kernel.org" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" width="38" height="38" alt="Linux" title="Linux"/></a>&nbsp;&nbsp;
  <a href="https://git-scm.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" width="38" height="38" alt="Git" title="Git"/></a>&nbsp;&nbsp;
  <a href="https://github.com/features/actions" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/githubactions/githubactions-original.svg" width="38" height="38" alt="GitHub Actions" title="GitHub Actions"/></a>
</p>

### Databases & Storage
<p align="left">
  <a href="https://supabase.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/supabase/supabase-original.svg" width="38" height="38" alt="Supabase" title="Supabase"/></a>&nbsp;&nbsp;
  <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" width="38" height="38" alt="PostgreSQL" title="PostgreSQL"/></a>&nbsp;&nbsp;
  <a href="https://www.mysql.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" width="38" height="38" alt="MySQL" title="MySQL"/></a>&nbsp;&nbsp;
  <a href="https://www.mongodb.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original.svg" width="38" height="38" alt="MongoDB" title="MongoDB"/></a>&nbsp;&nbsp;
  <a href="https://www.sqlite.org" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sqlite/sqlite-original.svg" width="38" height="38" alt="SQLite" title="SQLite"/></a>
</p>

### Tools & Workflow
<p align="left">
  <a href="https://code.visualstudio.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg" width="38" height="38" alt="VS Code" title="VS Code"/></a>&nbsp;&nbsp;
  <a href="https://www.postman.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postman/postman-original.svg" width="38" height="38" alt="Postman" title="Postman"/></a>&nbsp;&nbsp;
  <a href="https://developer.android.com/studio" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/androidstudio/androidstudio-original.svg" width="38" height="38" alt="Android Studio" title="Android Studio"/></a>
</p>

---

## 📊 &nbsp;GitHub Analytics

<div align="center">

<img height="150" src="https://github-readme-stats.vercel.app/api?username=Siddesh-bype&show_icons=true&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9&border_color=30363D"/>&nbsp;&nbsp;
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Siddesh-bype&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&border_color=30363D"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=Siddesh-bype&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF&sideLabels=8B949E&stroke=30363D&currStreakNum=F0F6FC&sideNums=8B949E&dates=8B949E" width="460" alt="GitHub Streak"/>

</div>

---

## 🐍 &nbsp;Contribution Graph

<div align="center">
  <img alt="GitHub Contribution Snake" src="https://raw.githubusercontent.com/Siddesh-bype/Siddesh-bype/output/github-snake-dark.svg" width="100%"/>
</div>

---

## 📫 &nbsp;Connect With Me

<div align="center">

<a href="mailto:siddeshshirote30052006@gmail.com"><img src="https://img.shields.io/badge/Email-siddeshshirote30052006%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>&nbsp;
<a href="https://www.linkedin.com/in/siddeshshirote2006/"><img src="https://img.shields.io/badge/LinkedIn-siddeshshirote2006-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>&nbsp;
<a href="https://github.com/Siddesh-bype"><img src="https://img.shields.io/badge/GitHub-Siddesh--bype-21262D?style=flat-square&logo=github&logoColor=white"/></a>&nbsp;
<a href="https://leetcode.com/u/Siddesh-bype"><img src="https://img.shields.io/badge/LeetCode-Siddesh--bype-FFA116?style=flat-square&logo=leetcode&logoColor=black"/></a>

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00D4B2,50:0080FF,100:0D1117&height=110&section=footer" alt="Footer wave" />

</div>
