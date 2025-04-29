# # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年04月27日

`LLM应用` `软件工程`

> Do Automatic Comment Generation Techniques Fall Short? Exploring the Influence of Method Dependencies on Code Understanding

# 摘要

> 方法级注释对提升代码理解力和软件维护至关重要。随着大型语言模型（LLMs）的进步，自动生成注释已成为研究热点。然而，现有方法往往忽视方法间的依赖关系，这影响了注释质量和代码可理解性。本研究深入探讨了依赖方法在软件项目中的普遍性和影响，并提出了一种基于依赖感知的注释生成方法。通过对10个流行Java项目的分析，我们发现依赖方法占总数的69.25%，且相较于独立方法，它们具有更高的参与度和变更倾向性。在44.8万个依赖方法和19.9万个独立方法的对比中，我们发现CodeT5+、CodeBERT等最先进的微调模型难以生成全面注释，ASAP等基于LLMs的方法也面临类似挑战。为解决这一问题，我们提出了HelpCOM——一种新型依赖感知技术，通过整合辅助方法信息，显著提升了注释的清晰度、全面性和相关性。实验结果显示，HelpCOM在句法（如BLEU）、语义（如SentenceBERT）和基于LLMs的评估指标上，比基线方法高出5.6%至50.4%。通过对156名软件从业者的调查，我们发现HelpCOM显著提升了涉及依赖方法的代码可理解性，这表明其在增强代码文档、可维护性和开发人员生产力方面具有巨大潜力，特别是在大规模系统中。

> Method-level comments are critical for improving code comprehension and supporting software maintenance. With advancements in large language models (LLMs), automated comment generation has become a major research focus. However, existing approaches often overlook method dependencies, where one method relies on or calls others, affecting comment quality and code understandability. This study investigates the prevalence and impact of dependent methods in software projects and introduces a dependency-aware approach for method-level comment generation. Analyzing a dataset of 10 popular Java GitHub projects, we found that dependent methods account for 69.25% of all methods and exhibit higher engagement and change proneness compared to independent methods. Across 448K dependent and 199K independent methods, we observed that state-of-the-art fine-tuned models (e.g., CodeT5+, CodeBERT) struggle to generate comprehensive comments for dependent methods, a trend also reflected in LLM-based approaches like ASAP. To address this, we propose HelpCOM, a novel dependency-aware technique that incorporates helper method information to improve comment clarity, comprehensiveness, and relevance. Experiments show that HelpCOM outperforms baseline methods by 5.6% to 50.4% across syntactic (e.g., BLEU), semantic (e.g., SentenceBERT), and LLM-based evaluation metrics. A survey of 156 software practitioners further confirms that HelpCOM significantly improves the comprehensibility of code involving dependent methods, highlighting its potential to enhance documentation, maintainability, and developer productivity in large-scale systems.

[Arxiv](https://arxiv.org/abs/2504.19459)