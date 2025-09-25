# 基于核心-边界感知的过采样与欠采样：一种数据质量驱动方法

发布时间：2025年09月24日

`其他` `基础理论`

> Oversampling and Downsampling with Core-Boundary Awareness: A Data Quality-Driven Approach

# 摘要

> 在不平衡分类任务中，机器学习模型的性能常受限于无法区分两类数据：决策边界附近的关键实例与数据分布核心的冗余样本。为此，本文提出一种系统识别并区分这两类数据的方法。我们通过在多个基准数据集上的大量实验发现：边界数据过采样方法在96%的数据集上F1分数提升高达10%；而核心感知约简方法能将数据集压缩90%且保持准确性，性能较原始数据集提升10倍。除不平衡分类外，该方法在高效模型训练中具有更广泛的应用前景，尤其适用于大型语言模型（LLM）训练等计算密集型领域。通过优先选择高质量、与决策相关的数据，该方法可扩展至文本、多模态及自监督学习场景，为实现更快收敛、更强泛化能力及大幅节省计算资源提供了可能。这项研究为数据高效学习领域的未来探索奠定了基础——智能采样将取代暴力扩张，引领下一代人工智能的进步。相关代码已封装为Python包，可通过https://pypi.org/project/adaptive-resampling/获取。

> The effectiveness of machine learning models, particularly in unbalanced classification tasks, is often hindered by the failure to differentiate between critical instances near the decision boundary and redundant samples concentrated in the core of the data distribution. In this paper, we propose a method to systematically identify and differentiate between these two types of data. Through extensive experiments on multiple benchmark datasets, we show that the boundary data oversampling method improves the F1 score by up to 10\% on 96\% of the datasets, whereas our core-aware reduction method compresses datasets up to 90\% while preserving their accuracy, making it 10 times more powerful than the original dataset. Beyond imbalanced classification, our method has broader implications for efficient model training, particularly in computationally expensive domains such as Large Language Model (LLM) training. By prioritizing high-quality, decision-relevant data, our approach can be extended to text, multimodal, and self-supervised learning scenarios, offering a pathway to faster convergence, improved generalization, and significant computational savings. This work paves the way for future research in data-efficient learning, where intelligent sampling replaces brute-force expansion, driving the next generation of AI advancements. Our code is available as a Python package at https://pypi.org/project/adaptive-resampling/ .

[Arxiv](https://arxiv.org/abs/2509.19856)