# # 缓解多模态空间关系中的幻觉：通过约束感知提示方法

发布时间：2025年02月12日

`LLM应用` `计算机视觉` `图像生成`

> Mitigating Hallucinations in Multimodal Spatial Relations through Constraint-Aware Prompting

# 摘要

> 空间关系幻觉一直是大型视觉语言模型（LVLMs）的顽疾，常导致对图像中物体位置和空间布局的错误预测。为解决这一难题，我们提出了一种基于约束感知的提示框架，旨在减少空间关系幻觉。具体来说，我们引入了两种约束：(1) 双向约束，确保物体间配对关系的一致性；(2) 传递性约束，强制多个物体间的关系依赖。通过整合这些约束，LVLMs能够生成更具有空间连贯性和一致性的输出。我们在三个广泛使用的空间关系数据集上评估了我们的方法，结果显示其性能优于现有方法。此外，对各种双向关系分析选择和传递性参考选择的系统性分析，进一步凸显了我们的方法在通过约束缓解空间关系幻觉方面的潜力。

> Spatial relation hallucinations pose a persistent challenge in large vision-language models (LVLMs), leading to generate incorrect predictions about object positions and spatial configurations within an image. To address this issue, we propose a constraint-aware prompting framework designed to reduce spatial relation hallucinations. Specifically, we introduce two types of constraints: (1) bidirectional constraint, which ensures consistency in pairwise object relations, and (2) transitivity constraint, which enforces relational dependence across multiple objects. By incorporating these constraints, LVLMs can produce more spatially coherent and consistent outputs. We evaluate our method on three widely-used spatial relation datasets, demonstrating performance improvements over existing approaches. Additionally, a systematic analysis of various bidirectional relation analysis choices and transitivity reference selections highlights greater possibilities of our methods in incorporating constraints to mitigate spatial relation hallucinations.

[Arxiv](https://arxiv.org/abs/2502.08317)