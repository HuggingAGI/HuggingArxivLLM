# 最大化信息检索在状态空间模型生成中的应用

发布时间：2025年06月13日

`RAG` `信息检索` `生成方法`

> Maximally-Informative Retrieval for State Space Model Generation

# 摘要

> 给定一个查询和数据集，回答的最佳方式是充分利用所有信息。现代大型语言模型（LLMs）虽能记住训练数据，但会遗忘未被重视的数据，也无法利用训练集外的信息。受限于模型资源（如 transformer 的上下文大小或状态空间模型的状态），推理时无法处理整个数据集，因此需要借助外部记忆。这一限制引出了一个问题：如何根据当前查询和模型，从海量数据中筛选出对推理至关重要的信息？

为降低测试阶段的模型不确定性，我们提出检索式上下文优化（RICO），这是一种利用 LLM 自身梯度来优化文档组合的检索方法。与依赖外部启发式方法的传统检索增强生成（RAG）不同，RICO 直接从模型获取反馈。理论上，我们证明了基于模型梯度的标准 top-k 检索可近似我们的优化过程，并与留一法损失建立了联系。实验表明，通过最小化以问题困惑度形式表示的无监督损失目标，RICO 可在无需微调的情况下，达到与 BM25 相当的检索性能。此外，在最终预测质量评估中，RICO 通常优于微调后的密集检索器，如 E5。


> Given a query and dataset, the optimal way of answering the query is to make use all the information available. Modern LLMs exhibit impressive ability to memorize training data, but data not deemed important during training is forgotten, and information outside that training set cannot be made use of. Processing an entire dataset at inference time is infeasible due to the bounded nature of model resources (e.g. context size in transformers or states in state space models), meaning we must resort to external memory. This constraint naturally leads to the following problem: How can we decide based on the present query and model, what among a virtually unbounded set of known data matters for inference? To minimize model uncertainty for a particular query at test-time, we introduce Retrieval In-Context Optimization (RICO), a retrieval method that uses gradients from the LLM itself to learn the optimal mixture of documents for answer generation. Unlike traditional retrieval-augmented generation (RAG), which relies on external heuristics for document retrieval, our approach leverages direct feedback from the model. Theoretically, we show that standard top-$k$ retrieval with model gradients can approximate our optimization procedure, and provide connections to the leave-one-out loss. We demonstrate empirically that by minimizing an unsupervised loss objective in the form of question perplexity, we can achieve comparable retriever metric performance to BM25 with \emph{no finetuning}. Furthermore, when evaluated on quality of the final prediction, our method often outperforms fine-tuned dense retrievers such as E5.

[Arxiv](https://arxiv.org/abs/2506.12149)