# 以分布一致性为导向的多模态哈希

发布时间：2024年12月19日

`其他` `多模态检索` `数据标注`

> Distribution-Consistency-Guided Multi-modal Hashing

# 摘要

> 多模态哈希方法因速度快、存储需求低而广受欢迎。其中，有监督方法借助标签作为监督信号，性能优于无监督方法。当下，几乎所有有监督的多模态哈希方法都有一个隐含假设，即训练集不存在噪声标签。但在实际场景中，由于人工标注，标签常被错误标注，这会严重影响检索性能。为解决此问题，我们首先通过实验发现了一种显著的分布一致性模式，即标签中每个类别存在与否的 1-0 分布与相对于类别中心的哈希码相似性得分的高低分布一致。受此模式启发，我们提出了一种新颖的分布一致性引导的多模态哈希（DCGMH）方法，旨在过滤和重构噪声标签以提升检索性能。具体而言，该方法先随机初始化若干类别中心，用于计算相似性得分的高低分布；接着依据发现的分布一致性模式分别滤除噪声标签和干净标签，以降低噪声标签的影响；随后，将依据分布一致性模式间接设计的校正策略应用于过滤后的噪声标签，校正高置信度标签，同时将低置信度标签视为未标注用于无监督学习，从而进一步提升模型性能。在三个广泛使用的数据集上开展的大量实验表明，在多模态检索任务中，所提方法优于最先进的基线。代码可在 https://github.com/LiuJinyu1229/DCGMH 获取。

> Multi-modal hashing methods have gained popularity due to their fast speed and low storage requirements. Among them, the supervised methods demonstrate better performance by utilizing labels as supervisory signals compared with unsupervised methods. Currently, for almost all supervised multi-modal hashing methods, there is a hidden assumption that training sets have no noisy labels. However, labels are often annotated incorrectly due to manual labeling in real-world scenarios, which will greatly harm the retrieval performance. To address this issue, we first discover a significant distribution consistency pattern through experiments, i.e., the 1-0 distribution of the presence or absence of each category in the label is consistent with the high-low distribution of similarity scores of the hash codes relative to category centers. Then, inspired by this pattern, we propose a novel Distribution-Consistency-Guided Multi-modal Hashing (DCGMH), which aims to filter and reconstruct noisy labels to enhance retrieval performance. Specifically, the proposed method first randomly initializes several category centers, which are used to compute the high-low distribution of similarity scores; Noisy and clean labels are then separately filtered out via the discovered distribution consistency pattern to mitigate the impact of noisy labels; Subsequently, a correction strategy, which is indirectly designed via the distribution consistency pattern, is applied to the filtered noisy labels, correcting high-confidence ones while treating low-confidence ones as unlabeled for unsupervised learning, thereby further enhancing the model's performance. Extensive experiments on three widely used datasets demonstrate the superiority of the proposed method compared to state-of-the-art baselines in multi-modal retrieval tasks. The code is available at https://github.com/LiuJinyu1229/DCGMH.

[Arxiv](https://arxiv.org/abs/2412.11216)