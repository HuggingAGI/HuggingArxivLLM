# <翻译失败>

发布时间：2025年06月05日

`LLM理论` `计算机科学` `机器学习`

> Conformal Prediction Adaptive to Unknown Subpopulation Shifts

# 摘要

> 合式预测（Conformal prediction）被广泛用于为黑箱机器学习模型配备不确定性量化，同时享有正式的覆盖率保证。然而，这些保证通常在存在分布偏移（distribution shifts）时失效，即测试时的数据分布与训练（或校准）分布不一致。在本研究中，我们专注于子群体偏移（subpopulation shifts）的情况，即测试环境中的子群体混合与校准数据相比未知且不同。我们提出了一种新的方法，能够证明将合式预测适应此类偏移，确保有效覆盖率，而无需明确了解子群体结构。我们的算法可扩展到高维设置，并在现实的机器学习任务中表现良好。在视觉（使用视觉变压器模型）和语言（使用大型语言模型）基准上的大量实验表明，我们的方法在标准合式预测失效的情况下，能够可靠地维持覆盖率并控制风险。

> Conformal prediction is widely used to equip black-box machine learning models with uncertainty quantification enjoying formal coverage guarantees. However, these guarantees typically break down in the presence of distribution shifts, where the data distribution at test time differs from the training (or calibration-time) distribution. In this work, we address subpopulation shifts, where the test environment exhibits an unknown and differing mixture of subpopulations compared to the calibration data. We propose new methods that provably adapt conformal prediction to such shifts, ensuring valid coverage without requiring explicit knowledge of subpopulation structure. Our algorithms scale to high-dimensional settings and perform effectively in realistic machine learning tasks. Extensive experiments on vision (with vision transformers) and language (with large language models) benchmarks demonstrate that our methods reliably maintain coverage and controls risk in scenarios where standard conformal prediction fails.

[Arxiv](https://arxiv.org/abs/2506.05583)