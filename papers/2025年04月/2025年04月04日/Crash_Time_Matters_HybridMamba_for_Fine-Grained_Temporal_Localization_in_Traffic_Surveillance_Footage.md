# 撞车时间至关重要：HybridMamba实现交通监控视频中的细粒度时间定位

发布时间：2025年04月04日

`其他` `交通监控` `视频分析`

> Crash Time Matters: HybridMamba for Fine-Grained Temporal Localization in Traffic Surveillance Footage

# 摘要

> # 摘要
在长视频监控中进行交通事故检测对于应急响应和基础设施规划至关重要，但由于碰撞事件短暂且罕见，这一任务仍然具有挑战性。我们提出了HybridMamba，一种结合视觉变换器与状态空间时间建模的新型架构，以实现精准的碰撞时间定位。我们的方法通过多级令牌压缩和分层时间处理，在不降低时间分辨率的情况下保持计算效率。在爱荷华州交通部提供的大规模数据集上进行评估，HybridMamba达到了1.50秒的平均绝对误差，其中65.2%的预测结果与真实值相差不超过一秒。与近期的视频-语言模型如TimeChat和VideoLLaMA2相比，HybridMamba的误差减少了多达2.8秒，同时参数量显著减少。我们的结果表明，HybridMamba在不同条件下时长从2分钟到40分钟的视频中具有强大的泛化能力。HybridMamba为交通监控中的精细时间定位提供了一个强大且高效的解决方案。代码将在论文发表后公开。

> Traffic crash detection in long-form surveillance videos is critical for emergency response and infrastructure planning but remains difficult due to the brief and rare nature of crash events. We introduce HybridMamba, a novel architecture that combines visual transformers with state-space temporal modeling to achieve accurate crash time localization. Our method uses multi-level token compression and hierarchical temporal processing to remain computationally efficient without sacrificing temporal resolution. Evaluated on a large-scale dataset from the Iowa Department of Transportation, HybridMamba achieves a mean absolute error of 1.50 seconds, with 65.2 percent of predictions within one second of the ground truth. It outperforms recent video-language models such as TimeChat and VideoLLaMA2 by up to 2.8 seconds, while using significantly fewer parameters. Our results demonstrate strong generalization across videos ranging from 2 to 40 minutes in diverse conditions. HybridMamba offers a robust and efficient solution for fine-grained temporal localization in traffic surveillance. The code will be released upon publication.

[Arxiv](https://arxiv.org/abs/2504.03235)