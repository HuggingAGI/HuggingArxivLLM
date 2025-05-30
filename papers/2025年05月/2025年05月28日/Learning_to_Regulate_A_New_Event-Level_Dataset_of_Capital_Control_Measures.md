# 学习调控：资本控制措施的新型事件级别数据集

发布时间：2025年05月28日

`LLM应用` `经济学` `政策分析`

> Learning to Regulate: A New Event-Level Dataset of Capital Control Measures

# 摘要

> 我们利用基于提示的大语言模型（LLMs）构建了一个全新的事件级别资本管制措施（CCM）数据集，覆盖了196个国家，时间跨度从1999年到2023年。该数据集支持基于丰富政策属性的事件研究分析和跨国比较，包括行动类型、强度、方向、实施主体以及其他多维特征。通过使用GPT-4.1的两步提示框架，我们从国际货币基金组织的《外汇安排与限制年报》（AREAER）中提取了结构化信息，得到了5,198个资本管制事件，每个事件都附有27个标注字段和相应的模型推理。其次，为了实现实时分类并扩展到外部来源，我们对开源的Meta Llama 3.1-8B模型进行了微调，命名为CCM-Llama，该模型基于AREAER变更日志和最终状态报告进行训练。该模型在类别分类中达到了90.09%的准确率，在状态预测中达到了99.55%的准确率。最后，我们将CCM数据集应用于实证研究：对中国、澳大利亚和美国的事件研究。结果显示，入境资本管制措施在一个月内显著减少了资金流入，而限制性政策往往比自由化政策产生更强的影响，不同国家之间存在显著的异质性。我们的工作通过提供一个新颖的高频政策数据集和一个可复制的框架，从多样且不断变化的信息来源中对资本管制事件进行自动分类，为经济学领域中使用LLMs的文献做出了贡献。

> We construct a novel event-level Capital Control Measures (CCM) dataset covering 196 countries from 1999 to 2023 by leveraging prompt-based large language models (LLMs). The dataset enables event study analysis and cross-country comparisons based on rich policy attributes, including action type, intensity, direction, implementing entity, and other multidimensional characteristics. Using a two-step prompt framework with GPT-4.1, we extract structured information from the IMF's Annual Report on Exchange Arrangements and Exchange Restrictions (AREAER), resulting in 5,198 capital control events with 27 annotated fields and corresponding model reasoning. Secondly, to facilitate real-time classification and extension to external sources, we fine-tune an open-source Meta Llama 3.1-8B model, named CCM-Llama, trained on AREAER change logs and final status reports. The model achieves 90.09\% accuracy in category classification and 99.55\% in status prediction. Finally, we apply the CCM dataset in an empirical application: an event study on China, Australia, and the US. The results show that inward capital control measures significantly reduce fund inflows within one month, and restrictive policies tend to have stronger effects than liberalizing ones, with notable heterogeneity across countries. Our work contributes to the growing literature on the use of LLMs in economics by providing both a novel high-frequency policy dataset and a replicable framework for automated classification of capital control events from diverse and evolving information sources.

[Arxiv](https://arxiv.org/abs/2505.23025)