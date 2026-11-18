<div align="center">

# Avvari Naga Harthikanand (Harthik)

**AI, Machine Learning & Systems Security Engineer**

Bangalore, Karnataka, India | harthikanand90@gmail.com

<br/>

<a href="https://www.linkedin.com/in/harthik">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
&nbsp;
<a href="mailto:harthikanand90@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
&nbsp;
<a href="https://github.com/harctik">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>
&nbsp;
<img src="https://img.shields.io/badge/Location-Bangalore%2C%20India-555?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />

<br/><br/>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

</div>

---

## Executive Profile

I am an AI and Machine Learning Engineer specializing in continuous behavioral authentication, adversarial threat intelligence, and neural systems engineering. My background bridges academic training in Artificial Intelligence & Machine Learning (BCA, CGPA 8.52 from Christ Academy Institute for Advanced Studies) with hands-on systems development across fraud prevention, distributed ledgers, and applied model training.

Currently working as an AI Data Generalist & LLM Trainer at Outlier, evaluating model reasoning, instruction adherence, and hallucination bounds. Previously built and shipped machine learning pipelines at Infosys Springboard 6.0 and computer vision models at Zebo.AI.

---

## Technical Competencies

<div align="center">

| Domain | Verified Tools and Frameworks |
|---|---|
| **Core Languages** | Python, TypeScript, JavaScript, SQL, Solidity |
| **Machine Learning & Deep Learning** | PyTorch, PyTorch Geometric (GNNs), scikit-learn, LightGBM, Isolation Forest, Transformers, VAEs, GRUs |
| **Large Language Models & Evaluation** | LangChain, LangGraph, Gemini API, Claude API, Arize Phoenix (LLM Evals), Qdrant Vector Search |
| **Backend & Infrastructure** | FastAPI, Flask, Docker, Kubernetes (Helm), GitHub Actions CI/CD, Celery, Redis, PostgreSQL |
| **Security & Cryptography** | Shannon Entropy Analysis, Punycode/Homoglyph Detection, Fernet Encryption, SHA-256 Audit Chains, JWT, CSRF |
| **Regulatory & Compliance** | RBI Master Directions 2021, PCI DSS 4.0, DPDP Act 2023, GDPR |
| **Blockchain Engineering** | Hyperledger Besu (QBFT), Solidity 0.8+, Foundry, zkML (EZKL / Halo2) |

</div>

---

## Featured Engineering Repositories

<div align="center">
<table>
<tr>
<td width="50%" valign="top">

### [AetherAuth: Continuous Behavioral Authentication](https://github.com/harctik/behavioral-biometrics)
**Zero-Trust Session Verification via Micro-Telemetry**
- 9-engine machine learning ensemble (Isolation Forest, GRU, Transformer, VAE, LightGBM) extracting over 200 micro-features across keystroke rhythms, cursor curvature, and interaction dynamics.
- Operates under a 50ms inference latency budget to eliminate friction (no CAPTCHAs, no recurrent SMS OTPs).
- Compliant with RBI Master Directions 2021, PCI DSS 4.0, and DPDP Act 2023; secured with SHA-256 hash-linked audit chains and Fernet key rotation.
- **Tech Stack:** Python, Flask 3, Next.js 16, PostgreSQL, Redis, Docker, Helm

[Live Application](https://frontend-dun-five-49.vercel.app) | [Source Code](https://github.com/harctik/behavioral-biometrics)

</td>
<td width="50%" valign="top">

### [PhishGuard: Real-Time Adversarial Phishing Intelligence](https://github.com/harctik/PhishGuard)
**Manifest V3 Browser Shield & FastAPI Inspection Engine**
- Intercepts zero-day credential harvesting and Punycode/homoglyph character substitution attacks directly inside client browsers.
- Multi-factor evaluation engine combining Shannon character entropy, lexical path analysis, brand target camouflage detection, and SSL verification.
- Pairs an asynchronous Manifest V3 Chrome Extension with a sub-10ms FastAPI inspection microservice.
- **Tech Stack:** Python, FastAPI, Chrome Extension (MV3), Shannon Entropy, REST APIs

[Source Code](https://github.com/harctik/PhishGuard)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [PRAMAANIK: Public Fund Flow Tracking](https://github.com/harctik/pramaanik)
**Cryptographic Provenance & GNN Anomaly Detection**
- 4-validator Hyperledger Besu QBFT network with 8 Foundry smart contracts tracking public welfare fund flows from sanction to final disbursement.
- 3-Layer Relational Graph Convolutional Network (RGCN) implemented in PyTorch Geometric for on-chain anomaly detection with zkML (EZKL/Halo2) zero-knowledge proofs.
- Verified with over 10,000 fuzz test runs in Foundry; features 3-tier role dashboards (Admin, Auditor, Citizen) with Hindi localization.
- **Tech Stack:** Solidity, Hyperledger Besu, PyTorch Geometric, Next.js 14, Foundry

[Live Application](https://pramaanik.vercel.app) | [Source Code](https://github.com/harctik/pramaanik)

</td>
<td width="50%" valign="top">

### [QuantRisk: Crypto Portfolio Optimization](https://github.com/harctik/Crypto-Investment-Manager)
**Quantitative Risk Analytics & Algorithmic Backtesting**
- Developed during Infosys Springboard 6.0; mathematical asset allocation modeling risk and return distributions from scratch.
- Monte Carlo engine evaluating 1,000+ stochastic asset paths; historical and parametric Value at Risk (VaR 95/99), Conditional VaR (Expected Shortfall), and Sharpe ratio maximization.
- Backtesting framework for technical crossover strategies with automated Resend API volatility notifications.
- **Tech Stack:** Python, Flask, SQLite, CoinGecko API, SciPy, Resend API

[Live Application](https://cryptomanagerapp.vercel.app) | [Source Code](https://github.com/harctik/Crypto-Investment-Manager)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [kira.ai: Autonomous Neural Model & Agent Engine](https://github.com/harctik/kira.ai)
**Decoder-Only Transformer Architecture Scalable to 3.2B**
- Custom-built PyTorch Transformer featuring modern Rotary Position Embeddings (RoPE), RMSNorm, SwiGLU activations, and Grouped-Query Attention (GQA).
- Pretrained strictly on human-authored corpora with zero synthetic AI contamination; includes custom 8,192-token BPE tokenizer trained from scratch.
- Continuous episodic memory loop with dynamic INT8 CPU quantization and sandboxed OS execution tools.
- **Tech Stack:** Python, PyTorch 2.0, FastAPI, Dynamic INT8 Quantization, BPE

[Source Code](https://github.com/harctik/kira.ai)

</td>
<td width="50%" valign="top">

### [Studvisor: Enterprise Academic ERP & Predictive Risk](https://github.com/harctik/Studvisor)
**AI-Powered Student Lifecycle & Early Warning System**
- High-security educational ERP platform built on FastAPI with three-tier RBAC guards and tamper-evident audit logging middleware.
- Integrated Anthropic Claude-3 and Ollama pipelines for predictive student dropout scoring, GPA projections, and context-aware academic tutoring.
- Modern React / Vite / Tailwind UI with gamified progression systems and conflict-aware scheduling solvers.
- **Tech Stack:** FastAPI, Python, React, PostgreSQL, Claude API, Docker

[Source Code](https://github.com/harctik/Studvisor)

</td>
</tr>
</table>
</div>

---

## Professional Certifications

<div align="center">

| Credential | Issuing Body | Primary Technical Focus |
|---|---|---|
| **LLM Evaluation Basics** | Arize AI | RAG evals, hallucination metrics, tracing |
| **Building with the Claude API** | Anthropic | Tool use, function calling, context caching |
| **Generative AI** | IBM | Prompt engineering, foundation model fine-tuning |
| **Python for Data Science** | IBM | Vectorized numerical computing, model validation |
| **Advanced Statistics & Data Mining** | Infosys Springboard | Probability distributions, regression, hypothesis testing |
| **Database Management Systems** | Infosys Springboard | Normalization, relational schema design, SQL tuning |
| **Artificial Intelligence Essentials** | EXIN BCS | Ethical AI, algorithmic heuristics, machine learning |

</div>

---

## GitHub Analytics

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=harctik&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=70A5FD&icon_color=70A5FD&text_color=FFFFFF" alt="GitHub Stats" height="175"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=harctik&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=70A5FD&text_color=FFFFFF" alt="Top Languages" height="175"/>

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=harctik&theme=tokyonight&hide_border=true&background=0D1117&stroke=70A5FD&ring=70A5FD&fire=FF6B6B&currStreakLabel=70A5FD" alt="GitHub Streak" />

</div>

---

## Engineering Attribution & Ownership

All repositories, architectures, machine learning models, smart contracts, backend microservices, and codebases displayed across this profile were designed, developed, and tested end-to-end by **Avvari Naga Harthikanand (Harthik)**.

- **Developer:** Avvari Naga Harthikanand
- **LinkedIn:** https://www.linkedin.com/in/harthik
- **GitHub:** https://github.com/harctik
- **Contact:** harthikanand90@gmail.com
- **Location:** Bangalore, Karnataka, India
