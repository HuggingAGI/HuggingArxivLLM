# 利用噪声感知偏好优化消除多模态大型语言模型的偏见

发布时间：2025年03月23日

`LLM应用` `多模态` `大型语言模型`

> Debiasing Multimodal Large Language Models via Noise-Aware Preference Optimization

# 摘要

> 多模态大型语言模型在多种任务中表现优异，但常受模态偏见困扰。这一问题表现为模型过度依赖单一模态，忽视其他模态的关键信息，导致注意力偏差和生成不相关回应。本文提出采用偏好优化范式解决这一问题，包括构建无偏见的偏好优化数据集 RLAIFVBias，以及噪声感知的偏好优化算法。具体来说，我们通过引入扰动降低某些模态的信息量，构建数据集，迫使模型在生成负向响应时依赖特定模态。为应对自动构建数据时的噪声问题，我们在直接偏好优化中结合了噪声鲁棒的平均绝对误差和二元交叉熵，并通过负 Box Cox 变换，根据数据中评估的噪声水平动态调整算法的噪声鲁棒性。大量实验验证了我们的方法，不仅证明了其在缓解模态偏见方面的有效性，还展示了其在显著减少幻觉生成中的重要作用。

> Multimodal Large Language Models excel in various tasks, yet often struggle with modality bias, where the model tends to rely heavily on a single modality and overlook critical information in other modalities, which leads to incorrect focus and generating irrelevant responses. In this paper, we propose using the paradigm of preference optimization to solve the modality bias problem, including RLAIFVBias, a debiased preference optimization dataset, and a Noise Aware Preference Optimization algorithm. Specifically, we first construct the dataset by introducing perturbations to reduce the informational content of certain modalities, compelling the model to rely on a specific modality when generating negative responses. To address the inevitable noise in automatically constructed data, we combine the noise robust Mean Absolute Error with the Binary Cross Entropy in Direct Preference Optimization by a negative Box Cox transformation, and dynamically adjust the algorithm noise robustness based on the evaluated noise levels in the data. Extensive experiments validate our approach, demonstrating not only its effectiveness in mitigating modality bias but also its significant role in minimizing hallucinations.

[Arxiv](https://arxiv.org/abs/2503.17928)