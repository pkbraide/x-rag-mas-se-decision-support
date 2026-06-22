# X-RAG-MAS: Explainable Retrieval-Augmented Multi-Agent System for Software Engineering Decision Support

## 📌 Overview
X-RAG-MAS is a research prototype that integrates Retrieval-Augmented Generation (RAG), Multi-Agent Large Language Models, and Explainable AI (XAI) to support software engineering decision-making. The system is designed to assist developers in debugging, code understanding, and architectural reasoning by grounding responses in verified software engineering knowledge sources.

---

## 🎯 Research Problem
Software engineering practitioners often rely on fragmented information sources (e.g., Stack Overflow, documentation, and bug reports), making decision-making inefficient and error-prone. Existing AI systems lack:
- Structured multi-agent reasoning
- Retrieval-grounded decision support
- Integrated explainability mechanisms

X-RAG-MAS addresses this gap.

---

## 🧠 Proposed Architecture
The system consists of:

- **Retrieval Agent** → Fetches relevant SE knowledge from multiple corpora
- **Reasoning Agent** → Performs multi-step logical inference
- **Code Analysis Agent** → Interprets and evaluates code snippets
- **Explanation Agent** → Generates traceable reasoning paths
- **X-Explainer Layer** → Links outputs to retrieved evidence for transparency

---

## 📚 Datasets Used
- Stack Overflow Developer Q&A Corpus  
- CodeSearchNet Dataset  
- PROMISE Software Engineering Dataset  
- Eclipse Bug Reports Dataset  

---

## ⚙️ Methodology
- Retrieval-Augmented Generation (RAG)
- Multi-Agent LLM orchestration
- Explainable AI integration (traceability layer)
- Cross-corpus retrieval fusion

---

## 📊 Evaluation Plan
- Accuracy (task correctness)
- Macro F1-score
- Retrieval Precision@K
- Explanation Faithfulness Score
- Latency / efficiency trade-off

Baseline comparisons:
- Vanilla RAG (single-agent)
- CodeBERT-based QA model
- ReAct / LLM reasoning baseline

---

## 🧪 Reproducibility
- Python 3.10+
- PyTorch 2.1+
- HuggingFace Transformers
- FAISS for vector retrieval
- Fixed seed: 42

---

## 📁 Repository Structure
src/ → model implementation
retrieval/ → retrieval pipeline
agents/ → multi-agent system
explainability/ → XAI layer
evaluation/ → metrics + baselines
notebooks/ → experiments
configs/ → hyperparameters
results/ → outputs

---

## 🚀 Status
This project is currently in research development stage as part of an academic proposal for publication in a Q1 Software Engineering journal.

---

## 📄 License
MIT License

---

## 👤 Author
Braide Paul Kobina  
KNUST – Computer Science  
Software Engineering & AI Research Track
