# 高效样本的大型语言模型优化：重置重放

发布时间：2025年08月08日

`LLM理论` `人工智能` `机器学习`

> Sample-efficient LLM Optimization with Reset Replay

# 摘要

> 大型语言模型（LLMs）的后训练优化，尤其是通过强化学习（RL）和偏好优化方法，取得了突破性进展，为提升模型推理能力注入了强劲动力。然而，这些方法在实践中仍面临两大瓶颈：样本效率低下和首因偏差问题，这些问题会导致模型过度依赖初始经验，从而影响学习效果和策略质量。为了解决这些难题，我们推出了一种全新的优化方案——带有重放重置机制的LLM优化方法（LoRR）。这一通用插件能够显著提升任何基于偏好的优化框架的样本效率。LoRR的核心优势在于其创新的高重放训练机制，通过充分利用每一批数据，最大化训练效能。针对高重放训练中可能存在的过拟合风险，LoRR特别设计了周期性重置策略，结合初始数据的复用，有效保持了模型的可塑性。此外，LoRR还采用了混合优化目标，将监督微调（SFT）与偏好损失相结合，进一步挖掘数据价值。通过大量实验证明，LoRR在数学推理和一般推理任务中为各类偏好优化方法带来了显著性能提升。特别是在解决复杂数学问题时，搭载LoRR的迭代式DPO方法表现卓越，超越了一些计算密集型的RL算法。这一成果充分表明，LoRR为LLM微调提供了一种高效、实用且效果显著的新范式，能够从有限数据中释放出更大的性能潜力。

> Recent advancements in post-training Large Language Models (LLMs), particularly through Reinforcement Learning (RL) and preference optimization methods, are key drivers for enhancing their reasoning capabilities. However, these methods are often plagued by low sample efficiency and a susceptibility to primacy bias, where overfitting to initial experiences degrades policy quality and damages the learning process. To address these challenges, we introduce LLM optimization with Reset Replay (LoRR), a general and powerful plugin designed to enhance sample efficiency in any preference-based optimization framework. LoRR core mechanism enables training at a high replay number, maximizing the utility of each collected data batch. To counteract the risk of overfitting inherent in high-replay training, LoRR incorporates a periodic reset strategy with reusing initial data, which preserves network plasticity. Furthermore, it leverages a hybrid optimization objective, combining supervised fine-tuning (SFT) and preference-based losses to further bolster data exploitation. Our extensive experiments demonstrate that LoRR significantly boosts the performance of various preference optimization methods on both mathematical and general reasoning benchmarks. Notably, an iterative DPO approach augmented with LoRR achieves comparable performance on challenging math tasks, outperforming some complex and computationally intensive RL-based algorithms. These findings highlight that LoRR offers a practical, sample-efficient, and highly effective paradigm for LLM finetuning, unlocking greater performance from limited data.

[Arxiv](https://arxiv.org/abs/2508.06412)