# 基于概率提示分布的学习方法用于动物姿态估计

发布时间：2025年03月20日

`其他` `计算机视觉` `动物学`

> Probabilistic Prompt Distribution Learning for Animal Pose Estimation

# 摘要

> 多物种动物姿态估计是一项充满挑战但又至关重要的任务，因其巨大的视觉多样性和不确定性而备受关注。本文提出了一种基于视觉-语言预训练模型（VLP）的高效提示学习方法，如CLIP，旨在解决跨物种的泛化难题。我们的解决方案以提示设计、概率提示建模和跨模态适应为核心，使提示能够弥补跨模态信息的不足，并有效应对数据分布不平衡带来的大规模数据差异。为此，我们提出了一种新颖的概率提示方法，充分挖掘文本描述的潜力，从而缓解长尾属性带来的多样性问题，并增强提示在未见类别实例上的适应能力。具体而言，我们首先引入了一组可学习的提示，并提出了一种多样性损失来保持提示之间的差异性，从而更好地表示多样化的图像属性。接着，我们从文本中采样多样化的概率表示，并将其作为姿态估计的指导。随后，我们在空间级别探索了三种不同的跨模态融合策略，以有效缓解视觉不确定性带来的不利影响。在多物种动物姿态估计基准测试上的广泛实验表明，我们的方法在监督和零样本设置下均达到了当前最优性能。代码可在https://github.com/Raojiyong/PPAP获取。

> Multi-species animal pose estimation has emerged as a challenging yet critical task, hindered by substantial visual diversity and uncertainty. This paper challenges the problem by efficient prompt learning for Vision-Language Pretrained (VLP) models, \textit{e.g.} CLIP, aiming to resolve the cross-species generalization problem. At the core of the solution lies in the prompt designing, probabilistic prompt modeling and cross-modal adaptation, thereby enabling prompts to compensate for cross-modal information and effectively overcome large data variances under unbalanced data distribution. To this end, we propose a novel probabilistic prompting approach to fully explore textual descriptions, which could alleviate the diversity issues caused by long-tail property and increase the adaptability of prompts on unseen category instance. Specifically, we first introduce a set of learnable prompts and propose a diversity loss to maintain distinctiveness among prompts, thus representing diverse image attributes. Diverse textual probabilistic representations are sampled and used as the guidance for the pose estimation. Subsequently, we explore three different cross-modal fusion strategies at spatial level to alleviate the adverse impacts of visual uncertainty. Extensive experiments on multi-species animal pose benchmarks show that our method achieves the state-of-the-art performance under both supervised and zero-shot settings. The code is available at https://github.com/Raojiyong/PPAP.

[Arxiv](https://arxiv.org/abs/2503.16120)