# 少即是多：上下文语言模型的局部固有维度分析

发布时间：2025年06月01日

`LLM理论` `人工智能`

> Less is More: Local Intrinsic Dimensions of Contextual Language Models

# 摘要

> 理解大型语言模型 (LLMs) 的内部机制仍然是一个充满挑战且复杂的任务。即使是像微调如何影响模型行为这样基本的问题，通常也需要进行广泛的实证评估。在这篇文章中，我们引入了一种基于上下文潜在嵌入几何属性的新视角，来研究训练和微调的影响。为此，我们测量了上下文语言模型潜在空间的局部维度，并分析了它们在训练和微调过程中的变化。我们发现，局部维度能够为理解模型的训练动态和泛化能力提供洞见。具体而言，局部维度的平均值可以预测模型训练能力何时耗尽，例如在对话状态跟踪任务中；它可以揭示过拟合现象，如在情绪识别任务中所示；以及它可以说明“领悟”（grokking）的过程，如算术任务中所展示的。此外，我们的实验提出了一种实用的启发式方法：平均局部维度的减少往往伴随着并预示着后续性能的提升。通过这项研究，我们旨在帮助从业者更深入地理解微调对嵌入空间的影响，从而在配置模型以满足特定应用需求时做出有依据的决策。这项工作的成果为关于 LLMs 的可解释性、适应性和泛化能力的持续讨论做出了贡献，它通过连接模型内部机制与相应嵌入的几何特性，弥合了两者之间的差距。

> Understanding the internal mechanisms of large language models (LLMs) remains a challenging and complex endeavor. Even fundamental questions, such as how fine-tuning affects model behavior, often require extensive empirical evaluation. In this paper, we introduce a novel perspective based on the geometric properties of contextual latent embeddings to study the effects of training and fine-tuning. To that end, we measure the local dimensions of a contextual language model's latent space and analyze their shifts during training and fine-tuning. We show that the local dimensions provide insights into the model's training dynamics and generalization ability. Specifically, the mean of the local dimensions predicts when the model's training capabilities are exhausted, as exemplified in a dialogue state tracking task, overfitting, as demonstrated in an emotion recognition task, and grokking, as illustrated with an arithmetic task. Furthermore, our experiments suggest a practical heuristic: reductions in the mean local dimension tend to accompany and predict subsequent performance gains. Through this exploration, we aim to provide practitioners with a deeper understanding of the implications of fine-tuning on embedding spaces, facilitating informed decisions when configuring models for specific applications. The results of this work contribute to the ongoing discourse on the interpretability, adaptability, and generalizability of LLMs by bridging the gap between intrinsic model mechanisms and geometric properties in the respective embeddings.

[Arxiv](https://arxiv.org/abs/2506.01034)