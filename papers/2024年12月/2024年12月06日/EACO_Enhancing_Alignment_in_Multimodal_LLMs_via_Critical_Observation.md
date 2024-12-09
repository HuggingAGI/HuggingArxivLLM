# EACO：借关键观察提升多模态大型语言模型的对齐程度

发布时间：2024年12月06日

`LLM应用` `语言模型`

> EACO: Enhancing Alignment in Multimodal LLMs via Critical Observation

# 摘要

> 多模态大型语言模型（MLLMs）借助特定数据集的指令微调，在各类视觉问答和推理任务中取得了显著成就。它们还能从人类标注的偏好数据中学习，从而增强推理能力、减少幻觉。多数偏好数据由模型自身生成。然而，现有的方法需要高质量的关键标签，这不仅成本高，还依赖于人类或诸如 GPT-4V 这样的专有模型。在本研究中，我们提出了通过关键观察增强 MLLMs 对齐的方法（EACO），它仅用 5k 张图像生成的偏好数据就能经济地实现 MLLMs 的对齐。我们的方法首先收集并优化评分评估指令调优数据集，以训练一个关键评估模型，即评论家。该评论家从多个维度观察模型响应，挑选出首选和非首选输出，用于改进直接偏好优化（DPO）调优。为进一步提升模型性能，在偏好调优后我们还采用了额外的监督微调阶段。EACO 在 HallusionBench 上使总体幻觉减少了 65.6%，在 MME-Cognition 上使推理能力提高了 21.8%。在多个基准测试中，EACO 比 LLaVA-v1.6-Mistral-7B 提高了 8.5%。值得注意的是，EACO 在开源的 MLLMs 中也展现出潜在的关键能力，这表明 EACO 是提升 MLLMs 能力的可行之道。

> Multimodal large language models (MLLMs) have achieved remarkable progress on various visual question answering and reasoning tasks leveraging instruction fine-tuning specific datasets. They can also learn from preference data annotated by human to enhance their reasoning ability and mitigate hallucinations. Most of preference data is generated from the model itself. However, existing methods require high-quality critical labels, which are costly and rely on human or proprietary models like GPT-4V. In this work, we propose Enhancing Alignment in MLLMs via Critical Observation (EACO), which aligns MLLMs by self-generated preference data using only 5k images economically. Our approach begins with collecting and refining a Scoring Evaluation Instruction-tuning dataset to train a critical evaluation model, termed the Critic. This Critic observes model responses across multiple dimensions, selecting preferred and non-preferred outputs for refined Direct Preference Optimization (DPO) tuning. To further enhance model performance, we employ an additional supervised fine-tuning stage after preference tuning. EACO reduces the overall hallucinations by 65.6% on HallusionBench and improves the reasoning ability by 21.8% on MME-Cognition. EACO achieves an 8.5% improvement over LLaVA-v1.6-Mistral-7B across multiple benchmarks. Remarkably, EACO also shows the potential critical ability in open-source MLLMs, demonstrating that EACO is a viable path to boost the competence of MLLMs.

[Arxiv](https://arxiv.org/abs/2412.04903)