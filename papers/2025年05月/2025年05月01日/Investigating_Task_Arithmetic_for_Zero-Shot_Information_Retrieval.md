# 探索零样本信息检索中的任务算术

发布时间：2025年05月01日

`LLM应用` `信息检索`

> Investigating Task Arithmetic for Zero-Shot Information Retrieval

# 摘要

> 大型语言模型（LLMs）在多种自然语言处理任务中展现出了令人印象深刻的零样本性能，但其效果在未见过的任务和领域中会有所下降，这主要是由于词汇和词分布的变化。本文提出了一种名为任务算术（Task Arithmetic）的技术，通过简单的数学运算（如加减法）结合不同任务或领域预训练的LLMs权重，从而无需额外微调即可适应检索模型。我们的方法能够将多样化的任务和领域知识整合到一个模型中，实现不同检索场景下的有效零样本适应。在公开的科学、生物医学和多语言数据集上进行的大量实验表明，我们的方法在NDCG@10和P@10指标上将最先进的重排序性能提升了高达18%和15%。此外，我们的分析还揭示了任务算术在零样本学习和模型适应中的优势与局限性。我们的代码已公开发布在https://github.com/DetectiveMB/Task-Arithmetic-for-ZS-IR。

> Large Language Models (LLMs) have shown impressive zero-shot performance across a variety of Natural Language Processing tasks, including document re-ranking. However, their effectiveness degrades on unseen tasks and domains, largely due to shifts in vocabulary and word distributions. In this paper, we investigate Task Arithmetic, a technique that combines the weights of LLMs pre-trained on different tasks or domains via simple mathematical operations, such as addition or subtraction, to adapt retrieval models without requiring additional fine-tuning. Our method is able to synthesize diverse tasks and domain knowledge into a single model, enabling effective zero-shot adaptation in different retrieval contexts. Extensive experiments on publicly available scientific, biomedical, and multilingual datasets show that our method improves state-of-the-art re-ranking performance by up to 18% in NDCG@10 and 15% in P@10. In addition to these empirical gains, our analysis provides insights into the strengths and limitations of Task Arithmetic as a practical strategy for zero-shot learning and model adaptation. We make our code publicly available at https://github.com/DetectiveMB/Task-Arithmetic-for-ZS-IR.

[Arxiv](https://arxiv.org/abs/2505.00649)