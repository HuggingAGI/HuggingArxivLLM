# 超越指令微调，MoTE：面向多任务嵌入模型的任务专家混合模型

发布时间：2025年06月21日

`LLM应用

论文摘要讨论了密集嵌入在RAG中的应用，以及通过引入MoTE变换块来提升模型生成专业嵌入的能力，属于LLM应用的范畴。` `信息检索` `表示学习`

> Beyond instruction-conditioning, MoTE: Mixture of Task Experts for Multi-task Embedding Models

# 摘要

> 密集嵌入是现代机器学习系统的核心，广泛应用于检索增强生成（RAG）、信息检索和表示学习。尽管指令调节已成为嵌入专业化的主导方法，但其直接应用于低容量模型时会带来根本性的表示限制，限制了专业化带来的性能提升。本文分析了这些限制，并引入了任务专家混合（MoTE）变换块，该块利用任务感知对比学习（	acl）训练的任务专用参数，以增强模型生成专业嵌入的能力。实证结果表明，MoTE在检索数据集上的性能提升高出64%（+3.27 → +5.21），在所有数据集上的性能提升高出43%（+1.81 → +2.60）。这些提升是在不更改指令、训练数据、推理时间和活跃参数数量的情况下实现的。

> Dense embeddings are fundamental to modern machine learning systems, powering Retrieval-Augmented Generation (RAG), information retrieval, and representation learning. While instruction-conditioning has become the dominant approach for embedding specialization, its direct application to low-capacity models imposes fundamental representational constraints that limit the performance gains derived from specialization. In this paper, we analyze these limitations and introduce the Mixture of Task Experts (MoTE) transformer block, which leverages task-specialized parameters trained with Task-Aware Contrastive Learning (\tacl) to enhance the model ability to generate specialized embeddings. Empirical results show that MoTE achieves $64\%$ higher performance gains in retrieval datasets ($+3.27 \rightarrow +5.21$) and $43\%$ higher performance gains across all datasets ($+1.81 \rightarrow +2.60$). Critically, these gains are achieved without altering instructions, training data, inference time, or number of active parameters.

[Arxiv](https://arxiv.org/abs/2506.17781)