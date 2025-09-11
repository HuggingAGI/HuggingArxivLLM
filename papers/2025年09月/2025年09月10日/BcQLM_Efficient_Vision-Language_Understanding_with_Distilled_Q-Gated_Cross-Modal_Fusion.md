# BcQLM：借助蒸馏Q门控跨模态融合实现高效视觉-语言理解

发布时间：2025年09月10日

`LLM应用` `基础理论`

> BcQLM: Efficient Vision-Language Understanding with Distilled Q-Gated Cross-Modal Fusion

# 摘要

> 随着多模态大型语言模型（MLLMs）的不断发展，其庞大架构给资源受限环境下的部署带来了难题。在大模型时代，能效、计算可扩展性与环境可持续性已成为核心诉求，因此轻量级高性能模型的研发对实际应用至关重要。为此，我们提出了一种面向端到端视觉问答的轻量级MLLM框架。其核心是BreezeCLIP——一个紧凑而强大的视觉-语言编码器，专为高效多模态理解而优化。该模型总参数量仅12亿，大幅降低了计算成本，同时性能可媲美标准尺寸的MLLMs。多数据集实验进一步证实了其在精度与效率间的出色平衡能力。模块化、可扩展的设计使其能轻松扩展至更广泛的多模态任务。该轻量级视觉-语言框架名为BcQLM（BreezeCLIP增强的Q门控多模态语言模型），为在实际硬件条件限制下部署MLLMs开辟了一条可行路径。项目源代码已开源，地址为https://github.com/thico0224/BcQLM。

> As multimodal large language models (MLLMs) advance, their large-scale architectures pose challenges for deployment in resource-constrained environments. In the age of large models, where energy efficiency, computational scalability and environmental sustainability are paramount, the development of lightweight and high-performance models is critical for real-world applications. As such, we propose a lightweight MLLM framework for end-to-end visual question answering. Our proposed approach centres on BreezeCLIP, a compact yet powerful vision-language encoder optimised for efficient multimodal understanding. With only 1.2 billion parameters overall, our model significantly reduces computational cost while achieving performance comparable to standard-size MLLMs. Experiments conducted on multiple datasets further validate its effectiveness in balancing accuracy and efficiency. The modular and extensible design enables generalisation to broader multimodal tasks. The proposed lightweight vision-language framework is denoted as BcQLM (BreezeCLIP-enhanced Q-Gated Multimodal Language Model). It offers a promising path toward deployable MLLMs under practical hardware constraints. The source code is available at https://github.com/thico0224/BcQLM.

[Arxiv](https://arxiv.org/abs/2509.08715)