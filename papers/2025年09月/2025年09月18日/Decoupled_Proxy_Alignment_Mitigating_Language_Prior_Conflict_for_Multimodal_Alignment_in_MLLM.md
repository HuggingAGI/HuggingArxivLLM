# 解耦式代理对齐：在MLLM多模态对齐中缓解语言先验冲突

发布时间：2025年09月18日

`LLM理论` `基础理论`

> Decoupled Proxy Alignment: Mitigating Language Prior Conflict for Multimodal Alignment in MLLM

# 摘要

> 多模态大型语言模型（MLLMs）凭借出色的视觉-语言模态整合能力备受关注。近年来，MLLMs的研究进展主要通过高质量数据集、新颖架构和优化训练策略来提升性能。但本文指出了一个此前被忽视的问题——语言先验冲突，即大型语言模型（LLMs）固有的语言先验与训练数据集中的语言先验不匹配。这种冲突会导致视觉-语言对齐效果不理想，原因是MLLMs容易受训练样本语言风格的影响。为解决这一问题，我们提出了一种名为解耦代理对齐（DPA）的全新训练方法。DPA包含两项核心创新：（1）在预训练阶段引入代理LLM，将视觉-语言对齐过程与语言先验干扰解耦；（2）基于视觉相关性的动态损失调整，强化视觉相关标记的优化信号。大量实验结果显示，DPA能显著缓解语言先验冲突，在不同数据集、模型家族及规模下均展现出更优的对齐性能。该方法不仅提升了MLLM训练的效率，还具备出色的泛化能力，是一种稳健的视觉-语言对齐方案。相关代码已开源：https://github.com/fnlp-vision/DPA。

> Multimodal large language models (MLLMs) have gained significant attention due to their impressive ability to integrate vision and language modalities. Recent advancements in MLLMs have primarily focused on improving performance through high-quality datasets, novel architectures, and optimized training strategies. However, in this paper, we identify a previously overlooked issue, language prior conflict, a mismatch between the inherent language priors of large language models (LLMs) and the language priors in training datasets. This conflict leads to suboptimal vision-language alignment, as MLLMs are prone to adapting to the language style of training samples. To address this issue, we propose a novel training method called Decoupled Proxy Alignment (DPA). DPA introduces two key innovations: (1) the use of a proxy LLM during pretraining to decouple the vision-language alignment process from language prior interference, and (2) dynamic loss adjustment based on visual relevance to strengthen optimization signals for visually relevant tokens. Extensive experiments demonstrate that DPA significantly mitigates the language prior conflict, achieving superior alignment performance across diverse datasets, model families, and scales. Our method not only improves the effectiveness of MLLM training but also shows exceptional generalization capabilities, making it a robust approach for vision-language alignment. Our code is available at https://github.com/fnlp-vision/DPA.

[Arxiv](https://arxiv.org/abs/2509.14735)