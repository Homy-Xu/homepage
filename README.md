# Homy Xu (许鸿铭)

[**GitHub**](https://github.com/Homy-Xu) · [**CV**](./files/CV_Homy_Xu.pdf) · [**Email**](mailto:muzhihai@sjtu.edu.cn)

**Undergraduate Student, School of Computer Science, Shanghai Jiao Tong University**  
**Information Security · Zhiyuan Honors Program**

---

I am an undergraduate student at the School of Computer Science, Shanghai Jiao Tong University, and a member of the Zhiyuan Honors Program.

My research interests lie at the intersection of **database systems** and **memory systems for large language models**. I am particularly interested in **database–LLM interaction**, **NL2SQL / Text-to-SQL**, **LLM agent memory**, **data-system evaluation and benchmarks**, and the **representation, retrieval, update, and maintenance of memory**. I am currently exploring unified orchestration, system implementation, and evaluation across heterogeneous memory approaches.

## Research Interests

- **Database Systems × LLMs** — database–LLM interaction, NL2SQL / Text-to-SQL, dialect-aware query generation
- **LLM Agent Memory** — memory representation, storage, extraction, retrieval, routing, update, and maintenance
- **Data Systems Evaluation** — benchmark design, system evaluation, ablation studies, and failure analysis
- **Memory Systems** — unified orchestration and evaluation across heterogeneous memory architectures

## News

- **Sep 2026** · *Dial: A Knowledge-Grounded Dialect-Specific NL2SQL System* is published in **PVLDB 2026**.
- **Jun 2026** · *Are We Ready For An Agent-Native Memory System?* is released on arXiv.
- **2026** · *Tensor-Network Physical Pages for Quantum-Ready Data Management* is accepted to **QCDKM 2026**.

## Selected Research

### Dial: A Knowledge-Grounded Dialect-Specific NL2SQL System

**PVLDB 2026 · Co-first Author (2nd)**  
[Paper](https://arxiv.org/abs/2603.07449) · [Code](https://github.com/weAIDB/Dial)

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

**Accepted at QCDKM 2026 · Quantum Database / Approximate Data Management**

This work explores **tensor-network physical-page representations** for quantum-ready data management and approximate data processing.

**My contributions**
- Participated in research on **TN-Page**, a tensor-network-based physical page representation for approximate data management and data-loading abstractions targeting quantum backends.
- Contributed to the study of workload-aware bucketization, semantic tensorization, tensor-network factorization, and backend-aware encoding.
- Helped organize evaluation around fidelity, compression, qubit usage, and gate depth.

## Education

### Shanghai Jiao Tong University

**School of Computer Science · Information Security**  
**Zhiyuan Honors Program**  
*Sep 2024 – Present · Shanghai, China*

**Selected Coursework:** Honors Data Structures; Honors Programming Methodology (C++); Compilers; Operating Systems; Computer Organization and Systems; Computer Programming Practice; Honors Mathematical Analysis; Honors Linear Algebra.

## Honors

- **Zhiyuan Honors Scholarship**

## Technical & Research Skills

**Programming & Systems:** C++, SQL, data structures and algorithms, operating systems, computer systems, Git / GitHub, LaTeX.

**Databases & LLM Systems:** SQL / NL2SQL, Text-to-SQL, LLM agents, memory systems, RAG, benchmark design.

**Research:** experimental design and analysis, ablation studies, failure analysis, academic writing, and rebuttal collaboration.

---

> **Contact:** [muzhihai@sjtu.edu.cn](mailto:muzhihai@sjtu.edu.cn)  
> **GitHub:** [github.com/Homy-Xu](https://github.com/Homy-Xu)
