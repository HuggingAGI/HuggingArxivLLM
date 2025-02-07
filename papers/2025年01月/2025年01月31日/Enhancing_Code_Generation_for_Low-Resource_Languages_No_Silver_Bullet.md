# 提升低资源语言的代码生成能力：没有万能解决方案

发布时间：2025年01月31日

`LLM应用

理由：这篇论文主要探讨了如何通过不同的方法（如微调、上下文学习等）来提升大型语言模型（LLMs）在低资源编程语言上的代码生成性能。这属于LLM在实际应用中的优化和改进，因此应归类为LLM应用。` `编程语言` `代码生成`

> Enhancing Code Generation for Low-Resource Languages: No Silver Bullet

# 摘要

> 大型语言模型（LLMs）的崛起极大地推动了自动代码生成领域的进步。LLMs依赖大规模多样化数据集来学习编程语言的语法、语义和使用模式。然而，对于低资源语言（即训练数据稀缺的利基编程语言），数据的匮乏限制了模型的泛化能力，导致其代码生成性能远不及高资源语言。为此，业界正积极探索缩小这一性能差距的技术。我们开展了一项实证研究，探讨了几种提升LLMs在低资源语言上性能的方法，包括：（i）经典的微调，但由于训练数据稀缺，其规模受限；（ii）三种上下文学习变体，通过精心设计的提示为LLM提供低资源语言的额外信息（如展示目标语言特征的少量示例）；（iii）一种预训练目标，教导模型如何在高低资源语言之间进行翻译。我们以两种低资源语言（R和Racket）和六种不同架构及规模的LLMs为研究对象。研究发现，对于较小的LLMs，微调通常是最佳选择，因为即使少量数据也足以训练其有限的参数。随着模型规模增大，上下文学习的效果逐渐增强，成为一种安全且经济的选择（即，它总能带来帮助，但效果各异）。相反，当对超大型LLMs进行微调时，其在低资源语言上的性能可能下降，这可能是由于缺乏足够的数据来有效更新其权重。

> The advent of Large Language Models (LLMs) has significantly advanced the field of automated code generation. LLMs rely on large and diverse datasets to learn syntax, semantics, and usage patterns of programming languages. For low-resource languages (i.e., niche programming languages characterized by the scarcity of training data), the limited availability of such data hampers the models' ability to generalize effectively, resulting in poorer code generation performance as compared to high-resource languages. For this reason, there is a quest for techniques able to close this performance gap. We present an empirical study investigating the effectiveness of several approaches for boosting LLMs' performance on low-resource languages, namely: (i) a classic fine-tuning, which is however capped in size by the scarcity of training data; (ii) three variants of in-context learning, with prompts crafted to provide the LLM with additional information about the low-resource language (e.g., few-shot examples showcasing features of the targeted language); and (iii) a pre-training objective teaching the model how to translate between high- and low-resource languages. The context of our study are two low-resource languages (R and Racket) and six LLMs having different architectures and sizes. Our findings reveal that a fine-tuning is usually the best choice for smaller LLMs, possibly due to the fact that even a small dataset is sufficient to train their limited number of parameters. With the increase in size of the models, in-context learning becomes more and more effective, representing a safe and cheap bet (i.e., it always helps, but with different magnitudes). Differently, very large LLMs may deteriorate their performance on low-resource languages when fine-tuning is performed, possibly due to the lack of enough data needed to effectively update their weights.

[Arxiv](https://arxiv.org/abs/2501.19085)