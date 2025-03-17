# OmniDiff：细粒度图像差异描述的全面基准测试

发布时间：2025年03月14日

`LLM应用` `计算机视觉` `图像处理`

> OmniDiff: A Comprehensive Benchmark for Fine-grained Image Difference Captioning

# 摘要

> 图像差异描述任务（IDC）致力于生成图像对之间细微差异的自然语言描述，这一过程需要精确的视觉变化定位和连贯的语义表达。尽管最近在该领域取得了进展，但现有数据集在广度和深度上仍显不足，限制了其在复杂和动态环境中的应用。具体而言：（1）从广度来看，现有数据集仅限于特定场景中物体的有限变化；（2）从深度来看，以往的基准测试往往提供过于简化的描述。为了解决这些挑战，我们推出了OmniDiff——一个全面的数据集，包含324个多样化场景，涵盖现实世界的复杂环境和3D合成设置，每条注释平均60个单词，并覆盖12种不同的变化类型。在此基础上，我们开发了M$^3$Diff——一个多模态大型语言模型，配备了一个即插即用的多尺度差异感知（MDP）模块。该模块显著提升了模型在准确识别和描述图像间差异方面的能力，同时保留了基础模型的泛化性能。借助OmniDiff数据集，M$^3$Diff在Spot-the-Diff、IEdit、CLEVR-Change、CLEVR-DC和OmniDiff等多个基准测试中达到了最先进的性能水平，与现有方法相比，在跨场景差异识别准确性方面取得了显著提升。该数据集、代码和模型将公开发布，以支持进一步研究。

> Image Difference Captioning (IDC) aims to generate natural language descriptions of subtle differences between image pairs, requiring both precise visual change localization and coherent semantic expression. Despite recent advancements, existing datasets often lack breadth and depth, limiting their applicability in complex and dynamic environments: (1) from a breadth perspective, current datasets are constrained to limited variations of objects in specific scenes, and (2) from a depth perspective, prior benchmarks often provide overly simplistic descriptions. To address these challenges, we introduce OmniDiff, a comprehensive dataset comprising 324 diverse scenarios-spanning real-world complex environments and 3D synthetic settings-with fine-grained human annotations averaging 60 words in length and covering 12 distinct change types. Building on this foundation, we propose M$^3$Diff, a MultiModal large language model enhanced by a plug-and-play Multi-scale Differential Perception (MDP) module. This module improves the model's ability to accurately identify and describe inter-image differences while maintaining the foundational model's generalization capabilities. With the addition of the OmniDiff dataset, M$^3$Diff achieves state-of-the-art performance across multiple benchmarks, including Spot-the-Diff, IEdit, CLEVR-Change, CLEVR-DC, and OmniDiff, demonstrating significant improvements in cross-scenario difference recognition accuracy compared to existing methods. The dataset, code, and models will be made publicly available to support further research.

[Arxiv](https://arxiv.org/abs/2503.11093)