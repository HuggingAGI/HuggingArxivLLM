# VideoWorld: 从未标注视频中探索知识学习

发布时间：2025年01月16日

`其他

理由：这篇论文主要探讨了深度生成模型通过视觉输入学习复杂知识的能力，特别是通过视频数据进行训练。虽然提到了与文本模型（如LLMs）的对比，但研究的核心是视觉数据的知识获取，而不是直接涉及LLM的应用、理论、Agent或RAG（Retrieval-Augmented Generation）。因此，将其分类为“其他”更为合适。` `机器人`

> VideoWorld: Exploring Knowledge Learning from Unlabeled Videos

# 摘要

> # 摘要
本研究探讨了深度生成模型能否仅凭视觉输入学习复杂知识，与当前主流的文本模型（如LLMs）形成鲜明对比。我们开发了VideoWorld，一个基于未标记视频的自回归视频生成模型，并在围棋和机器人控制任务中测试其知识获取能力。实验发现：（1）仅通过视频训练即可获取规则、推理和规划等知识；（2）视觉变化的表示对知识获取至关重要。为提高效率，我们引入了潜在动态模型（LDM）作为VideoWorld的核心组件。令人瞩目的是，VideoWorld仅用3亿参数模型便在Video-GoBench中达到5段专业水平，且无需依赖强化学习中的搜索算法或奖励机制。在机器人任务中，VideoWorld表现出色，能够学习多样化控制操作并在不同环境中泛化，接近CALVIN和RLBench中oracle模型的性能。这项研究为视觉数据知识获取开辟了新方向，所有代码、数据和模型均已开源。

> This work explores whether a deep generative model can learn complex knowledge solely from visual input, in contrast to the prevalent focus on text-based models like large language models (LLMs). We develop VideoWorld, an auto-regressive video generation model trained on unlabeled video data, and test its knowledge acquisition abilities in video-based Go and robotic control tasks. Our experiments reveal two key findings: (1) video-only training provides sufficient information for learning knowledge, including rules, reasoning and planning capabilities, and (2) the representation of visual change is crucial for knowledge acquisition. To improve both the efficiency and efficacy of this process, we introduce the Latent Dynamics Model (LDM) as a key component of VideoWorld. Remarkably, VideoWorld reaches a 5-dan professional level in the Video-GoBench with just a 300-million-parameter model, without relying on search algorithms or reward mechanisms typical in reinforcement learning. In robotic tasks, VideoWorld effectively learns diverse control operations and generalizes across environments, approaching the performance of oracle models in CALVIN and RLBench. This study opens new avenues for knowledge acquisition from visual data, with all code, data, and models open-sourced for further research.

[Arxiv](https://arxiv.org/abs/2501.09781)