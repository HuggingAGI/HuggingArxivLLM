# 基于大型语言模型的知识蒸馏优化Walmart电商搜索相关性

发布时间：2025年05月11日

`LLM应用

理由：这篇论文主要探讨了如何通过知识蒸馏技术将大型语言模型（LLM）压缩为高效的学生模型，以解决其在实时系统中的高延迟问题。研究集中在模型压缩和应用优化上，属于LLM的实际应用领域。` `电子商务` `知识蒸馏`

> Knowledge Distillation for Enhancing Walmart E-commerce Search Relevance Using Large Language Models

# 摘要

> 提升电子商务搜索结果的相关性是优化用户体验的关键。深度学习模型凭借其强大的语义理解能力，在搜索相关性匹配中得到了广泛应用。尽管大型语言模型（LLMs）在排序任务中表现出色，但其高延迟特性使其难以直接应用于实时系统。为解决这一矛盾，我们提出了一种创新框架，通过知识蒸馏将高性能的LLM压缩为一个高效且低延迟的学生模型。在训练过程中，我们首先将教师LLM转化为一个带有软标签的分类器。随后，利用均方误差损失函数，我们引导学生模型学习查询下产品对之间的相关性差异。与传统方法不同，我们通过生成未标注数据并借助教师模型的预测进行标注，大幅扩充了学生模型的训练集。实验结果表明，学生模型的性能随着增强数据量的增加而不断提升。实际上，当增强数据足够丰富时，学生模型的表现甚至超越了教师模型。目前，该学生模型已在Walmart.com成功上线，取得了显著的积极效果。

> Ensuring the products displayed in e-commerce search results are relevant to users queries is crucial for improving the user experience. With their advanced semantic understanding, deep learning models have been widely used for relevance matching in search tasks. While large language models (LLMs) offer superior ranking capabilities, it is challenging to deploy LLMs in real-time systems due to the high-latency requirements. To leverage the ranking power of LLMs while meeting the low-latency demands of production systems, we propose a novel framework that distills a high performing LLM into a more efficient, low-latency student model. To help the student model learn more effectively from the teacher model, we first train the teacher LLM as a classification model with soft targets. Then, we train the student model to capture the relevance margin between pairs of products for a given query using mean squared error loss. Instead of using the same training data as the teacher model, we significantly expand the student model dataset by generating unlabeled data and labeling it with the teacher model predictions. Experimental results show that the student model performance continues to improve as the size of the augmented training data increases. In fact, with enough augmented data, the student model can outperform the teacher model. The student model has been successfully deployed in production at Walmart.com with significantly positive metrics.

[Arxiv](https://arxiv.org/abs/2505.07105)