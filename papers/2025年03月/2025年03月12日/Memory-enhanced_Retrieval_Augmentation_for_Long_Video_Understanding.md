# # 基于内存增强的检索增强技术，提升长视频理解能力

发布时间：2025年03月12日

`RAG` `视频处理` `视频分析`

> Memory-enhanced Retrieval Augmentation for Long Video Understanding

# 摘要

> 检索增强生成（RAG）在长视频理解（LVU）任务方面展现出强大潜力。然而，传统RAG方法由于依赖显式搜索查询而在根本上存在限制，而在许多情况下这些查询并不可用。为克服这一挑战，我们提出了一种基于人类认知记忆的全新RAG框架，名为MemVid。我们的方法通过四个基本步骤运行：记忆整体视频信息、基于记忆推理任务的信息需求、根据信息需求检索关键 moments，以及聚焦于检索到的 moments 生成最终答案。为了提升系统基于记忆的推理能力并实现最优端到端性能，我们提出了一种课程学习策略。该策略从监督学习良好标注的推理结果开始，然后逐步通过强化学习探索并强化更合理的推理结果。我们在流行LVU基准测试（包括MLVU、VideoMME和LVBench）上进行了广泛评估。实验结果表明，MemVid显著超越现有RAG方法和流行LVU模型，证明了我们方法的有效性。我们的模型和源代码将在接受后公开发布。

> Retrieval-augmented generation (RAG) shows strong potential in addressing long-video understanding (LVU) tasks. However, traditional RAG methods remain fundamentally limited due to their dependence on explicit search queries, which are unavailable in many situations. To overcome this challenge, we introduce a novel RAG-based LVU approach inspired by the cognitive memory of human beings, which is called MemVid. Our approach operates with four basics steps: memorizing holistic video information, reasoning about the task's information needs based on the memory, retrieving critical moments based on the information needs, and focusing on the retrieved moments to produce the final answer. To enhance the system's memory-grounded reasoning capabilities and achieve optimal end-to-end performance, we propose a curriculum learning strategy. This approach begins with supervised learning on well-annotated reasoning results, then progressively explores and reinforces more plausible reasoning outcomes through reinforcement learning. We perform extensive evaluations on popular LVU benchmarks, including MLVU, VideoMME and LVBench. In our experiment, MemVid significantly outperforms existing RAG-based methods and popular LVU models, which demonstrate the effectiveness of our approach. Our model and source code will be made publicly available upon acceptance.

[Arxiv](https://arxiv.org/abs/2503.09149)