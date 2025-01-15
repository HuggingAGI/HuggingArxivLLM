# 揭秘代码生成中大型语言模型的提供者偏见

发布时间：2025年01月14日

`LLM应用

理由：这篇论文主要研究了大型语言模型（LLMs）在代码生成中的提供商偏见问题，并开发了一套系统方法来量化这种偏见。研究涉及对多个顶尖模型生成的响应进行分析，并评估了去偏见提示技术的效果。这些内容属于LLM在实际应用中的表现和问题，因此归类为“LLM应用”。` `推荐系统` `云计算`

> Unveiling Provider Bias in Large Language Models for Code Generation

# 摘要

> # 摘要
大型语言模型（LLMs）已成为新一代推荐引擎，在代码生成等领域超越了传统方法。我们的研究揭示了一种新型的提供商偏见：在没有明确提示的情况下，LLMs在推荐中会系统性偏好特定提供商（如偏爱Google Cloud而非Microsoft Azure）。这种偏见不仅可能助长数字垄断，影响市场平衡，还可能误导用户，违背其期望。本文首次对LLM代码生成中的提供商偏见进行了全面实证研究。我们开发了一套系统方法，包括自动化数据集生成管道，涵盖6类编码任务和30个真实场景。通过对七个顶尖模型生成的60万条响应（约5亿token，计算成本超5000美元）的分析，我们量化了提供商偏见，并评估了七种去偏见提示技术的效果。研究发现，LLMs显著偏好Google和Amazon的服务，甚至会在用户未请求时自主修改代码以纳入其偏爱的提供商。此外，对话推荐与代码实现中的提供商选择存在差异。完整数据集与分析结果已公开。

> Large Language Models (LLMs) have emerged as the new recommendation engines, outperforming traditional methods in both capability and scope, particularly in code generation applications. Our research reveals a novel provider bias in LLMs, namely without explicit input prompts, these models show systematic preferences for services from specific providers in their recommendations (e.g., favoring Google Cloud over Microsoft Azure). This bias holds significant implications for market dynamics and societal equilibrium, potentially promoting digital monopolies. It may also deceive users and violate their expectations, leading to various consequences. This paper presents the first comprehensive empirical study of provider bias in LLM code generation. We develop a systematic methodology encompassing an automated pipeline for dataset generation, incorporating 6 distinct coding task categories and 30 real-world application scenarios. Our analysis encompasses over 600,000 LLM-generated responses across seven state-of-the-art models, utilizing approximately 500 million tokens (equivalent to \$5,000+ in computational costs). The study evaluates both the generated code snippets and their embedded service provider selections to quantify provider bias. Additionally, we conduct a comparative analysis of seven debiasing prompting techniques to assess their efficacy in mitigating these biases. Our findings demonstrate that LLMs exhibit significant provider preferences, predominantly favoring services from Google and Amazon, and can autonomously modify input code to incorporate their preferred providers without users' requests. Notably, we observe discrepancies between providers recommended in conversational contexts versus those implemented in generated code. The complete dataset and analysis results are available in our repository.

[Arxiv](https://arxiv.org/abs/2501.07849)