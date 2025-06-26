# 基于大型语言模型的表格数据分类中的自动实例选择机制

发布时间：2025年06月25日

`LLM应用` `数据科学` `人工智能`

> Automatic Demonstration Selection for LLM-based Tabular Data Classification

# 摘要

> 在将 ICL 应用于表格数据分类时，如何确定提示中理想演示的数量是一个核心问题。本研究通过提出一种自动选择合理演示数量的算法，成功解决了这一挑战。我们的方法创新性地将表格数据的分布、用户选择的提示模板以及特定的大型语言模型 (LLM) 集成到计算过程中。基于谱图理论，我们定义了一个全新的度量标准，用于量化不同演示之间的相似性。通过构建相似性图并分析其拉普拉斯矩阵的特征值，我们推导出能够在 LLM 的固有表示空间中有效表征数据的最小演示数量。实验结果表明，与传统的随机选择算法相比，我们的方法在多种数据集和 LLM 上均展现出显著优势，验证了其有效性。


> A fundamental question in applying In-Context Learning (ICL) for tabular data classification is how to determine the ideal number of demonstrations in the prompt. This work addresses this challenge by presenting an algorithm to automatically select a reasonable number of required demonstrations. Our method distinguishes itself by integrating not only the tabular data's distribution but also the user's selected prompt template and the specific Large Language Model (LLM) into its estimation. Rooted in Spectral Graph Theory, our proposed algorithm defines a novel metric to quantify the similarities between different demonstrations. We then construct a similarity graph and analyze the eigenvalues of its Laplacian to derive the minimum number of demonstrations capable of representing the data within the LLM's intrinsic representation space. We validate the efficacy of our approach through experiments comparing its performance against conventional random selection algorithms on diverse datasets and LLMs.

[Arxiv](https://arxiv.org/abs/2506.20451)