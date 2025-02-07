# 一切尽在 [MASK]：简单指令调优让 BERT 式掩码语言模型变身生成分类器

发布时间：2025年02月06日

`LLM应用

理由：这篇论文介绍了ModernBERT-Large-Instruct模型，并讨论了其在分类和知识任务上的表现。虽然论文涉及模型架构和训练方法，但其核心关注点是如何利用该模型进行生成式分类，并在实际任务中表现出色。因此，这篇论文主要属于LLM应用类别，因为它侧重于将模型应用于具体的NLP任务，并展示了其在实际应用中的潜力。` `机器学习`

> It's All in The [MASK]: Simple Instruction-Tuning Enables BERT-like Masked Language Models As Generative Classifiers

# 摘要

> 虽然BERT和ModernBERT等仅编码器模型在NLP应用中无处不在，但与基于解码器的LLMs相比，它们对任务特定分类头的依赖限制了其适用性。本文介绍了ModernBERT-Large-Instruct，一个0.4B参数的编码器模型，利用其MLM头进行生成式分类。我们的方法采用简单的训练循环和推理机制，无需复杂预处理或架构修改。ModernBERT-Large-Instruct在分类和知识任务上表现出色，在MMLU上超越类似大小的LLMs，并以60%更少的参数达到Llama3-1B的93%性能。微调后，MLM头的生成方法在各种NLU任务中匹配甚至超越传统分类头方法。这种能力特别出现在训练于多样化数据的模型中，而训练于较少样化数据的模型表现较弱。这些初步结果展示了在下游任务中使用MLM头的潜力，值得进一步探索。

> While encoder-only models such as BERT and ModernBERT are ubiquitous in real-world NLP applications, their conventional reliance on task-specific classification heads can limit their applicability compared to decoder-based large language models (LLMs). In this work, we introduce ModernBERT-Large-Instruct, a 0.4B-parameter encoder model that leverages its masked language modelling (MLM) head for generative classification. Our approach employs an intentionally simple training loop and inference mechanism that requires no heavy pre-processing, heavily engineered prompting, or architectural modifications. ModernBERT-Large-Instruct exhibits strong zero-shot performance on both classification and knowledge-based tasks, outperforming similarly sized LLMs on MMLU and achieving 93% of Llama3-1B's MMLU performance with 60% less parameters. We also demonstrate that, when fine-tuned, the generative approach using the MLM head matches or even surpasses traditional classification-head methods across diverse NLU tasks.This capability emerges specifically in models trained on contemporary, diverse data mixes, with models trained on lower volume, less-diverse data yielding considerably weaker performance. Although preliminary, these results demonstrate the potential of using the original generative masked language modelling head over traditional task-specific heads for downstream tasks. Our work suggests that further exploration into this area is warranted, highlighting many avenues for future improvements.

[Arxiv](https://arxiv.org/abs/2502.03793)