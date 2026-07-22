<!--
  Ahmad Faour — GitHub Profile README
  AI Researcher | Senior AI Engineer | LLM Systems Architect
  Research-driven AI systems, production engineering, and intelligent automation.

  GitHub analytics are referenced from locally generated SVG files under:
  profile-summary-card-output/github_dark/
  Add the companion workflow at .github/workflows/profile-summary-cards.yml,
  then run it once from GitHub Actions to generate the cards.
-->

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&height=210&color=0:0f172a,45:1d4ed8,75:0284c7,100:10b981&text=Ahmad%20Faour&fontColor=ffffff&fontSize=58&fontAlignY=36&desc=AI%20Researcher%20%7C%20Senior%20AI%20Engineer%20%7C%20LLM%20Systems%20Architect&descAlignY=61&descSize=18&animation=fadeIn"
    alt="Ahmad Faour — AI Researcher, Senior AI Engineer, and LLM Systems Architect"
    width="100%"
  />
</p>

<p align="center">
  I design, evaluate, and deploy AI systems that move from <b>research hypotheses</b><br />
  to <b>reliable, secure, observable, and cost-aware production software</b>.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ahmad-faour-052b20168/">
    <img src="https://img.shields.io/badge/LinkedIn-Ahmad%20Faour-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect with Ahmad Faour on LinkedIn" />
  </a>
  <a href="mailto:ahmad.saleh.faour@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Ahmad Faour" />
  </a>
  <a href="https://ahmadsalehfaour.github.io/Portfolio/">
    <img src="https://img.shields.io/badge/Portfolio-Research%20%26%20Engineering-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="View Ahmad Faour's portfolio" />
  </a>
  <a href="https://github.com/AhmadFaour9?tab=repositories">
    <img src="https://img.shields.io/badge/GitHub-Selected%20Repositories-181717?style=for-the-badge&logo=github&logoColor=white" alt="View Ahmad Faour's GitHub repositories" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=AhmadFaour9&label=Profile%20views&color=0284c7&style=flat-square" alt="GitHub profile views" />
  <img src="https://img.shields.io/badge/Location-Riyadh%2C%20Saudi%20Arabia-10B981?style=flat-square" alt="Based in Riyadh, Saudi Arabia" />
  <img src="https://img.shields.io/badge/Focus-LLMs%20%7C%20RAG%20%7C%20Agents%20%7C%20MLOps-1D4ED8?style=flat-square" alt="Focus: LLMs, RAG, agents, and MLOps" />
</p>

---

## Professional Profile

I am an **AI Researcher and Senior AI Engineer** working at the intersection of scientific experimentation and production software engineering. My focus is building AI systems that are grounded in evidence, measurable under realistic evaluation, and maintainable after deployment.

My work spans **LLM platforms, retrieval-augmented generation, agentic workflows, Arabic and multilingual AI, computer vision, OCR, speech systems, model optimization, secure backend services, and cloud delivery**.

<table>
  <tr>
    <td width="25%" valign="top"><b>Research Engineering</b><br />Paper-to-code, reproducible experiments, benchmarking, ablations, claim verification, and evaluation design.</td>
    <td width="25%" valign="top"><b>LLM Systems</b><br />RAG, GraphRAG, agents, tool use, structured outputs, reranking, guardrails, and human review.</td>
    <td width="25%" valign="top"><b>Production AI</b><br />Secure APIs, inference services, observability, CI/CD, latency and cost optimization, and cloud deployment.</td>
    <td width="25%" valign="top"><b>Arabic-First AI</b><br />Arabic NLP, dialect modeling, speech, OCR, RTL-aware interfaces, and multilingual assistants.</td>
  </tr>
</table>

### Engineering principles

- Start from the problem, data, and measurable success criteria—not from a fashionable model.
- Separate prototypes from production systems through explicit reliability, security, latency, and cost requirements.
- Evaluate retrieval quality, hallucinations, edge cases, and failure modes before optimizing headline metrics.
- Use human review when uncertainty, operational risk, or domain impact is high.
- Build observable systems with reproducible experiments, versioned artifacts, and clear rollback paths.

---

## Selected Outcomes

> Project-level outcomes reported from the systems described below.

| Outcome | System |
|---|---|
| **60–80%** of customer inquiries automated | NexusAI customer experience platform |
| **12% F1 improvement** over a Whisper-only baseline | Arabic dialect-aware voice assistant |
| **59% smaller model** and **2.3× faster CPU inference** | Arabic handwriting recognition |
| Approximately **92% character-level accuracy** on 50,000 samples | Handwritten prescription recognition |
| **35% reduction** in prescription interpretation errors | OCR and verification pipeline |

---

## Featured Research & Production Systems

### 1. AI Research Intelligence Agent

**Research intelligence platform for paper discovery, forensic analysis, claim verification, and paper-to-code generation.**

- Built a GraphRAG-based workflow for parsing and analyzing technical papers across text, tables, figures, and OCR-extracted content.
- Developed a **Scientific Code Forge** that converts paper sections into modular Python and PyTorch project structures.
- Added claim-to-evidence checks that compare extracted claims with reported metrics, tables, and experimental results.
- Designed scientific auditing workflows using adversarial review, hype scoring, and consensus reporting.
- Mapped paper concepts to relevant GitHub implementations for implementation-oriented research.

**Stack:** Python, Asyncio, Streamlit, ChromaDB, GraphRAG, Docling, PyMuPDF, OCR, OpenAI, Anthropic, Gemini, Ollama  
**Repository:** [AI-Research-Intelligence-Agent](https://github.com/AhmadFaour9/AI-Research-Intelligence-Agent)

---

### 2. NexusAI — Intelligent Customer Experience Platform

**Enterprise support automation combining intent classification, RAG, multilingual interaction, and live operations.**

- Automated **60–80% of customer inquiries** through intent classification and retrieval-grounded response generation.
- Delivered English and Arabic interaction with automatic RTL handling.
- Built workflows for agent takeover, case management, orders, staff administration, and operational monitoring.
- Implemented JWT authentication with HTTP-only cookies and role-based access control.
- Added analytics for latency, error rates, intent distribution, traffic, and operational quality.

**Stack:** Next.js, React, TypeScript, Node.js, Cloud Run, Vertex AI Gemini, Firestore, BigQuery, Docker  
**Demo:** [NexusAI](https://chatbot-frontend-aljdeea7va-uc.a.run.app/) · **Repository:** [nexus-ai](https://github.com/ahmadfaour/nexus-ai)

---

### 3. Dialect-Aware AI Voice Assistant

**Low-latency multilingual voice assistant with Arabic dialect classification.**

- Combined Whisper v3, a fine-tuned MARBERTv2 classifier, and downstream LLM reasoning in a modular inference pipeline.
- Targeted **sub-500 ms response time** for short utterances.
- Improved dialect-recognition F1 by **12%** over a Whisper-only baseline.
- Built real-time communication using Flask, React, REST APIs, and WebSockets.
- Orchestrated retries, queues, events, and human review using n8n and Elsa Workflows.

**Stack:** Whisper, MARBERTv2, Flask, React, WebSockets, n8n, Elsa Workflows  
**Repository:** [AIVoiceAsisstent](https://github.com/AhmadFaour9/AIVoiceAsisstent)

---

### 4. Arabic Handwriting Recognition

**Deployment-oriented Arabic character recognition with model compression and CPU optimization.**

- Trained a CNN on **120,000 handwritten samples** across 28 classes.
- Achieved **85% top-1 accuracy** using preprocessing, augmentation, and dropout regularization.
- Applied quantization-aware training and ONNX conversion.
- Reduced model size by **59%** and improved CPU inference speed by **2.3×**.
- Exposed the model through a Flask API for public use.

**Stack:** TensorFlow, Flask, ONNX, PythonAnywhere  
**Demo:** [LearnWithUs](https://ahmadfaour9.github.io/LearnWithUs/) · **Repository:** [LearnWithUs](https://github.com/AhmadFaour9/LearnWithUs)

<details>
<summary><b>More applied AI systems</b></summary>
<br />

### Handwritten Cardiac Prescription Recognition

- Designed a multitask pipeline combining GANs, CRNN, and CTC loss for mixed Arabic and Latin handwriting.
- Processed dosage units, physician signatures, and hospital seals.
- Added hospital-seal verification and dosage standardization.
- Reported approximately **92% character-level accuracy** on a 50,000-sample dataset and a **35% reduction** in interpretation errors.

**Stack:** GANs, CRNN, CTC Loss, TensorFlow, OCR, Multitask Learning

### Schema-Aware Query Generator

- Built a retrieval-grounded natural-language-to-SQL assistant for MS SQL Server.
- Added schema validation to reduce hallucinated tables and columns.
- Enforced safety constraints against unsafe or overly broad queries.

**Stack:** Python, Streamlit, MS SQL Server, Vanna, ChromaDB

</details>

---

## Research Agenda

- Scientific AI agents, paper analysis, and paper-to-code systems
- GraphRAG, long-context retrieval, reranking, and knowledge-grounded reasoning
- LLM evaluation, hallucination detection, claim verification, and reliability engineering
- Arabic NLP, dialect-aware intelligence, speech systems, and multilingual assistants
- OCR, document intelligence, and multimodal verification pipelines
- Efficient inference, quantization, ONNX, model serving, and cost-aware deployment

---

## Technical Capability Map

### AI, ML & Research

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=111827" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white" alt="Google Gemini" />
</p>

**Methods:** LLMs, RAG, GraphRAG, embeddings, reranking, structured outputs, prompt evaluation, guardrails, OCR, speech AI, computer vision, fine-tuning, PEFT/LoRA, RLHF-style workflows, quantization, and ONNX.

### Software, Data & Cloud

<p>
  <img src="https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt="ASP.NET Core" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Google Cloud" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

**Engineering:** ASP.NET Core, Entity Framework, REST APIs, WebSockets, React, FastAPI, Flask, Docker, IIS, CI/CD, OpenTelemetry, Prometheus, Grafana, MLflow, and Weights & Biases.

---

## Experience

| Period | Role | Organization | Focus |
|---|---|---|---|
| Dec 2024 – Present | **Senior AI Engineer** | NVSSoft | AI services, ASP.NET Core, React, CI/CD, IIS, n8n, Elsa Workflows |
| Dec 2025 – Present | **AI Training & Model Evaluation Specialist** | micro1 | LLM evaluation, rubric design, failure analysis, RLHF/RLAIF workflows |
| Dec 2024 – Dec 2025 | **AI Engineer** | Reality AI Lab | Generative-image training pipelines, augmentation, evaluation, scalability |
| Sep 2024 – Feb 2025 | **Data Scientist Intern** | Darrebni | Predictive modeling, SQL analytics, Tableau, feature engineering |
| Sep 2022 – Dec 2024 | **AI Engineer** | Freelancer.com | NLP, Arabic handwriting recognition, optimization, agentic workflows |

<details>
<summary><b>Education and certifications</b></summary>
<br />

### Education

- **M.Sc. Artificial Intelligence**, University of Hull — Sep 2025–Present  
  Focus: computer vision, deep learning, and LLM applications.
- **B.Sc. Information Technology Engineering**, University of Kalamoon — Aug 2018–Feb 2024  
  Graduated with distinction; ranked **2nd in class**.

### Certifications

| Certification | Issuer | Date |
|---|---|---|
| Develop AI-Powered Prototypes in Google AI Studio | Google | Feb 2026 |
| AI Software Engineer | micro1 | Oct 2025 |
| Generative AI with Large Language Models | Coursera / AWS | Oct 2024 |
| Introduction to Retrieval Augmented Generation | Duke University / Coursera | Dec 2024 |
| Intermediate Machine Learning | Kaggle | Feb 2025 |
| Feature Engineering | Kaggle | Nov 2024 |
| AWS EMEA Innovate: Migrate. Modernize. Build. | AWS | Oct 2024 |
| Azure DevOps: Intro to CI/CD | United Latino Students Association | Mar 2024 |

</details>

---

## GitHub Engineering Activity

<!--
  These cards are stored in this repository rather than requested from a public
  statistics API every time the profile loads. This avoids common rate-limit and
  uptime failures. Run the companion GitHub Actions workflow once to create them.
-->

<p align="center">
  <img src="./profile-summary-card-output/github_dark/0-profile-details.svg" alt="Ahmad Faour GitHub contribution summary" width="96%" />
</p>

<p align="center">
  <img src="./profile-summary-card-output/github_dark/1-repos-per-language.svg" alt="Repositories by language" width="48%" />
  <img src="./profile-summary-card-output/github_dark/2-most-commit-language.svg" alt="Most committed languages" width="48%" />
</p>

<p align="center">
  <img src="./profile-summary-card-output/github_dark/3-stats.svg" alt="GitHub summary statistics" width="48%" />
  <img src="./profile-summary-card-output/github_dark/4-productive-time.svg" alt="Productive time in UTC+3" width="48%" />
</p>

---

## Research-to-Production Workflow

```text
Problem framing
    → hypothesis and success criteria
    → data and evidence audit
    → reproducible prototype
    → evaluation and failure analysis
    → security, latency, cost, and reliability hardening
    → monitored deployment
    → evidence-driven iteration
```

---

<p align="center">
  <b>Research-backed AI. Production-grade engineering. Systems designed to be evaluated, operated, and trusted.</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ahmad-faour-052b20168/">LinkedIn</a>
  ·
  <a href="mailto:ahmad.saleh.faour@gmail.com">Email</a>
  ·
  <a href="https://ahmadsalehfaour.github.io/Portfolio/">Portfolio</a>
  ·
  <a href="https://github.com/AhmadFaour9?tab=repositories">Repositories</a>
</p>

<p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&height=115&color=0:0f172a,45:1d4ed8,75:0284c7,100:10b981&section=footer"
    alt="Footer decoration"
    width="100%"
  />
</p>
