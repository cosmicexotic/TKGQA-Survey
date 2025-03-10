# Temporal Knowledge Graph Question Answering: A Survey

Knowledge Graph Question Answering (KGQA) has been a long-standing field to answer questions based on Knowledge Graphs (KGs). Recently, the evolving nature of knowledge has attracted a growing interest in Temporal Knowledge Graph Question Answering (TKGQA), an emerging task to answer temporal questions based on Temporal Knowledge Graphs (TKGs). However, this field grapples with ambiguities in defining temporal questions and lacks a systematic categorization of existing TKGQA methods. Motivated by this, this paper presents a thorough survey from two perspectives: the taxonomy of temporal questions and the categorization of TKGQA methodologies. Specifically, we first propose a detailed taxonomy of temporal questions explored in prior studies. Subsequently, we provide an in-depth review of TKGQA methodologies of two categories: semantic parsing-based and TKG embedding-based. We explicate advanced solutions as well as techniques used when answering temporal questions. Then, we discuss the potential impact of Large Language Models (LLMs) on TKGQA. Building on the above review, we highlight potential research directions for TKGQA. This work aims to serve as a comprehensive reference for TKGQA and to inspire further research in this area.

<img src="./figures/intro-task.png" alt="intro-task" style="zoom:30%;" />

**Paper link:** https://arxiv.org/abs/2406.14191
A longer version is coming...

---
A curated list of resources dedicated to temporal knowledge graph question answering (TKGQA).

## Benchmarks for TKGQA

- The *Organization* column only records the organization of the first author.

| Date       | Title                                                        | Benchmark             | Organization                              | Code                                                | Leaderboard                                                  |
| ---------- | ------------------------------------------------------------ | --------------------- | ----------------------------------------- | --------------------------------------------------- | ------------------------------------------------------------ |
| 2018/04/23 | [TempQuestions: A Benchmark for Temporal Question Answering](https://dl.acm.org/doi/10.1145/3184558.3191536) | TempoQuestions        | Southwest Jiaotong University             | [Code](https://github.com/zhenjia2017/tequila)      | [Leaderboard](https://paperswithcode.com/sota/question-answering-on-tempquestions) |
| 2022/01/15 | [A Benchmark for Generalizable and Interpretable Temporal Question Answering over Knowledge Bases](https://arxiv.org/abs/2201.05793) | TempoQA-WD            | IBM Research                              | [Code](https://github.com/IBM/tempqa-wd)            | [Leaderboard](https://paperswithcode.com/sota/question-answering-on-tempqa-wd) |
| 2022/09/18 | [Complex Temporal Question Answering on Knowledge Graphs](https://arxiv.org/abs/2109.08935) | TimeQuestions         | Southwest Jiaotong University             | [Code](https://exaqt.mpi-inf.mpg.de/)               | [Leaderboard](https://paperswithcode.com/sota/question-answering-on-timequestions) |
| 2021/06/03 | [Question Answering Over Temporal Knowledge Graphs](https://arxiv.org/abs/2106.01515) | CronQuestions         | Indian Institute of Science Bangalore     | [Code](https://github.com/apoorvumang/CronKGQA)     | [Leaderboard](https://paperswithcode.com/sota/question-answering-on-cronquestions) |
| 2022/09/05 | [Temporal knowledge graph question answering via subgraph reasoning](https://dl.acm.org/doi/10.1016/j.knosys.2022.109134) | Complex-CronQuestions | National University of Defense Technology | [Code](https://github.com/czy1999/SubGTR)           | [Leaderboard](https://paperswithcode.com/sota/question-answering-on-complex-cronquestions) |
| 2023/07/01 | [Multi-granularity Temporal Question Answering over Knowledge Graphs](https://aclanthology.org/2023.acl-long.637.pdf) | MultiTQ               | National University of Defense Technology | [Code](https://github.com/czy1999/MultiTQ)          | [Leaderboard](https://paperswithcode.com/sota/question-answering-on-multitq) |
| 2024/08/01 | [MusTQ: A Temporal Knowledge Graph Question Answering Dataset for Multi-Step Temporal Reasoning](https://aclanthology.org/2024.findings-acl.696.pdf) | MusTQ                 | Soochow University                        |                                                     |                                                              |
| 2022/08/12 | [ForecastTKGQuestions: A Benchmark for Temporal Question Answering and Forecasting over Temporal Knowledge Graphs](https://arxiv.org/abs/2208.06501) | ForecastTKGQuestions  | LMU Muni                                  | [Code](https://github.com/ZifengDing/ForecastTKGQA) | [Leaderboard](https://paperswithcode.com/sota/question-answering-on-timequestions) |
| 2024/02/23 | [Faithful Temporal Question Answering over Heterogeneous Sources](https://arxiv.org/abs/2402.15400) | TIQ                   | Southwest Jiaotong University             | [Code](https://github.com/zhenjia2017/TIQ)          | [Leaderboard](https://faith.mpi-inf.mpg.de/)                 |



## Systems for TKGQA

- The *Organization* column only records the organization of the first author.

