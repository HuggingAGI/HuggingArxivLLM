# # 动态分配跨知识库查询，实现逐步检索增强推理

发布时间：2025年05月28日

`RAG` `问答系统` `多模态`

> Learning to Route Queries Across Knowledge Bases for Step-wise Retrieval-Augmented Reasoning

# 摘要

> 多模态检索增强生成（MRAG）在多模态大语言模型（MLLMs）中展现出减少幻觉现象的潜力，通过在生成过程中引入外部知识。现有方法通常采用静态检索流程，从多个知识库中获取信息并进行优化，但忽视了MLLMs在推理过程中动态与知识库交互的能力。为解决这一问题，我们提出了R1-Router，一种全新的MRAG框架，能够根据推理状态的变化，智能决定何时何地检索知识。具体来说，R1-Router可根据当前推理步骤生成后续查询，并将其路由到最适合的知识库，整合外部知识以形成连贯的推理轨迹，从而回答原始查询。此外，我们引入了分步组相对策略优化（Step-GRPO），一种定制的强化学习算法，通过分配特定步骤的奖励来优化MLLMs的推理行为。在多个跨模态的开放领域问答基准测试中，R1-Router比基线模型高出7%以上。进一步分析表明，R1-Router能够自适应且有效地利用多样化的知识库，减少不必要的检索，同时提升效率和准确性。

> Multimodal Retrieval-Augmented Generation (MRAG) has shown promise in mitigating hallucinations in Multimodal Large Language Models (MLLMs) by incorporating external knowledge during generation. Existing MRAG methods typically adopt a static retrieval pipeline that fetches relevant information from multiple Knowledge Bases (KBs), followed by a refinement step. However, these approaches overlook the reasoning and planning capabilities of MLLMs to dynamically determine how to interact with different KBs during the reasoning process. To address this limitation, we propose R1-Router, a novel MRAG framework that learns to decide when and where to retrieve knowledge based on the evolving reasoning state. Specifically, R1-Router can generate follow-up queries according to the current reasoning step, routing these intermediate queries to the most suitable KB, and integrating external knowledge into a coherent reasoning trajectory to answer the original query. Furthermore, we introduce Step-wise Group Relative Policy Optimization (Step-GRPO), a tailored reinforcement learning algorithm that assigns step-specific rewards to optimize the reasoning behavior of MLLMs. Experimental results on various open-domain QA benchmarks across multiple modalities demonstrate that R1-Router outperforms baseline models by over 7%. Further analysis shows that R1-Router can adaptively and effectively leverage diverse KBs, reducing unnecessary retrievals and improving both efficiency and accuracy.

[Arxiv](https://arxiv.org/abs/2505.22095)