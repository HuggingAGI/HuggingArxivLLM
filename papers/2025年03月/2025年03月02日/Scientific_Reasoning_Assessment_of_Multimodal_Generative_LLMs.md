# 科学推理：多模态生成大语言模型的评测

发布时间：2025年03月02日

`LLM应用` `科学领域` `问答系统`

> Scientific Reasoning: Assessment of Multimodal Generative LLMs

# 摘要

> 大型语言模型（LLMs）不仅能回答问题，还能处理科学领域等复杂任务。我们对多种多模态大型语言模型（MLLMs）在ScienceQA上的表现进行了评估。结果显示，在少量上下文的情况下，Gemini模型展现出最高的准确性；而在更丰富的上下文中，其文本与人类解释的相似度也最高。值得注意的是，对较小规模的MLLMs进行适配器微调并未显著提升性能。此外，从Gemini的输出进行训练始终不如直接从原始数据训练表现优异。

> Large language models (LLMs) can answer questions and reason about complex tasks, also from the scientific domain. We assess several multimodal LLMs (MLLMs) on ScienceQA and find that Gemini models show the highest accuracy with little context, and the highest textual similarity to human explanations with richer context. Adapter-tuning of smaller MLLMs did not lead to any reliable performance. Training from Gemini outputs consistently underperformed training from the original data.

[Arxiv](https://arxiv.org/abs/2503.01064)