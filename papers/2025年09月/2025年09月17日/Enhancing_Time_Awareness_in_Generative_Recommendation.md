# 提升生成式推荐的时间感知能力

发布时间：2025年09月17日

`LLM应用` `零售与电商`

> Enhancing Time Awareness in Generative Recommendation

# 摘要

> 生成式推荐作为一种极具潜力的范式应运而生，它将推荐任务转化为文本到文本的生成问题，充分利用大型语言模型的海量知识。然而，现有研究多关注物品的顺序，却忽略了物品间的时间动态——这些动态恰恰能反映用户偏好的演变。针对这一不足，我们提出一种新型模型——生成式时间感知推荐模型（GRUT），借助多种时间信号有效捕捉用户的隐藏偏好。我们首先提出时间感知提示，包含两个核心上下文：用户级时间上下文用于建模跨时间戳和时间间隔的个性化时间模式，而物品级过渡上下文则提供用户间的过渡模式。我们还设计了趋势感知推理机制，这是一种无需训练的方法，通过融合物品的趋势信息与生成概率来优化排序。大量实验结果显示，GRUT性能超越现有最优模型，在Recall@5和NDCG@5指标上，在四个基准数据集上的提升分别高达15.4%和14.3%。相关源代码已开源，地址为https://github.com/skleee/GRUT。

> Generative recommendation has emerged as a promising paradigm that formulates the recommendations into a text-to-text generation task, harnessing the vast knowledge of large language models. However, existing studies focus on considering the sequential order of items and neglect to handle the temporal dynamics across items, which can imply evolving user preferences. To address this limitation, we propose a novel model, Generative Recommender Using Time awareness (GRUT), effectively capturing hidden user preferences via various temporal signals. We first introduce Time-aware Prompting, consisting of two key contexts. The user-level temporal context models personalized temporal patterns across timestamps and time intervals, while the item-level transition context provides transition patterns across users. We also devise Trend-aware Inference, a training-free method that enhances rankings by incorporating trend information about items with generation likelihood. Extensive experiments demonstrate that GRUT outperforms state-of-the-art models, with gains of up to 15.4% and 14.3% in Recall@5 and NDCG@5 across four benchmark datasets. The source code is available at https://github.com/skleee/GRUT.

[Arxiv](https://arxiv.org/abs/2509.13957)