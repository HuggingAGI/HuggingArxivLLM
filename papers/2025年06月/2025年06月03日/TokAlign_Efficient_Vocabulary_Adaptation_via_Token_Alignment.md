# TokAlign：通过Token对齐实现高效词汇适应

发布时间：2025年06月03日

`LLM应用

理由：这篇论文专注于优化大型语言模型的分词过程，提出了一种方法来提高词汇表的对齐和模型间的知识迁移。这些改进直接影响LLM的训练和生成效率，属于具体的应用层面，因此归类为LLM应用。` `多语言处理`

> TokAlign: Efficient Vocabulary Adaptation via Token Alignment

# 摘要

> 分词是大型语言模型（LLMs）处理文本的基础步骤。在新的领域或语言中，分词器效率低下会拖慢LLM的训练和生成速度。词汇表的不匹配也会阻碍LLM之间如词元级别蒸馏等深度知识迁移。为解决这一问题，我们提出了一种高效的方法，名为TokAlign，它基于词元共现的视角替换LLM的词汇表，并进一步在模型间转移词元级别的知识。该方法首先通过学习一个词元ID的一对一映射矩阵，将源词汇表与目标词汇表对齐。模型参数（包括嵌入层）会被重新排列并逐步针对新词汇表进行微调。我们的方法显著提升了多语言文本压缩率和LLMs的词汇表初始化效果，使困惑度从强基线方法的3.4【数学公式】下降至初始化后的1.2【数学公式】。在不同参数规模的模型上的实验结果证明了TokAlign的有效性和泛化能力，仅需5k步即可恢复基础模型性能。统一LLMs的词汇表后，词元级别蒸馏能显著提升基础模型性能（较句子级别蒸馏提升+4.4%），仅需235M个词元。

> Tokenization serves as a foundational step for Large Language Models (LLMs) to process text. In new domains or languages, the inefficiency of the tokenizer will slow down the training and generation of LLM. The mismatch in vocabulary also hinders deep knowledge transfer between LLMs like token-level distillation. To mitigate this gap, we propose an efficient method named TokAlign to replace the vocabulary of LLM from the token co-occurrences view, and further transfer the token-level knowledge between models. It first aligns the source vocabulary to the target one by learning a one-to-one mapping matrix for token IDs. Model parameters, including embeddings, are rearranged and progressively fine-tuned for the new vocabulary. Our method significantly improves multilingual text compression rates and vocabulary initialization for LLMs, decreasing the perplexity from 3.4$\text{e}^2$ of strong baseline methods to 1.2$\text{e}^2$ after initialization. Experimental results on models across multiple parameter scales demonstrate the effectiveness and generalization of TokAlign, which costs as few as 5k steps to restore the performance of the vanilla model. After unifying vocabularies between LLMs, token-level distillation can remarkably boost (+4.4% than sentence-level distillation) the base model, costing only 235M tokens.

[Arxiv](https://arxiv.org/abs/2506.03523)