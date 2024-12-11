# CBraMod：一种用于脑电图解码的交叉大脑基础模型

发布时间：2024年12月10日

`其他` `脑机接口`

> CBraMod: A Criss-Cross Brain Foundation Model for EEG Decoding

# 摘要

> 脑电图（EEG）作为一种非侵入式技术，用于测量和记录大脑电活动，在各类脑机接口（BCI）及医疗保健应用中广泛运用。早期的脑电图解码方法依赖监督学习，受特定任务和数据集所限，阻碍了模型性能与泛化能力。随着大型语言模型取得成功，越来越多的研究聚焦于脑电图基础模型。然而，这些研究仍面临挑战：其一，多数现有的脑电图基础模型采用全脑电图建模策略，将所有脑电图斑块间的空间和时间依赖性一并建模，却忽略了因脑电图信号独特的结构特征，其空间和时间依赖性是异质的。其二，由于脑电图数据格式各异，现有的脑电图基础模型在广泛的下游 BCI 任务中的泛化能力有限，难以适应。为应对这些挑战，我们提出了一种名为 CBraMod 的新型基础模型。具体而言，我们设计了一个交叉变压器作为核心，充分利用脑电图信号的结构特征，它能通过两个并行的注意力机制分别对空间和时间依赖性进行建模。并且我们采用了一种非对称条件位置编码方案，能够对脑电图斑块的位置信息进行编码，且易于适应各种格式的脑电图。CBraMod 通过基于斑块的掩码脑电图重建在庞大的脑电图语料库上进行了预训练。我们在多达 10 个下游 BCI 任务（12 个公共数据集）上对 CBraMod 进行了评估。CBraMod 在众多任务中达到了领先水平，展现出强大的能力和泛化能力。源代码在 url{https://github.com/wjq-learning/CBraMod} 公开可获取。

> Electroencephalography (EEG) is a non-invasive technique to measure and record brain electrical activity, widely used in various BCI and healthcare applications. Early EEG decoding methods rely on supervised learning, limited by specific tasks and datasets, hindering model performance and generalizability. With the success of large language models, there is a growing body of studies focusing on EEG foundation models. However, these studies still leave challenges: Firstly, most of existing EEG foundation models employ full EEG modeling strategy. It models the spatial and temporal dependencies between all EEG patches together, but ignores that the spatial and temporal dependencies are heterogeneous due to the unique structural characteristics of EEG signals. Secondly, existing EEG foundation models have limited generalizability on a wide range of downstream BCI tasks due to varying formats of EEG data, making it challenging to adapt to. To address these challenges, we propose a novel foundation model called CBraMod. Specifically, we devise a criss-cross transformer as the backbone to thoroughly leverage the structural characteristics of EEG signals, which can model spatial and temporal dependencies separately through two parallel attention mechanisms. And we utilize an asymmetric conditional positional encoding scheme which can encode positional information of EEG patches and be easily adapted to the EEG with diverse formats. CBraMod is pre-trained on a very large corpus of EEG through patch-based masked EEG reconstruction. We evaluate CBraMod on up to 10 downstream BCI tasks (12 public datasets). CBraMod achieves the state-of-the-art performance across the wide range of tasks, proving its strong capability and generalizability. The source code is publicly available at url{https://github.com/wjq-learning/CBraMod}.

[Arxiv](https://arxiv.org/abs/2412.07236)