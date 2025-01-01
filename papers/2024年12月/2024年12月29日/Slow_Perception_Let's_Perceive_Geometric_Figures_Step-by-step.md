# 缓慢感知：让我们一步步感知几何图形

发布时间：2024年12月29日

`LLM应用` `视觉推理` `几何数学`

> Slow Perception: Let's Perceive Geometric Figures Step-by-step

# 摘要

> 近来，“视觉 o1”逐渐走入人们的视线，大家期望这种慢思考的设计能搞定视觉推理任务，尤其是几何数学难题。但实际情况是，当下的 LVLMs（大型视觉语言模型）连一个几何图形都难以准确复制，更别提真正领会几何形状里复杂的内在逻辑和空间关系了。我们觉得准确复制（强感知）是视觉 o1 的首要步骤。于是，我们引入了“慢感知”（SP）的概念，引导模型像人类一样逐步感知基本的点线组合，逐步重构复杂的几何结构。SP 包含两个阶段：a）感知分解。感知并非瞬间完成的。在这一阶段，复杂的几何图形会被拆解为基本的简单单元，以统一几何表示。b）感知流，要知道准确追踪一条线并非易事。此阶段旨在利用提出的“感知尺子”一笔一划地追踪每条线，避免在回归线段时出现“长视觉跳跃”。令人惊奇的是，这种类人的感知方式遵循推理时间缩放定律——越慢越好。以往，研究人员致力于加快模型的感知速度，而我们却再次将其放慢，让模型一步步仔细读取图像。

> Recently, "visual o1" began to enter people's vision, with expectations that this slow-thinking design can solve visual reasoning tasks, especially geometric math problems. However, the reality is that current LVLMs (Large Vision Language Models) can hardly even accurately copy a geometric figure, let alone truly understand the complex inherent logic and spatial relationships within geometric shapes. We believe accurate copying (strong perception) is the first step to visual o1. Accordingly, we introduce the concept of "slow perception" (SP), which guides the model to gradually perceive basic point-line combinations, as our humans, reconstruct complex geometric structures progressively. There are two-fold stages in SP: a) perception decomposition. Perception is not instantaneous. In this stage, complex geometric figures are broken down into basic simple units to unify geometry representation. b) perception flow, which acknowledges that accurately tracing a line is not an easy task. This stage aims to avoid "long visual jumps" in regressing line segments by using a proposed "perceptual ruler" to trace each line stroke-by-stroke. Surprisingly, such a human-like perception manner enjoys an inference time scaling law -- the slower, the better. Researchers strive to speed up the model's perception in the past, but we slow it down again, allowing the model to read the image step-by-step and carefully.

[Arxiv](https://arxiv.org/abs/2412.20631)