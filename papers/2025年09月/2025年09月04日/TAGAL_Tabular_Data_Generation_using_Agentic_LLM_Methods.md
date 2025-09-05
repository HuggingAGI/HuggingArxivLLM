# TAGAL：基于智能体LLM方法的表格数据生成

发布时间：2025年09月04日

`Agent` `基础理论`

> TAGAL: Tabular Data Generation using Agentic LLM Methods

# 摘要

> 数据生成是提升机器学习任务性能的常用手段，分类模型训练便是其中之一。本文提出TAGAL——一种基于智能体工作流生成合成表格数据的方法集合。该方法集合借助大型语言模型（LLMs）实现自动迭代过程，通过反馈优化生成数据，且无需对LLM进行额外训练。LLMs的应用还支持在生成过程中融入外部知识。我们在多种数据集上从生成数据质量的不同维度对TAGAL进行了评估，考察了下游机器学习模型的效用，包括仅用合成数据训练分类器以及将真实数据与合成数据结合两种场景。此外，我们还对比了真实数据与生成数据的相似性。结果表明，TAGAL的性能可与需LLM训练的最先进方法相媲美，且通常优于其他无需训练的方法。这些发现彰显了智能体工作流的潜力，并为基于LLM的数据生成方法开辟了新方向。

> The generation of data is a common approach to improve the performance of machine learning tasks, among which is the training of models for classification. In this paper, we present TAGAL, a collection of methods able to generate synthetic tabular data using an agentic workflow. The methods leverage Large Language Models (LLMs) for an automatic and iterative process that uses feedback to improve the generated data without any further LLM training. The use of LLMs also allows for the addition of external knowledge in the generation process. We evaluate TAGAL across diverse datasets and different aspects of quality for the generated data. We look at the utility of downstream ML models, both by training classifiers on synthetic data only and by combining real and synthetic data. Moreover, we compare the similarities between the real and the generated data. We show that TAGAL is able to perform on par with state-of-the-art approaches that require LLM training and generally outperforms other training-free approaches. These findings highlight the potential of agentic workflow and open new directions for LLM-based data generation methods.

[Arxiv](https://arxiv.org/abs/2509.04152)