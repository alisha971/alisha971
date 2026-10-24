
<div align="center">

# Alisha Shaikh

**AI Research · Speech & Audio · Intelligent Systems**

*Understanding how models represent information, how they behave, and how we can build better systems around them.*

[Research](#research) · [Projects](#selected-projects) · [Tools](#tools) · [GitHub Activity](#github-activity)

</div>

---

## About

I'm interested in the space between **understanding machine learning models and building with them**.

My work and learning span mechanistic interpretability, audio and speech processing, multimodal learning, and AI engineering. I enjoy exploring research questions, turning them into experiments, and building systems that make ideas useful in practice.

This profile is a growing collection of research projects, experiments, engineering work, and notes from things I'm learning.

## Research

<details>
<summary><strong>Mechanistic Interpretability</strong> · Transformer representations</summary>

Exploring how transformer models process information and how internal mechanisms can be studied through controlled experiments.

- [Soccer MI — Player Prediction from Match Events](https://github.com/alisha971/soccer_mi)

</details>

<details>
<summary><strong>Audio & Speech</strong> · Prosody and conversational behaviour</summary>

Learning the foundations of audio processing while investigating how speech delivery and conversational context relate to one another.

- [Introduction to Audio Processing](https://github.com/alisha971/intro_to_audio_processing)
- [CODA — Conversational Delivery Adaptation](https://github.com/alisha971/coda)

</details>

<details>
<summary><strong>Multimodal AI</strong> · Model behaviour and representations</summary>

An ongoing interest in how models process and combine information across modalities, and how their behaviour can be evaluated and understood.

</details>


## Selected Projects

<details>
  <summary><strong>CODA — Conversational Delivery Adaptation</strong> <code><span style="color:#B8A4FF">research</span></code> <code><span style="color:#8BD5CA">audio</span></code> <code><span style="color:#E5B567">in progress</span></code></summary>

  A controlled measurement study investigating whether a conversation partner's prosodic delivery predicts a reply's delivery beyond the words spoken, evaluated on speakers held out from training.

  **Focus:** Prosody, conversational function, speaker-disjoint evaluation, statistical controls.

  **Status:** Under active development; results are not yet available.

  **Repository:** [alisha971/coda](https://github.com/alisha971/coda)

</details>

<details>
  <summary><strong>Soccer MI — Player Prediction from Match Events</strong> <code><span style="color:#B8A4FF">research</span></code> <code><span style="color:#8BD5CA">transformers</span></code> <code><span style="color:#E5B567">interpretability</span></code></summary>

  A sequential prediction project studying on-ball player prediction from soccer event sequences. Compares statistical baselines with transformer models across different context lengths and model depths.

  **Focus:** Mechanistic interpretability, event sequences, statistical baselines, transformer evaluation.

  **Repository:** [alisha971/soccer_mi](https://github.com/alisha971/soccer_mi)

</details>

<details>
  <summary><strong>Introduction to Audio Processing</strong> <code><span style="color:#8BD5CA">learning</span></code> <code><span style="color:#B8A4FF">speech</span></code> <code><span style="color:#E5B567">notebooks</span></code></summary>

  An open learning journal with plain-language concept notes, practical notebooks, and research-paper guides for learning audio and speech processing.

  **Topics:** Digital audio, waveforms, spectrograms, pitch, prosody, feature extraction, and paper reading.

  **Repository:** [alisha971/intro_to_audio_processing](https://github.com/alisha971/intro_to_audio_processing)

</details>

<details>
  <summary><strong>Stratos — LLM-Based Idea Research & Analysis</strong> <code><span style="color:#B8A4FF">agentic AI</span></code> <code><span style="color:#8BD5CA">RAG</span></code> <code><span style="color:#E5B567">prototype</span></code></summary>

  An AI research platform that turns an initial idea into a structured, two-sided analysis. Its intended workflow combines guided clarification, evidence gathered for and against an idea, source citations, a weighed verdict, and explicit unknowns.

  **Focus:** Agent orchestration, research workflows, evidence retrieval, and structured analysis.

  **Status:** MVP / research prototype under active development.

  **Repository:** [Stratos — public repository](https://github.com/alisha971/Stratos-LLM-Based-Idea-Research-and-Analysis-Platform)

</details>

<details>
  <summary><strong>Nimbus API — ML Model Serving</strong> <code><span style="color:#8BD5CA">MLOps</span></code> <code><span style="color:#B8A4FF">cloud</span></code> <code><span style="color:#E5B567">inference</span></code></summary>

  A cloud-hosted inference system with synchronous prediction endpoints and asynchronous batch processing, integrating model lifecycle management and cloud infrastructure.

  **Stack:** Google Cloud Run, MLflow, Cloud SQL, Memorystore (Redis), Celery, Google Cloud Storage.

  **Repository:** [Nimbus-Inference-Service](https://github.com/alisha971/Nimbus-Inference-Service)

</details>

<details>
  <summary><strong>PulseBoard — Distributed Analytics Platform</strong> <code><span style="color:#8BD5CA">backend</span></code> <code><span style="color:#B8A4FF">event-driven</span></code> <code><span style="color:#E5B567">distributed systems</span></code></summary>

  A team productivity analytics platform that decouples event ingestion from background analytics processing using queues, workers, caching, and dedicated services.

  **Stack:** React, Node.js, FastAPI, RabbitMQ, PostgreSQL, Redis, Docker, Nginx.

  **Repository:** [Pulseboard-Analytics](https://github.com/alisha971/Pulseboard-Analytics)

</details>

<details>
  <summary><strong>Industrial Asset Monitoring API</strong> <code><span style="color:#8BD5CA">Java</span></code> <code><span style="color:#B8A4FF">Spring Boot</span></code> <code><span style="color:#E5B567">REST API</span></code></summary>

  A REST API for industrial assets, sensors, measurements, and operational alerts. It uses layered services and repository abstractions, with alert state transitions and threshold-based escalation.

  **Stack:** Java 25, Spring Boot, Maven, Spring Web, Jakarta Bean Validation.

  **Note:** Current repository implementations store data in memory.

  **Repository:** [asset-monitoring-api](https://github.com/alisha971/asset-monitoring-api)

</details>

<details>
  <summary><strong>CampaignIQ — Predictive Marketing Analytics</strong> <code><span style="color:#E5B567">machine learning</span></code> <code><span style="color:#8BD5CA">full stack</span></code> <code><span style="color:#B8A4FF">visualisation</span></code></summary>

  A marketing analytics web application combining campaign-performance prediction, interactive dashboards, data visualisation, and an AI chatbot.

  **Stack:** React, Vite, Tailwind CSS, Node.js, Express, MongoDB, Python, scikit-learn, Chart.js.

  **Repository:** [CampaignIQ](https://github.com/alisha971/CampaignIQ-Predictive-Analytics-for-Marketing-Success)

</details>

<details>
  <summary><strong>Vehicle Insurance Analysis</strong> <code><span style="color:#E5B567">analytics</span></code> <code><span style="color:#8BD5CA">BI dashboard</span></code></summary>

  An interactive business intelligence dashboard analysing vehicle insurance performance from 2014–2018, including customers, premiums, claims, and risk across vehicle segments.

  **Repository:** [Insurance-Company-Analysis](https://github.com/alisha971/Insurance-Company-Analysis)

</details>

<details>
  <summary><strong>Employee Payroll Management</strong> <code><span style="color:#8BD5CA">full stack</span></code> <code><span style="color:#B8A4FF">automation</span></code></summary>

  A payroll management application covering employee records, attendance, salary calculations, tax deductions, benefits, and reporting.

  **Stack:** React, Node.js, Express.

  **Repository:** [Employee-Payroll-Management](https://github.com/alisha971/Employee-Payroll-Management)

</details>

<details>
  <summary><strong>AI Plays Flappy Bird</strong> <code><span style="color:#E5B567">AI experiment</span></code> <code><span style="color:#8BD5CA">game development</span></code></summary>

  A Flappy Bird environment created for a team project demonstrating the NEAT evolutionary algorithm. My contribution was building the game environment; the team worked on the algorithm.

  **Repository:** [AI-plays-Flappy-Bird](https://github.com/alisha971/AI-plays-Flappy-Bird)

</details>

## Tools

**Languages**

<p>
  <img src="https://skillicons.dev/icons?i=python,cpp,java,js,ts&theme=dark" alt="Python, C++, Java, JavaScript and TypeScript" />
</p>

**Machine Learning**

<p>
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn&theme=dark" alt="PyTorch, TensorFlow and scikit-learn" />
</p>

**Development & Infrastructure**

<p>
  <img src="https://skillicons.dev/icons?i=fastapi,spring,nodejs,react,mongodb,postgres,redis,docker,git,gcp&theme=dark" alt="FastAPI, Spring, Node.js, React, MongoDB, PostgreSQL, Redis, Docker, Git and Google Cloud" />
</p>

## GitHub Activity

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=alisha971&show_icons=true&hide_border=true&bg_color=0D1117&title_color=B8A4FF&text_color=C9D1D9&icon_color=8BD5CA" alt="GitHub statistics" />

<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=alisha971&layout=compact&hide_border=true&bg_color=0D1117&title_color=B8A4FF&text_color=C9D1D9" alt="Most-used repository languages" />

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=alisha971&bg_color=0D1117&color=C9D1D9&line=B8A4FF&point=8BD5CA&area=true&hide_border=true" width="100%" alt="GitHub contribution activity" />

</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/alisha971/alisha971/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/alisha971/alisha971/output/github-snake.svg" />
    <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/alisha971/alisha971/output/github-snake.svg" width="100%" />
  </picture>
</div>

---

<div align="center">

<sub>Study the mechanism. Question the result. Build the system.</sub>

</div>
