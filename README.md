<img width="1774" height="887" alt="image" src="https://github.com/user-attachments/assets/5e699336-d7ee-4aa9-8912-fec0a6ea15b1">

# Hi, I'm Hamza Ahmed Sharif

**Full-Stack AI Engineer | RAG & Multi-Agent Systems | Open to Remote Roles**

I build AI systems end to end — classical ML, computer vision, and LLM applications — and I report what they actually measured, including when the result is a tie. Every project below is complete, public, and linked to its result.

**📍 Chengdu, China (GMT+8) · 🌍 Remote · 💬 English (native), Urdu (native), Mandarin (HSK5)**

---

### Try it live — in under 2 minutes

| Demo | What you can do |
| :--- | :--- |
| **[DocMind Agent — live demo](https://huggingface.co/spaces/HamzaAhmedSharif/DocMind-Agent)** | Upload a PDF, ask a question, get an answer with sources. Multi-agent RAG (LangGraph) with web search when a question needs it. |
| **[PaperQA — live demo](https://project-5-paperapp-rag-system.streamlit.app/)** | Upload a PDF, ask a question, get an answer with page-number citations. Built from scratch, no LangChain. |

No demo link here is a screenshot or a promise — both apps are running now.

---

### Featured Projects

| Project | What it is | Verified result |
| :--- | :--- | :--- |
| **[DocMind Agent](https://github.com/HamzaAhmedSharif/Project-6-DocMind-Agent)** | LangGraph multi-agent RAG (supervisor / researcher / writer) with FAISS retrieval and Tavily web search, plus a controlled baseline-vs-multi-agent evaluation | On 20 questions / 26 key facts, strict coverage was a tie within noise: baseline 84.6% (22/26), single-call 88.5% (23/26), multi-agent 84.6% (22/26). Multi-agent costs 2.3–3.5× the tokens and 2.9–3.9× the API time, routes correctly 20/20, and is the only system that can search the web. 49 offline tests, GitHub Actions CI green, MIT license. |
| **[PaperQA RAG System](https://github.com/HamzaAhmedSharif/Project-5-PaperQA-RAG-System)** | PDF question answering built from scratch — no LangChain — with BGE embeddings, FAISS search and page-number citations | Live on Streamlit Community Cloud (link above). |
| **[CIFAR-100 Image Classification](https://github.com/HamzaAhmedSharif/Project-4.5-CIFAR-100-Image-Classification)** | Three-architecture benchmark; winner is ViT-Base fine-tuned with LoRA (parameter-efficient transfer) | **92.49% test accuracy** with only ~1.49% of parameters trainable; LoRA adapter published on [Hugging Face](https://huggingface.co/HamzaAhmedSharif/cifar100-vit-lora-adapter) |
| **[CIFAR-10 Image Classification](https://github.com/HamzaAhmedSharif/Project-4---CIFAR-10-Image-Classification)** | 3-stage pipeline benchmarking a from-scratch CNN, Wide ResNet-28-10 and EfficientNet-V2-S, with GPU throughput benchmarks | **EfficientNet-V2-S: 95.85% test accuracy** |
| **[Customer Churn Prediction + LLM Explainability](https://github.com/HamzaAhmedSharif/Project-3---Customer-Churn-Prediction)** | XGBoost churn prediction on ~982K customers, with flan-t5-large generating plain-language explanations of individual predictions | **ROC-AUC 0.9101, accuracy 82.31%, F1 0.6780 at tuned threshold** |
| **[Retail Sales Forecasting](https://github.com/HamzaAhmedSharif/Project-2---Retails-Sales-Forecasting)** | XGBoost time-series forecasting with lag and rolling features over 100K sales records (10 stores × 10 categories × 5 years) | **R² 0.7552, MAE $547.51, RMSE $773.66** |
| **[Bank Loan Default Prediction](https://github.com/HamzaAhmedSharif/Project-1-Bank-Loan-Default-Prediction)** | Model comparison (Logistic Regression vs Random Forest vs XGBoost) with engineered risk features on 10,000 loan applicants | **Logistic Regression won: 89.35% accuracy, ROC-AUC 0.934** — the simplest model beat both ensembles |

**How to judge this work in 2 minutes:** open DocMind, read its Results and Limitations sections — the evaluation, its cost, and its known bugs are all documented there, not just the headline.

---

### About Me

- Full-Stack AI Engineer (independent, self-directed portfolio) based in Chengdu, China; originally from Pakistan.
- 7 completed portfolio projects: ML forecasting and classification, computer vision with parameter-efficient fine-tuning, RAG systems, and a LangGraph multi-agent system with a controlled baseline-vs-multi-agent evaluation.
- DocMind (Project 6) ships with a `DECISIONS.md` — a decision log where each engineering choice is recorded with its evidence, the rejected alternatives, and the trade-off accepted.
- Final-year Bachelor's student (2+2 program, Sichuan Normal University, Chengdu).
- Languages: English (native), Urdu (native), Mandarin Chinese (HSK5).
- Open to remote AI engineering roles (also listed as ML Engineer / AI Engineer / Applied AI Engineer).

---

### Tech Stack — only what these repos actually use

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-%23EB4227.svg?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-%231C3C3C.svg?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-%23004699.svg?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-%23FF4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23181717.svg?style=for-the-badge&logo=github&logoColor=white)

### Current Focus

Agentic RAG systems, LLM evaluation methodology, and production AI engineering — hardening the DocMind line of work toward deployed, monitored systems. Production deployment (APIs, containers, monitoring) is the work in progress, not something already claimed above.

---

### GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=HamzaAhmedSharif&show_icons=true&theme=radical)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=HamzaAhmedSharif&layout=compact&theme=radical)

---

### Connect

- LinkedIn: https://www.linkedin.com/in/hamza-ahmed-sharif
- Email: ha684985@gmail.com
- Hugging Face: https://huggingface.co/HamzaAhmedSharif
