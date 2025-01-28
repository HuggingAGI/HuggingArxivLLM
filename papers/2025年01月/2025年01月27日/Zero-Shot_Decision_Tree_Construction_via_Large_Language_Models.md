# 基于大型语言模型的零-shot 决策树构建

发布时间：2025年01月27日

`LLM应用

理由：该论文提出了一种利用大型语言模型（LLMs）以零-shot方式构建决策树的新算法。这种方法依赖于LLMs的预训练知识，无需标记数据即可完成决策树的构建，属于LLM在实际应用中的创新使用。因此，将其分类为“LLM应用”是合适的。` `机器学习` `决策树`

> Zero-Shot Decision Tree Construction via Large Language Models

# 摘要

> 本文提出了一种基于CART原理、利用LLMs以零-shot方式构建决策树的新算法。传统方法依赖标记数据，通过信息增益或基尼指数递归划分数据，而我们的方法则利用LLMs的预训练知识，无需训练数据即可构建决策树。该方法通过LLMs完成属性离散化、概率计算及基尼指数计算等关键步骤。实验表明，这些零-shot决策树不仅超越了基线零-shot方法，还在表格数据集上达到了与监督数据驱动决策树相当的性能。该方法构建的决策树透明且可解释，既解决了数据稀缺问题，又保持了模型的可解释性。这一研究为低数据机器学习设立了新基准，提供了一种基于知识的、原则性的树构建替代方案。

> This paper introduces a novel algorithm for constructing decision trees using large language models (LLMs) in a zero-shot manner based on Classification and Regression Trees (CART) principles. Traditional decision tree induction methods rely heavily on labeled data to recursively partition data using criteria such as information gain or the Gini index. In contrast, we propose a method that uses the pre-trained knowledge embedded in LLMs to build decision trees without requiring training data. Our approach leverages LLMs to perform operations essential for decision tree construction, including attribute discretization, probability calculation, and Gini index computation based on the probabilities. We show that these zero-shot decision trees can outperform baseline zero-shot methods and achieve competitive performance compared to supervised data-driven decision trees on tabular datasets. The decision trees constructed via this method provide transparent and interpretable models, addressing data scarcity while preserving interpretability. This work establishes a new baseline in low-data machine learning, offering a principled, knowledge-driven alternative to data-driven tree construction.

[Arxiv](https://arxiv.org/abs/2501.16247)