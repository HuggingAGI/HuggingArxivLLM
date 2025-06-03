# CVC：大规模中文价值观规则语料库，助力大型语言模型价值对齐

发布时间：2025年06月02日

`LLM应用` `人工智能`

> CVC: A Large-Scale Chinese Value Rule Corpus for Value Alignment of Large Language Models

# 摘要

> 确保大型语言模型 (LLMs) 与主流人类价值观和伦理规范保持一致，是实现人工智能安全与可持续发展的关键。当前的价值评估与对齐方法受限于西方文化偏见和依赖非本土规则的不完整框架；此外，缺乏可扩展的基于规则的情景生成方法，导致评估在不同文化背景下成本高昂且效果不足。为解决这些挑战，我们提出了一种基于核心中国价值观的分层价值框架，涵盖三个主要维度、12个核心价值观和50个衍生价值观。基于此框架，我们构建了一个包含超过25万条通过人工标注增强和扩展的价值规则的大型中文价值观语料库 (CVC)。实验结果表明，CVC引导的情景在价值边界和内容多样性方面表现更优。在对代孕、自杀等六个敏感主题的评估中，七种主流 LLMs 在70.5%以上的情况下更倾向于选择 CVC 生成的选项，而五位中国人工标注员与 CVC 的一致性达到87.5%，证实了其普遍性、文化相关性和与中国价值观的高度对齐。此外，我们构建了40万个基于规则的道德困境场景，客观捕捉了在17种 LLM 中价值优先级冲突中的细微差异。我们的工作建立了一个具有中国特色的、适应文化背景的价值评估与对齐综合基准框架。所有数据均可在 https://huggingface.co/datasets/Beijing-AISI/CVC 获取，代码可在 https://github.com/Beijing-AISI/CVC 获取。

> Ensuring that Large Language Models (LLMs) align with mainstream human values and ethical norms is crucial for the safe and sustainable development of AI. Current value evaluation and alignment are constrained by Western cultural bias and incomplete domestic frameworks reliant on non-native rules; furthermore, the lack of scalable, rule-driven scenario generation methods makes evaluations costly and inadequate across diverse cultural contexts. To address these challenges, we propose a hierarchical value framework grounded in core Chinese values, encompassing three main dimensions, 12 core values, and 50 derived values. Based on this framework, we construct a large-scale Chinese Values Corpus (CVC) containing over 250,000 value rules enhanced and expanded through human annotation. Experimental results show that CVC-guided scenarios outperform direct generation ones in value boundaries and content diversity. In the evaluation across six sensitive themes (e.g., surrogacy, suicide), seven mainstream LLMs preferred CVC-generated options in over 70.5% of cases, while five Chinese human annotators showed an 87.5% alignment with CVC, confirming its universality, cultural relevance, and strong alignment with Chinese values. Additionally, we construct 400,000 rule-based moral dilemma scenarios that objectively capture nuanced distinctions in conflicting value prioritization across 17 LLMs. Our work establishes a culturally-adaptive benchmarking framework for comprehensive value evaluation and alignment, representing Chinese characteristics. All data are available at https://huggingface.co/datasets/Beijing-AISI/CVC, and the code is available at https://github.com/Beijing-AISI/CVC.

[Arxiv](https://arxiv.org/abs/2506.01495)