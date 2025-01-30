# 增强基于文本的人物搜索中的弱阳性样本

发布时间：2025年01月29日

`其他

理由：这篇论文主要讨论的是大型视觉语言模型在跨模态对象检索领域的应用，特别是针对基于文本的人物搜索（TBPS）的挑战。虽然涉及到了视觉语言模型，但主要内容集中在数据增强技术和模型训练策略上，而不是直接讨论LLM的理论、应用、Agent或RAG。因此，将其分类为“其他”更为合适。` `计算机视觉` `跨模态检索`

> Boosting Weak Positives for Text Based Person Search

# 摘要

> 大型视觉语言模型在跨模态对象检索领域取得了革命性进展，但基于文本的人物搜索（TBPS）由于数据稀缺和任务细粒度特性，仍面临挑战。现有方法大多聚焦于将图像-文本对映射到同一表示空间，却忽视了现实中正样本对之间相似度的多样性。这导致模型倾向于简单样本，甚至在某些最新方法中，挑战性样本被误判为噪声而丢弃。为此，我们提出了一种动态增强技术，在训练中识别并强化这些困难样本。该方法借鉴经典增强思想，动态调整弱正样本权重，特别是那些排名第一但与查询身份不符的样本。通过赋予这些误判样本更高的损失权重，迫使网络更加关注它们。实验表明，我们的方法在四个行人数据集上均取得了性能提升，验证了所提模块的有效性。

> Large vision-language models have revolutionized cross-modal object retrieval, but text-based person search (TBPS) remains a challenging task due to limited data and fine-grained nature of the task. Existing methods primarily focus on aligning image-text pairs into a common representation space, often disregarding the fact that real world positive image-text pairs share a varied degree of similarity in between them. This leads models to prioritize easy pairs, and in some recent approaches, challenging samples are discarded as noise during training. In this work, we introduce a boosting technique that dynamically identifies and emphasizes these challenging samples during training. Our approach is motivated from classical boosting technique and dynamically updates the weights of the weak positives, wherein, the rank-1 match does not share the identity of the query. The weight allows these misranked pairs to contribute more towards the loss and the network has to pay more attention towards such samples. Our method achieves improved performance across four pedestrian datasets, demonstrating the effectiveness of our proposed module.

[Arxiv](https://arxiv.org/abs/2501.17586)