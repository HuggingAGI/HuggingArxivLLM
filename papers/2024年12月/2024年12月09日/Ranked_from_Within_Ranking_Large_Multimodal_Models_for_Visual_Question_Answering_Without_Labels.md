# 《从内部排名：无标签情况下对用于视觉问答的大型多模态模型进行排序》

发布时间：2024年12月09日

`LLM应用` `视觉问答` `模型评估`

> Ranked from Within: Ranking Large Multimodal Models for Visual Question Answering Without Labels

# 摘要

> 随着大型多模态模型（LMMs）在各类应用中的广泛部署，对具有适应性的真实世界模型排名的需求变得极为关键。传统评估方法多以数据集为核心，依赖固定且有标签的数据集以及监督指标，不仅资源消耗大，而且在新场景中可能缺乏通用性，这凸显了无监督排名的重要性。在本研究中，我们借助其不确定性信号（如 softmax 概率）探索 LMMs 的无监督模型排名。我们在视觉问答基准上评估了前沿的 LMMs（如 LLaVA），分析基于不确定性的指标如何反映模型性能。我们的发现表明，从 softmax 分布得出的不确定性分数为不同任务中的模型排名提供了坚实且一致的依据。这一发现实现了在真实世界的未标记数据上对 LMMs 进行视觉问答排名，为在不同领域选择模型提供了无需手动标注的实用途径。

> As large multimodal models (LMMs) are increasingly deployed across diverse applications, the need for adaptable, real-world model ranking has become paramount. Traditional evaluation methods are largely dataset-centric, relying on fixed, labeled datasets and supervised metrics, which are resource-intensive and may lack generalizability to novel scenarios, highlighting the importance of unsupervised ranking. In this work, we explore unsupervised model ranking for LMMs by leveraging their uncertainty signals, such as softmax probabilities. We evaluate state-of-the-art LMMs (e.g., LLaVA) across visual question answering benchmarks, analyzing how uncertainty-based metrics can reflect model performance. Our findings show that uncertainty scores derived from softmax distributions provide a robust, consistent basis for ranking models across varied tasks. This finding enables the ranking of LMMs on real-world, unlabeled data for visual question answering, providing a practical approach for selecting models across diverse domains without requiring manual annotation.

[Arxiv](https://arxiv.org/abs/2412.06461)