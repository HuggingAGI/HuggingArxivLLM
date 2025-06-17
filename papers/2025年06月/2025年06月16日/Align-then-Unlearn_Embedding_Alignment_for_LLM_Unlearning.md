# 先对齐再遗忘：LLM取消学习中的嵌入对齐方法

发布时间：2025年06月16日

`LLM理论` `机器学习`

> Align-then-Unlearn: Embedding Alignment for LLM Unlearning

# 摘要

> 大型语言模型 (LLMs) 基于海量数据训练，可能无意中保留敏感信息，引发隐私和伦理问题。为解决这一问题，我们提出了一种名为Align-then-Unlearn的全新遗忘训练框架。该框架在语义嵌入空间中执行遗忘训练，而非直接作用于输出标记。首先，通过训练一个嵌入式预测模块来增强LLM，使其能够预测未来的上下文表示。随后，通过微调模型以最小化这些预测嵌入与目标嵌入之间的相似性来实现遗忘训练，目标嵌入代表了待移除的概念。初步结果显示，Align-then-Unlearn能够有效移除目标知识，同时对模型整体效用的影响降至最低。这一发现表明，基于嵌入的遗忘训练为移除概念性知识提供了一种有前途且稳健的方法。我们的代码可在https://github.com/ExplainableML/align-then-unlearn获取。

> As large language models (LLMs) are trained on massive datasets, they have raised significant privacy and ethical concerns due to their potential to inadvertently retain sensitive information. Unlearning seeks to selectively remove specific data from trained models, such as personal information or copyrighted content. Current approaches targeting specific output sequences at the token level often fail to achieve complete forgetting and remain susceptible to prompt rephrasing. We propose Align-then-Unlearn, a novel framework that performs unlearning in the semantic embedding space rather than directly on output tokens. Align-then-Unlearn first augments the LLM with an embedding prediction module trained to anticipate future context representations. Unlearning is then achieved by fine-tuning the model to minimize the similarity between these predicted embeddings and a target embedding that represents the concept to be removed. Initial results show that Align-then-Unlearn effectively removes targeted knowledge with minimal degradation in overall model utility. These findings suggest that embedding-based unlearning offers a promising and robust approach to removing conceptual knowledge. Our code is available at https://github.com/ExplainableML/align-then-unlearn.

[Arxiv](https://arxiv.org/abs/2506.13181)