# LLMulator：面向输入自适应控制流数据流加速器的可泛化成本建模

发布时间：2025年08月25日

`LLM应用` `工业与制造`

> LLMulator: Generalizable Cost Modeling for Dataflow Accelerators with Input-Adaptive Control Flow

# 摘要

> 对于基于数据流的加速器而言，准确且快速的性能预测是高效硬件设计与设计空间探索的关键，但现有方法在跨架构、跨应用及处理输入相关控制流时泛化能力不足。为此，我们提出LLMulator——一种渐进式数值建模框架，它借助预训练大型语言模型（LLMs）的程序语义知识，实现了稳健的硬件与应用感知预测。该数值模型将性能值视作分类标记序列，可实现与范围无关的估计，并能对未见应用进行置信感知预测。针对输入相关控制流问题，我们引入基于强化学习的动态校准方法：相比静态模型，周期预测误差降低9.7%，且经过几次迭代后误差收敛至11.2%。在跨硬件泛化方面，我们设计了渐进式数据增强策略，通过生成涵盖多级数据流结构、内存参数及循环映射原语的多样化数据集，大幅提升了跨架构与跨配置的预测精度。

> Accurate and fast performance prediction for dataflow-based accelerators is vital for efficient hardware design and design space exploration, yet existing methods struggle to generalize across architectures, applications, and input-dependent control flows. We present LLMulator, a progressive numeric modeling framework leveraging the program semantic knowledge of pre-trained large language models (LLMs) for robust, hardware- and application-aware prediction. Our numeric model treats performance values as categorical token sequences, enabling range-agnostic estimates and confidence-aware predictions for unseen applications. To handle input-dependent control flows, we introduce a reinforcement learning-based dynamic calibration method, reducing cycle prediction error by 9.7% over static models and converging to 11.2% error after a few iterations. For cross-hardware generalization, we develop a progressive data augmentation strategy that generates diverse datasets covering multi-level dataflow structures, memory parameters, and loop mapping primitives, significantly boosting prediction accuracy across architectures and configurations.

[Arxiv](https://arxiv.org/abs/2508.17826)