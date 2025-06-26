# NSFW分类器引导的提示清理技术，实现安全文本到图像生成

发布时间：2025年06月23日

`其他` `图像生成` `内容安全`

> NSFW-Classifier Guided Prompt Sanitization for Safe Text-to-Image Generation

# 摘要

> 文本到图像（T2I）模型（如Stable Diffusion）的快速发展显著提升了其根据文本描述生成图像的能力。然而，这种技术进步也伴随着滥用风险的增加，包括生成色情、暴力、歧视等有害内容，这与T2I技术的伦理目标背道而驰，阻碍了其可持续发展。受大型语言模型中通过细微提示修改绕过限制的"越狱"攻击启发，我们提出了一种名为NSFW-Classifier引导提示净化（PromptSan）的新方法，可在不改变模型架构或降低生成能力的情况下消除有害提示。PromptSan包含两种变体：PromptSan-Modify通过文本NSFW分类器迭代识别并替换输入提示中的有害令牌；PromptSan-Suffix则通过训练优化的后缀令牌序列来中和有害意图，同时通过文本和图像NSFW分类器的检查。大量实验证明，PromptSan在减少有害内容生成方面实现了跨多指标的最先进性能，成功实现了安全性和可用性的有效平衡。

> The rapid advancement of text-to-image (T2I) models, such as Stable Diffusion, has enhanced their capability to synthesize images from textual prompts. However, this progress also raises significant risks of misuse, including the generation of harmful content (e.g., pornography, violence, discrimination), which contradicts the ethical goals of T2I technology and hinders its sustainable development. Inspired by "jailbreak" attacks in large language models, which bypass restrictions through subtle prompt modifications, this paper proposes NSFW-Classifier Guided Prompt Sanitization (PromptSan), a novel approach to detoxify harmful prompts without altering model architecture or degrading generation capability. PromptSan includes two variants: PromptSan-Modify, which iteratively identifies and replaces harmful tokens in input prompts using text NSFW classifiers during inference, and PromptSan-Suffix, which trains an optimized suffix token sequence to neutralize harmful intent while passing both text and image NSFW classifier checks. Extensive experiments demonstrate that PromptSan achieves state-of-the-art performance in reducing harmful content generation across multiple metrics, effectively balancing safety and usability.

[Arxiv](https://arxiv.org/abs/2506.18325)