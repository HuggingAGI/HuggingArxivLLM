# BEE-RAG：平衡熵工程实现增强生成

发布时间：2025年08月07日

`RAG` `问答系统` `信息处理`

> BEE-RAG: Balanced Entropy Engineering for Retrieval-Augmented Generation

# 摘要

> 大型语言模型（LLMs）的快速发展催生了检索增强生成（RAG）这一重要方法，用于弥补LLMs的知识局限性。然而，由于检索信息量通常较大，RAG往往需要处理较长的上下文长度。从熵工程的角度来看，我们发现不受约束的熵增长以及由于长检索上下文导致的注意力稀释是影响RAG性能的重要因素。本文提出了一种平衡熵工程增强的RAG框架（BEE-RAG），通过熵不变性原理提升了RAG系统对不同上下文长度的适应能力。通过利用平衡上下文熵重新设计注意力机制，BEE-RAG将注意力敏感度与上下文长度分离，确保了熵水平的稳定。在此基础上，我们引入了一种零样本推理策略用于多重要性估计，并提出了一种参数高效的自适应微调机制，以获得不同设置下的最优平衡因子。在多个RAG任务上的广泛实验验证了BEE-RAG的有效性。

> With the rapid advancement of large language models (LLMs), retrieval-augmented generation (RAG) has emerged as a critical approach to supplement the inherent knowledge limitations of LLMs. However, due to the typically large volume of retrieved information, RAG tends to operate with long context lengths. From the perspective of entropy engineering, we identify unconstrained entropy growth and attention dilution due to long retrieval context as significant factors affecting RAG performance. In this paper, we propose the balanced entropy-engineered RAG (BEE-RAG) framework, which improves the adaptability of RAG systems to varying context lengths through the principle of entropy invariance. By leveraging balanced context entropy to reformulate attention dynamics, BEE-RAG separates attention sensitivity from context length, ensuring a stable entropy level. Building upon this, we introduce a zero-shot inference strategy for multi-importance estimation and a parameter-efficient adaptive fine-tuning mechanism to obtain the optimal balancing factor for different settings. Extensive experiments across multiple RAG tasks demonstrate the effectiveness of BEE-RAG.

[Arxiv](https://arxiv.org/abs/2508.05100)