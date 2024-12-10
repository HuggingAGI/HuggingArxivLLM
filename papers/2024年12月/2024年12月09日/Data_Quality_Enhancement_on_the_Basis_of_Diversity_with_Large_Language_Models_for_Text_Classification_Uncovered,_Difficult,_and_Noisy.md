# 基于多样性借助大型语言模型提高文本分类的数据质量：未被察觉的、棘手的和有噪声的

发布时间：2024年12月09日

`LLM应用` `文本分类` `数据质量`

> Data Quality Enhancement on the Basis of Diversity with Large Language Models for Text Classification: Uncovered, Difficult, and Noisy

# 摘要

> 近年来，大型语言模型（LLMs）用于文本分类这一应用备受瞩目。不过，LLMs 的分类准确率还未普遍超越较小的模型。LLMs 能够通过微调来提升其在文本分类中的表现。然而，基于 LLMs 现有的数据质量研究难以直接用于解决文本分类问题。为进一步提升 LLMs 在分类任务中的性能，本文提出了一种基于 LLMs 的文本分类数据质量增强（DQE）方法。此方法先是运用贪心算法选取数据，把数据集划分为采样和未采样子集，接着用采样数据对 LLMs 进行微调。随后，用该模型预测未采样数据的结果，将错误预测的数据归为未覆盖、困难和噪声数据这几类。实验结果显示，我们的方法切实提高了 LLMs 在文本分类任务中的性能，大幅提升了训练效率，节省了将近一半的训练时间。我们的方法在若干开源分类任务中达到了领先水平。

> In recent years, the use of large language models (LLMs) for text classification has attracted widespread attention. Despite this, the classification accuracy of LLMs has not yet universally surpassed that of smaller models. LLMs can enhance their performance in text classification through fine-tuning. However, existing data quality research based on LLMs is challenging to apply directly to solve text classification problems. To further improve the performance of LLMs in classification tasks, this paper proposes a data quality enhancement (DQE) method for text classification based on LLMs. This method starts by using a greedy algorithm to select data, dividing the dataset into sampled and unsampled subsets, and then performing fine-tuning of the LLMs using the sampled data. Subsequently, this model is used to predict the outcomes for the unsampled data, categorizing incorrectly predicted data into uncovered, difficult, and noisy data. Experimental results demonstrate that our method effectively enhances the performance of LLMs in text classification tasks and significantly improves training efficiency, saving nearly half of the training time. Our method has achieved state-of-the-art performance in several open-source classification tasks.

[Arxiv](https://arxiv.org/abs/2412.06575)