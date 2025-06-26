# UniMind：释放出 LLMs 的力量，实现统一的多任务脑解码

发布时间：2025年06月23日

`LLM应用` `脑机接口`

> UniMind: Unleashing the Power of LLMs for Unified Multi-Task Brain Decoding

# 摘要

> 从脑电图（EEG）信号中解码人脑活动是神经科学与人工智能交叉领域中的核心挑战，为精神状态评估、临床监测及人机交互等多种应用场景提供了可能性。近期研究大量探索了基于EEG的通用脑基础模型，以实现对脑活动的泛化解码，这些研究采用了跨多数据集的大规模训练方法。然而，由于解码任务间的显著异质性，大多数尝试在不进行特定任务调优的情况下难以达到令人满意的性能。为应对这些挑战，我们提出了UniMind，一种用于统一多任务脑解码的通用EEG基础模型。UniMind通过独特地释放大型语言模型理解复杂神经模式的能力，实现了这一目标。UniMind具有多个优势。首先，我们设计了一个神经-语言连接器，以弥合神经信号与大型语言模型之间的模态差距，将EEG数据的时空神经模式进行蒸馏和转换，生成语言模型可理解的表征。其次，我们提出了一个任务感知查询选择模块，通过动态生成任务自适应查询令牌，将任务感知注入跨模态对齐过程中，从而实现对跨任务相关神经模式的学习。在十个数据集上的广泛实验表明，UniMind显著超越了现有的多任务解码模型，平均提升了12%的性能，同时为跨任务的神经功能关联提供了有价值的神经科学见解。代码将公开发布。

> Decoding human brain activity from electroencephalography (EEG) signals is a central challenge at the intersection of neuroscience and artificial intelligence, enabling diverse applications in mental state assessment, clinical monitoring, and human-machine interaction. Recent efforts have extensively explored EEG-based brain foundation models for generalized brain decoding, employing large-scale training on multiple datasets. However, most of these attempts struggle with generalizability and fail to achieve satisfactory performance without task-specific tuning due to pronounced inherent heterogeneity among decoding tasks. To address these challenges, we present UniMind, a general-purpose EEG foundation model for unified multi-task brain decoding by uniquely unleashing the power of large language models to comprehend complex neural patterns. UniMind offers several advantages. First, we design a Neuro-Language Connector to bridge the modality gap between neural signals and large language models, distilling and transforming the spatiotemporal neural patterns of EEG data into representations understandable by language models. Second, a Task-aware Query Selection module is proposed to inject task-awareness into the cross-modal alignment by dynamically generating task-adaptive query tokens, enabling learning of task-relevant neural patterns across diverse tasks. Extensive experiments across ten datasets demonstrate that UniMind substantially outperforms state-of-the-art multi-task decoding models, with an average gain of 12 percent, while also offering valuable neuroscientific insights into neural functional correlations across tasks. The code will be made publicly available.

[Arxiv](https://arxiv.org/abs/2506.18962)