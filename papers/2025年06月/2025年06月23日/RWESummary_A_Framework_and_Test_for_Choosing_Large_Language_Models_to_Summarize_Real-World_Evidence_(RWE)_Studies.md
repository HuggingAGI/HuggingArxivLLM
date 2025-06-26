# RWESummary：一个框架和测试，用于选择适合的大语言模型对真实世界证据研究进行总结

发布时间：2025年06月23日

`LLM应用` `真实世界证据`

> RWESummary: A Framework and Test for Choosing Large Language Models to Summarize Real-World Evidence (RWE) Studies

# 摘要

> 尽管大型语言模型（LLMs）在通用摘要任务和医学研究辅助方面已得到广泛应用和评估，但目前尚未针对从真实世界证据（RWE）研究的结构化输出中总结真实世界证据的任务进行专门评估。为此，我们提出了RWESummary，作为MedHELM框架（Bedi, Cui, Fuentes, Unell等，2025）的扩展，旨在为这一任务提供基准测试方案。RWESummary包含一个场景和三项评估，覆盖了在医学研究总结中常见的主要错误类型，并基于Atropos Health的专有数据开发而成。此外，我们通过RWESummary对不同LLMs在内部RWE总结工具中的性能进行了比较。截至目前，基于13项不同的RWE研究，我们发现Gemini 2.5模型（包括Flash和Pro版本）表现最佳。因此，我们建议将RWESummary作为真实世界证据研究总结的新型和实用基础模型基准。

> Large Language Models (LLMs) have been extensively evaluated for general summarization tasks as well as medical research assistance, but they have not been specifically evaluated for the task of summarizing real-world evidence (RWE) from structured output of RWE studies. We introduce RWESummary, a proposed addition to the MedHELM framework (Bedi, Cui, Fuentes, Unell et al., 2025) to enable benchmarking of LLMs for this task. RWESummary includes one scenario and three evaluations covering major types of errors observed in summarization of medical research studies and was developed using Atropos Health proprietary data. Additionally, we use RWESummary to compare the performance of different LLMs in our internal RWE summarization tool. At the time of publication, with 13 distinct RWE studies, we found the Gemini 2.5 models performed best overall (both Flash and Pro). We suggest RWESummary as a novel and useful foundation model benchmark for real-world evidence study summarization.

[Arxiv](https://arxiv.org/abs/2506.18819)