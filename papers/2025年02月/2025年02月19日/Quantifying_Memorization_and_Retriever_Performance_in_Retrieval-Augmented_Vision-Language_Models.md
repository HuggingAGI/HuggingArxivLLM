# 检索增强视觉语言模型中的记忆量化与检索性能评估

发布时间：2025年02月19日

`LLM应用

摘要中讨论了大型语言模型在问答任务中的应用，评估其记忆和检索依赖程度，并通过实际测试比较了不同模型的表现。这属于将LLMs应用于具体任务的研究，因此归类为LLM应用。` `问答系统`

> Quantifying Memorization and Retriever Performance in Retrieval-Augmented Vision-Language Models

# 摘要

> 大型语言模型（LLMs）在问答（QA）任务中表现出色，但评估其记忆与检索依赖程度的指标仍不完善。尽管微调模型在特定领域任务中表现优异，通用模型如GPT-4o却具备强大的零样本性能，这引发了关于记忆、泛化与检索之间权衡的探讨。本研究通过WebQA基准测试，对比了多模态检索增强的视觉语言模型（VLMs）与基线VLMs在训练数据记忆程度上的差异。我们分析了微调对数据记忆的影响，并提出了一些替代指标来量化端到端检索与问答系统中的记忆程度。研究发现，微调模型对记忆的依赖程度较高，而检索增强的VLMs记忆得分较低，但准确率也相应下降（在WebQA测试集上为72% vs 52%）。这为未来研究在开放领域问答和联合检索问答任务中平衡记忆与泛化提出了挑战。

> Large Language Models (LLMs) demonstrate remarkable capabilities in question answering (QA), but metrics for assessing their reliance on memorization versus retrieval remain underdeveloped. Moreover, while finetuned models are state-of-the-art on closed-domain tasks, general-purpose models like GPT-4o exhibit strong zero-shot performance. This raises questions about the trade-offs between memorization, generalization, and retrieval. In this work, we analyze the extent to which multimodal retrieval-augmented VLMs memorize training data compared to baseline VLMs. Using the WebQA benchmark, we contrast finetuned models with baseline VLMs on multihop retrieval and question answering, examining the impact of finetuning on data memorization. To quantify memorization in end-to-end retrieval and QA systems, we propose several proxy metrics by investigating instances where QA succeeds despite retrieval failing. Our results reveal the extent to which finetuned models rely on memorization. In contrast, retrieval-augmented VLMs have lower memorization scores, at the cost of accuracy (72% vs 52% on WebQA test set). As such, our measures pose a challenge for future work to reconcile memorization and generalization in both Open-Domain QA and joint Retrieval-QA tasks.

[Arxiv](https://arxiv.org/abs/2502.13836)