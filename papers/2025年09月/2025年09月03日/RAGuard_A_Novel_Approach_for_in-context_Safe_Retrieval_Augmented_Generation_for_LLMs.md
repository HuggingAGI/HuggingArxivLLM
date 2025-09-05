# RAGuard：一种新颖的大型语言模型（LLMs）上下文内安全检索增强生成方法

发布时间：2025年09月03日

`RAG` `能源与环保`

> RAGuard: A Novel Approach for in-context Safe Retrieval Augmented Generation for LLMs

# 摘要

> 在海上风电（OSW）运维中，准确性与安全性至关重要，但传统大型语言模型（LLMs）在面对高度专业化或突发场景时往往表现不佳。为此，我们提出RAGuard——一个增强型检索增强生成（RAG）框架，它将安全关键文档与技术手册明确集成。通过向两个索引发出并行查询，并为知识和安全分配独立的检索预算，RAGuard确保了技术深度与安全覆盖的双重保障。我们进一步开发了SafetyClamp扩展，它能获取更大的候选池，并通过“硬钳制”精确槽位来确保安全性。我们在稀疏（BM25）、密集（密集段落检索）及混合检索范式上进行评估，测量技术召回率@K和安全召回率@K。RAG的这两项扩展使安全召回率@K从RAG中的近0%提升至RAGuard中的50%以上，同时保持技术召回率超过60%。这些结果表明，RAGuard与SafetyClamp有望为在关键运维场景中将安全保障融入基于LLM的决策支持系统树立新标准。

> Accuracy and safety are paramount in Offshore Wind (OSW) maintenance, yet conventional Large Language Models (LLMs) often fail when confronted with highly specialised or unexpected scenarios. We introduce RAGuard, an enhanced Retrieval-Augmented Generation (RAG) framework that explicitly integrates safety-critical documents alongside technical manuals.By issuing parallel queries to two indices and allocating separate retrieval budgets for knowledge and safety, RAGuard guarantees both technical depth and safety coverage. We further develop a SafetyClamp extension that fetches a larger candidate pool, "hard-clamping" exact slot guarantees to safety. We evaluate across sparse (BM25), dense (Dense Passage Retrieval) and hybrid retrieval paradigms, measuring Technical Recall@K and Safety Recall@K. Both proposed extensions of RAG show an increase in Safety Recall@K from almost 0\% in RAG to more than 50\% in RAGuard, while maintaining Technical Recall above 60\%. These results demonstrate that RAGuard and SafetyClamp have the potential to establish a new standard for integrating safety assurance into LLM-powered decision support in critical maintenance contexts.

[Arxiv](https://arxiv.org/abs/2509.03768)