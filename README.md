# Homy Xu (许鸿铭)

[**GitHub**](https://github.com/Homy-Xu) · [**CV**](./files/CV_Hongming_Xu.pdf) · [**Webpage**](https://sjtu-edu-4.gitbook.io/sjtu.edu-docs) · [**Email**](mailto:muzhihai@sjtu.edu.cn) · [**Gmail**](mailto:xuhm3410@gmail.com)

**Undergraduate Student, School of Computer Science, Shanghai Jiao Tong University**  
**Zhiyuan Honors Program**

---

I am an undergraduate student at the School of Computer Science, Shanghai Jiao Tong University, and a member of the Zhiyuan Honors Program.

My research interests mainly lie in **coding foundation models, long-horizon agents, and self-improving AI**. I focus on **agent memory, parametric memory, coding-model post-training, and recursive self-improvement**, especially how models and agents accumulate, update, and reuse experience over long-term interaction. I also have a background in **database systems and data management**, which led me toward agentic coding, long-horizon memory, and model self-improvement.

## Research Interests

- **Coding Foundation Models & Long-Horizon Agents** — agentic coding, persistent execution history, and repository-scale software engineering
- **Agent & Parametric Memory** — memory representation, storage, extraction, retrieval, routing, update, maintenance, and learned memory
- **Coding-Model Post-Training & Self-Improvement** — task construction, training data and trajectory curation, capability evaluation, and recursive improvement
- **Database Systems & Data Management** — database–LLM interaction, NL2SQL / Text-to-SQL, and data-management foundations for memory systems

## News

- **2026** · *MemTrace: State-Consistent Memory for Long-Horizon Coding Agents* is under review at **ICLR 2027**.
- **2026** · *Dial: A Knowledge-Grounded Dialect-Specific NL2SQL System* appears in **PVLDB 2026**.
- **2026** · *Are We Ready For An Agent-Native Memory System?* is under review at **VLDB**.
- **2026** · *Tensor-Network Physical Pages for Quantum-Ready Data Management* is part of **QCDKM 2026**.

## Selected Research

### MemTrace: State-Consistent Memory for Long-Horizon Coding Agents

**Under Review at ICLR 2027 · First Author**<br>
[Paper](https://arxiv.org/abs/2610.04838) · [Repository](https://github.com/Homy-Xu/MemTrace)

MemTrace is a state-consistent memory system for long-horizon coding agents. It combines structured execution traces with repository grounding to validate historical evidence before reuse.

**My contributions**
- Developed the memory system and its repository-grounded evidence validation workflow.
- Evaluated the approach across three software-engineering benchmarks and two coding-agent harnesses, improving the primary metric over native memory strategies.

---

### Dial: A Knowledge-Grounded Dialect-Specific NL2SQL System

**PVLDB 2026 · Co-first Author (2nd)**  
[Paper](https://arxiv.org/abs/2603.07449) · [Code](https://github.com/OpenDataBox/Dial)

**Xiang Zhang, Hongming Xu, Le Zhou, Wei Zhou, Xuanhe Zhou, Guoliang Li, Yuyu Luo, Changdong Liu, Guorun Chen, Jiang Liao, Fan Wu**

Dial studies **dialect-specific NL2SQL** for heterogeneous database systems, where different SQL dialects introduce distinct syntax, functions, and execution constraints.

**My contributions**
- Contributed to natural-language request preprocessing and the construction of **NL-LQP / dialect-aware logical plans**, supporting semantic decomposition from user requests to logical plans.
- Contributed to dialect-sensitive intermediate representations, operator annotation, and knowledge retrieval for error-prone SQL semantics such as dates, strings, and type conversions.
- Participated in the design and initialization of the **HINT-KB** knowledge base, as well as multi-round feedback generation, semantic correction, failure analysis, and rebuttal revisions.

---

### Are We Ready For An Agent-Native Memory System?

**Under Review at VLDB · Agent Memory / Data Management Systems**  
[Paper](https://arxiv.org/abs/2606.24775) · [Code](https://github.com/OpenDataBox/MemoryData)

**Wei Zhou, Xuanhe Zhou, Shaokun Han, Hongming Xu, Guoliang Li, Zhiyu Li, Feiyu Xiong, Fan Wu**

This work studies **LLM agent memory from a data-management perspective**, treating memory as a system composed of multiple interacting modules rather than a monolithic retrieval component.

**My contributions**
- Participated in decomposing agent memory into core modules including **representation and storage, extraction, retrieval/routing, and maintenance**.
- Contributed to systematic evaluation across task effectiveness, retrieval fidelity, robustness to dynamic updates, long-horizon stability, and runtime cost.
- Helped analyze experimental results and identify where different memory architectures are effective across conversational QA, factual recall, temporal reasoning, and long-running scenarios.

---

### Tensor-Network Physical Pages for Quantum-Ready Data Management

**QCDKM 2026 · Quantum Database / Approximate Data Management**

This work explores **tensor-network physical-page representations** for quantum-ready data management and approximate data processing.

**My contributions**
- Participated in research on **TN-Page**, a tensor-network-based physical page representation for approximate data management and data-loading abstractions targeting quantum backends.
- Contributed to the study of workload-aware bucketization, semantic tensorization, tensor-network factorization, and backend-aware encoding.
- Helped organize evaluation around fidelity, compression, qubit usage, and gate depth.

## Research Experience

### MemTensor

**Research Intern · Mentor: Juncheng Zhang (Tsinghua University)**<br>
*Aug. 2026 – Present*

- Contribute to coding-oriented post-training of a **284B-parameter DeepSeek-V4-Flash-0731** foundation model by designing software-engineering tasks, curating training data and execution trajectories, and evaluating post-trained checkpoints on coding and repository-level tasks.
- Explore memory mechanisms for long-horizon coding agents, focusing on persistent execution history, repository-state alignment, and reliable reuse of historical evidence; led the first-author **MemTrace** project.

### Shanghai Jiao Tong University — Theseus Lab

**Undergraduate Researcher · Supervisor: Prof. Xuanhe Zhou**<br>
*Aug. 2025 – Jun. 2026*

- Worked on **Dial**, contributing to dialect-aware logical planning and the construction of **HINT-KB** for heterogeneous SQL dialects.
- Extended this data-management perspective toward agent memory through *Are We Ready for An Agent-Native Memory System?*, studying memory representation, storage, extraction, retrieval, maintenance, and systematic evaluation.

## Education

### Shanghai Jiao Tong University

**School of Computer Science**<br>
**Zhiyuan Honors Program**  
*Sep 2024 – Present · Shanghai, China*

**Selected Coursework:** Honors Data Structures; Honors Programming Methodology (C++); Compilers; Operating Systems; Computer Organization and Systems; Computer Programming Practice; Honors Mathematical Analysis; Honors Linear Algebra.

## Honors

- **Zhiyuan Honors Scholarship**

## Technical & Research Skills

**Programming & Systems:** C++, SQL, data structures and algorithms, operating systems, computer systems, Git / GitHub, LaTeX.

**Databases & LLM Systems:** SQL / NL2SQL, Text-to-SQL, LLM agents, agent and parametric memory, coding-model post-training, RAG, benchmark design.

**Research:** experimental design and analysis, ablation studies, failure analysis, academic writing, and rebuttal collaboration.

---

> **Contact:** [muzhihai@sjtu.edu.cn](mailto:muzhihai@sjtu.edu.cn) · [xuhm3410@gmail.com](mailto:xuhm3410@gmail.com)<br>
> **GitHub:** [github.com/Homy-Xu](https://github.com/Homy-Xu)
