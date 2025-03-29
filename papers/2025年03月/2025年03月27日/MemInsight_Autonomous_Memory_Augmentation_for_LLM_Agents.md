# MemInsight：LLM 代理的自主内存增强方案

发布时间：2025年03月27日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLM）代理在整合长期记忆功能和提升语义数据表示与检索机制方面的应用。它通过具体的方法改进（MemInsight）和实验验证，展示了LLM在对话推荐、问答和事件总结等任务中的实际应用效果，因此归类为LLM应用。` `对话系统` `信息检索`

> MemInsight: Autonomous Memory Augmentation for LLM Agents

# 摘要

> 大型语言模型 (LLM) 代理已发展到能够智能处理信息、做出决策并与用户或工具互动。其关键能力在于整合长期记忆功能，使这些代理能够利用历史交互和知识。然而，日益增长的记忆容量和语义结构的需求带来了重大挑战。在本研究中，我们提出了一种自主记忆增强方法——MemInsight，旨在提升语义数据表示和检索机制。通过利用对历史交互的自主增强，LLM 代理被证明能够提供更准确且情境化的响应。我们通过三个任务场景——对话推荐、问答和事件总结——实证验证了我们方法的有效性。在 LLM-REDIAL 数据集上，MemInsight 将推荐的说服力提升了高达 14%。此外，在 LoCoMo 检索中，MemInsight 的召回率比 RAG 基线高出 34%。我们的实证结果表明，MemInsight 有望提升 LLM 代理在多个任务中的情境表现。

> Large language model (LLM) agents have evolved to intelligently process information, make decisions, and interact with users or tools. A key capability is the integration of long-term memory capabilities, enabling these agents to draw upon historical interactions and knowledge. However, the growing memory size and need for semantic structuring pose significant challenges. In this work, we propose an autonomous memory augmentation approach, MemInsight, to enhance semantic data representation and retrieval mechanisms. By leveraging autonomous augmentation to historical interactions, LLM agents are shown to deliver more accurate and contextualized responses. We empirically validate the efficacy of our proposed approach in three task scenarios; conversational recommendation, question answering and event summarization. On the LLM-REDIAL dataset, MemInsight boosts persuasiveness of recommendations by up to 14%. Moreover, it outperforms a RAG baseline by 34% in recall for LoCoMo retrieval. Our empirical results show the potential of MemInsight to enhance the contextual performance of LLM agents across multiple tasks.

[Arxiv](https://arxiv.org/abs/2503.21760)