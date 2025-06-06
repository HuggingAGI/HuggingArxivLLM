# SafeSteer：可解释的安全引导与拒绝-规避机制在LLMs中的应用

发布时间：2025年05月31日

`LLM应用` `内容安全`

> SafeSteer: Interpretable Safety Steering with Refusal-Evasion in LLMs

# 摘要

> 微调大型语言模型（LLMs）以适应不断变化的安全政策既昂贵又不切实际。机制可解释性通过潜在激活引导在推理时实现控制，然而，其在精确、可定制的安全调整方面的潜力尚未被充分挖掘。本文研究了一种名为SafeSteer的方法，用于引导LLMs的输出，具体方法包括：(i) 利用类别特定的引导向量实现更精确的控制，(ii) 采用一种简单且无梯度的无监督方法，增强安全引导的同时保持文本质量、主题相关性，并避免明确拒绝，(iii) 在此过程中无需强制要求对比配对安全数据。我们还强调，我们的方法简单而有效，与近期研究表明简单技术在激活引导中往往优于复杂方法的观点相契合。我们在多种LLMs、数据集和风险类别上展示了我们方法的有效性，证明了其提供精确控制、防止 blanket refusals 并引导模型生成安全内容的能力，同时保持主题相关性。

> Fine-tuning large language models (LLMs) to adapt to evolving safety policies is costly and impractical. Mechanistic interpretability enables inference-time control through latent activation steering, yet its potential for precise, customizable safety adjustments remains largely untapped. This paper investigates an approach called SafeSteer for guiding the outputs of LLMs by: (i) leveraging category-specific steering vectors for more precise control, (ii) employing a simple, gradient-free unsupervised method to enhance safety steering while preserving text quality, topic relevance, and without explicit refusal, and (iii) accomplishing this without a hard requirement of contrastive pairwise safe data. We also highlight that our method, being simple and effective, aligns with recent studies suggesting that simple techniques often outperform more complex ones in activation steering. We showcase the effectiveness of our approach across various LLMs, datasets, and risk categories, demonstrating its ability to provide precise control, prevent blanket refusals, and guide models toward generating safe content while maintaining topic relevance.

[Arxiv](https://arxiv.org/abs/2506.04250)