# 轻量级多专家生成式语言模型系统用于工程信息与知识抽取

发布时间：2025年05月27日

`LLM应用` `生成式AI` `分布式系统`

> A Lightweight Multi-Expert Generative Language Model System for Engineering Information and Knowledge Extraction

# 摘要

> 尽管大型语言模型（LLMs）在领域自适应技术方面取得了显著进展，但现有方法仍面临两大挑战：计算成本高昂以及幻觉问题频发。当前大多数自适应方法未能有效降低微调和推理所需的计算资源。尽管幻觉问题随着模型更新逐步改善，但在工程场景中仍普遍存在，因为生成结构严谨、误差最小的文本至关重要。针对这一现状，我们提出了一种名为小型语言图（SLG）的创新解决方案。该系统采用图结构，每个节点代表一个专注于特定领域的小型语言模型，这些模型经过精简文本微调，具备高效的推理能力。实验结果显示，与传统微调方法相比，SLG在Exact Match指标上提升了3倍，且微调速度提升了1.7倍。这一突破为中小型企业打开了大门，使其能够以更低的计算成本自信地部署生成式AI技术，如LLMs。同时，SLG的图架构和轻量化设计也为分布式AI系统提供了新思路，有望缓解对昂贵集中式计算集群的依赖。

> Despite recent advancements in domain adaptation techniques for large language models, these methods remain computationally intensive, and the resulting models can still exhibit hallucination issues. Most existing adaptation methods do not prioritize reducing the computational resources required for fine-tuning and inference of language models. Hallucination issues have gradually decreased with each new model release. However, they remain prevalent in engineering contexts, where generating well-structured text with minimal errors and inconsistencies is critical. This work introduces a novel approach called the Small Language Graph (SLG), which is a lightweight adaptation solution designed to address the two key challenges outlined above. The system is structured in the form of a graph, where each node represents a lightweight expert - a small language model fine-tuned on specific and concise texts. The results of this study have shown that SLG was able to surpass conventional fine-tuning methods on the Exact Match metric by 3 times. Additionally, the fine-tuning process was 1.7 times faster compared to that of a larger stand-alone language model. These findings introduce a potential for small to medium-sized engineering companies to confidently use generative AI technologies, such as LLMs, without the necessity to invest in expensive computational resources. Also, the graph architecture and the small size of expert nodes offer a possible opportunity for distributed AI systems, thus potentially diverting the global need for expensive centralized compute clusters.

[Arxiv](https://arxiv.org/abs/2505.21109)