# VISTA：利用跨模态互信息最大化，增强多语言大型语言模型的视觉与文本对齐效果。

发布时间：2025年05月16日

`LLM应用` `计算机视觉`

> VISTA: Enhancing Vision-Text Alignment in MLLMs via Cross-Modal Mutual Information Maximization

# 摘要

> 多模态大型语言模型（MLLMs）在模态对齐方面面临一个关键挑战：它们往往过于偏重文本信息，而忽视视觉等其他模态。本文通过对广泛使用的交叉熵损失进行系统的信息论分析，揭示了其隐含的对齐目标。我们发现，这一目标存在固有限制，随着文本序列长度增加，跨模态对齐效果会逐渐下降，导致多模态信息融合受阻。为解决这一问题，我们提出了视觉-文本对齐（VISTA），一种基于理论洞见的创新方法。VISTA引入了明确的对齐目标，旨在最大化跨模态互信息，从而防止视觉对齐效果的退化。值得注意的是，VISTA无需额外模块或数据，即可增强现有MLLMs的视觉理解能力，兼具高效与实用。在包括VQAv2、MMStar和MME在内的多个基准数据集上，我们的方法显著超越了基线模型，为MLLM模态对齐研究指明了新方向。

> Current multimodal large language models (MLLMs) face a critical challenge in modality alignment, often exhibiting a bias towards textual information at the expense of other modalities like vision. This paper conducts a systematic information-theoretic analysis of the widely used cross-entropy loss in MLLMs, uncovering its implicit alignment objective. Our theoretical investigation reveals that this implicit objective has inherent limitations, leading to a degradation of cross-modal alignment as text sequence length increases, thereby hindering effective multimodal information fusion. To overcome these drawbacks, we propose Vision-Text Alignment (VISTA), a novel approach guided by our theoretical insights. VISTA introduces an explicit alignment objective designed to maximize cross-modal mutual information, preventing the degradation of visual alignment. Notably, VISTA enhances the visual understanding capabilities of existing MLLMs without requiring any additional trainable modules or extra training data, making it both efficient and practical. Our method significantly outperforms baseline models across more than a dozen benchmark datasets, including VQAv2, MMStar, and MME, paving the way for new directions in MLLM modal alignment research.

[Arxiv](https://arxiv.org/abs/2505.10917)