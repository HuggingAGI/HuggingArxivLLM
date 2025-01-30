# 大型语言模型在单步与多步飞行轨迹预测中的应用

发布时间：2025年01月29日

`LLM应用

**理由**：这篇论文探讨了将大型语言模型（LLMs）应用于飞行轨迹预测这一具体任务，属于将LLMs应用于特定领域的实践研究，因此归类为LLM应用。` `时间序列预测`

> Large Language Models for Single-Step and Multi-Step Flight Trajectory Prediction

# 摘要

> # 飞行轨迹预测
飞行轨迹预测是航空领域的关键时间序列任务。尽管深度学习方法展现出巨大潜力，但大型语言模型（LLMs）在此领域的应用仍待深入探索。本研究创新性地将飞行轨迹预测转化为语言建模问题，首次将LLMs引入该领域。具体而言，我们从ADS-B飞行数据中提取飞机位置和状态特征，构建基于提示的数据集，将轨迹航点转化为语言标记。通过微调LLMs，模型得以学习复杂的时空模式，实现精准预测。实验表明，LLMs在单步和多步预测中均显著优于传统方法，其中LLaMA-3.1模型表现最佳。然而，LLMs的高推理延迟对实时应用构成挑战，亟需进一步研究以解决这一问题。

> Flight trajectory prediction is a critical time series task in aviation. While deep learning methods have shown significant promise, the application of large language models (LLMs) to this domain remains underexplored. This study pioneers the use of LLMs for flight trajectory prediction by reframing it as a language modeling problem. Specifically, We extract features representing the aircraft's position and status from ADS-B flight data to construct a prompt-based dataset, where trajectory waypoints are converted into language tokens. The dataset is then employed to fine-tune LLMs, enabling them to learn complex spatiotemporal patterns for accurate predictions. Comprehensive experiments demonstrate that LLMs achieve notable performance improvements in both single-step and multi-step predictions compared to traditional methods, with LLaMA-3.1 model achieving the highest overall accuracy. However, the high inference latency of LLMs poses a challenge for real-time applications, underscoring the need for further research in this promising direction.

[Arxiv](https://arxiv.org/abs/2501.17459)