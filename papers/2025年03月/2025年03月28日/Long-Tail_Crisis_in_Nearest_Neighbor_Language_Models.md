# # 最近邻语言模型的长尾危机

发布时间：2025年03月28日

`RAG`

> Long-Tail Crisis in Nearest Neighbor Language Models

# 摘要

> $k$-近邻语言模型（$k$NN-LM）作为检索增强型语言模型的代表，通过在推理过程中直接访问由任意文本数据构建的大型数据存储库，显著提升了模型的困惑度表现。关于其成功的原因，普遍认为是其显式记忆（即数据存储库）增强了对长尾现象的预测能力。然而，现有研究主要关注其检索长尾上下文的能力，而模型在推理过程中对长尾目标词的概率估计表现仍鲜有探索。本文深入研究了$k$NN-LM在低频词上的行为，重点分析了预测概率、检索准确性、数据存储库中的词分布以及乘积量化近似误差。实验结果表明，$k$NN-LM并未提升低频词的预测性能，而主要对高频词的预测能力有所改善，这一结论与数据存储库中是否存在长尾上下文无关。

> The $k$-nearest-neighbor language model ($k$NN-LM), one of the retrieval-augmented language models, improves the perplexity for given text by directly accessing a large datastore built from any text data during inference. A widely held hypothesis for the success of $k$NN-LM is that its explicit memory, i.e., the datastore, enhances predictions for long-tail phenomena. However, prior works have primarily shown its ability to retrieve long-tail contexts, leaving the model's performance remain underexplored in estimating the probabilities of long-tail target tokens during inference. In this paper, we investigate the behavior of $k$NN-LM on low-frequency tokens, examining prediction probability, retrieval accuracy, token distribution in the datastore, and approximation error of the product quantization. Our experimental results reveal that $k$NN-LM does not improve prediction performance for low-frequency tokens but mainly benefits high-frequency tokens regardless of long-tail contexts in the datastore.

[Arxiv](https://arxiv.org/abs/2503.22426)