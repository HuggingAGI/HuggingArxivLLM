# 大型语言模型 (LLMs) 真的能有多擅长处理表格数据？

发布时间：2025年05月12日

`LLM应用` `数据分析` `数据科学`

> How well do LLMs reason over tabular data, really?

# 摘要

> 大型语言模型（LLMs）在自然语言任务中表现出色，但在处理表格数据的推理能力方面，人们了解较少。此前的研究设计了评估策略，但这些策略未能很好地反映LLMs在处理表格查询时的真实性能。此外，我们对LLMs在处理现实世界中表格输入变化的鲁棒性了解有限。因此，我们提出问题：通用型LLMs能否真正推理表格数据？并聚焦于两个问题：1）通用型LLMs的表格推理能力是否能应对真实世界中表格输入的特点，2）如何才能现实地评估LLMs在分析性表格查询上的性能？基于最近的表格推理基准测试，我们首先揭示了其多项选择提示评估策略的不足，以及常用自由文本指标（如SacreBleu和BERT-score）的缺陷。我们表明，将LLMs作为评估者的过程能提供更可靠的表现见解，并揭示了LLMs在表格推理性能上的显著不足。接着，我们将表格输入扩展到反映实际中常见的三个特点：1）缺失值，2）重复实体，3）结构变化。实验表明，通用型LLMs的表格推理能力会受到这些变化的影响，强调了提升其在现实表格输入中鲁棒性的重要性。


> Large Language Models (LLMs) excel in natural language tasks, but less is known about their reasoning capabilities over tabular data. Prior analyses devise evaluation strategies that poorly reflect an LLM's realistic performance on tabular queries. Moreover, we have a limited understanding of the robustness of LLMs towards realistic variations in tabular inputs. Therefore, we ask: Can general-purpose LLMs reason over tabular data, really?, and focus on two questions 1) are tabular reasoning capabilities of general-purpose LLMs robust to real-world characteristics of tabular inputs, and 2) how can we realistically evaluate an LLM's performance on analytical tabular queries? Building on a recent tabular reasoning benchmark, we first surface shortcomings of its multiple-choice prompt evaluation strategy, as well as commonly used free-form text metrics such as SacreBleu and BERT-score. We show that an LLM-as-a-judge procedure yields more reliable performance insights and unveil a significant deficit in tabular reasoning performance of LLMs. We then extend the tabular inputs reflecting three common characteristics in practice: 1) missing values, 2) duplicate entities, and 3) structural variations. Experiments show that the tabular reasoning capabilities of general-purpose LLMs suffer from these variations, stressing the importance of improving their robustness for realistic tabular inputs.

[Arxiv](https://arxiv.org/abs/2505.07453)