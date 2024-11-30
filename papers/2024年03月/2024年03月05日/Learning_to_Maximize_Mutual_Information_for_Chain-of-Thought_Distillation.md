# 本研究致力于学习如何优化互信息，以应用于链式思考蒸馏技术中，旨在提升模型对复杂问题的推理能力。

发布时间：2024年03月05日

`Agent`

> Learning to Maximize Mutual Information for Chain-of-Thought Distillation

# 摘要

> 知识蒸馏技术，让大型复杂模型的知识流向小型模型，是实现高效AI部署的重要突破。新提出的“步步蒸馏”（DSS）创新性地运用了链式思考（CoT）的知识蒸馏策略，成功将大型模型的强大推理力注入小型模型中。在该方法下，经过蒸馏的小型模型通过多任务学习机制能同步生成推理依据并预测标签。不过，DSS未充分探究两个训练任务间的内在联系，导致CoT知识在标签预测任务中的融合不够理想。因此，我们从信息瓶颈角度出发，探索两者任务间的关系，并将其表述为最大化两任务特征表示的互信息目标。我们进一步提出一种基于学习的变分方法以求解此优化问题。实验证明，在四个不同数据集上，我们的方法均超越了当前最先进步步蒸馏技术的表现。这些发现为今后的语言模型蒸馏研究及涉及CoT的应用研发提供了深刻启示，相关代码和模型将会很快对外发布。

> Knowledge distillation, the technique of transferring knowledge from large, complex models to smaller ones, marks a pivotal step towards efficient AI deployment. Distilling Step-by-Step (DSS), a novel method utilizing chain-of-thought (CoT) distillation, has demonstrated promise by imbuing smaller models with the superior reasoning capabilities of their larger counterparts. In DSS, the distilled model acquires the ability to generate rationales and predict labels concurrently through a multi-task learning framework. However, DSS overlooks the intrinsic relationship between the two training tasks, leading to ineffective integration of CoT knowledge with the task of label prediction. To this end, we investigate the mutual relationship of the two tasks from Information Bottleneck perspective and formulate it as maximizing the mutual information of the representation features of the two tasks. We propose a variational approach to solve this optimization problem using a learning-based method. Our experimental results across four datasets demonstrate that our method outperforms the state-of-the-art DSS. Our findings offer insightful guidance for future research on language model distillation as well as applications involving CoT. Code and models will be released soon.

[Arxiv](https://arxiv.org/abs/2403.03348)