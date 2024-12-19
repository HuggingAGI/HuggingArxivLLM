# 用于细粒度情感识别的时空面向模糊的多模态元学习

发布时间：2024年12月18日

`其他` `多媒体` `疾病诊断`

> Spatio-Temporal Fuzzy-oriented Multi-Modal Meta-Learning for Fine-grained Emotion Recognition

# 摘要

> 细粒度情感识别（FER）在诸如疾病诊断、个性化推荐以及多媒体挖掘等众多领域都起着关键作用。然而，现有的 FER 方法在实际运用中面临着三大关键挑战：其一，由于现实中的情感复杂且模糊，它们得依靠大量持续标注的数据来保证准确性，这既费钱又费时；其二，它们难以捕捉因情感模式变化而产生的时间异质性，因为它们通常假定采样周期内的时间相关性是一致的；其三，它们未考虑不同 FER 场景的空间异质性，也就是说，不同数据中情感信息的分布可能存在偏差或干扰。为应对这些挑战，我们提出了一个时空模糊导向的多模态元学习框架（ST-F2M）。具体来说，ST-F2M 首先把多模态视频分成多个视图，每个视图对应一种情感的一种模态。针对相同情感的多个随机选取的视图构成一个元训练任务。接着，ST-F2M 运用带有空间和时间卷积的集成模块对每个任务的数据进行编码，体现出空间和时间的异质性。随后，它依据广义模糊规则为每个任务添加模糊语义信息，这有助于应对情感的复杂性和模糊性。最后，ST-F2M 通过元循环神经网络学习与情感相关的通用元知识，从而实现快速且稳健的细粒度情感识别。大量实验表明，ST-F2M 在准确性和模型效率方面都优于各类最先进的方法。此外，我们还构建了消融研究并进行了进一步分析，以探究 ST-F2M 表现出色的缘由。

> Fine-grained emotion recognition (FER) plays a vital role in various fields, such as disease diagnosis, personalized recommendations, and multimedia mining. However, existing FER methods face three key challenges in real-world applications: (i) they rely on large amounts of continuously annotated data to ensure accuracy since emotions are complex and ambiguous in reality, which is costly and time-consuming; (ii) they cannot capture the temporal heterogeneity caused by changing emotion patterns, because they usually assume that the temporal correlation within sampling periods is the same; (iii) they do not consider the spatial heterogeneity of different FER scenarios, that is, the distribution of emotion information in different data may have bias or interference. To address these challenges, we propose a Spatio-Temporal Fuzzy-oriented Multi-modal Meta-learning framework (ST-F2M). Specifically, ST-F2M first divides the multi-modal videos into multiple views, and each view corresponds to one modality of one emotion. Multiple randomly selected views for the same emotion form a meta-training task. Next, ST-F2M uses an integrated module with spatial and temporal convolutions to encode the data of each task, reflecting the spatial and temporal heterogeneity. Then it adds fuzzy semantic information to each task based on generalized fuzzy rules, which helps handle the complexity and ambiguity of emotions. Finally, ST-F2M learns emotion-related general meta-knowledge through meta-recurrent neural networks to achieve fast and robust fine-grained emotion recognition. Extensive experiments show that ST-F2M outperforms various state-of-the-art methods in terms of accuracy and model efficiency. In addition, we construct ablation studies and further analysis to explore why ST-F2M performs well.

[Arxiv](https://arxiv.org/abs/2412.13541)