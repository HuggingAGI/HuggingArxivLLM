# VideoMind：链式LoRA驱动的长视频推理代理

发布时间：2025年03月17日

`Agent` `视频理解` `智能体`

> VideoMind: A Chain-of-LoRA Agent for Long Video Reasoning

# 摘要

> 视频凭借其独特的时间维度，要求答案直接与可解释的视觉证据相关联的精准理解。尽管大型语言模型在推理能力方面取得了重大突破，但多模态推理——尤其是针对视频的推理——仍然未被探索。本研究引入了VideoMind，这是一种专为时间感知视频理解设计的创新视频-语言智能体。VideoMind融合了两大关键创新点：(i) 我们识别出视频时间推理所需的核心能力，并开发出一种基于角色的智能体工作流程，包括用于协调不同角色的规划器、用于时间定位的定位器、用于评估时间间隔准确性的验证器，以及用于问答的问答器。 (ii) 为了高效整合这些多样化角色，我们提出了一种新型的Chain-of-LoRA策略，通过轻量级的LoRA适配器实现无缝的角色切换，同时避免了使用多个模型带来的额外开销，从而在效率与灵活性之间实现了平衡。在14个公开基准上的广泛实验表明，我们的智能体在多样化的视频理解任务中达到了最先进的性能，包括3个基于事实的视频问答任务、6个视频时间定位任务，以及5个通用视频问答任务，充分证明了其在推动视频智能体和长序列时间推理方面的有效性。

> Videos, with their unique temporal dimension, demand precise grounded understanding, where answers are directly linked to visual, interpretable evidence. Despite significant breakthroughs in reasoning capabilities within Large Language Models, multi-modal reasoning - especially for videos - remains unexplored. In this work, we introduce VideoMind, a novel video-language agent designed for temporal-grounded video understanding. VideoMind incorporates two key innovations: (i) We identify essential capabilities for video temporal reasoning and develop a role-based agentic workflow, including a planner for coordinating different roles, a grounder for temporal localization, a verifier to assess temporal interval accuracy, and an answerer for question-answering. (ii) To efficiently integrate these diverse roles, we propose a novel Chain-of-LoRA strategy, enabling seamless role-switching via lightweight LoRA adaptors while avoiding the overhead of multiple models, thus balancing efficiency and flexibility. Extensive experiments on 14 public benchmarks demonstrate that our agent achieves state-of-the-art performance on diverse video understanding tasks, including 3 on grounded video question-answering, 6 on video temporal grounding, and 5 on general video question-answering, underscoring its effectiveness in advancing video agent and long-form temporal reasoning.

[Arxiv](https://arxiv.org/abs/2503.13444)