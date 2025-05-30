# 通往成功的阶梯：零样本楼层感知目标导向导航，基于LLM驱动的粗细结合探索。

发布时间：2025年05月28日

`Agent` `机器人`

> Stairway to Success: Zero-Shot Floor-Aware Object-Goal Navigation via LLM-Driven Coarse-to-Fine Exploration

# 摘要

> 目标导向导航（OGN）在多层建筑环境和开放词汇描述的对象中仍具挑战性。观察发现，广泛使用的基准测试如HM3D和MP3D中的大多数场景都涉及多层建筑，其中许多需要明确的楼层转换。然而，现有方法通常局限于单层环境或预定义的对象类别。为了解决这些问题，我们提出了ASCENT框架，该框架结合了用于层次化语义地图构建的多层空间抽象模块，以及利用大型语言模型（LLMs）进行上下文感知探索的粗到细前沿推理模块。我们的方法无需额外针对新对象语义或运动数据进行训练。在HM3D和MP3D基准测试中，我们的方法超越了现有的ZS-OGN方法，同时实现了高效的多层导航。我们进一步通过在四足机器人上的实际部署验证了其实用性，成功实现了跨未知楼层的对象探索。

> Object-Goal Navigation (OGN) remains challenging in real-world, multi-floor environments and under open-vocabulary object descriptions. We observe that most episodes in widely used benchmarks such as HM3D and MP3D involve multi-floor buildings, with many requiring explicit floor transitions. However, existing methods are often limited to single-floor settings or predefined object categories. To address these limitations, we tackle two key challenges: (1) efficient cross-level planning and (2) zero-shot object-goal navigation (ZS-OGN), where agents must interpret novel object descriptions without prior exposure. We propose ASCENT, a framework that combines a Multi-Floor Spatial Abstraction module for hierarchical semantic mapping and a Coarse-to-Fine Frontier Reasoning module leveraging Large Language Models (LLMs) for context-aware exploration, without requiring additional training on new object semantics or locomotion data. Our method outperforms state-of-the-art ZS-OGN approaches on HM3D and MP3D benchmarks while enabling efficient multi-floor navigation. We further validate its practicality through real-world deployment on a quadruped robot, achieving successful object exploration across unseen floors.

[Arxiv](https://arxiv.org/abs/2505.23019)