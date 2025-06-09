# 基于大型语言模型的多源证据模糊聚合实现零样本事件因果识别

发布时间：2025年06月05日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLMs）进行事件因果识别，并提出了一种新的零样本框架MEFA，以解决因果幻觉的问题。它主要关注于LLMs在因果识别中的应用和改进，属于LLM的应用层面。` `因果推理`

> Zero-Shot Event Causality Identification via Multi-source Evidence Fuzzy Aggregation with Large Language Models

# 摘要

> 事件因果识别（ECI）致力于在文本中发现事件间的因果关系。现有模型多依赖监督学习，面临对大规模标注数据的强依赖问题。虽然大型语言模型（LLMs）支持零样本因果识别，但它们容易产生因果幻觉，错误建立虚假因果关系。为解决这一难题，我们提出了基于多源证据模糊聚合的新型零样本框架MEFA。该框架首先将因果推理分解为时间性判定、必要性分析和充分性验证三大核心任务，并辅以三项辅助任务。通过精心设计的提示，引导LLMs生成不确定响应与确定性输出。最终，量化子任务响应，运用模糊聚合整合证据，实现因果评分与判定。在三个基准数据集上的实验表明，MEFA在F1值和精确度上分别比第二好的无监督基线高出6.2%和9.3%，同时大幅降低了幻觉错误。深入分析证实了任务分解的有效性与模糊聚合的优越性。

> Event Causality Identification (ECI) aims to detect causal relationships between events in textual contexts. Existing ECI models predominantly rely on supervised methodologies, suffering from dependence on large-scale annotated data. Although Large Language Models (LLMs) enable zero-shot ECI, they are prone to causal hallucination-erroneously establishing spurious causal links. To address these challenges, we propose MEFA, a novel zero-shot framework based on Multi-source Evidence Fuzzy Aggregation. First, we decompose causality reasoning into three main tasks (temporality determination, necessity analysis, and sufficiency verification) complemented by three auxiliary tasks. Second, leveraging meticulously designed prompts, we guide LLMs to generate uncertain responses and deterministic outputs. Finally, we quantify LLM's responses of sub-tasks and employ fuzzy aggregation to integrate these evidence for causality scoring and causality determination. Extensive experiments on three benchmarks demonstrate that MEFA outperforms second-best unsupervised baselines by 6.2% in F1-score and 9.3% in precision, while significantly reducing hallucination-induced errors. In-depth analysis verify the effectiveness of task decomposition and the superiority of fuzzy aggregation.

[Arxiv](https://arxiv.org/abs/2506.05675)