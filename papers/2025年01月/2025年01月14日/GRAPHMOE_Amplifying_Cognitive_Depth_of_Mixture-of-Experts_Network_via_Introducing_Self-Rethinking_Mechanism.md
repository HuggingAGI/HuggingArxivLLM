# GRAPHMOE：引入自我反思机制，提升专家混合网络的认知深度

发布时间：2025年01月14日

`LLM理论

理由：这篇论文主要讨论了一种新的方法（GRAPHMOE）来增强语言模型的认知深度，通过构建在伪图MoE网络上的自我反思机制和循环路由策略来提升语言模型的推理能力。这涉及到对语言模型内部结构和机制的改进，属于对大型语言模型（LLM）的理论研究和优化，因此应归类为LLM理论。` `人工智能`

> GRAPHMOE: Amplifying Cognitive Depth of Mixture-of-Experts Network via Introducing Self-Rethinking Mechanism

# 摘要

> 传统的混合专家（MoE）网络通过使用多个较小的专家模型而非单一大型网络而受益。然而，这些专家通常独立运作，这引发了一个问题：这些模型之间的相互连接是否能提升MoE网络的性能？为此，我们提出了GRAPHMOE，这是一种通过构建在伪图MoE网络上的自我反思机制来增强语言模型认知深度的新方法。GRAPHMOE采用循环路由策略模拟迭代思维步骤，促进专家节点间的信息流动。我们使用低秩适应技术（LoRA）实现了GRAPHMOE架构，并在多个基准数据集上进行了广泛实验。实验结果显示，GRAPHMOE优于其他基于LoRA的模型，达到了最先进的（SOTA）性能。此外，本研究探索了一种新的循环路由策略，有望为提升语言模型的推理能力提供新的思路。

> Traditional Mixture-of-Experts (MoE) networks benefit from utilizing multiple smaller expert models as opposed to a single large network. However, these experts typically operate independently, leaving a question open about whether interconnecting these models could enhance the performance of MoE networks. In response, we introduce GRAPHMOE, a novel method aimed at augmenting the cognitive depth of language models via a self-rethinking mechanism constructed on Pseudo GraphMoE networks. GRAPHMOE employs a recurrent routing strategy to simulate iterative thinking steps, thereby facilitating the flow of information among expert nodes. We implement the GRAPHMOE architecture using Low-Rank Adaptation techniques (LoRA) and conduct extensive experiments on various benchmark datasets. The experimental results reveal that GRAPHMOE outperforms other LoRA based models, achieving state-of-the-art (SOTA) performance. Additionally, this study explores a novel recurrent routing strategy that may inspire further advancements in enhancing the reasoning capabilities of language models.

[Arxiv](https://arxiv.org/abs/2501.07890)