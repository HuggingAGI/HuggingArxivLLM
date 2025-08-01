# ISO-Bench：通过过程计划评估视觉语言模型的多模态因果推理能力

发布时间：2025年07月30日

`LLM应用` `多模态` `因果推理`

> ISO-Bench: Benchmarking Multimodal Causal Reasoning in Visual-Language Models through Procedural Plans

# 摘要

> 跨模态因果关系的理解是多模态模型在现实环境中面临的重大挑战。我们推出ISO-Bench基准，用于评估模型能否推断视觉观察与程序性文本间的因果依赖。每个示例包含一个任务步骤的图像和一段来自计划的文本，目标是判断视觉步骤是在文本步骤之前还是之后发生。在十个前沿视觉-语言模型上的评估结果令人失望：最佳零样本F1值仅为0.57，链式推理也只能带来有限提升（最高0.62 F1），远低于人类的0.98 F1。我们的分析为提升多模态模型的因果理解提供了明确的方向。

> Understanding causal relationships across modalities is a core challenge for multimodal models operating in real-world environments. We introduce ISO-Bench, a benchmark for evaluating whether models can infer causal dependencies between visual observations and procedural text. Each example presents an image of a task step and a text snippet from a plan, with the goal of deciding whether the visual step occurs before or after the referenced text step. Evaluation results on ten frontier vision-language models show underwhelming performance: the best zero-shot F1 is only 0.57, and chain-of-thought reasoning yields only modest gains (up to 0.62 F1), largely behind humans (0.98 F1). Our analysis further highlights concrete directions for improving causal understanding in multimodal models.

[Arxiv](https://arxiv.org/abs/2507.23135)