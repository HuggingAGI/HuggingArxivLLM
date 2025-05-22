# # 可靠的决策支持：基于LLMs的二元文本分类应用一致性评估框架
构建可靠决策支持系统：基于LLMs的二元文本分类应用一致性评估框架

发布时间：2025年05月20日

`LLM应用

LLM应用` `企业应用`

> Reliable Decision Support with LLMs: A Framework for Evaluating Consistency in Binary Text Classification Applications

# 摘要

> 本研究提出了一种评估大型语言模型 (LLM) 二元文本分类一致性的框架，旨在解决现有可靠性评估方法的缺失问题。我们借鉴心理测量学原理，确定了样本量要求，制定了无效响应的评估指标，并对内部和外部评分者一致性进行了评估。我们的案例研究涵盖了 14 个 LLM（包括 claude-3-7-sonnet、gpt-4o、deepseek-r1、gemma3、llama3.2、phi4 和 command-r-plus），在 1,350 篇文章上对每个模型进行了五次重复测试。结果显示，所有模型在内部一致性上表现优异，90-98% 的示例达到了完美一致。来自同一模型家族的昂贵模型和经济模型之间差异微乎其微。与 StockNewsAPI 标签进行验证时，模型表现强劲（准确率 0.76-0.88），其中较小的模型如 gemma3:1B、llama3.2:3B 和 claude-3-5-haiku 表现优于更大规模的同类模型。然而，所有模型在预测实际市场走势时表现与随机猜测无异，这表明任务本身存在限制，而非模型能力不足。本研究的框架为 LLM 选择、样本量规划和可靠性评估提供了系统性指导，帮助企业优化资源以提升分类任务效果。

> This study introduces a framework for evaluating consistency in large language model (LLM) binary text classification, addressing the lack of established reliability assessment methods. Adapting psychometric principles, we determine sample size requirements, develop metrics for invalid responses, and evaluate intra- and inter-rater reliability. Our case study examines financial news sentiment classification across 14 LLMs (including claude-3-7-sonnet, gpt-4o, deepseek-r1, gemma3, llama3.2, phi4, and command-r-plus), with five replicates per model on 1,350 articles. Models demonstrated high intra-rater consistency, achieving perfect agreement on 90-98% of examples, with minimal differences between expensive and economical models from the same families. When validated against StockNewsAPI labels, models achieved strong performance (accuracy 0.76-0.88), with smaller models like gemma3:1B, llama3.2:3B, and claude-3-5-haiku outperforming larger counterparts. All models performed at chance when predicting actual market movements, indicating task constraints rather than model limitations. Our framework provides systematic guidance for LLM selection, sample size planning, and reliability assessment, enabling organizations to optimize resources for classification tasks.

[Arxiv](https://arxiv.org/abs/2505.14918)