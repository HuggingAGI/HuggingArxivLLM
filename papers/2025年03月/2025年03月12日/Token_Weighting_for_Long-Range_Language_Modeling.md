# 长距离语言建模中的Token权重分配

发布时间：2025年03月12日

`LLM理论` `模型优化`

> Token Weighting for Long-Range Language Modeling

# 摘要

> 大型语言模型 (LLMs) 的许多应用场景需要长上下文理解能力，但模型在这些任务上仍然表现挣扎。我们假设传统的下一个词预测训练方式可能对此有影响，因为每个词被赋予了相同的权重。然而，直觉上，准确预测下一个词所需上下文的长度在不同数据之间差异很大。为此，我们提出了多种新颖的token加权方案，在损失函数中为每个训练token分配不同的权重，从而推广了现有工作。我们使用一个两步框架对token加权方法进行分类，通过比较长上下文和短上下文模型的置信度来对token进行评分。我们在多个长上下文理解任务上评估了所有方法，并证明了非均匀的损失权重有助于提高LLMs的长上下文能力。不同的短上下文模型可以有效地用于token评分，包括比训练的长上下文模型小得多的模型。综上所述，这项工作有助于更好地理解长上下文语言建模所面临的权衡，并通过基于实证证据的损失加权提供了模型调整的指导。代码可在GitHub上找到。

> Many applications of large language models (LLMs) require long-context understanding, but models continue to struggle with such tasks. We hypothesize that conventional next-token prediction training could contribute to this, because each token is assigned equal weight. Yet, intuitively, the amount of context needed to predict the next token accurately varies greatly across different data. To reflect this, we propose various novel token-weighting schemes that assign different weights to each training token in the loss, thereby generalizing existing works. For this, we categorize token-weighting methods using a two-step framework which compares the confidences of a long-context and short-context model to score tokens. We evaluate all methods on multiple long-context understanding tasks and show that non-uniform loss weights are helpful to improve the long-context abilities of LLMs. Different short-context models can be used effectively for token scoring, including models that are much smaller than the long-context model that is trained. All in all, this work contributes to a better understanding of the trade-offs long-context language modeling faces and provides guidelines for model steering via loss-weighting based on empirical evidence. The code can be found on Github.

[Arxiv](https://arxiv.org/abs/2503.09202)