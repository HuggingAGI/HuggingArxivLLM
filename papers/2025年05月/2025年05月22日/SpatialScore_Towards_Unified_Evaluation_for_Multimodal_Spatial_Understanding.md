# 空间评分：致力于多模态空间理解的统一评估方法

发布时间：2025年05月22日

`LLM应用` `计算机视觉` `空间推理`

> SpatialScore: Towards Unified Evaluation for Multimodal Spatial Understanding

# 摘要

> 多模态大型语言模型 (MLLMs) 在问答任务中表现卓越，但其空间理解能力仍有待深入探索。本研究聚焦一个核心问题：现有的 MLLMs 是否具备 3D 空间感知与理解能力？在本文中，我们做出了以下贡献：

(i) 我们推出 VGBench，一个专为评估 MLLMs 在视觉几何感知（如相机姿势和运动估计）方面能力而设计的基准；

(ii) 我们提出 SpatialScore，这是目前最全面且多样化的多模态空间理解基准，整合了 VGBench 与其他 11 个现有数据集。该基准涵盖 28,000 个样本，涉及多种空间理解任务、模态和问答格式，并包含一个精心策划的高挑战性子集 SpatialScore-Hard；

(iii) 我们开发了 SpatialAgent，一个创新型多智能体系统，集成了 9 个专注于空间理解的工具，支持 Plan-Execute 和 ReAct 两种推理范式；

(iv) 我们进行了广泛评估，揭示了空间推理中的持续挑战，同时验证了 SpatialAgent 的有效性。

我们坚信，SpatialScore 将为 MLLMs 的未来发展提供重要洞见，并作为一项严格的基准测试。

> Multimodal large language models (MLLMs) have achieved impressive success in question-answering tasks, yet their capabilities for spatial understanding are less explored. This work investigates a critical question: do existing MLLMs possess 3D spatial perception and understanding abilities? Concretely, we make the following contributions in this paper: (i) we introduce VGBench, a benchmark specifically designed to assess MLLMs for visual geometry perception, e.g., camera pose and motion estimation; (ii) we propose SpatialScore, the most comprehensive and diverse multimodal spatial understanding benchmark to date, integrating VGBench with relevant data from the other 11 existing datasets. This benchmark comprises 28K samples across various spatial understanding tasks, modalities, and QA formats, along with a carefully curated challenging subset, SpatialScore-Hard; (iii) we develop SpatialAgent, a novel multi-agent system incorporating 9 specialized tools for spatial understanding, supporting both Plan-Execute and ReAct reasoning paradigms; (iv) we conduct extensive evaluations to reveal persistent challenges in spatial reasoning while demonstrating the effectiveness of SpatialAgent. We believe SpatialScore will offer valuable insights and serve as a rigorous benchmark for the next evolution of MLLMs.

[Arxiv](https://arxiv.org/abs/2505.17012)