# Aklesh Mishra

**Research Engineer | LLM Post-Training, Evaluation & Reliable Agent Systems**

I work at the intersection of **reward modeling, reasoning-model evaluation, verifiable post-training, and agentic AI engineering**. My projects emphasize reproducible experiments, trustworthy feedback signals, controlled baselines, and failure analysis—not just headline benchmark scores.

## Selected research

- **[Stable Outcome Reward Modeling via Pairwise Preference Learning](https://github.com/Coder-12/stable-outcome-reward-modeling)** — Studied pointwise reward-model instability and pairwise outcome supervision. Reported **96.3% held-out pairwise accuracy** (90% bootstrap CI: 95.3–97.1%) within the project's evaluation setup. [Preprint](https://github.com/Coder-12/stable-outcome-reward-modeling/blob/main/paper/Stable_Outcome_Reward_Modeling_Pairwise_ORM.pdf) · [Model](https://huggingface.co/LossFunctionLover/pairwise-orm-model) · [Dataset](https://huggingface.co/datasets/LossFunctionLover/orm-pairwise-preference-pairs)
- **[Verifiable Agentic RL Lab](https://github.com/Coder-12/verifiable-agentic-rl-lab)** — Built a strict symbolic verifier and evaluated a small reasoning model using sampling, LoRA, and GRPO. On 200 frozen Countdown tasks, untouched-model greedy success was **4.5%**, versus **23.0% best-of-8 verifier selection** (an inference-time comparison). Controlled RLVR runs **did not establish reliable held-out correctness gains**; the negative result and limitations are documented.
- **[MAGI-RM](https://github.com/Coder-12/magi-rm)** — Experimental shared-encoder outcome/process reward-model pipeline with training utilities, labeled reasoning-chain data, and quality-control tooling. Trained-model performance is not yet established in the public repository.

## Agentic and LLM systems

- **[Nexus RAG](https://github.com/Coder-12/nexus-rag)** — Domain-specific retrieval-augmented question answering with dense + BM25 retrieval, reranking, citations, refusal handling, and evaluation workflows.
- **[MARCS](https://github.com/Coder-12/MARCS)** — Research prototype for LLM-assisted code review, journaled patch application, recovery, safety checks, and traceable reports; not presented as production-hardened.
- **[SERA](https://github.com/Coder-12/SERA)** — Research-paper ingestion pipeline with arXiv retrieval, PDF processing, embeddings, and metadata storage.

**Current direction:** execution-verified Python code repair and agent training, starting with authentic-task feasibility and independent verification; supervised adaptation and RL are conditional on evidence.

**Technical focus:** Python · PyTorch · Transformers / PEFT / TRL · LoRA / GRPO · LLM evaluation · RAG / retrieval · FastAPI · Docker

**Interested in:** research engineering and applied AI engineering roles spanning LLM evaluation, alignment/post-training, and reliable agents.

[LinkedIn](https://linkedin.com/in/akleshmishra) · [Hugging Face](https://huggingface.co/LossFunctionLover) · **Email:** akleshmishra7@gmail.com
