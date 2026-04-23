# 👋 Hi, I'm Akshay Kakar

**Senior AI/ML Systems Engineer (Generative AI, RAG, LLM Systems)**
Building production-grade AI systems across healthcare, life sciences, and decision intelligence.

💰 **Impact:** Scaled R&D portfolio $350M → $1B+ | Delivered $7M+ healthcare cost savings | Led $650M+ in AI/tech investments
⚙️ **Focus:** LLM systems, retrieval pipelines, agentic workflows, applied ML
- **Strength:** End-to-end systems from retrieval and modeling to deployment and productization
- **Domain edge:** Healthcare, drug discovery, medical imaging, clinical analytics

📍 **Edmonton, AB, Canada** | 🔗 [LinkedIn](https://linkedin.com/in/akakar) | 🎯 [Kaggle](https://www.kaggle.com/ak7180979) | 📧 akshaykakar@gmail.com

---

## Why I stand out

I combine deep AI engineering with senior business leadership experience. That means I do not just train models — I build systems that solve real operational problems, ship reliably, and connect to measurable value.

## 🎯 What I do
I design and deploy end-to-end AI systems, not just models:

- **RAG Systems**: Semantic retrieval (FAISS + embeddings) + grounded LLM generation
- **LLM Applications**: Structured workflows, evaluation pipelines, hallucination control
- **Agent Systems**: Multi-step reasoning + tool integration (APIs, scheduling, state)
- **Production Deployment**: Dockerized systems on GCP Cloud Run / Railway
- **Applied ML systems:** Medical imaging, patient stratification, drug discovery, and scientific ML pipelines

---

## 🚀 Selected Projects

### 📄ATS Resume Tailor — RAG + LLM System 
[Live App](https://resume-app-16199155134.us-central1.run.app/) · [Repository](https://github.com/PoweredwithAI/Resume-tailor-ats-groq)

Built a grounded resume-tailoring system that transforms source resumes into job-specific, ATS-style rewrites without inventing employers, degrees, or achievements.

**Highlights**
- End-to-end pipeline: PDF parsing → chunking → embeddings → FAISS retrieval → LLM rewrite
- Context-aware chunking by section, company, and role to improve retrieval precision
- Integrated Groq GPT-OSS models for deterministic resume generation
- Added ATS-style scoring, keyword gap detection, and seniority fit analysis
- Deployed as a real-time user-facing application

**Tech:** Streamlit, Groq GPT-OSS, Sentence Transformers, FAISS, pypdf, Docker, GCP Cloud Run

---

### 🤖 Telegram AI Career Agent — Agentic AI in Production
[Live Bot](https://t.me/Akka2026_bot) · [Repository](https://github.com/PoweredwithAI/Telegram_agent_AI)

Built and deployed a production AI agent that answers career and project questions grounded in live resume PDFs and can autonomously start meeting-booking workflows.

**Highlights**
- Grounded answers on live PDF resumes with strict anti-hallucination design
- Supports multi-turn interactions about projects, product decisions, and technical background
- Detects scheduling links and initiates calendar booking flows
- Tracks users, messages, and admin controls through SQLite-backed workflows
- Deployed 24/7 on Railway

**Why it matters**
Built as a direct response to a live hiring challenge and shipped in under 48 hours.

**Tech:** Python, Groq LLaMA, python-telegram-bot, Dropbox API, SQLite, Railway

---

### 🧠 Applied ML & Scientific Systems

#### 💊 Pioneer Spirit - AI Drug Discovery Platform 
[Demo](https://www.youtube.com/watch?v=qcCzyao6460) · [Live App V1.0 Target Scraper only](https://targetscraper.streamlit.app)

Architected an AI platform for drug discovery that supports molecule generation, scoring, binding estimation, retrosynthesis, and literature mining.

**Highlights:**
- Generates novel drug candidates using LSTM transfer learning (poly-pharmacophore molecules)
- Predicts biological potency with Random Forest QSAR models
- Estimates protein binding affinity via Boltz-2 diffusion models
- Identifies synthesis routes using transformer-based retrosynthesis (RSGPT)
- Mine research literature with BioBERT NER for target identification

**Data sources**
ChEMBL, PubChem, BindingDB, Protein Data Bank, UniProt, and PMC literature

**Tech:** PyTorch, RDKit, Boltz-2, BioBERT, GCP, Streamlit

**Presented to:** University of Illinois College of Medicine, with advisors from Sanofi and GSK

#### 🦴 Bone Age Assessment — Medical Imaging Pipeline
[Repository](https://github.com/PoweredwithAI/Bone-age-XRay-preprocessing-DL-comparison)

Built a medical imaging preprocessing and benchmarking workflow to test whether artifact removal and contrast standardization improve downstream bone-age prediction.

**Highlights:**
- Builds a 3-stage preprocessing pipeline: percentile normalization → CLAHE → FSCNN-based artifact removal
- Trained FastSurferCNN (U-Net) for binary hand masks prediction
- Achieved **92.79%** mean DICE score against 528 ground-truth masks
- Created three controlled benchmarking datasets (Raw / Enhanced / Cleaned) across 5 deep learning architectures (ResNet-50, EfficientNet-B3, EfficientNet-V2, ViT-B/16, ConvNeXt-V2)
- Added experiment tracking with Weights & Biases (project: `rsna-bone-age-matrix`)

**Dataset:** RSNA Pediatric Bone Age Challenge 2017 — 12,611 labelled pediatric hand X-rays

**Tech:** PyTorch, PyTorch Lightning, FastSurferCNN, OpenCV, scikit-image, Albumentations, W&B

**Status:** Phase 1 (preprocessing pipeline) ✅ complete | Phase 2 (DL benchmarking) 🔄 in progress

#### 🧬 Patient Stratification Platform (Unsupervised ML)
[Live App](https://patient-stratification.streamlit.app) · [Repository](https://github.com/PoweredwithAI/PatientStratification)

Built an unsupervised learning pipeline to identify patient subgroups from high-dimensional biological data for precision medicine use cases.

**Highlights:**
- Analyzed 9,500 patients × 2,000 gene expression markers
- Improved clustering performance by **125%** over baseline
- Achieved **0.741 silhouette score vs 0.33 baseline**
- Benchmarked multiple algorithms across raw, reduced, and latent feature spaces
- Designed for sparse, zero-inflated biological datasets
  
**Applications:** Clinical trial enrollment, treatment stratification, biomarker discovery

**Tech:** Scikit-learn, autoencoders, UMAP, IsolationForest, Streamlit

#### 🔍 TargetScraper: Research Intelligence Platform
[Demo](https://www.youtube.com/watch?v=k_CxplwJz58) · [Live App](https://targetscraper.streamlit.app) · [Repository](https://github.com/PoweredwithAI/PSP)

Built a biomedical research intelligence platform to accelerate target discovery from literature and public databases.

**Highlights**
- Automated extraction of drug targets from biomedical literature
- Performed entity recognition for genes, proteins, and diseases
- Integrated PubMed, PMC, and OpenTargets
- Added relationship visualization and target prioritization workflows

**Tech:** LLMs, REST APIs, biomedical literature pipelines, Streamlit

---

## Technical stack

- **AI/ML:** PyTorch, TensorFlow, scikit-learn, Transformers, CNNs, ViTs, diffusion models
- **LLM systems:** RAG, FAISS, embeddings, Hugging Face, Groq, structured prompting, evaluation pipelines
- **Data & pipelines:** Python, Pandas, OpenCV, UMAP, APIs, SQLite
- **MLOps & deployment:** Docker, GCP, Railway, Weights & Biases, CI/CD
- **Domain tools:** RDKit, ChEMBL, PubChem, BioBERT, DICOM preprocessing, FastSurferCNN

---

## 🎓 Education
**eMasters — Artificial Intelligence & Machine Learning** | IIT-Kanpur (Ranked #36 globally for AI/ML)  
**MBA — Finance** | XLRI (Top 3 business school in India)  
**Bachelor of Engineering — Mechanical** | University of Delhi  
**Executive Education — AI Strategy** | MIT Sloan School of Management

---

## **Open to:**
- Senior AI/ML Engineer roles
- GenAI / LLM / RAG engineering roles
- Applied AI roles in healthcare, biotech, and life sciences
- Remote, hybrid, or relocation-friendly opportunities in Canada or the US
  
---

## 📞 Contact

- 💼[LinkedIn](https://linkedin.com/in/akakar)
- 🌐[Kaggle](https://www.kaggle.com/ak7180979)
- 📧[Email](mailto:akshaykakar@gmail.com)

---

## 💡 What Sets Me Apart

- **Systems Builder:** End-to-end AI systems (retrieval → generation → evaluation → deployment)
- **Business + AI:** 20 years scaling revenue (strategy, operations, and investment) + deep technical AI capability
- **Production Mindset:** Handles real-world constraints (latency, hallucination, reliability)
- **Healthcare Native:** 15+ years in pharma R&D, digital health operations, clinical trial analytics, remote patient monitoring
- **Startup + Enterprise:** Co-founder experience + Fortune 500 leadership + biotech scale-up

---

### 🌟 Recent Activity

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

---
*Building AI systems that work in the real world — not just notebooks.*
---
**⭐ If you're hiring for AI/ML leadership in healthcare/pharma, let's talk: akshaykakargmail.com**

