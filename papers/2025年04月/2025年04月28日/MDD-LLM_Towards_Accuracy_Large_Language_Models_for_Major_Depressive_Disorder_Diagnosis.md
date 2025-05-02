# MDD-LLM：面向抑郁症诊断的高精度大型语言模型

发布时间：2025年04月28日

`LLM应用`

> MDD-LLM: Towards Accuracy Large Language Models for Major Depressive Disorder Diagnosis

# 摘要

> 重性抑郁障碍（MDD）影响全球超3亿人口，凸显了这一重大公共卫生问题。然而，医疗资源分布不均及诊断方法复杂性导致众多国家和地区对该障碍关注不足。本文介绍了一款高性能MDD诊断工具——MDD-LLM，该AI驱动框架利用微调后的大型语言模型（LLMs）和大量真实世界样本，旨在解决MDD诊断中的挑战。我们从英国生物银行队列中选取了274,348份个体记录，并设计了一种表格数据转换方法，以此构建大规模语料库，用于训练和评估所提方法。为展示MDD-LLM的优势，我们进行了全面实验，并在多个评估指标下与现有基于模型的解决方案进行了多项对比分析。实验结果表明，MDD-LLM（70B）实现了0.8378的准确率和0.8919的AUC（95% CI: 0.8799 - 0.9040），显著超越现有用于MDD诊断的机器学习和深度学习框架。鉴于LLMs在MDD诊断领域的探索有限，我们考察了可能影响所提方法性能的诸多因素，如表格数据转换技术及不同的微调策略。

> Major depressive disorder (MDD) impacts more than 300 million people worldwide, highlighting a significant public health issue. However, the uneven distribution of medical resources and the complexity of diagnostic methods have resulted in inadequate attention to this disorder in numerous countries and regions. This paper introduces a high-performance MDD diagnosis tool named MDD-LLM, an AI-driven framework that utilizes fine-tuned large language models (LLMs) and extensive real-world samples to tackle challenges in MDD diagnosis. Therefore, we select 274,348 individual information from the UK Biobank cohort to train and evaluate the proposed method. Specifically, we select 274,348 individual records from the UK Biobank cohort and design a tabular data transformation method to create a large corpus for training and evaluating the proposed approach. To illustrate the advantages of MDD-LLM, we perform comprehensive experiments and provide several comparative analyses against existing model-based solutions across multiple evaluation metrics. Experimental results show that MDD-LLM (70B) achieves an accuracy of 0.8378 and an AUC of 0.8919 (95% CI: 0.8799 - 0.9040), significantly outperforming existing machine learning and deep learning frameworks for MDD diagnosis. Given the limited exploration of LLMs in MDD diagnosis, we examine numerous factors that may influence the performance of our proposed method, such as tabular data transformation techniques and different fine-tuning strategies.

[Arxiv](https://arxiv.org/abs/2505.00032)