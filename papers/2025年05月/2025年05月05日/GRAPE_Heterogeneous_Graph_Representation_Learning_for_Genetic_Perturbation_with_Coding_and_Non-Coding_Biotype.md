# GRAPE：结合编码与非编码生物类型，用于基因扰动分析的异质图表示学习。

发布时间：2025年05月05日

`LLM应用

摘要中提到的研究使用了预训练的大型语言模型（LLM）和DNA序列模型来处理基因描述和DNA序列，提取特征并构建基因调控网络。这表明研究的重点在于将LLM应用于基因研究，属于应用层面。因此，正确的分类是LLM应用。` `生物信息学` `图神经网络`

> GRAPE: Heterogeneous Graph Representation Learning for Genetic Perturbation with Coding and Non-Coding Biotype

# 摘要

> 预测基因扰动能够提前识别潜在的关键基因，显著提升实验效率。基因作为细胞生命的基础，构建基因调控网络（GRN）对于理解基因扰动至关重要。然而，现有方法未能充分利用基因信息，仅依赖简单指标构建粗粒度网络，且忽略了基因类型间的功能差异，限制了对基因相互作用的捕捉。在本研究中，我们利用预训练的大型语言模型和DNA序列模型，从基因描述和DNA序列中提取特征，作为基因表示的初始化。首次引入基因生物类型信息，模拟不同基因类型在调控过程中的不同作用，通过图结构学习（GSL）捕获隐含基因关系。我们提出了GRAPE，一种异质图神经网络（HGNN），该方法利用从描述和序列中提取特征初始化的基因表示，建模不同基因类型的作用，并通过GSL动态细化GRN。实验结果表明，我们的方法达到了当前最优性能。

> Predicting genetic perturbations enables the identification of potentially crucial genes prior to wet-lab experiments, significantly improving overall experimental efficiency. Since genes are the foundation of cellular life, building gene regulatory networks (GRN) is essential to understand and predict the effects of genetic perturbations. However, current methods fail to fully leverage gene-related information, and solely rely on simple evaluation metrics to construct coarse-grained GRN. More importantly, they ignore functional differences between biotypes, limiting the ability to capture potential gene interactions. In this work, we leverage pre-trained large language model and DNA sequence model to extract features from gene descriptions and DNA sequence data, respectively, which serve as the initialization for gene representations. Additionally, we introduce gene biotype information for the first time in genetic perturbation, simulating the distinct roles of genes with different biotypes in regulating cellular processes, while capturing implicit gene relationships through graph structure learning (GSL). We propose GRAPE, a heterogeneous graph neural network (HGNN) that leverages gene representations initialized with features from descriptions and sequences, models the distinct roles of genes with different biotypes, and dynamically refines the GRN through GSL. The results on publicly available datasets show that our method achieves state-of-the-art performance.

[Arxiv](https://arxiv.org/abs/2505.03853)