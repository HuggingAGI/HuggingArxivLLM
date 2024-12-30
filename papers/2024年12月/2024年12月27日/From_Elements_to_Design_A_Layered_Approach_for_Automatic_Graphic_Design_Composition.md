# 从元素走向设计：自动图形设计合成的分层式途径

发布时间：2024年12月27日

`其他` `图形设计` `自动设计`

> From Elements to Design: A Layered Approach for Automatic Graphic Design Composition

# 摘要

> 在这项工作中，我们探究了由多模态图形元素构成的自动设计组合。尽管近来的研究为图形设计开发了各类生成模型，但它们往往存在如下局限：只聚焦于某些子任务，远未达成设计组合任务；在生成过程中，不考虑图形设计的分层信息。为应对这些问题，我们把分层设计原则引入大型多模态模型（LMMs），并提出一种新颖的方法——LaDeCo，来完成这一颇具挑战的任务。具体而言，LaDeCo 首先针对给定的元素集进行层规划，依据元素内容将其划分到不同的语义层。基于规划结果，它接着以分层的方式预测控制设计组合的元素属性，并把先前生成层的渲染图像纳入上下文。凭借这一富有洞察力的设计，LaDeCo 将艰巨的任务拆解为更小的、易于管理的步骤，让生成过程更顺畅、更清晰。实验结果表明 LaDeCo 在设计组合方面的有效性。此外，我们展示了 LaDeCo 在图形设计中的一些有趣应用，比如分辨率调整、元素填充、设计变化等。而且，在没有任何针对特定任务的训练情况下，它在某些设计子任务中的表现甚至优于专门的模型。

> In this work, we investigate automatic design composition from multimodal graphic elements. Although recent studies have developed various generative models for graphic design, they usually face the following limitations: they only focus on certain subtasks and are far from achieving the design composition task; they do not consider the hierarchical information of graphic designs during the generation process. To tackle these issues, we introduce the layered design principle into Large Multimodal Models (LMMs) and propose a novel approach, called LaDeCo, to accomplish this challenging task. Specifically, LaDeCo first performs layer planning for a given element set, dividing the input elements into different semantic layers according to their contents. Based on the planning results, it subsequently predicts element attributes that control the design composition in a layer-wise manner, and includes the rendered image of previously generated layers into the context. With this insightful design, LaDeCo decomposes the difficult task into smaller manageable steps, making the generation process smoother and clearer. The experimental results demonstrate the effectiveness of LaDeCo in design composition. Furthermore, we show that LaDeCo enables some interesting applications in graphic design, such as resolution adjustment, element filling, design variation, etc. In addition, it even outperforms the specialized models in some design subtasks without any task-specific training.

[Arxiv](https://arxiv.org/abs/2412.19712)