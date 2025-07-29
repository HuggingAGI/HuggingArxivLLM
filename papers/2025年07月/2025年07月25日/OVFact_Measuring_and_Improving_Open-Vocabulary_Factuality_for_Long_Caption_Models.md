# OVFact：评测与优化长描述模型的开放词汇事实性

发布时间：2025年07月25日

`LLM应用` `计算机视觉` `数据科学`

> OVFact: Measuring and Improving Open-Vocabulary Factuality for Long Caption Models

# 摘要

> 大型视觉语言模型（VLMs）在生成长且事实性的描述时常常力不从心。然而，传统的幻觉和事实性评估指标并不适用于更长、更多样化的描述，尤其是在缺乏真实标注的情况下。我们提出了OV-Fact，这是一种无需依赖人工标注的新方法，通过开放词汇视觉定位和工具验证来评估长描述的事实性。与人工判断的吻合度相比，我们的方法显著提升，同时在同一指标中兼顾描述性（召回率）和事实准确性。此外，与以往的指标不同，我们的无参考方法设计为基于事实性的数据过滤开辟了新应用。我们发现，使用OVFact过滤后的大型噪声预训练集（规模缩小2.5-5倍）进行训练的模型，在多个下游长描述基准测试中，事实准确性得到了显著提升，同时保持了描述的丰富性。

> Large vision-language models (VLMs) often struggle to generate long and factual captions. However, traditional measures for hallucination and factuality are not well suited for evaluating longer, more diverse captions and in settings where ground-truth human-annotated captions are unavailable. We introduce OV-Fact, a novel method for measuring caption factuality of long captions that leverages open-vocabulary visual grounding and tool-based verification without depending on human annotations. Our method improves agreement with human judgments and captures both caption descriptiveness (recall) and factual precision in the same metric. Furthermore, unlike previous metrics, our reference-free method design enables new applications towards factuality-based data filtering. We observe models trained on an OVFact-filtered (2.5-5x less) subset of a large-scale, noisy (VLM-generated) pretraining set meaningfully improve factuality precision without sacrificing caption descriptiveness across a range of downstream long caption benchmarks.

[Arxiv](https://arxiv.org/abs/2507.19262)