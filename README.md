<!-- ═══════════════════════════════════════════════════════════════════════════════════ -->
<!--   SIDDESH SHIROTE · AI/ML & SYSTEMS ENGINEER                                      -->
<!-- ═══════════════════════════════════════════════════════════════════════════════════ -->

<p align="center">
  <img src="./assets/hero.svg" alt="Siddesh Shirote — AI/ML &amp; Systems Engineer" width="100%" />
</p>

<div align="center">

<!-- MONOSPACE TYPING BANNER -->
[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=17&duration=2600&pause=1000&color=00D4B2&center=true&vCenter=true&random=false&width=680&lines=Hi+%F0%9F%91%8B%2C+I'm+Siddesh+Shirote;%F0%9F%A4%96+AI%2FML+%26+Systems+Engineer;%F0%9F%8E%93+Computer+Engineering+%40+VIT+Pune;%F0%9F%A7%A0+Deep+Learning+%C2%B7+LLMs+%26+ML+Systems;%F0%9F%9B%A1%EF%B8%8F+Adversarial+ML+%26+Cyber+Defense;%F0%9F%8E%AF+Open+to+AI%2FML+%26+Software+Internships)](https://git.io/typing-svg)

<br/>

<!-- PRIMARY STATUS BADGES -->
<a href="https://www.vit.edu/"><img src="https://img.shields.io/badge/%F0%9F%8E%93_VIT_Pune-Comp_Engg_%2728-0080FF?style=flat-square" alt="VIT Pune Computer Engineering"/></a>&nbsp;
<a href="https://www.linkedin.com/in/siddeshshirote2006/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>&nbsp;
<a href="https://leetcode.com/u/Siddesh-bype"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black" alt="LeetCode"/></a>&nbsp;
<img src="https://img.shields.io/badge/%F0%9F%92%BC_Open_to_Internships-10B981?style=flat-square" alt="Open to Internships"/>&nbsp;
<img src="https://komarev.com/ghpvc/?username=Siddesh-bype&style=flat-square&color=00D4B2&label=PROFILE+VIEWS" alt="Profile Views"/>

</div>

---

## 👋 &nbsp;About Me

I am a Computer Engineering undergraduate at **Vishwakarma Institute of Technology (VIT Pune)** (Batch of 2028).

My engineering work is centered on **AI/ML and Systems Engineering** — building end-to-end machine learning pipelines, deep learning models, and hardened AI infrastructure. My work bridges predictive modeling and adversarial AI defense: from real-time neural intrusion detection (A.I.R.S) and inline prompt-injection firewalls to low-level multithreaded C++ socket servers and spatial computer vision.

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
  - **Repo:** [Siddesh-bype/SolarSense_AR](https://github.com/Siddesh-bype/SolarSense_AR)
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
  <summary><strong>🔒 Secure Socket Chat Engine</strong> · <code>group-k11</code> · <em>C++ POSIX Sockets &amp; React</em></summary>
  <br/>

  Full-stack secure communication platform designed for Group K11's OOP project at VIT Pune. Features a custom multithreaded C++ socket server using POSIX sockets, dedicated connection handler classes, custom packet encryption, and password hashing, connected to a modern React frontend with Supabase authentication and WebSockets.

  - **Role:** Systems & Socket Architecture Collaborator (`group-k11` @ VIT Pune).
  - **Impact:** High-throughput encrypted byte streaming with zero third-party networking library dependencies.
  - **Stack:** C++ · POSIX Sockets · TCP/IP · Multithreading · React · Supabase · WebSockets
  - **Repo:** [Siddesh-bype/OOPs-Project-K11---Socket-based-Secure-Chat-App](https://github.com/Siddesh-bype/OOPs-Project-K11---Socket-based-Secure-Chat-App)
</details>

<details>
  <summary><strong>📦 Project Archive</strong> · <em>Full-Stack, Agents &amp; Telemetry</em></summary>
  <br/>

  - **[Call-Shield](https://github.com/Siddesh-bype/call-shield)** — Real-time AI voice authenticity, deepfake, and social-engineering defense platform `(Python · Kotlin · Android)`.
  - **[Bias-Aware 360° Review Desk](https://github.com/Siddesh-bype/bias-aware-360-review-system)** — Human-in-the-loop review pipeline with automated claim citation and bias verification `(Python · FastAPI · NLP)`.
  - **[Retail POS &amp; Inventory Engine](https://github.com/group-k11/Mobile-app-development)** — Mobile inventory tracking with barcode scanning, expiry alerts, and offline sync `(Flutter · Dart · Firebase)`.
  - **[SaaS Spend-Waste Agent](https://github.com/Siddesh-bype/SaaS-Spend-Waste-Agent)** — Autonomous automation agent auditing cloud subscriptions to eliminate recurring waste `(Python · GenAI · Tooling)`.
  - **[ProbeIQ](https://github.com/Siddesh-bype/ProbeIQ)** — High-speed API health diagnostics and real-time latency inspection `(Python · FastAPI · Telemetry)`.
</details>

---

## 🎯 &nbsp;Availability &amp; Opportunity Filter

| Parameter | Current Status &amp; Preferences |
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
  <a href="https://developer.android.com/studio" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/androidstudio/androidstudio-original.svg" width="38" height="38" alt="Android Studio" title="Android Studio"/></a>&nbsp;&nbsp;
  <a href="https://www.docker.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" width="38" height="38" alt="Docker" title="Docker"/></a>&nbsp;&nbsp;
  <a href="https://www.kernel.org" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" width="38" height="38" alt="Linux" title="Linux"/></a>&nbsp;&nbsp;
  <a href="https://git-scm.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" width="38" height="38" alt="Git" title="Git"/></a>&nbsp;&nbsp;
  <a href="https://github.com/features/actions" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/githubactions/githubactions-original.svg" width="38" height="38" alt="GitHub Actions" title="GitHub Actions"/></a>
</p>

### Databases &amp; Backend Tools
<p align="left">
  <a href="https://supabase.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/supabase/supabase-original.svg" width="38" height="38" alt="Supabase" title="Supabase"/></a>&nbsp;&nbsp;
  <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postgresql/postgresql-original.svg" width="38" height="38" alt="PostgreSQL" title="PostgreSQL"/></a>&nbsp;&nbsp;
  <a href="https://www.mysql.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg" width="38" height="38" alt="MySQL" title="MySQL"/></a>&nbsp;&nbsp;
  <a href="https://www.mongodb.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mongodb/mongodb-original.svg" width="38" height="38" alt="MongoDB" title="MongoDB"/></a>&nbsp;&nbsp;
  <a href="https://www.sqlite.org" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sqlite/sqlite-original.svg" width="38" height="38" alt="SQLite" title="SQLite"/></a>&nbsp;&nbsp;
  <a href="https://code.visualstudio.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg" width="38" height="38" alt="VS Code" title="VS Code"/></a>&nbsp;&nbsp;
  <a href="https://www.postman.com" target="_blank" rel="noreferrer"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/postman/postman-original.svg" width="38" height="38" alt="Postman" title="Postman"/></a>
</p>

---

## 📊 &nbsp;GitHub Analytics

<div align="center">

<img height="155em" src="https://github-readme-stats-ashen-kappa-16.vercel.app/api?username=Siddesh-bype&show_icons=true&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=58A6FF&text_color=C9D1D9&border_color=30363D"/>&nbsp;&nbsp;
<img height="155em" src="https://github-readme-stats-ashen-kappa-16.vercel.app/api/top-langs/?username=Siddesh-bype&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9&border_color=30363D"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=Siddesh-bype&hide_border=true&background=0D1117&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF&sideLabels=8B949E&stroke=30363D&currStreakNum=F0F6FC&sideNums=8B949E&dates=8B949E" width="460"/>

</div>

---

## 🐍 &nbsp;Contribution Graph

<div align="center">
  <img alt="GitHub Contribution Snake" src="./assets/github-snake.svg" width="100%"/>
</div>

---

## 📫 &nbsp;Connect With Me

<div align="center">

<a href="mailto:siddeshshirote30052006@gmail.com"><img src="https://img.shields.io/badge/Email-siddeshshirote30052006%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>&nbsp;
<a href="https://www.linkedin.com/in/siddeshshirote2006/"><img src="https://img.shields.io/badge/LinkedIn-siddeshshirote2006-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>&nbsp;
<a href="https://github.com/Siddesh-bype"><img src="https://img.shields.io/badge/GitHub-Siddesh--bype-21262D?style=flat-square&logo=github&logoColor=white"/></a>&nbsp;
<a href="https://leetcode.com/u/Siddesh-bype"><img src="https://img.shields.io/badge/LeetCode-Siddesh--bype-FFA116?style=flat-square&logo=leetcode&logoColor=black"/></a>

</div>
