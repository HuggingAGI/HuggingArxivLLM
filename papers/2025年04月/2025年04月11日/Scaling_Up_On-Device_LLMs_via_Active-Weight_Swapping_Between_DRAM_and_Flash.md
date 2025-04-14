# 借助 DRAM 与 Flash 之间的主动权重交换，扩展设备端大型语言模型
Scaling Up On-Device LLMs via Active-Weight Swapping Between DRAM and Flash

发布时间：2025年04月11日

`LLM应用` `移动设备` `人工智能`

> Scaling Up On-Device LLMs via Active-Weight Swapping Between DRAM and Flash

# 摘要

> 大型语言模型（LLMs）正逐步部署于移动设备，但受限于DRAM容量，可部署模型规模受限。本文提出ActiveFlow，首个实现现代LLMs自适应DRAM使用的推理框架，助力扩展模型部署规模。该框架基于全新主动权重DRAM-Flash交换理念，并融合三项创新技术：（1）跨层主动权重预加载，利用当前层激活预测后续层主动权重，实现计算与数据加载重叠，支持大数据传输。（2）稀疏感知自蒸馏，调整主动权重输出分布，弥补稀疏性近似。（3）主动权重DRAM-Flash交换流水线，协调内存分配，优化权重管理。实验结果表明，ActiveFlow在性能与成本间达到最优平衡，超越现有优化方法。

> Large language models (LLMs) are increasingly being deployed on mobile devices, but the limited DRAM capacity constrains the deployable model size. This paper introduces ActiveFlow, the first LLM inference framework that can achieve adaptive DRAM usage for modern LLMs (not ReLU-based), enabling the scaling up of deployable model sizes. The framework is based on the novel concept of active weight DRAM-flash swapping and incorporates three novel techniques: (1) Cross-layer active weights preloading. It uses the activations from the current layer to predict the active weights of several subsequent layers, enabling computation and data loading to overlap, as well as facilitating large I/O transfers. (2) Sparsity-aware self-distillation. It adjusts the active weights to align with the dense-model output distribution, compensating for approximations introduced by contextual sparsity. (3) Active weight DRAM-flash swapping pipeline. It orchestrates the DRAM space allocation among the hot weight cache, preloaded active weights, and computation-involved weights based on available memory. Results show ActiveFlow achieves the performance-cost Pareto frontier compared to existing efficiency optimization methods.

[Arxiv](https://arxiv.org/abs/2504.08378)