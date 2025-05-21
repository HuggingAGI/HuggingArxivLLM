# 使用哥伦比亚-自杀严重程度评定量表评价推理型大型语言模型在自杀筛查中的应用

发布时间：2025年05月11日

`LLM应用` `公共卫生` `心理健康`

> Evaluating Reasoning LLMs for Suicide Screening with the Columbia-Suicide Severity Rating Scale

# 摘要

> 自杀预防仍是重要的公共卫生挑战。尽管像Reddit的r/SuicideWatch这样的在线平台为人们提供了表达自杀念头和寻求支持的空间，但大型语言模型（LLMs）的出现带来了新范式——人们可能开始向AI而非人类披露自杀意念。本研究评估了LLMs使用哥伦比亚-自杀严重程度评分量表（C-SSRS）进行自动化自杀风险评估的能力。我们测试了Claude、GPT、Mistral和LLaMA等六种模型在7个严重程度等级（0-6级）上的零-shot分类性能。结果显示，Claude和GPT与人工标注高度一致，Mistral的序数预测误差最低。大多数模型表现出序数敏感性，误分类通常发生在相邻级别间。我们进一步分析了混淆模式、误分类来源及伦理考量，强调了人类监督、透明度和谨慎部署的重要性。完整代码和补充材料可在https://github.com/av9ash/llm_cssrs_code获取。

> Suicide prevention remains a critical public health challenge. While online platforms such as Reddit's r/SuicideWatch have historically provided spaces for individuals to express suicidal thoughts and seek community support, the advent of large language models (LLMs) introduces a new paradigm-where individuals may begin disclosing ideation to AI systems instead of humans. This study evaluates the capability of LLMs to perform automated suicide risk assessment using the Columbia-Suicide Severity Rating Scale (C-SSRS). We assess the zero-shot performance of six models-including Claude, GPT, Mistral, and LLaMA-in classifying posts across a 7-point severity scale (Levels 0-6). Results indicate that Claude and GPT closely align with human annotations, while Mistral achieves the lowest ordinal prediction error. Most models exhibit ordinal sensitivity, with misclassifications typically occurring between adjacent severity levels. We further analyze confusion patterns, misclassification sources, and ethical considerations, underscoring the importance of human oversight, transparency, and cautious deployment. Full code and supplementary materials are available at https://github.com/av9ash/llm_cssrs_code.

[Arxiv](https://arxiv.org/abs/2505.13480)