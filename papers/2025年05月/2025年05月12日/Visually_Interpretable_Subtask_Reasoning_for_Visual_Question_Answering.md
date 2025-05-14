# # 视觉问答中的可解释子任务推理

发布时间：2025年05月12日

`LLM应用` `计算机视觉` `多模态`

> Visually Interpretable Subtask Reasoning for Visual Question Answering

# 摘要

> 回答复杂视觉问题，如 `哪些红色家具可以用来坐？`，需要多步推理，包括物体识别、属性筛选和关系理解。近期研究通过将任务分解为子任务程序提升了多模态大语言模型（MLLMs）的可解释性，但这些方法由于对目标数据适应性差，计算成本高昂且准确度较低。为解决这一问题，我们引入了VISTAR（视觉可解释子任务感知推理模型），这是一种基于子任务的训练框架，通过在MLLMs内生成文本和视觉解释来提升可解释性和推理能力。VISTAR不依赖外部模型，而是微调MLLMs以生成结构化的子任务思维 rationale（逐步推理序列）。在两个基准测试中的实验表明，VISTAR在保持可解释性的同时，显著提高了推理准确度。我们的代码和数据集将在https://github.com/ChengJade/VISTAR上开放获取。

> Answering complex visual questions like `Which red furniture can be used for sitting?' requires multi-step reasoning, including object recognition, attribute filtering, and relational understanding. Recent work improves interpretability in multimodal large language models (MLLMs) by decomposing tasks into sub-task programs, but these methods are computationally expensive and less accurate due to poor adaptation to target data. To address this, we introduce VISTAR (Visually Interpretable Subtask-Aware Reasoning Model), a subtask-driven training framework that enhances both interpretability and reasoning by generating textual and visual explanations within MLLMs. Instead of relying on external models, VISTAR fine-tunes MLLMs to produce structured Subtask-of-Thought rationales (step-by-step reasoning sequences). Experiments on two benchmarks show that VISTAR consistently improves reasoning accuracy while maintaining interpretability. Our code and dataset will be available at https://github.com/ChengJade/VISTAR.

[Arxiv](https://arxiv.org/abs/2505.08084)