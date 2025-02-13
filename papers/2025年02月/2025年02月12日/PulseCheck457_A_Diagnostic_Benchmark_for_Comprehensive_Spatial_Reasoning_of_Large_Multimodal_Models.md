# PulseCheck457：面向大型多模态模型全面空间推理能力的诊断评测基准

发布时间：2025年02月12日

`LLM应用` `计算机视觉` `机器人学`

> PulseCheck457: A Diagnostic Benchmark for Comprehensive Spatial Reasoning of Large Multimodal Models

# 摘要

> 尽管大型多模态模型（LMMs）在视觉场景解释和推理方面表现卓越，但其在复杂且精确的三维空间推理能力上仍有待验证。现有基准测试主要聚焦于二维空间理解，缺乏全面评估6D空间推理能力的框架。为此，我们推出PulseCheck457，一个可扩展且无偏见的合成数据集，基于多物体识别、二维位置、三维位置和三维方向4个关键能力设计。我们构建了涵盖5个难度等级的7种问题类型，从基本的单物体识别到全新的复杂6D空间推理任务。实验结果显示，随着任务复杂度的增加，模型性能普遍下降，尤其在三维推理和6D空间任务中表现明显。我们引入相对性能下降率（RPDR）量化这些挑战，揭示了三维推理能力的关键弱点。通过分析数据集的无偏见属性设计，我们发现不同属性的预测偏见，并在真实世界图像设置中观察到类似模式。

> Although large multimodal models (LMMs) have demonstrated remarkable capabilities in visual scene interpretation and reasoning, their capacity for complex and precise 3-dimensional spatial reasoning remains uncertain. Existing benchmarks focus predominantly on 2D spatial understanding and lack a framework to comprehensively evaluate 6D spatial reasoning across varying complexities. To address this limitation, we present PulseCheck457, a scalable and unbiased synthetic dataset designed with 4 key capability for spatial reasoning: multi-object recognition, 2D location, 3D location, and 3D orientation. We develop a cascading evaluation structure, constructing 7 question types across 5 difficulty levels that range from basic single object recognition to our new proposed complex 6D spatial reasoning tasks. We evaluated various large multimodal models (LMMs) on PulseCheck457, observing a general decline in performance as task complexity increases, particularly in 3D reasoning and 6D spatial tasks. To quantify these challenges, we introduce the Relative Performance Dropping Rate (RPDR), highlighting key weaknesses in 3D reasoning capabilities. Leveraging the unbiased attribute design of our dataset, we also uncover prediction biases across different attributes, with similar patterns observed in real-world image settings.

[Arxiv](https://arxiv.org/abs/2502.08636)