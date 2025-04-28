# # 高效单次训练，助力多轮推理

发布时间：2025年04月25日

`LLM理论` `人工智能` `推理系统`

> Efficient Single-Pass Training for Multi-Turn Reasoning

# 摘要

> 研究表明，训练大型语言模型 (LLMs) 在生成答案前进行明确推理，能够显著提升其在数学和编程等任务中的表现。然而，在多轮推理数据集上微调LLMs时，我们遇到了一个独特挑战：模型生成的推理过程不能作为后续输入提供给自身。这一限制使得我们无法通过单次前向传递处理完整对话，而这一优化在微调多轮非推理数据集时是可行的。针对这一问题，我们提出了一种创新方法，通过复制响应令牌和定制注意力掩码，确保模型在推理过程中获得适当的可见性约束。这种方法不仅显著缩短了训练时间，还为高效微调多轮推理数据集提供了可能。

> Training Large Language Models ( LLMs) to generate explicit reasoning before they produce an answer has been shown to improve their performance across various tasks such as mathematics and coding. However, fine-tuning LLMs on multi-turn reasoning datasets presents a unique challenge: LLMs must generate reasoning tokens that are excluded from subsequent inputs to the LLM. This discrepancy prevents us from processing an entire conversation in a single forward pass-an optimization readily available when we fine-tune on a multi-turn non-reasoning dataset. This paper proposes a novel approach that overcomes this limitation through response token duplication and a custom attention mask that enforces appropriate visibility constraints. Our approach significantly reduces the training time and allows efficient fine-tuning on multi-turn reasoning datasets.

[Arxiv](https://arxiv.org/abs/2504.18246)