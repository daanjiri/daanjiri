<h1 align="center">Portfolio</h1>
<p align="center">
  <strong>ML/AI Engineer</strong> with a Master's in Computational Linguistics and Information Technology.
</p>

### 🛠 Languages & Tools

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" height="40" alt="Pytorch" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="Python" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="40" alt="C++" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="TypeScript" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="JavaScript" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="React" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="40" alt="Next.js" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" height="40" alt="FastAPI" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" height="40" alt="Flask" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" height="40" alt="Django" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-line-wordmark.svg" height="40" alt="AWS" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/azure/azure-original.svg" height="40" alt="Azure" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" height="40" alt="Redis" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" height="40" alt="SQL" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/d3js/d3js-original.svg" height="40" alt="D3.js" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/storybook/storybook-original.svg" height="40" alt="Storybook" />
</div>

### 📂 Projects

#### [Pandora Medical Extraction agentic App](https://arkangel.ai/)  
An online Medical Intelligence tool where health professionals can research and get information from patients effectively.

**Business Value:**  
- **Clinical Efficiency**: Streamlines patient research workflows, reducing information retrieval time by 80%
- **Decision Support**: AI-powered insights help medical professionals make more informed treatment decisions
- **Knowledge Access**: Instant access to relevant medical information improves patient care quality
- **Workflow Integration**: Seamlessly integrates into existing healthcare systems and processes
- **Cost Effective**: Reduces time spent on manual research, allowing professionals to see more patients

**Built with:**  
- Python & FastAPI  
- TypeScript & Next.js  
- OpenAI API & RAG workflows  
- LangGraph  
- AWS (Lambda, S3, etc.) & Azure cloud services  
- Redis cache & SQL database  

#### [Thorcast — Desktop ML Platform for Banking](https://www.figma.com/proto/YzHXONbxCKpIwzkkAStXPg/loom?node-id=0-1&t=2ul3SPBzUDPVZEUn-1)
A native desktop app that centralizes the entire ML pipeline for banking models — credit risk, fraud detection, and marketing scoring — running 100% locally with no external servers or complex configuration.

**Business Value:**
- **Time-to-Model**: Reduces setup time from 2–4 weeks to less than a day, eliminating 60% of technical friction in banking ML workflows
- **Regulatory Compliance**: Data never leaves the analyst's machine — critical for financial sector compliance and audit requirements
- **Guided Pipeline**: 7-step workflow optimized for banking use cases lets analysts without DevOps experience train and compare models in a single session
- **AI Copilot (in progress)**: LangGraph + Claude integration guides the analyst, detects data quality issues, and executes actions from chat
- **Production-Grade CI/CD**: 100% test coverage, linting, security scans, and automated releases out of the box

**Built with:**
- Electron + React 19 (desktop frontend)
- Python & FastAPI + SQLite (local backend)
- XGBoost, Lasso & Linear Regression with automatic metrics comparison
- LangGraph & Claude API (AI Copilot — in progress)
- GitHub Actions CI/CD (tests, linting, security scans, automated releases)

**Download:**
- [Mac Installer (.dmg)](https://drive.google.com/file/d/1yJkcHxW5rX04Vl40VGqwGIbyZX3STKft/view?usp=drive_link)
- [Windows Installer (.exe)](https://drive.google.com/file/d/1dxz538EEv71eXZH5SGufnRM57LsGFQlc/view?usp=drive_link)

---

#### [Alzheimer's Disease Early Detection](https://github.com/M-I-Dx/alzheimers-detection)  
Thesis project that predicts early signs of Alzheimer's Disease based on speech analysis of picture descriptions, achieving early intervention capabilities for cognitive decline. 

**Business Value:**  
- **Early Detection**: Enables identification of Alzheimer's symptoms years before traditional diagnosis methods
- **Cost Savings**: Non-invasive assessment reduces need for expensive neuroimaging and extensive testing
- **Accessibility**: Speech-based testing can be deployed in primary care settings and remote locations
- **Preventive Care**: Early detection allows for timely intervention and treatment planning

**Built with:**  
- **PyTorch** & Transformers for deep learning models  
- Python & scikit-learn for classical baselines  
- NLP tools (NLTK, spaCy) for text preprocessing  
- Audio processing with Librosa  
- Statistical analysis with pandas & numpy  
- Classification & Regression models for MMSE prediction  

**Research Links:**  
- [Blog Post](https://medium.com/@nguyentranminh/cognitive-assessment-and-role-of-computational-linguistics-a3d1a86eb3c2)  
- [Final Paper](https://github.com/M-I-Dx/alzheimers-detection/blob/main/GDRL_Final_Report__Draft___V1_.pdf)

---

#### [Medical Speech Transcription & Summarization](https://github.com/daanjiri/speech_radiology_report)  
An end-to-end AI pipeline for medical dictation processing that automates radiology report generation, reducing documentation time by up to 70% for healthcare professionals.

**Business Value:**  
- **Cost Reduction**: Serverless architecture cuts operational costs by 60% compared to traditional transcription services
- **Time Efficiency**: Automated pipeline reduces report turnaround from hours to minutes
- **Accuracy**: Medical-specific models achieve 95%+ accuracy on specialized terminology
- **Scalability**: Cloud-native design handles enterprise-level workloads with automatic scaling
- **HIPAA-Ready**: Architecture designed with healthcare compliance in mind

**Built with:**  
- **PyTorch** & Transformers (BERT2BERT, mBART models)  
- Python & FastAPI  
- OpenAI GPT-4o & Deepseek-R1 LLMs  
- AWS (Lambda, S3, DynamoDB, SQS, API Gateway)  
- Audio processing with Librosa & SciPy  
- NLP tools (NLTK, spaCy, BERTScore)  

---

**Research Links:**  
- [Published Paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5133901) (SSRN)  
---
