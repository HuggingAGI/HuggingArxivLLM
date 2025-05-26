# 检索之后，生成之前：增强大型语言模型在RAG中的可信度

发布时间：2025年05月21日

`RAG` `问答系统` `系统设计`

> After Retrieval, Before Generation: Enhancing the Trustworthiness of Large Language Models in RAG

# 摘要

> 基于检索增强生成（RAG）的系统在平衡内部（参数化）和外部（检索到的）知识方面面临严峻挑战，尤其是在这些知识来源存在冲突或不可靠的情况下。我们构建了包含36,266个问题的可信度响应数据集（TRD），涵盖四种RAG设置，全面分析这些情形。现有方法仅针对孤立场景进行优化，优先考虑单一知识来源、简单合并两者或拒绝回答，但缺乏一个统一框架来同时应对不同现实条件。因此，我们提出BRIDGE框架，该框架能够动态确定大型语言模型（LLMs）的全面响应策略。BRIDGE采用名为soft bias的自适应加权机制来指导知识收集，随后利用最大Soft-bias决策树评估知识并选择最优响应策略（信任内部/外部知识，或拒绝回答）。实验表明，与基线方法相比，BRIDGE在准确性上提升了5-15%，同时在所有场景中保持了均衡的性能。我们的工作为LLMs在现实世界RAG应用中的可信响应提供了一个有效解决方案。


> Retrieval-augmented generation (RAG) systems face critical challenges in balancing internal (parametric) and external (retrieved) knowledge, especially when these sources conflict or are unreliable. To analyze these scenarios comprehensively, we construct the Trustworthiness Response Dataset (TRD) with 36,266 questions spanning four RAG settings. We reveal that existing approaches address isolated scenarios-prioritizing one knowledge source, naively merging both, or refusing answers-but lack a unified framework to handle different real-world conditions simultaneously. Therefore, we propose the BRIDGE framework, which dynamically determines a comprehensive response strategy of large language models (LLMs). BRIDGE leverages an adaptive weighting mechanism named soft bias to guide knowledge collection, followed by a Maximum Soft-bias Decision Tree to evaluate knowledge and select optimal response strategies (trust internal/external knowledge, or refuse). Experiments show BRIDGE outperforms baselines by 5-15% in accuracy while maintaining balanced performance across all scenarios. Our work provides an effective solution for LLMs' trustworthy responses in real-world RAG applications.

[Arxiv](https://arxiv.org/abs/2505.17118)