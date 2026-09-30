# Aklesh Mishra
**ML Research Engineer — Reward Modeling, LLM Evaluation & Alignment**

I build reward models and evaluation systems for LLM reasoning, with a focus on reliable oversight signals.

## Research
- **Stable Outcome Reward Modeling via Pairwise Preference Learning** — pointwise ORMs collapsed to AUC ~0.5; pairwise training reached **96.3%** held-out pairwise accuracy (90% CI [95.3, 97.1]), anti-symmetry r = −0.998. [Paper](<PAPER_PDF_URL>) · [Code](https://github.com/Coder-12/stable-outcome-reward-modeling) · [Model](https://huggingface.co/LossFunctionLover/pairwise-orm-model) · [Dataset](https://huggingface.co/datasets/LossFunctionLover/orm-pairwise-preference-pairs)
- **Ongoing:** matched implicit process evaluators — single-score vs pairwise step scoring under frozen optimization pressure (scalable oversight).

## Systems
- **[MAGI-RM](https://github.com/Coder-12/magi-rm)** — dual-head ORM + PRM (OPT-1.3B), DDP/Accelerate, activation checkpointing, OOM recovery.
- **[Nexus RAG](https://github.com/Coder-12/nexus-rag)** — hybrid retrieval (BM25 + dense + RRF) + reranking; **93% Precision@3**, 55-question eval suite.
- **[MARCS](https://github.com/Coder-12/MARCS)** — multi-agent code review with journaled, crash-safe patching; 250 annotated PRs, **88% precision**.
- **[SERA](https://github.com/Coder-12/SERA)** — research-agent ingestion pipeline: async arXiv retrieval, resumable downloads, end-to-end tests.

## Stack
Python, C++, PyTorch, Transformers, Accelerate/DDP, LoRA/QLoRA, DPO, RLVR, LangGraph, FastAPI, Docker, AWS, GCP

## Also
Top 10% Facebook HackerCup 2022 · 1,500+ Codeforces problems 

📧 akleshmishra7@gmail.com · [LinkedIn](https://linkedin.com/in/akleshmishra) · 🤗 [Hugging Face](https://huggingface.co/LossFunctionLover)
