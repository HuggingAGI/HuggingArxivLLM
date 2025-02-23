# # 增强多模态基础模型的认知与可解释性：自合成数据的助力
借助自合成数据，我们成功提升了多模态基础模型的认知与可解释性，为模型性能的全面提升奠定了坚实基础。

发布时间：2025年02月19日

`LLM应用` `计算机视觉`

> Enhancing Cognition and Explainability of Multimodal Foundation Models with Self-Synthesized Data

# 摘要

> 大型多模态模型（LMMs）在视觉任务中表现卓越，但在细粒度视觉推理方面仍存在不足，难以识别特定领域目标并提供合理预测解释。为解决这一问题，我们提出了一种创新的视觉拒绝采样框架，通过自合成数据提升LMMs的认知与可解释性。具体而言，视觉微调需要图像、查询和目标答案。我们的方法首先合成包含人类可验证视觉特征的可解释答案，这些特征基于专家定义的概念，经过严格筛选以确保与图像内容一致。每次微调后，我们采用无奖励模型的过滤机制，挑选最优的可解释答案用于下一轮调优。通过数据合成与微调的迭代过程，模型逐步提升生成准确合理解释的能力。实验结果表明，我们的方法显著提高了专业视觉分类任务的准确性和可解释性。

> Large multimodal models (LMMs) have shown impressive capabilities in a wide range of visual tasks. However, they often struggle with fine-grained visual reasoning, failing to identify domain-specific objectives and provide justifiable explanations for their predictions. To address this, we propose a novel visual rejection sampling framework to improve the cognition and explainability of LMMs using self-synthesized data. Specifically, visual fine-tuning requires images, queries, and target answers. Our approach begins by synthesizing interpretable answers that include human-verifiable visual features. These features are based on expert-defined concepts, carefully selected based on their alignment with the image content. After each round of fine-tuning, we apply a reward model-free filtering mechanism to select the highest-quality interpretable answers for the next round of tuning. This iterative process of data synthesis and fine-tuning progressively improves the model's ability to generate accurate and reasonable explanations. Experimental results demonstrate the effectiveness of our method in improving both the accuracy and explainability of specialized visual classification tasks.

[Arxiv](https://arxiv.org/abs/2502.14044)