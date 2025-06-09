# 连接外部与参数化知识：通过双流知识中的共享与私有语义协同缓解LLMs的幻觉

发布时间：2025年06月06日

`RAG` `问答系统` `知识增强`

> Bridging External and Parametric Knowledge: Mitigating Hallucination of LLMs with Shared-Private Semantic Synergy in Dual-Stream Knowledge

# 摘要

> RAG是一种通过将外部知识融入生成过程来有效缓解LLMs幻觉问题的方法。然而，外部知识可能与模型内部的知识产生冲突。现有的LLMs缺乏有效的机制来处理这种知识冲突，导致传统RAG方法在性能和稳定性上表现欠佳。因此，我们提出了一个名为DSSP-RAG的双流知识增强框架，用于实现共享与私有语义的协同。该框架的核心创新在于将传统的自注意力机制改进为混合注意力机制，能够区分共享语义和私有语义，从而实现对内部和外部知识的可控融合。为了更好地支持RAG中的DSSP机制，我们还引入了两种创新方法：一种是基于认知不确定性的无监督幻觉检测方法，用于确保引入知识的必要性；另一种是基于注意力差异矩阵的能量商（EQ），用于减少外部知识中的噪声。通过在多个基准数据集上的大量实验，我们发现DSSP-RAG能够有效解决知识冲突，显著增强双流知识的互补性，最终在与强基线模型的对比中展现出更优越的性能。

> Retrieval-augmented generation (RAG) is a cost-effective approach to mitigate the hallucination of Large Language Models (LLMs) by incorporating the retrieved external knowledge into the generation process. However, external knowledge may conflict with the parametric knowledge of LLMs. Furthermore, current LLMs lack inherent mechanisms for resolving such knowledge conflicts, making traditional RAG methods suffer from degraded performance and stability. Thus, we propose a Dual-Stream Knowledge-Augmented Framework for Shared-Private Semantic Synergy (DSSP-RAG). Central to the framework is a novel approach that refines self-attention into a mixed-attention, distinguishing shared and private semantics for a controlled internal-external knowledge integration. To effectively facilitate DSSP in RAG, we further introduce an unsupervised hallucination detection method based on cognitive uncertainty, ensuring the necessity of introducing knowledge, and an Energy Quotient (EQ) based on attention difference matrices to reduce noise in the retrieved external knowledge. Extensive experiments on benchmark datasets show that DSSP-RAG can effectively resolve conflicts and enhance the complementarity of dual-stream knowledge, leading to superior performance over strong baselines.

[Arxiv](https://arxiv.org/abs/2506.06240)