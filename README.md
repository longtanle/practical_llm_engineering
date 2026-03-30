# 🧠 Practical LLM Engineering

> A hands-on, engineering-focused learning resource for Large Language Models and Generative AI systems.

[![Python](https://img.shields.io/badge/python-3.10%2B-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Notebooks](https://img.shields.io/badge/notebooks-Jupyter-orange)](https://jupyter.org/)

---

## 🎯 What This Repository Is

Most LLM tutorials focus on prompting or high-level concepts. This repository goes deeper — covering **how modern LLM systems actually work under the hood**, from tokenization to production inference pipelines.

Every topic ships as a **self-documented Jupyter notebook** with:
- Clear conceptual explanations
- Architecture diagrams
- Runnable implementation code
- Practical experiments
- Engineering insights you won't find in papers

---

## 🗺️ Learning Path

```
01 Fundamentals          → Tokens, embeddings, attention, generation
02 Prompting             → Zero-shot, few-shot, CoT, structured prompts
03 Embeddings & Retrieval → Sentence embeddings, vector DBs, hybrid search
04 RAG Systems           → Basic → Advanced → Agentic RAG
05 LLM Agents            → Tool use, function calling, memory, multi-step
06 Evaluation            → Perplexity, BLEU/ROUGE, LLM-as-judge
07 Fine-tuning           → LoRA, QLoRA, instruction tuning
08 Alignment             → RLHF, DPO, reward models
09 Inference Engineering → KV cache, batching, quantization, streaming
10 Advanced Inference    → Speculative decoding, EAGLE, Medusa
11 Systems Engineering   → Production pipelines, GPU memory, edge deployment
```

---

## 📂 Repository Structure

```
practical-llm-engineering/
├── README.md
├── ROADMAP.md
├── setup/
│   ├── requirements.txt
│   └── environment_setup.ipynb
├── 01_fundamentals/
├── 02_prompting/
├── 03_embeddings_and_retrieval/
├── 04_rag_systems/
├── 05_llm_agents/
├── 06_llm_evaluation/
├── 07_finetuning/
├── 08_alignment/
├── 09_llm_inference_engineering/
├── 10_advanced_inference/
├── 11_llm_systems_engineering/
├── projects/
│   ├── rag_chatbot/
│   ├── research_paper_assistant/
│   └── code_generation_agent/
├── utils/
└── figures/
```

---

## 🚀 Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/your-username/practical-llm-engineering.git
cd practical-llm-engineering

# 2. Create virtual environment
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

# 3. Install dependencies
pip install -r setup/requirements.txt

# 4. Launch Jupyter
jupyter lab
```

---

## 📚 Module Overview

| # | Module | Key Topics | Notebooks |
|---|--------|-----------|-----------|
| 01 | Fundamentals | Tokenization, attention, sampling | 5 |
| 02 | Prompting | Zero-shot, CoT, structured | 5 |
| 03 | Embeddings & Retrieval | Vector DBs, hybrid search | 5 |
| 04 | RAG Systems | Pipeline, reranking, evaluation | 5 |
| 05 | LLM Agents | Tools, memory, multi-step | 4 |
| 06 | Evaluation | Perplexity, BLEU, LLM-judge | 4 |
| 07 | Fine-tuning | LoRA, QLoRA, datasets | 4 |
| 08 | Alignment | RLHF, DPO, reward models | 5 |
| 09 | Inference Engineering | KV cache, batching, quantization | 5 |
| 10 | Advanced Inference | Speculative, EAGLE, Medusa | 5 |
| 11 | Systems Engineering | Production, GPU, edge | 8 |

---

## 🧩 Notebook Structure

Every notebook follows a consistent format:

```
1. Overview & Learning Objectives
2. Background Concepts
3. Architecture Diagram
4. Step-by-Step Implementation
5. Experiments & Benchmarks
6. Engineering Notes & Gotchas
7. Exercises
8. References
```

---

## 🤝 Contributing

Contributions are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.