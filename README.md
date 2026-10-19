<!-- ═════════════ HEADER ═════════════ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=200&section=header&text=Aarushi%20Ahluwalia&fontSize=48&fontColor=ffffff&fontAlignY=38&desc=AI%20Engineer%20%C2%B7%20LLM%20Security%20%C2%B7%20RAG%20Systems&descSize=18&descAlignY=58&animation=fadeIn" width="100%" alt="header" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&pause=1200&color=5EEAD4&center=true&vCenter=true&width=700&lines=Building+production-grade+AI+systems;Securing+RAG+agents+against+memory+poisoning;Research+intern+%40+MNIT+Jaipur;Open+to+internships+%F0%9F%9F%A2" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aarushi-ahluwalia-8b3336330)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aarushiahluwaliajaipur@gmail.com)
![Profile Views](https://komarev.com/ghpvc/?username=Aarushi1512006&color=5eead4&style=for-the-badge&label=VIEWS)

</div>

---

## 👩‍💻 About Me

I'm a 3rd-year **B.Tech CSE (Artificial Intelligence)** student at **Poornima College of Engineering, Jaipur**. I build AI systems end to end: from research idea, to evaluated prototype, to deployed service.

```python
class Aarushi:
    role      = "AI/ML Engineer (student)"
    focus     = ["LLM Security", "RAG & Agents", "Medical AI", "Computer Vision"]
    languages = ["Python", "C++"]
    research  = "Memory-poisoning defense for RAG agents @ MNIT Jaipur"
    status    = "🟢 Open to internships"

    def mission(self):
        return "Build AI that is useful, measurable, and safe."
```

- 🔬 **Completed a 45-day research internship at MNIT Jaipur** on securing RAG-based LLM agents
- 🛡️ Reduced memory-injection attack success from **58.7% → 9.7%** with my TCA guardrail
- 🚀 Multiple ML/LLM apps **deployed live** (Streamlit Cloud, Render, Hugging Face)
- 🏆 Hackathon builder: Smart India Hackathon (internal), PayPal AI Hackathon, ISRO Bharatiya Antariksh Hackathon 2026 (participation certificate)

---

## 🧰 Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,cpp,tensorflow,pytorch,sklearn,fastapi,flask,react,vite,docker,git,github,redis,sqlite,supabase,vscode&perline=8" alt="skills" />

<br/><br/>

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat-square)
![Mistral AI](https://img.shields.io/badge/Mistral_AI-FF7000?style=flat-square)
![NVIDIA NIM](https://img.shields.io/badge/NVIDIA_NIM-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

</div>

| Area | Tools |
|---|---|
| **LLM / Agents** | LangChain, LangGraph, RAG, ChromaDB, Mistral, Llama-3.3-70B (NVIDIA NIM) |
| **Deep Learning / ML** | TensorFlow, Keras, PyTorch, Scikit-learn, CNNs, ensemble models |
| **Backend / Deploy** | FastAPI, Flask, Docker, Render, Streamlit Cloud, Hugging Face Spaces |
| **Data / Infra** | Pandas, NumPy, Redis, SQLite, Supabase, GitHub Actions |
| **Security** | Adversarial ML, prompt injection, memory-poisoning (MINJA) defense |

---

## ⭐ Featured Projects

### 🛡️ [TCA Guardrail: Temporal Consistency Auditing for RAG Agents](https://github.com/Aarushi1512006/tca-guardrail)
> *Research-to-production · built during my research internship at MNIT Jaipur*

A **store-time security guardrail** that protects RAG-based LLM agents from **answer-reversal memory-injection attacks (MINJA threat model)**. It audits new memories by comparing the model's answers with and without that context, and blocks entries that flip the answer.

| Metric | Result |
|---|---|
| Attack Success Rate | **58.7% → 9.7%** |
| Mean block rate | **48.3%** |
| False-positive rate | **2.23%** |

- Evaluated on **Llama-3.3-70B** via NVIDIA NIM
- Converted from a research notebook into a **deployable FastAPI middleware** with a monitoring dashboard

`Python` `FastAPI` `LLMs` `RAG` `Adversarial ML`

---

### 🤖 [CI/CD Auto-Debugging & Refactoring Agent](https://github.com/Aarushi1512006/ci-debug-agent)
> *An agent that fixes your failing tests and opens the PR for you*

- Watches GitHub repos for **pytest failures**, diagnoses the bug with **LLM reasoning + RAG (ChromaDB)**, applies a patch, and **opens a pull request automatically**
- Verified with a **successful end-to-end run** against a real repo
- Extending with dynamic repo cloning and a fork-based, issue-first PR flow for external repos

`FastAPI` `LangChain` `ChromaDB` `Mistral AI` `GitHub API`

---

### 🩺 [Breast Cancer Dual-Engine Diagnostic System](https://github.com/Aarushi1512006/Breast-Cancer-ML-Explorer)
> *Medical AI that combines vision and tabular models into one consensus*

- **Dual engine:** CNN histopathology analysis + **7 tabular ML classifiers**
- **Consensus diagnosis** with weighted averaging (Vision 60% · Numerical 40%)
- Trained on **BreaKHis** (7,909 microscopy images) and **Wisconsin Diagnostic** (569 samples)
- **Tesseract OCR** parses uploaded medical reports automatically
- Live dashboard with model comparison and confidence scores

[![Live Demo](https://img.shields.io/badge/Live_Demo-Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/ItsMe1501/Breast-Cancer-ML-Explorer)

`TensorFlow` `Keras` `Scikit-learn` `Streamlit` `Pytesseract`

---

### More Projects

| Project | What it does | Stack |
|---|---|---|
| 🎭 [**mood-ai**](https://github.com/Aarushi1512006/mood-ai) · [Live](https://mood-ai-eaqwc5bdqdnfh9sn7q9ptt.streamlit.app/) | Mood-switching chatbot that changes personality on demand | LangChain, Mistral, Streamlit |
| 🎞️ [**Cine-Extract**](https://github.com/Aarushi1512006/Cine-Extract) | Structured movie-data extraction from free text with LLMs | LangChain, Mistral, Streamlit |
| ⚖️ **Legal Metrology Compliance Checker** | Verifies product labels using OCR plus RAG over legal rules | Flask, PaddleOCR, RAG, Supabase, Redis, Docker |
| 💳 **DisputeShield** | AI dispute assistant for small merchants (PayPal AI Hackathon) | LangGraph, PayPal Sandbox |

---

## 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Aarushi1512006&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=5EEAD4&icon_color=5EEAD4&include_all_commits=true" alt="stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Aarushi1512006&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=5EEAD4" alt="top languages" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Aarushi1512006&theme=tokyonight&hide_border=true&background=0D1117&ring=5EEAD4&fire=5EEAD4&currStreakLabel=5EEAD4" alt="streak" />

</div>

---

## 🧭 Currently

- 🔭 Extending the **CI debug agent** to work on external repos with maintainer approval
- 🔐 Taking **TCA** further: stronger evaluation and a production-ready deployment
- 📚 Preparing for placements: DSA, core CS, system design
- 🌱 Learning **FastAPI** deeply through a real-time content-moderation capstone

---

## 🤝 Let's Connect

I'm looking for **AI/ML and LLM engineering internships**, and I'm happy to collaborate on **LLM security, RAG systems, agents, and medical AI**.

<div align="center">

[![LinkedIn](https://img.shields.io/badge/Connect_on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aarushi-ahluwalia-8b3336330)
[![Email](https://img.shields.io/badge/Email_Me-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aarushiahluwaliajaipur@gmail.com)

<br/>

*"Building AI systems that solve real-world problems."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=100&section=footer" width="100%" alt="footer" />

</div>
