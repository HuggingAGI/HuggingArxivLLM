# ALN-P3: 用于自动驾驶的统一语言对齐感知、预测与规划

发布时间：2025年05月21日

`LLM应用` `自动驾驶` `人工智能`

> ALN-P3: Unified Language Alignment for Perception, Prediction, and Planning in Autonomous Driving

# 摘要

> 近期研究探索了将大型语言模型（LLMs）整合到端到端自动驾驶系统中，以增强其泛化能力和可解释性。然而，现有方法大多只能在驾驶性能或视觉语言推理中发挥优势，难以同时兼顾。本文提出了一种名为ALN-P3的统一协同蒸馏框架，通过在“快速”的视觉基础自动驾驶系统与“慢速”的语言驱动推理模块之间实现跨模态对齐，解决了这一难题。ALN-P3框架集成了三种创新的对齐机制：感知对齐（P1A）、预测对齐（P2A）和规划对齐（P3A），这些机制在完整的感知、预测和规划流程中显式地对齐视觉标记与相应的语言输出。所有对齐模块仅在训练阶段应用，不会增加推理阶段的额外计算成本。在nuScenes、Nu-X、TOD3Cap和nuScenes QA这四个具有挑战性的基准测试中进行的大量实验表明，ALN-P3显著提升了驾驶决策和语言推理能力，达到了目前最先进的水平。

> Recent advances have explored integrating large language models (LLMs) into end-to-end autonomous driving systems to enhance generalization and interpretability. However, most existing approaches are limited to either driving performance or vision-language reasoning, making it difficult to achieve both simultaneously. In this paper, we propose ALN-P3, a unified co-distillation framework that introduces cross-modal alignment between "fast" vision-based autonomous driving systems and "slow" language-driven reasoning modules. ALN-P3 incorporates three novel alignment mechanisms: Perception Alignment (P1A), Prediction Alignment (P2A), and Planning Alignment (P3A), which explicitly align visual tokens with corresponding linguistic outputs across the full perception, prediction, and planning stack. All alignment modules are applied only during training and incur no additional costs during inference. Extensive experiments on four challenging benchmarks-nuScenes, Nu-X, TOD3Cap, and nuScenes QA-demonstrate that ALN-P3 significantly improves both driving decisions and language reasoning, achieving state-of-the-art results.

[Arxiv](https://arxiv.org/abs/2505.15158)