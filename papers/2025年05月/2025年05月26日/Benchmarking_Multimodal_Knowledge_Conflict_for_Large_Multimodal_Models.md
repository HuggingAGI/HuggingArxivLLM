# # 评估大型多模态模型中的多模态知识冲突
评估大型多模态模型中的多模态知识冲突

发布时间：2025年05月26日

`RAG` `人工智能` `多模态系统`

> Benchmarking Multimodal Knowledge Conflict for Large Multimodal Models

# 摘要

> 大型多模态模型（LMMs）在处理多模态知识冲突时面临重大挑战，尤其是在检索增强生成（RAG）框架下，外部信息可能与模型内部知识产生矛盾，导致输出不可靠。然而，现有基准测试未能涵盖这些真实场景中的冲突问题。大多数研究仅关注内部记忆冲突，而上下文-记忆冲突和跨上下文冲突则未得到充分探索。此外，基于事实知识的评估常被忽视，现有数据集缺乏对冲突检测能力的深入研究。为了解决这一问题，我们提出了MMKC-Bench，一个专注于评估上下文-记忆和跨上下文场景下事实知识冲突的基准。MMKC-Bench包含三种类型的多模态知识冲突，覆盖了23种广泛类型，其中包括1,573个知识实例和3,381张图像，通过自动化管道收集并经人工验证。我们对三种代表性的LMMs系列在模型行为分析和冲突检测任务中进行了评估。研究发现，尽管当前LMMs能够识别知识冲突，但它们更倾向于依赖内部参数知识而非外部证据。我们希望MMKC-Bench能够推动多模态知识冲突研究，并提升多模态RAG系统的发展。源代码可在https://github.com/MLLMKCBENCH/MLLMKC获取。

> Large Multimodal Models(LMMs) face notable challenges when encountering multimodal knowledge conflicts, particularly under retrieval-augmented generation(RAG) frameworks where the contextual information from external sources may contradict the model's internal parametric knowledge, leading to unreliable outputs. However, existing benchmarks fail to reflect such realistic conflict scenarios. Most focus solely on intra-memory conflicts, while context-memory and inter-context conflicts remain largely investigated. Furthermore, commonly used factual knowledge-based evaluations are often overlooked, and existing datasets lack a thorough investigation into conflict detection capabilities. To bridge this gap, we propose MMKC-Bench, a benchmark designed to evaluate factual knowledge conflicts in both context-memory and inter-context scenarios. MMKC-Bench encompasses three types of multimodal knowledge conflicts and includes 1,573 knowledge instances and 3,381 images across 23 broad types, collected through automated pipelines with human verification. We evaluate three representative series of LMMs on both model behavior analysis and conflict detection tasks. Our findings show that while current LMMs are capable of recognizing knowledge conflicts, they tend to favor internal parametric knowledge over external evidence. We hope MMKC-Bench will foster further research in multimodal knowledge conflict and enhance the development of multimodal RAG systems. The source code is available at https://github.com/MLLMKCBENCH/MLLMKC.

[Arxiv](https://arxiv.org/abs/2505.19509)