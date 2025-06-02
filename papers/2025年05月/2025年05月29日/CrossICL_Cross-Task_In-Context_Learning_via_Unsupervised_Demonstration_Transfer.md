# # CrossICL: 跨任务上下文学习新方法：通过无监督示例转移实现的 CrossICL

发布时间：2025年05月29日

`LLM应用` `上下文学习`

> CrossICL: Cross-Task In-Context Learning via Unsupervised Demonstration Transfer

# 摘要

> 上下文学习（ICL）通过演示样例增强了大型语言模型（LLMs）的表现，但获取这些样例主要依赖人工。现实中，用户往往无法或不愿提供这些样例。受人类启发，我们提出了一种新的 ICL 范式 CrossICL，研究如何在 ICL 中利用现有源任务的演示样例，无需额外人工干预即可获得可靠指导。为此，我们设计了两阶段对齐策略，以缓解任务间差距的干扰，作为实验基础。基于此，我们对 CrossICL 进行了全面探索，涵盖 Super-NI 基准中的 875 个 NLP 任务和六种 LLMs，包括 GPT-4o。实验结果验证了 CrossICL 的有效性，并为跨任务演示选择等关键问题提供了见解，揭示了任务差距在 CrossICL 中引发的干扰类型。

> In-Context Learning (ICL) enhances the performance of large language models (LLMs) with demonstrations. However, obtaining these demonstrations primarily relies on manual effort. In most real-world scenarios, users are often unwilling or unable to provide such demonstrations. Inspired by the human analogy, we explore a new ICL paradigm CrossICL to study how to utilize existing source task demonstrations in the ICL for target tasks, thereby obtaining reliable guidance without any additional manual effort. To explore this, we first design a two-stage alignment strategy to mitigate the interference caused by gaps across tasks, as the foundation for our experimental exploration. Based on it, we conduct comprehensive exploration of CrossICL, with 875 NLP tasks from the Super-NI benchmark and six types of LLMs, including GPT-4o. Experimental results demonstrate the effectiveness of CrossICL and provide valuable insights on questions like the criteria for selecting cross-task demonstrations, as well as the types of task-gap-induced interference in CrossICL.

[Arxiv](https://arxiv.org/abs/2505.24143)