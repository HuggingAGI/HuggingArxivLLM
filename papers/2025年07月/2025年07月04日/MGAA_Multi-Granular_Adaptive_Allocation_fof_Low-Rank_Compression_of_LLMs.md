# # MGAA: 多粒度自适应分配方法用于实现大型语言模型的低秩压缩

发布时间：2025年07月04日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的压缩技术，特别是低秩近似技术的应用。论文提出了一种新的参数多粒度自适应分配方法（MGAA），用于优化模型压缩过程中的参数分配。研究内容涉及模型压缩的理论和方法，因此应归类为LLM理论。` `人工智能`

> MGAA: Multi-Granular Adaptive Allocation fof Low-Rank Compression of LLMs

# 摘要

> 大型语言模型（LLMs）的庞大参数规模使其成为模型压缩领域的研究热点，旨在通过压缩技术缓解部署和推理阶段的计算资源需求。作为极具前景的技术方向，低秩近似技术已取得显著成果。然而，绝大多数现有研究采用统一的压缩比例应用于所有权重矩阵，忽视了不同权重矩阵对模型性能的差异化影响。尽管近期有少量研究尝试采用启发式搜索策略实现最优参数分配，但此类方法计算效率低下且在大语言模型时代丧失了泛化能力。本研究提出了一种新颖的参数多粒度自适应分配方法（MGAA），可在无需特定任务评估的情况下自适应地在子层间及子层内进行参数分配。MGAA包含两个核心组件：1）在不同子层间，依据输入与输出之间的余弦相似性分配压缩比例，从而实现对重要程度各异的子层进行更精细的压缩；2）在每个子层内部，基于权重矩阵的能量分布特性分配不同的压缩比例，在保持一致的能量保留率的同时优化压缩效率。通过在多个大语言模型主干模型及基准数据集上的全面评估，验证了MGAA的优越性能。此外，我们将MGAA应用于多模态模型LLaVA，取得了显著的性能提升。

> The enormous parameter scale of large language models (LLMs) has made model compression a research hotspot, which aims to alleviate computational resource demands during deployment and inference. As a promising direction, low-rank approximation technique has made remarkable achievements. Nevertheless, unfortunately, the vast majority of studies to low-rank approximation compression generally apply uniform compression ratios across all weight matrices, while disregarding their inherently differentiated impacts on the model's performance. Although a few recent work attempts to employ heuristic search strategies to achieve the optimal parameter allocation, such strategies are computationally inefficient and lose the generalization ability in the era of LLMs. In this study, we propose a novel parameter Multi-Granular Adaptive Allocation (MGAA) method, which can adaptively allocate parameters between and within sublayers without task-specific evaluations in the compression process. MGAA consists of two components: 1) Among different sublayers, it assigns compression ratios based on their cosine similarity between inputs and outputs, allowing for a more tailored compression in sublayers with varying degrees of importance, and 2) Within each sublayer, it allocates different compression ratios to weight matrices based on their energy distribution characteristics, ensuring a consistent energy retention ratio while optimizing compression efficiency. Comprehensive evaluations of MGAA across multiple LLMs backbone models and benchmark datasets demonstrate its superior performance. Additionally, we apply our MGAA to multimodal model LLaVA, exhibiting remarkable performance improvements.

[Arxiv](https://arxiv.org/abs/2507.03294)