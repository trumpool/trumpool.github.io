---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

[Download the PDF version](/assets/CV.pdf)

### Area of interest

- Multimodal Model
- Image Editing
- Natural Language Processing

### Education

-----

- University of Pennsylvania, Philadelphia, PA
- MS in Computer and Information Science, Sep 2025 - May 2027

- Zhejiang University, Zhejiang, China
- BS in Computer Science and Technology, Sep 2021 - May 2025
  - GPA: 3.96 / 4.00 (Average Score: 90.71/100)
- **Core courses:**
  - CS: Fundamental Data Structure (98/100), B/S Software Development (96/100), Operating System (98/100), C Programming(94/100), Computer Organization(93/100), Database System(90/100), Natural Language Processing(95/100)
  - Mathematics: Computational Theory (95/100), Probability Theory(95/100), Calculus (93/100), Linear Algebra(91/100)

### Professional Experience

-----
### Upstart: Machine Learning Engineer Intern
#### San Jose, CA, Jun 2026 - Aug 2026

- Scaled BERT embeddings feeding the personal-loan underwriting model across **16 single-GPU** Metaflow shards with indexed **Parquet** reads; validation runs: **2x** faster, **80%** cheaper, **90%** less peak RAM.
- Traced bin flips in **2.13%** of borrower records to a 1-ULP **NumPy log1p** drift across hosts; froze raw-amount thresholds to restore **1e-5** embedding parity and remove a source of train/serve skew.
- Found CPU tokenization starving GPU inference and vectorized it, lifting GPU utilization **~4x**.
- Benchmarked GPU training of a six-bag **PyTorch** ensemble with GPU-resident feature matrices and parallel feature prep; verified **1e-5** CPU/GPU output parity and cut runtime **3h21m to 1h38m** and cost **73%**.
- Shipped fixes for **AWS Batch** GPU contention and **16-min** TCP stalls in the company-wide `@batch` decorator.

### Molardata & 2077 AI: Machine Learning Engineer Intern
#### Zhejiang, China, Apr 2025 - Aug 2025

- Built a **LangChain** multi-agent pipeline (**GPT-4o** generator, **GPT-4o-mini** critic for missed attack types, GPT-4o coverage judge) that produced validated adversarial tests for **1,700** Codeforces problems.
- Gated LLM verdicts behind execution checks (input verifier, reference and known-wrong solutions), reaching near-**100%** error detection in a pilot; ran up to three feedback rounds with per-step **checkpoints**.
- Built an **LLM-as-judge** for **200** three-turn **FLUX** image-editing sequences, comparing result and target captions; **83%** passed manual review, vs. an embedding baseline that caught only half of identity drifts.

### DCD Lab, Zhejiang University: Research Assistant
#### Advisor: Juncheng Li, Jun 2024 - Jan 2025

- Adapted and ran seven image-editing data pipelines, producing **500K+** training pairs for AnyEdit (**CVPR 2025 Oral**); evaluated edits with **CLIP**, **DINO**, and L1 metrics.
- Sharded generation across two GPUs with skip-if-exists **checkpointing** for resumable batches.

### Selected Projects

-----
### Flight Delay Prediction
#### CIS 5450 Big Data Analytics, Team of 4 (owned modeling), Apr 2026

- Modeled 15+ minute delays on **6.8M** 2024 U.S. flights joined with NOAA hourly weather, progressing from logistic regression and random forest to **XGBoost** and **LightGBM** under a time-based split.
- Tuned XGBoost to **0.817 AUC**; class weights beat SMOTE on recall and AUC, a tuned threshold gave 0.663 precision at 0.525 recall, and AUC held within **0.002** on the full 5.6M-row set.
- Tested delay drivers with permutation tests (budget vs. legacy carriers, hub vs. non-hub), bootstrap CIs (summer vs. winter), and a Monte Carlo χ² test for weather.

### QUAKER: Two-Stage Product Retrieval
#### CIS 5200 Machine Learning Course Project, Dec 2025

- Fine-tuned a **BERT-large** category classifier (~90% top-4 hit rate) to filter items before **E5** ranking on 21K vague queries; reached **74.8%** top-200 accuracy, **+32** pts over TF-IDF.
- Traced a batched-vs-single scoring mismatch to per-batch padding lengths and fixed it with fixed-length padding; precomputed item embeddings to make evaluation **~45x** faster.

### Publication

-----

- **CVPR 2025 Oral**: [AnyEdit: Mastering Unified High-Quality Image Editing for Any Idea](https://arxiv.org/abs/2411.15738). Q. Yu, W. Chow, Z. Yue, K. Pan, Y. Wu, **X. Wan**, J. Li, S. Tang, H. Zhang, and Y. Zhuang.

### Other Projects

-----
### Multimodal RAG: Anime-to-Manga Retrieval
#### Student research MVP with Hongjun Liu, Jan 2024 - Apr 2024

- Implemented an anime-to-manga **RAG** MVP: embedded manga pages with **CLIP ViT-L/14** and stored the vectors in Docker-hosted **Milvus** with page descriptions and metadata for cosine search.
- Crawled **100+** annotated manga pages spanning **75 chapters** from a manga wiki; filtered out non-story pages such as ads.
- Retrieved the **top-5** pages for each anime frame and passed them with their descriptions to **GPT-4V** to generate plot-aware scene descriptions; built a **Gradio** demo.

### 2D Game Development in NUS School of Computing Summer Workshop
#### Lecturer: Kelvin Sung, Jun 2023

- Actively participated in the entire game development process, from the initial proposal, creating prototypes, and rough demos, through alpha and beta testing, to the final player testing and game release.
- Build a solid turn-based game system to support multiple players and their skill casting at arbitrary time, using Unity and C#.
- **Achieved an A+ score** (top 5% in the course), and [our game](https://fluuuegel.github.io/WebGL/) secured the **2nd place** in the final showcase. Remarkably, this was accomplished without any prior hands-on experience in Unity, while competing against seasoned game developers in the course.

### DAMO Academy & ModelScope Practical AIGC Training Program
#### Aug 2023 - Sep 2023

- Created stylized AIGC styles based on base model majicMix-v6 by prompt-engineering to create solid 
art style, and trained LoRA to make New Year Style portraits.
- Integrated new styles we create into facechain, a deep-learning toolchain for generating your DigitalTwin released by modelscope.
- Won **3rd prize in the 6th Open Source Innovation Competition** for the new portrait style we provided.

### Zhejiang University B/S Software Development Course (96/100)
#### Course Project: Building a MQTT server for managing Internet of Things (IoT) devices.

- Utilized the UmiJS framework, Ant Design component library and React to build a user interface for device management. Implemented features include login authentication, data analytics, and device location tracking.
- Adopted Go as the programming language for backend development, integrated with the Gin framework for efficient architecture, and utilized GORM for seamless database operations, all while working with a MySQL database.

### Skills

-----

- **Statistics & Modeling**: Hypothesis Testing, Supervised Learning, XGBoost, LightGBM, Class Imbalance, Model Validation
- **Machine Learning**: PyTorch, scikit-learn, BERT, E5, Embeddings, Feature Engineering, Ensembles, LLM-as-Judge
- **Data**: Python, SQL, NumPy, pandas, Parquet/PyArrow, Large-Scale Batch Processing, Vectorization
- **LLM & Vision**: LangChain, Multi-Agent Systems, Prompt Engineering, CLIP, Diffusion Models
- **Platforms**: Metaflow, AWS Batch, EC2, S3, Docker, MLflow, GPU Training & Inference, Linux, Git
- Language Skills: Strong English communication abilities, with a **TOEFL score of 114**, including 26 in speaking and 28 in writing.
- GRE: 328 Verbal Reasoning:158, Quantitative Reasoning:170, Analytical Writing:3.5 (Sep 2024)

### Awards

-----

- The 6th Open Source Innovation Competition - Third prize (National competition)
- Asian Games Organizing Committee - Excellent Volunteers for the 19th Hangzhou Asian
Games
- Zhejiang University - Third Class Scholarship 2023
