# FRED：基于金融检索增强的语言模型幻觉检测与编辑

发布时间：2025年07月28日

`LLM应用` `问答系统`

> FRED: Financial Retrieval-Enhanced Detection and Editing of Hallucinations in Language Models

# 摘要

> 大语言模型的幻觉现象对需要事实可靠性的应用提出了严峻挑战，尤其是在金融等高风险领域。本研究提出了一种基于给定上下文检测和编辑模型生成回复中事实错误内容的有效方法。针对用户定义的领域特定错误分类法，我们通过在财务问答语料库中插入标记化错误来构建合成数据集，并对四个语言模型（Phi-4、Phi-4-mini、Qwen3-4B 和 Qwen3-14B）进行微调，以检测和编辑这些事实不准确之处。我们表现最佳的微调模型 Phi-4 在二元 F1 分数上比 OpenAI-o3 提升了 8%，整体检测性能提升了 30%。值得注意的是，尽管 Phi-4-mini 模型仅有 40 亿参数，但其性能依然强劲，与 OpenAI-o3 相比，二元检测仅下降 2%，整体检测下降 0.1%。本研究为金融文本生成中的事实不一致检测和编辑提供了一种实用解决方案，同时引入了一个通用框架，可提升大语言模型在金融及其他多样化应用场景中的可信度和一致性。我们的代码和数据可在 https://github.com/pegasi-ai/fine-grained-editting 获取。

> Hallucinations in large language models pose a critical challenge for applications requiring factual reliability, particularly in high-stakes domains such as finance. This work presents an effective approach for detecting and editing factually incorrect content in model-generated responses based on the provided context. Given a user-defined domain-specific error taxonomy, we construct a synthetic dataset by inserting tagged errors into financial question-answering corpora and then fine-tune four language models, Phi-4, Phi-4-mini, Qwen3-4B, and Qwen3-14B, to detect and edit these factual inaccuracies. Our best-performing model, fine-tuned Phi-4, achieves an 8% improvement in binary F1 score and a 30% gain in overall detection performance compared to OpenAI-o3. Notably, our fine-tuned Phi-4-mini model, despite having only 4 billion parameters, maintains competitive performance with just a 2% drop in binary detection and a 0.1% decline in overall detection compared to OpenAI-o3. Our work provides a practical solution for detecting and editing factual inconsistencies in financial text generation while introducing a generalizable framework that can enhance the trustworthiness and alignment of large language models across diverse applications beyond finance. Our code and data are available at https://github.com/pegasi-ai/fine-grained-editting.

[Arxiv](https://arxiv.org/abs/2507.20930)