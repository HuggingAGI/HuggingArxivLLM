# Transformer模型在面对上下文劫持攻击时的鲁棒性研究：线性分类任务中的表现分析

发布时间：2025年02月21日

`LLM理论` `人工智能` `机器学习`

> On the Robustness of Transformers against Context Hijacking for Linear Classification

# 摘要

> 基于Transformer的大型语言模型（LLMs）展现了强大的上下文学习能力，但其预测容易受到“上下文劫持”的干扰，这是一个严重的鲁棒性问题。我们基于线性Transformer的最新进展，提出了一种上下文线性分类问题的理论分析框架。在实验中，我们将上下文令牌设计为事实正确的问答对，其中问题与最终问题相似但标签相反。通过深入分析，我们发现模型深度、训练上下文长度和劫持上下文令牌数量都会显著影响线性Transformer的鲁棒性。研究发现，更深的Transformer模型能够实现更高的鲁棒性，这与实际观察结果一致。这种优势源于更深的层能够实现更精细的优化步骤，从而有效缓解上下文劫持的干扰。我们的数值实验也充分验证了这一结论。这些发现不仅揭示了更深架构的优势，也为理解Transformer架构提供了重要的理论支持。

> Transformer-based Large Language Models (LLMs) have demonstrated powerful in-context learning capabilities. However, their predictions can be disrupted by factually correct context, a phenomenon known as context hijacking, revealing a significant robustness issue. To understand this phenomenon theoretically, we explore an in-context linear classification problem based on recent advances in linear transformers. In our setup, context tokens are designed as factually correct query-answer pairs, where the queries are similar to the final query but have opposite labels. Then, we develop a general theoretical analysis on the robustness of the linear transformers, which is formulated as a function of the model depth, training context lengths, and number of hijacking context tokens. A key finding is that a well-trained deeper transformer can achieve higher robustness, which aligns with empirical observations. We show that this improvement arises because deeper layers enable more fine-grained optimization steps, effectively mitigating interference from context hijacking. This is also well supported by our numerical experiments. Our findings provide theoretical insights into the benefits of deeper architectures and contribute to enhancing the understanding of transformer architectures.

[Arxiv](https://arxiv.org/abs/2502.15609)