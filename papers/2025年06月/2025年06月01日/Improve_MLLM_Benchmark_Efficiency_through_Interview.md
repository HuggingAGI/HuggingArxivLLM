# # 访谈助力提升MLLM基准效率

发布时间：2025年06月01日

`LLM应用` `评估策略` `问答系统`

> Improve MLLM Benchmark Efficiency through Interview

# 摘要

> 多模态大型语言模型（MLLM）的快速发展推动了其在多个领域的广泛应用，随之也涌现出了许多基准数据集用于评估MLLM的能力。然而，基于大规模数据进行全面覆盖的问答测试需要大量资源且耗时较长。为了解决这一问题，我们提出了MLLM Interview（MITV）策略，旨在通过少量问题快速获取MLLM的性能指标。

首先，我们构建了面试数据集，该数据集基于现有的MLLM评估数据集，并通过添加难度标签进行扩展，这些标签基于该数据集中一些典型MLLM的表现。其次，我们提出了MLLM Interview策略，该策略通过少量主题的问答测试，快速获取大型模型的初始性能情况，并持续尝试测试模型的极限。

通过大量实验，结果表明本文提出的MITV策略在MLLM基准数据集上表现良好，并且能够通过少量的问答测试快速获得模型的评估能力。

> The rapid development of Multimodal Large Language Models (MLLM) has led to a wide range of MLLM applications, and a number of benchmark datasets have sprung up in order to assess MLLM abilities. However, full-coverage Q&A testing on large-scale data is resource-intensive and time-consuming. To address this issue, we propose the MLLM Interview (MITV) strategy, which aims to quickly obtain MLLM performance metrics by quizzing fewer question. First, First, we constructed the interview dataset, which was built on an existing MLLM assessment dataset, by adding difficulty labels based on the performance of some typical MLLMs in this dataset. Second, we propose an MLLM Interview strategy, which obtains an initial performance situation of the large model by quizzing a small number of topics and then continuously tries to test the model's limits. Through extensive experiments, the result shows that the MITV strategy proposed in this paper performs well on MLLM benchmark datasets, and it is able to obtain the model evaluation capability faster through a small number of questions and answers.

[Arxiv](https://arxiv.org/abs/2506.00883)