# Awesome-LLM-Education-Model-Training-From-Scratch

# Awesome-LLM-Education-Model-Training-From-Scratch



Top LLM Education Model Training From Scratch (Opensource) 🌟 Star if you like it! 🌟



A curated list of top LLM education platforms, from-scratch transformer & GPT implementation repositories, pure-C/CUDA & Python pre-training frameworks, tokenization/alignment tutorials, and open AI curricula—featuring commercial SaaS/Hosted learning platforms alongside their open-source equivalents.



---



## Table of Contents



- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source Equivalents & Tools](#open-source-equivalents--tools)

  - [Complete End-to-End LLM From-Scratch Repositories](#complete-end-to-end-llm-from-scratch-repositories)

  - [Minimalist & Pure-C / CUDA / Rust LLM Training Implementations](#minimalist--pure-c--cuda--rust-llm-training-implementations)

  - [Tokenization, Attention & Architecture Deep-Dive Guides](#tokenization-attention--architecture-deep-dive-guides)

  - [Post-Training, Fine-Tuning, RLHF & Reasoning From Scratch](#post-training-fine-tuning-rlhf--reasoning-from-scratch)

  - [Open-Source AI Courses, Books & Interactive Curricula](#open-source-ai-courses-books--interactive-curricula)

- [Contributing](#contributing)



---



## Sector Overview & Market Dynamics

The global AI in education and digital tech upskilling market is estimated at approximately **$5.0B to $7.0B** (expanding at an aggressive CAGR of >30% toward $60B+ by the mid-2030s). The sector is **highly fragmented** rather than winner-take-all, characterized by low market concentration where leading platforms collectively hold under 20% market share alongside university MOOCs, specialized coding sandboxes, and niche developer upskilling tools.

---

## SaaS/Hosted Platforms

Commercial, cloud-hosted AI education platforms, interactive coding sandboxes, and subscription-based machine learning certification programs. Sorted in descending order by company valuation / scale.

| Platform | Company Scale (Valuation / Revenue) | Starting Pricing (Paid Tier) | Free Tier / Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Kaggle](https://kaggle.com)** | ~$2.2T parent market cap (Alphabet/Google subsidiary; acquired 2017) | Free ($0 / mo, no paid tier; compute quota capped) | Free forever: 30 hrs/wk NVIDIA T4 GPU compute (max 12h/session) & 20 hrs/wk TPU v5e/v3-8 compute (max 9h/session); 20 min idle timeout | Google-hosted data science & ML platform offering free GPU/TPU-accelerated Jupyter notebooks, micro-courses, and open community datasets. |
| **[Coursera](https://coursera.org)** | ~$1.35B public market cap (NYSE: COUR; FY24 revenue ~$695M) | $59.00 / month (Coursera Plus monthly) or $399.00 / year | 7-day free trial for Coursera Plus (full catalog access; auto-renews); free course preview limited to first module/lecture videos only (no graded items or certificates) | Hosted online learning platform featuring university-backed AI specializations, graded cloud notebooks, and verified certificates. |
| **[edX](https://edx.org)** | $800M acquisition valuation by 2U; 2U revenue ~$945M | $50.00 / course (Verified Track starting price; programs $200–$1,500+) | Free audit track available per course: limited strictly to video lectures and un-graded reading materials for a temporary course access window (no graded assignments or certificates) | Hosted academic learning platform providing university-level machine learning, deep learning, and foundation model courses. |
| **[DataCamp](https://datacamp.com)** | ~$625M private valuation ($100M+ ARR milestone) | $13.00 / month (billed annually at $156/yr for Premium, or $35/mo month-to-month) | Free forever Basic plan: strictly limited to the first chapter/lesson only of courses across the catalog (no certificates, complete skill paths, or graded projects) | Interactive browser-based learning platform featuring guided Python, PyTorch, Hugging Face, and LLM fine-tuning tracks. |
| **[Codecademy](https://codecademy.com)** | $525M acquisition valuation by Skillsoft (~$42M ARR at acquisition) | $14.99 / month (billed annually for Plus, or $29.99 month-to-month; Pro starts at $17.49/mo) | Free forever Basic tier: limited to ~20 introductory basic courses (no structured skill/career paths, quizzes, real-world portfolio projects, or certificates) | Cloud-hosted interactive coding platform offering step-by-step NLP, transformer, and generative AI developer paths. |
| **[Brilliant.org](https://brilliant.org)** | ~$305M private valuation (~$10M–$50M est. annual revenue) | $13.49 / month (billed annually at $161.88/yr for Premium, or $24.99 month-to-month) | Free forever tier: strictly limited to 2 daily problem keys per day (keys reset at midnight; unlocks 2 interactive concepts daily; sequential progression only, no skipping ahead) | Commercial interactive visual learning platform teaching the math, probability, and intuition behind neural networks and LLMs. |
| **[Udacity](https://udacity.com)** | ~$100M+ scale (acquired by Accenture LearnVantage in 2024; $1B peak 2015 valuation) | $249.00 / month (or 4-month bundle at ~$846 upfront) | 7-day free trial via select promotions (requires credit card, auto-renews; certificate creation locked during trial); free unverified course catalog limited strictly to raw video lectures | Commercial nanodegree platform offering mentor-supported deep learning, NLP, and generative AI engineering tracks with GPU workspaces. |
| **[DeepLearning.AI](https://deeplearning.ai)** | ~$52M–$79M est. annual revenue ($100M+ cumulative Coursera platform sales) | $30.00 / month (DeepLearning.AI Pro monthly, or $25/mo billed annually at $300/yr) | Free forever tier: video lectures and community forum access only; 7-day free trial for Pro (full interactive lab and graded quiz access; requires payment info, auto-renews) | Founded by Andrew Ng, offering hands-on AI engineering courses, short courses on transformers and agentic AI, and hosted Jupyter lab environments. |
| **[Pluralsight](https://pluralsight.com)** | Enterprise scale ($1.3B debt restructuring / lender recapitalization in 2024; $3.5B Vista 2021 buyout) | $29.00 / month (Standard Tech library, or $299.00 / year for Complete catalog) | 10-day free trial (requires credit card upfront; auto-renews unless canceled; full offline downloads and select cloud sandbox environments restricted during trial) | Enterprise technology learning platform offering video courses, skill assessments, and cloud sandboxes for AI model development. |



---



## Open-Source Equivalents & Tools



Free and open-source software (FOSS) educational repositories, line-by-line from-scratch LLM implementations, minimal C/CUDA trainers, and community-driven AI courses.



### Complete End-to-End LLM From-Scratch Repositories



* **[train-llm-from-scratch (FareedKhan-dev)](https://github.com)** - Comprehensive, step-by-step open-source guide and codebase covering every stage of training a Large Language Model from scratch.

* **[LLMs-from-scratch (Sebastian Raschka)](https://github.com)** - Bestselling open-source companion repository implementing a ChatGPT-like LLM in PyTorch step-by-step—from tokenization and attention to pre-training and instruction fine-tuning.

* **[nanoGPT (Andrej Karpathy)](https://github.com)** - The simplest, fastest, and cleanest open-source repository for training and fine-tuning medium-sized GPT models from scratch in ~600 lines of PyTorch.

* **[LitGPT (Lightning AI)](https://github.com)** - Hackable, clean open-source implementations of 20+ modern LLM architectures (Llama 3, Gemma, Mistral, Phi) with zero-abstraction pre-training and fine-tuning scripts.

* **[SmolLM / Nanotron Educational Recipes (Hugging Face)](https://github.com)** - Minimalist, open-source 3D-parallelism LLM pre-training framework used to train SmolLM models from scratch with full reproducible configs.

* **[TinyLlama](https://github.com)** - Open-source project pre-training a 1.1B Llama model on 3 trillion tokens with transparent training logs, FlashAttention-2, and reproducible scripts.

* **[OLMo (Allen Institute for AI)](https://github.com)** - Truly open language model suite releasing complete pre-training code, model weights, training data pipelines (Dolma), and evaluation harnesses.



### Minimalist & Pure-C / CUDA / Rust LLM Training Implementations



* **[llm.c (Andrej Karpathy)](https://github.com)** - Pure C and CUDA implementation of GPT-2/GPT-3 training directly on bare metal without PyTorch or Python framework dependencies.

* **[micrograd (Andrej Karpathy)](https://github.com)** - Tiny scalar-valued autograd engine and neural network library in ~150 lines of Python designed to teach backpropagation from first principles.

* **[makemore (Andrej Karpathy)](https://github.com)** - Step-by-step autoregressive character-level language model series progressing from bigrams and MLPs to WaveNet and Transformers.

* **[candle (Hugging Face Rust ML)](https://github.com)** - Minimalist ML framework for Rust featuring clean, readable from-scratch implementations of Llama, Mistral, Whisper, and BERT.

* **[PicoGPT](https://github.com)** - Unnecessarily tiny, educational implementation of GPT-2 forward pass in ~40 lines of pure NumPy.



### Tokenization, Attention & Architecture Deep-Dive Guides



* **[minbpe (Andrej Karpathy)](https://github.com)** - Minimal, clean, educational Byte Pair Encoding (BPE) tokenizer implementation written from scratch in Python (the exact algorithm behind GPT-4).

* **[The Annotated Transformer (Harvard NLP)](https://github.com)** - Line-by-line annotated PyTorch implementation of the foundational "Attention Is All You Need" paper.

* **[FlashAttention (Tri Dao)](https://github.com)** - Open-source IO-aware exact attention CUDA kernels with clear algorithmic documentation explaining hardware-efficient Transformer training.

* **[Llama 3 from Scratch (naklecha)](https://github.com)** - Detailed, visual tensor-by-tensor implementation of Meta's Llama 3 architecture (RoPE, GQA, SwiGLU, RMSNorm) written in pure PyTorch.

* **[DeepSeek-V3 / MLA & MoE From-Scratch Walkthroughs (deepseek-ai)](https://github.com)** - Official open-source architecture code demonstrating Multi-Head Latent Attention (MLA) and Mixture-of-Experts (MoE) routing.



### Post-Training, Fine-Tuning, RLHF & Reasoning From Scratch



* **[Reasoning-from-scratch (Sebastian Raschka)](https://github.com)** - Open-source educational codebase demonstrating how to build reasoning LLMs step-by-step using inference-time scaling, GRPO, and reinforcement learning.

* **[TRL (Transformer Reinforcement Learning - Hugging Face)](https://github.com)** - Full-stack open-source library for post-training foundation models using SFT, Reward Modeling, PPO, DPO, and GRPO.

* **[Unsloth](https://github.com)** - Open-source high-speed LLM fine-tuning framework providing transparent Triton kernels and free Colab/Kaggle notebooks for Llama, Qwen, and Gemma.

* **[nanoAha! / TinyZero](https://github.com)** - Minimalist open-source reproduction of DeepSeek-R1-Zero showing emergent reasoning via pure reinforcement learning on small models.



### Open-Source AI Courses, Books & Interactive Curricula



* **[fast.ai (Practical Deep Learning for Coders)](https://github.com)** - Free, top-down open-source deep learning course and Jupyter book teaching neural networks, NLP, and transformers from scratch.

* **[Neural Networks: Zero to Hero (Andrej Karpathy)](https://github.com)** - Free video lecture series and interactive Jupyter notebooks building neural networks, backprop, and GPT from scratch.

* **[Hugging Face LLM Course](https://github.com)** - Free, open-source comprehensive curriculum covering Transformers, Datasets, Tokenizers, fine-tuning, and RLHF.

* **[Stanford CS336: Language Modeling from Scratch](https://github.io)** - Open university course materials covering data curation, GPU kernels, distributed training, scaling laws, and alignment.

* **[d2l.ai (Dive into Deep Learning)](https://github.com)** - Open-source interactive deep learning textbook with runnable PyTorch, JAX, and TensorFlow code across 100+ chapters.

* **[The Ultra-Scale Playbook (Hugging Face)](https://huggingface.co)** - Free, interactive open-source guide to training LLMs across large GPU clusters (DP, TP, PP, ZeRO, and kernel optimization).



---



## Contributing



Contributions are welcome! Feel free to open a Pull Request to add more open-source from-scratch LLM implementations, educational transformer repositories, or free AI curricula.



1. Fork the repository.

2. Add your project under the appropriate category with a concise description.

3. Submit a Pull Request.
