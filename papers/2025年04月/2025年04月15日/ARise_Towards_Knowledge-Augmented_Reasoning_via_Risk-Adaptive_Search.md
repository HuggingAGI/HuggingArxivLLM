# # ARise：借助风险自适应搜索实现知识增强推理

发布时间：2025年04月15日

`LLM应用`

> ARise: Towards Knowledge-Augmented Reasoning via Risk-Adaptive Search

# 摘要

> 大型语言模型（LLMs）凭借其卓越的能力吸引了广泛关注，尤其是在通过扩展推理计算来提升推理水平方面。然而，它们在开放性、知识密集型和复杂推理场景中的应用仍存在局限。推理导向的方法因假设完整的知识储备，难以有效应对开放性场景。而知识增强推理（KAR）方法也未能突破两大核心挑战：1）错误传播，早期错误会沿链式反应扩散；2）验证瓶颈，多分支决策中探索与利用的权衡问题。为了解决这些问题，我们提出了ARise框架，它在蒙特卡洛树搜索范式下，将中间推理状态的风险评估与动态检索增强生成（RAG）相结合。这种方法能够高效构建和优化跨多个假设分支的推理计划。实验结果表明，ARise相比现有KAR方法，性能提升达23.10%，相比最新RAG增强的大型推理模型，性能提升达25.37%。

> Large language models (LLMs) have demonstrated impressive capabilities and are receiving increasing attention to enhance their reasoning through scaling test--time compute. However, their application in open--ended, knowledge--intensive, complex reasoning scenarios is still limited. Reasoning--oriented methods struggle to generalize to open--ended scenarios due to implicit assumptions of complete world knowledge. Meanwhile, knowledge--augmented reasoning (KAR) methods fail to address two core challenges: 1) error propagation, where errors in early steps cascade through the chain, and 2) verification bottleneck, where the explore--exploit tradeoff arises in multi--branch decision processes. To overcome these limitations, we introduce ARise, a novel framework that integrates risk assessment of intermediate reasoning states with dynamic retrieval--augmented generation (RAG) within a Monte Carlo tree search paradigm. This approach enables effective construction and optimization of reasoning plans across multiple maintained hypothesis branches. Experimental results show that ARise significantly outperforms the state--of--the--art KAR methods by up to 23.10%, and the latest RAG-equipped large reasoning models by up to 25.37%.

[Arxiv](https://arxiv.org/abs/2504.10893)