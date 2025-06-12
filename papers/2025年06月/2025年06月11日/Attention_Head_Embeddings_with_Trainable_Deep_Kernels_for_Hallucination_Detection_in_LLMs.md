# LLM幻觉检测的可训练深度核注意力头嵌入方法

发布时间：2025年06月11日

`LLM理论` `人工智能` `模型优化`

> Attention Head Embeddings with Trainable Deep Kernels for Hallucination Detection in LLMs

# 摘要

> 我们提出了一种新颖的方法，通过分析提示与响应的隐藏状态分布之间的概率分歧来检测大型语言模型 (LLMs) 中的幻觉现象。令人意外的是，我们发现幻觉生成的回复与提示之间的偏差往往小于基于事实的回复，这表明幻觉通常源于表面的改写而非实质性的推理。基于这一发现，我们提出了一种基于模型内在的检测方法，利用分布距离作为原理性的幻觉评分标准，从而避免了对外部知识或辅助模型的依赖。为了提高敏感度，我们采用了深度学习的可训练核函数，使其能够自动适应并捕捉分布间细微的几何差异。我们的方法在多个基准测试中超越了现有基线，展现了最先进的性能。即使不进行核函数训练，该方法仍保持竞争力，为幻觉检测提供了一种强大且可扩展的解决方案。

> We present a novel approach for detecting hallucinations in large language models (LLMs) by analyzing the probabilistic divergence between prompt and response hidden-state distributions. Counterintuitively, we find that hallucinated responses exhibit smaller deviations from their prompts compared to grounded responses, suggesting that hallucinations often arise from superficial rephrasing rather than substantive reasoning. Leveraging this insight, we propose a model-intrinsic detection method that uses distributional distances as principled hallucination scores, eliminating the need for external knowledge or auxiliary models. To enhance sensitivity, we employ deep learnable kernels that automatically adapt to capture nuanced geometric differences between distributions. Our approach outperforms existing baselines, demonstrating state-of-the-art performance on several benchmarks. The method remains competitive even without kernel training, offering a robust, scalable solution for hallucination detection.

[Arxiv](https://arxiv.org/abs/2506.09886)