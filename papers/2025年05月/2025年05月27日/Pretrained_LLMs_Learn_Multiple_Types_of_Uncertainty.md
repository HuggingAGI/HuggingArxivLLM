# 预训练的LLMs掌握多种不确定性类型

发布时间：2025年05月27日

`LLM理论` `大型语言模型` `不确定性`

> Pretrained LLMs Learn Multiple Types of Uncertainty

# 摘要

> 大型语言模型 (LLMs) 擅长捕捉现实世界知识，使其在许多下游任务中表现出色。然而，尽管有近期进展，这些模型仍然容易出现所谓的幻觉，导致生成不想要的和事实错误的文本。在本研究中，我们探讨了LLMs如何捕捉不确定性，而无需专门针对此进行训练。我们发现，如果将不确定性视为模型潜在空间中的一个线性概念，它确实可能被捕获，即使仅经过预训练。我们进一步发现，尽管这听起来有些违反直觉，但LLMs似乎能够捕捉到几种不同类型的不确定性，每种类型都可以用于预测特定任务或基准的正确性。此外，我们展示了深入的研究结果，例如我们的修正预测与模型使用词语避免传播错误信息的能力之间的相关性，以及模型扩展对捕捉不确定性缺乏影响。最后，我们发现，通过指令微调或[IDK]-token微调将不同类型的不确定性统一为一种形式，对模型在正确性预测方面是有帮助的。

> Large Language Models are known to capture real-world knowledge, allowing them to excel in many downstream tasks. Despite recent advances, these models are still prone to what are commonly known as hallucinations, causing them to emit unwanted and factually incorrect text. In this work, we study how well LLMs capture uncertainty, without explicitly being trained for that. We show that, if considering uncertainty as a linear concept in the model's latent space, it might indeed be captured, even after only pretraining. We further show that, though unintuitive, LLMs appear to capture several different types of uncertainty, each of which can be useful to predict the correctness for a specific task or benchmark. Furthermore, we provide in-depth results such as demonstrating a correlation between our correction prediction and the model's ability to abstain from misinformation using words, and the lack of impact of model scaling for capturing uncertainty. Finally, we claim that unifying the uncertainty types as a single one using instruction-tuning or [IDK]-token tuning is helpful for the model in terms of correctness prediction.

[Arxiv](https://arxiv.org/abs/2505.21218)