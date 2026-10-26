<h1 align="center">Shre Hari Prem Anandh</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=900&center=true&vCenter=true&width=620&lines=AI+Engineer+shipping+agents+to+production;MSc+Artificial+Intelligence+%40+Sheffield;First-author+IEEE+paper%2C+CCPIS+2025;I+build+ML+systems+that+actually+ship" alt="headline" />
</p>

<p align="center">
  <a href="https://shrehari.github.io"><img src="https://img.shields.io/badge/Portfolio-shrehari.github.io-BF3B0B?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/shrehari"><img src="https://img.shields.io/badge/LinkedIn-shrehari-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:shrehari66@gmail.com"><img src="https://img.shields.io/badge/Email-shrehari66%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

Most machine learning projects die in a notebook, so the part I care about is everything after it: the queues, retries, tests and evals that let a model hold up in front of real users.

I'm an **AI Engineer Intern at NexCell Solutions**, shipping a production WhatsApp AI agent that books property viewings through MCP tools, and I've just finished an **MSc in Artificial Intelligence at the University of Sheffield**. **Available now for full-time roles in the UK**, Graduate Route eligible, no sponsorship needed.

## 🔨 Things I have built

| Project | What it does |
|---|---|
| **[AgentForge](https://github.com/ShreHari/agentforge)** · live on GKE | Job-hunt agent: researches the company, rates a CV against every requirement in a job ad, then drafts tailored CV bullets and likely interview questions. A LangGraph workflow behind a Pub/Sub queue on GKE Autopilot, with a Postgres checkpoint after every step, crash recovery and graceful shutdown. 15/15 on its evals and 128 automated tests, built solo in two weeks. **[Try it live](https://34-102-210-23.sslip.io)** (sign in with any Google account) |
| **[Visualising Emotion](https://github.com/ShreHari/visualising-emotion-msc)** · MSc dissertation | Can a text-to-image model draw a feeling? Scored 1,012 public drawings with BLIP-VQA, BART-MNLI and GoEmotions against a permutation null: valence agreement 64.0% vs 45.6% by chance, and describing an image first beat asking CLIP directly by 30.6 points |
| **[Aria, AI voice receptionist](https://github.com/ShreHari/hotel-voice-receptionist)** | Hands-free hotel agent with a hand-written agent loop, five MCP tools, neural TTS, and Docker. **[Talk to her live](https://aria-hotel-receptionist.onrender.com)** (Chrome, first load may take a minute) |
| **Real-time disease monitoring** · IEEE, first author | Random Forest and Logistic Regression risk models plus ARIMA trend forecasts; combining them with rule-based checks cut false alerts by about 25%, and anyone inside a 400 m red zone gets an SMS warning. Published at IEEE CCPIS 2025 |
| **Extractive document QA** | RoBERTa pipeline over 300-word overlapping chunks with a custom composite scorer; lifted F1 from 0.50 to 0.69 through error analysis alone |
| **Speech rate classifier** | Handcrafted log-mel feature pipelines plus an RBF SVM; 98.2% accuracy on speaking speed against a 24.6% kNN baseline |
| **Medical image clustering (BloodMNIST)** | Convolutional autoencoder vs PCA for 12k-dim blood cell images; ARI 0.40 vs 0.26 across 8 cell types |
| **Edge fish disease detection** | CNN quantised onto a Raspberry Pi with sub-second latency; Smart India Hackathon finalist |

## 🧰 Tools I reach for

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph">
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face">
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/OpenAI%20API-412991?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes">
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Google Cloud">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
</p>

Plus the practical rest: MCP servers and tool calling, evals and LLM judges, RAG, Celery and Redis, AWS SES and SNS, Cloud SQL and Pub/Sub, REST APIs with JWT and Pydantic, Grafana observability, and Agile delivery.

## 💼 Where I have worked

- **NexCell Solutions** (Jul 2026 – present) — AI Engineer Intern: a production WhatsApp AI agent that can only act through MCP tools, event-driven lead intake on AWS SES and SNS, idempotent reminders on Celery and Redis, and GDPR erasure and opt-out rules on every chat. 600+ commits, all through CI and code review
- **Hamiltonian Systems** (Jun – Jul 2024) — Software Engineer Intern: Python backend services handling 100k+ records a week across three live client applications, 6+ production REST APIs, and 15+ recurring production failures resolved through log analysis

## 🏅 Recognition

First-author IEEE paper (CCPIS 2025) · World Space Week 2023, 1st place (ISRO SDSC SHAR) · Smart India Hackathon national finalist (2023)

## 📫 Say hello

Available now for full-time AI, ML and backend roles in the UK. The full write-up is at **[shrehari.github.io](https://shrehari.github.io)**; the fastest ways to reach me are [LinkedIn](https://www.linkedin.com/in/shrehari) or shrehari66@gmail.com.
