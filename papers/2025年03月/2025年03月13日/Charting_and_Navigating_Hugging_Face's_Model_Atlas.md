# # 探索与导航 Hugging Face 的模型图谱

发布时间：2025年03月13日

`其他` `数据科学` `计算机视觉`

> Charting and Navigating Hugging Face's Model Atlas

# 摘要

> 面对数百万个公开可用的神经网络，搜索和分析大型模型库变得日益重要。然而，由于大多数模型文档记录不完整，面对如此众多的模型，我们需要一个图谱来导航，但绘制这样的图谱仍然充满挑战。为了挖掘模型库的隐藏潜力，我们绘制了一个初步的图谱，代表了Hugging Face文档的一部分。它提供了模型格局和演化的惊人可视化效果。我们展示了这个图谱的几个应用，包括预测模型属性（例如准确性），以及分析计算机视觉模型的趋势。然而，由于当前图谱仍然不完整，我们提出了一种绘制未记录区域的方法。具体而言，我们基于主导的现实世界模型训练实践，识别出高置信度的结构先验。利用这些先验，我们的方法能够准确地绘制出之前未记录的图谱区域。我们公开发布了我们的数据集、代码和交互式图谱，以促进更广泛的研究与应用。

> As there are now millions of publicly available neural networks, searching and analyzing large model repositories becomes increasingly important. Navigating so many models requires an atlas, but as most models are poorly documented charting such an atlas is challenging. To explore the hidden potential of model repositories, we chart a preliminary atlas representing the documented fraction of Hugging Face. It provides stunning visualizations of the model landscape and evolution. We demonstrate several applications of this atlas including predicting model attributes (e.g., accuracy), and analyzing trends in computer vision models. However, as the current atlas remains incomplete, we propose a method for charting undocumented regions. Specifically, we identify high-confidence structural priors based on dominant real-world model training practices. Leveraging these priors, our approach enables accurate mapping of previously undocumented areas of the atlas. We publicly release our datasets, code, and interactive atlas.

[Arxiv](https://arxiv.org/abs/2503.10633)