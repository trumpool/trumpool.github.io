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

- Optimized a **Metaflow** transaction-embedding pipeline via **16 single-GPU BERT** shards and indexed **Parquet** reads; in validation runs: **2x** speedup, **80%** lower cost, **90%** less peak shard RAM.
- Replaced **NumPy** scans with hash lookups over 7M trade accounts; cut whitelist filtering from **875s to 11s**.
- Traced bin flips in **2.13%** of borrower records to 1-ULP **NumPy log1p** drift across CPU and library versions; froze raw-amount thresholds for **1e-5** embedding parity across hosts.
- Fixed **AWS Batch** GPU contention via device pinning, and **16-min** TCP stalls via a request timeout in the shared Metaflow `@batch` decorator.
- Benchmarked six-bag **PyTorch** GPU training with cached feature matrices and parallel prep; cut runtime from **3h21m to 1h38m**, compute cost by **73%**, and prep time by **37%**.

### Molardata & 2077 AI: Machine Learning Engineer Intern
#### Zhejiang, China, Apr 2025 - Aug 2025

- Built a **LangChain** generator-critic-judge pipeline that generated adversarial test cases for **2,700** Codeforces problems: **GPT-4o** wrote generator scripts, **GPT-4o-mini** flagged missing attack types, and a GPT-4o judge scored coverage and returned feedback.
- Validated tests with an input verifier plus reference and known-wrong solutions (near-**100%** error detection in a **20-problem** pilot); ran up to three feedback rounds with per-step **checkpoints** for resumable runs.
- Auto-validated **1,700** problems; **200/400** reviewed test suites passed subsequent human quality checks.
- Built a **FLUX** three-turn editing MVP for **200** image sequences: GPT-4 wrote edit prompts and target captions, a vision model captioned each result, and an **LLM judge** checked it against the target caption.
- Achieved an **83%** manual-review pass rate on 200 sequences; refined prompts to catch left-right position swaps.

### DCD Lab, Zhejiang University: Research Assistant
#### Advisor: Juncheng Li, Jun 2024 - Jan 2025

- Adapted and ran seven existing image-editing data pipelines (add, remove, move, background, material, tone, rotation), producing **500K+** of the **2.5M** AnyEdit image pairs.
- Split editing instructions into index ranges across **two GPUs** and used skip-if-exists **checkpointing**, so interrupted batches resumed without regenerating finished images.
- Compared pipelines for the move & resize edit type on accuracy, efficiency, and visual consistency, and used object masks to choose the most suitable object to edit.
- Evaluated generated edits with **CLIP**, **DINO**, and L1 metrics.

### Selected Project

-----
### Multimodal RAG: Anime-to-Manga Retrieval
#### Student research MVP with Hongjun Liu, Jan 2024 - Apr 2024

- Implemented an anime-to-manga **RAG** MVP: embedded manga pages with **CLIP ViT-L/14** and stored the vectors in Docker-hosted **Milvus** with page descriptions and metadata for cosine search.
- Crawled **100+** annotated manga pages spanning **75 chapters** from a manga wiki; filtered out non-story pages such as ads.
- Retrieved the **top-5** pages for each anime frame and passed them with their descriptions to **GPT-4V** to generate plot-aware scene descriptions; built a **Gradio** demo.

### Publication

-----

- **CVPR 2025 Oral**: [AnyEdit: Mastering Unified High-Quality Image Editing for Any Idea](https://arxiv.org/abs/2411.15738). Q. Yu, W. Chow, Z. Yue, K. Pan, Y. Wu, **X. Wan**, J. Li, S. Tang, H. Zhang, and Y. Zhuang.

### Other Projects

-----
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

- **Programming & Systems**: Python, C++, Go, SQL, Linux, Git, Multithreading, TCP Networking
- **Machine Learning**: PyTorch, scikit-learn, Transformers, BERT, MPNet, FastText, GPU Inference, Model Training
- **Data Engineering**: NumPy, pandas, Parquet/PyArrow, Feature Engineering, Batch Processing, Vectorization, Caching
- **LLM & Vision**: LangChain, Multi-Agent Systems, Prompt Engineering, LLM Evaluation, CLIP, Diffusion Models, Milvus
- **Cloud & MLOps**: AWS Batch, EC2, S3, Metaflow, MLflow, Docker, Workflow Monitoring, Checkpointing
- Language Skills: Strong English communication abilities, with a **TOEFL score of 114**, including 26 in speaking and 28 in writing.
- GRE: 328 Verbal Reasoning:158, Quantitative Reasoning:170, Analytical Writing:3.5 (Sep 2024)

### Awards

-----

- The 6th Open Source Innovation Competition - Third prize (National competition)
- Asian Games Organizing Committee - Excellent Volunteers for the 19th Hangzhou Asian
Games
- Zhejiang University - Third Class Scholarship 2023
