# 小规模数据投毒是否会进一步加剧大型语言模型中的方言相关偏见？

发布时间：2025年07月25日

`LLM应用

理由：这篇论文探讨了大型语言模型在处理不同方言时的偏见问题，特别是数据投毒如何加剧这种偏见。它属于模型应用中的伦理和社会影响问题，因此归类为LLM应用。` `人工智能` `社会公平`

> Can Small-Scale Data Poisoning Exacerbate Dialect-Linked Biases in Large Language Models?

# 摘要

> 尽管大型语言模型（LLMs）的设计不断改进，旨在促进包容性和平衡的回应，但这些系统仍然容易编码和放大社会偏见。本研究聚焦于方言变体，特别是非洲裔美国英语（AAVE）与标准美式英语（SAE），探讨它们如何与数据投毒相互作用，进而影响输出毒性。通过实验，我们发现即使是轻微的数据投毒暴露，也会显著增加AAVE输入的毒性，而对SAE则相对影响较小。大型模型表现出更显著的毒性放大效应，表明模型规模越大，对偏见的敏感性越高。进一步评估中，我们采用了GPT-4o作为公平性审计工具，该工具识别出与AAVE输入相关联的有害刻板印象模式，包括攻击性、犯罪倾向和智力低下的描绘，且这些模式与AAVE输入的关联程度远高于其他方言。这些发现突显了数据投毒与方言偏见的叠加效应，并强调了在模型开发过程中，需要进行方言敏感性评估、针对性的去偏干预以及社会负责任的训练协议的重要性。

> Despite the ongoing improvements in the design of large language models (LLMs) to foster inclusion and balanced responses, these systems remain susceptible to encoding and amplifying social biases. This study examines how dialectal variation, specifically African American Vernacular English (AAVE) versus Standard American English (SAE), interacts with data poisoning to influence toxicity in outputs. Using both small- and medium-scale LLaMA models, we show that even minimal exposure to poisoned data significantly increases toxicity for AAVE inputs, while it remains comparatively unaffected for SAE. Larger models exhibit a more significant amplification effect which suggests heightened susceptibility with scale. To further assess these disparities, we employed GPT-4o as a fairness auditor, which identified harmful stereotypical patterns disproportionately tied to AAVE inputs, including portrayals of aggression, criminality, and intellectual inferiority. These findings underscore the compounding impact of data poisoning and dialectal bias and emphasize the need for dialect-aware evaluation, targeted debiasing interventions, and socially responsible training protocols during development.

[Arxiv](https://arxiv.org/abs/2507.19195)