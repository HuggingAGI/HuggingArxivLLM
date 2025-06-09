# # SAVVY：通过视觉与听觉实现空间感知的音频视觉大语言模型

发布时间：2025年06月04日

`LLM应用` `计算机视觉` `音频处理`

> SAVVY: Spatial Awareness via Audio-Visual LLMs through Seeing and Hearing

# 摘要

> 在动态视听环境中进行3D空间推理是人类认知的基石，但现有视听大语言模型（AV-LLMs）及基准测试主要集中在静态或2D场景，对这一领域的探索仍十分有限。我们推出SAVVY-Bench，这是首个针对动态场景中3D空间推理的基准测试，特别注重同步空间音频的运用。SAVVY-Bench包含数千个涉及静止与移动物体的关系，要求实现精准的时间定位、一致的3D定位以及多模态标注。为应对这一挑战，我们提出SAVVY，一种无需训练的推理流水线，包含两个阶段：(i) 第一阶段为自我中心空间轨迹估计，利用AV-LLMs及其他视听方法，通过视觉和空间音频线索追踪与查询相关的关键物体轨迹；(ii) 第二阶段为动态全局地图构建，整合多模态查询物体轨迹并将其转换为统一的全局动态地图。通过构建的地图，最终通过坐标变换将全局地图与查询视点对齐，获得QA答案。实证评估表明，SAVVY显著提升了现有先进AV-LLMs的性能，为动态3D空间推理设定了新的标准和研究方向。

> 3D spatial reasoning in dynamic, audio-visual environments is a cornerstone of human cognition yet remains largely unexplored by existing Audio-Visual Large Language Models (AV-LLMs) and benchmarks, which predominantly focus on static or 2D scenes. We introduce SAVVY-Bench, the first benchmark for 3D spatial reasoning in dynamic scenes with synchronized spatial audio. SAVVY-Bench is comprised of thousands of relationships involving static and moving objects, and requires fine-grained temporal grounding, consistent 3D localization, and multi-modal annotation. To tackle this challenge, we propose SAVVY, a novel training-free reasoning pipeline that consists of two stages: (i) Egocentric Spatial Tracks Estimation, which leverages AV-LLMs as well as other audio-visual methods to track the trajectories of key objects related to the query using both visual and spatial audio cues, and (ii) Dynamic Global Map Construction, which aggregates multi-modal queried object trajectories and converts them into a unified global dynamic map. Using the constructed map, a final QA answer is obtained through a coordinate transformation that aligns the global map with the queried viewpoint. Empirical evaluation demonstrates that SAVVY substantially enhances performance of state-of-the-art AV-LLMs, setting a new standard and stage for approaching dynamic 3D spatial reasoning in AV-LLMs.

[Arxiv](https://arxiv.org/abs/2506.05414)