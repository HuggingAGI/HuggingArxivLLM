# # TabFlex: 基于线性注意力机制的百万级别表格学习扩展

发布时间：2025年06月05日

`LLM应用` `数据处理`

> TabFlex: Scaling Tabular Learning to Millions with Linear Attention

# 摘要

> 大型语言模型（LLMs）的上下文学习（ICL）能力在表格分类任务中展现出无需训练即可适应多种数据集的特性，备受研究者关注。近期的TabPFN在小规模表格数据集上表现优异，但面对大规模复杂数据集时遇到了瓶颈。我们的研究通过引入线性注意力机制，成功为复杂度二次的自注意力机制提供了可扩展的替代方案，显著提升了TabPFN在大规模数据集上的效率和扩展性。我们的模型TabFlex能够高效处理包含数千个特征和数百个类别的表格数据集，并可轻松扩展至数百万个样本。例如，TabFlex仅需5秒即可完成对包含逾百万样本的德州扑克牌型数据集的处理。通过全面的性能评估，我们发现TabFlex相较于TabPFN实现了超过2倍的速度提升，相较于经典的XGBoost算法则提升了1.5倍。在涵盖多种数据集的测试中，TabFlex在效率方面超越了25个基准模型。此外，TabFlex在大规模数据集上表现尤为出色，不仅性能强劲，且计算成本大幅降低。尤其当结合降维和数据采样等数据高效技术时，其优势更加明显。

> Leveraging the in-context learning (ICL) capability of Large Language Models (LLMs) for tabular classification has gained significant attention for its training-free adaptability across diverse datasets. Recent advancements, like TabPFN, excel in small-scale tabular datasets but struggle to scale for large and complex datasets. Our work enhances the efficiency and scalability of TabPFN for larger datasets by incorporating linear attention mechanisms as a scalable alternative to complexity-quadratic self-attention. Our model, TabFlex, efficiently handles tabular datasets with thousands of features and hundreds of classes, scaling seamlessly to millions of samples. For instance, TabFlex processes the poker-hand dataset with over a million samples in just 5 seconds. Our extensive evaluations demonstrate that TabFlex can achieve over a 2x speedup compared to TabPFN and a 1.5x speedup over XGBoost, outperforming 25 tested baselines in terms of efficiency across a diverse range of datasets. Furthermore, TabFlex remains highly effective on large-scale datasets, delivering strong performance with significantly reduced computational costs, especially when combined with data-efficient techniques such as dimensionality reduction and data sampling.

[Arxiv](https://arxiv.org/abs/2506.05584)