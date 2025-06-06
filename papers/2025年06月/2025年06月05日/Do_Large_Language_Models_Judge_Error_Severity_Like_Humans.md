# 大型语言模型能否像人类一样评估错误的严重程度？

发布时间：2025年06月05日

`LLM应用` `计算机视觉`

> Do Large Language Models Judge Error Severity Like Humans?

# 摘要

> 大型语言模型（LLMs）在自然语言生成中越来越多地被用作自动评估器，但它们能否准确复制人类对错误严重性的判断仍存疑。本研究系统比较了人类与LLM对包含受控语义错误的图像描述的评估。我们扩展了van Miltenburg等人（2020年）的实验框架，将其应用于单模态（纯文本）和多模态（文本+图像）设置，评估了年龄、性别、服装类型和服装颜色四种错误类型。研究发现，人类对不同错误类型的严重性赋予了不同级别，视觉上下文显著放大了对颜色和类型错误的感知严重性。值得注意的是，大多数LLM对性别错误赋予低分，但对颜色错误却赋予了过高的分数，这与人类不同，人类认为这两种错误都很严重，但原因不同。这表明这些模型可能已经内化了影响性别判断的社会规范，但缺乏感知基础来模仿人类对颜色的敏感性，而这种敏感性是由不同的神经机制塑造的。在评估的LLM中，只有Doubao复制了人类对错误严重性的人类-like排序，但它无法像人类那样清晰地区分错误类型。令人惊讶的是，单模态LLM DeepSeek-V3在单模态和多模态条件下都实现了与人类判断的最高对齐，甚至超过了最先进的多模态模型。

> Large Language Models (LLMs) are increasingly used as automated evaluators in natural language generation, yet it remains unclear whether they can accurately replicate human judgments of error severity. In this study, we systematically compare human and LLM assessments of image descriptions containing controlled semantic errors. We extend the experimental framework of van Miltenburg et al. (2020) to both unimodal (text-only) and multimodal (text + image) settings, evaluating four error types: age, gender, clothing type, and clothing colour. Our findings reveal that humans assign varying levels of severity to different error types, with visual context significantly amplifying perceived severity for colour and type errors. Notably, most LLMs assign low scores to gender errors but disproportionately high scores to colour errors, unlike humans, who judge both as highly severe but for different reasons. This suggests that these models may have internalised social norms influencing gender judgments but lack the perceptual grounding to emulate human sensitivity to colour, which is shaped by distinct neural mechanisms. Only one of the evaluated LLMs, Doubao, replicates the human-like ranking of error severity, but it fails to distinguish between error types as clearly as humans. Surprisingly, DeepSeek-V3, a unimodal LLM, achieves the highest alignment with human judgments across both unimodal and multimodal conditions, outperforming even state-of-the-art multimodal models.

[Arxiv](https://arxiv.org/abs/2506.05142)