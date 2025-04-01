# 大型语言模型对医疗查询中用户驱动因素的敏感性分析

发布时间：2025年03月26日

`LLM应用` `人工智能`

> Susceptibility of Large Language Models to User-Driven Factors in Medical Queries

# 摘要

> 大型语言模型（LLMs）在医疗领域的应用日益广泛，但其可靠性受用户驱动因素显著影响，如问题表述方式和临床信息的完整性。本研究重点分析了误导性信息框架、信息来源权威性、模型角色设定以及关键临床细节遗漏对LLM诊断准确性和输出可靠性的影响。

我们设计了两项实验：一项通过引入不同坚定程度的误导性外部观点进行扰动测试，另一项通过移除特定类别的患者信息进行消融测试。基于MedQA和Medbullets公开数据集，我们对专有模型（GPT-4o、Claude 3.5 Sonnet、Claude 3.5 Haiku、Gemini 1.5 Pro、Gemini 1.5 Flash）和开源模型（LLaMA 3 8B、LLaMA 3 Med42 8B、DeepSeek R1 8B）进行了全面评估。

研究发现所有模型均易受用户驱动型误导信息影响，其中专有模型尤其易受坚定且权威性语言影响。坚定语气对准确性负面影响最大。在消融测试中，遗漏体格检查结果和实验室数据导致性能下降最为显著。尽管专有模型基础准确率更高，但其在面对误导信息时表现大幅下滑。

这些结果凸显了结构良好提示词和完整临床语境的重要性。用户应避免使用权威性误导信息框架，并提供完整临床细节，尤其是在处理复杂病例时。

> Large language models (LLMs) are increasingly used in healthcare, but their reliability is heavily influenced by user-driven factors such as question phrasing and the completeness of clinical information. In this study, we examined how misinformation framing, source authority, model persona, and omission of key clinical details affect the diagnostic accuracy and reliability of LLM outputs. We conducted two experiments: one introducing misleading external opinions with varying assertiveness (perturbation test), and another removing specific categories of patient information (ablation test). Using public datasets (MedQA and Medbullets), we evaluated proprietary models (GPT-4o, Claude 3.5 Sonnet, Claude 3.5 Haiku, Gemini 1.5 Pro, Gemini 1.5 Flash) and open-source models (LLaMA 3 8B, LLaMA 3 Med42 8B, DeepSeek R1 8B). All models were vulnerable to user-driven misinformation, with proprietary models especially affected by definitive and authoritative language. Assertive tone had the greatest negative impact on accuracy. In the ablation test, omitting physical exam findings and lab results caused the most significant performance drop. Although proprietary models had higher baseline accuracy, their performance declined sharply under misinformation. These results highlight the need for well-structured prompts and complete clinical context. Users should avoid authoritative framing of misinformation and provide full clinical details, especially for complex cases.

[Arxiv](https://arxiv.org/abs/2503.22746)