# 知识增强的迭代检索机制在多智能体系统中的应用

发布时间：2025年03月17日

`Agent` `知识图谱` `问答系统`

> Knowledge-Aware Iterative Retrieval for Multi-Agent Systems

# 摘要

> 我们提出了一种基于大型语言模型（LLM）的新型代理框架，通过动态演化的知识实现查询的迭代优化和上下文证据的智能筛选。该系统的核心创新在于将外部数据源与内部知识缓存解耦，通过持续更新的知识缓存指导查询生成和证据选择。这种设计不仅有效缓解了偏见强化循环，还实现了动态可追踪的搜索路径，使代理在自主决策中更好地平衡信息探索的广度与结果的准确性。我们的方法在开放领域问答基准测试中表现出色，尤其在模拟真实场景的多步骤任务中，展现了从多源信息整合中提取关键内容的能力。实验结果表明，相比传统迭代检索方法，该系统不仅在各种难度的任务中超越了单步骤基线，更在复杂任务中凭借精准的证据推理和高效的执行效率展现出显著优势。此外，系统支持多代理协作与竞争模式，随着任务难度的增加，多代理配置的优势更加明显，且收敛步骤随难度线性扩展，具备良好的成本效益与可扩展性。

> We introduce a novel large language model (LLM)-driven agent framework, which iteratively refines queries and filters contextual evidence by leveraging dynamically evolving knowledge. A defining feature of the system is its decoupling of external sources from an internal knowledge cache that is progressively updated to guide both query generation and evidence selection. This design mitigates bias-reinforcement loops and enables dynamic, trackable search exploration paths, thereby optimizing the trade-off between exploring diverse information and maintaining accuracy through autonomous agent decision-making. Our approach is evaluated on a broad range of open-domain question answering benchmarks, including multi-step tasks that mirror real-world scenarios where integrating information from multiple sources is critical, especially given the vulnerabilities of LLMs that lack explicit reasoning or planning capabilities. The results show that the proposed system not only outperforms single-step baselines regardless of task difficulty but also, compared to conventional iterative retrieval methods, demonstrates pronounced advantages in complex tasks through precise evidence-based reasoning and enhanced efficiency. The proposed system supports both competitive and collaborative sharing of updated context, enabling multi-agent extension. The benefits of multi-agent configurations become especially prominent as task difficulty increases. The number of convergence steps scales with task difficulty, suggesting cost-effective scalability.

[Arxiv](https://arxiv.org/abs/2503.13275)