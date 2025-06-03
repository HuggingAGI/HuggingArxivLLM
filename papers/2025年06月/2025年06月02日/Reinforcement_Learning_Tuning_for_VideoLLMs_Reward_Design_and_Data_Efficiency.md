# 针对视频大模型的强化学习调优：奖励设计与数据效率优化

发布时间：2025年06月02日

`LLM应用` `视频处理` `计算机视觉`

> Reinforcement Learning Tuning for VideoLLMs: Reward Design and Data Efficiency

# 摘要

> 理解复杂语义和长时序依赖的现实世界视频仍是计算机视觉的核心挑战。近年来，多模态大语言模型（MLLMs）在视觉-语言任务中表现卓越，而强化学习调优（RLT）进一步提升了其推理能力。本研究将RLT作为后训练策略，专注于提升MLLMs的视频推理能力。基于组相对策略优化（GRPO）框架，我们提出双奖励公式，通过离散和连续奖励信号分别监督语义推理和时序推理。为实现有效的偏好优化，我们引入基于重复推理的方差感知数据选择策略，用于识别具有学习价值的样本。我们在八个代表性视频理解任务（包括视频问答、时序视频定位和基于 grounding 的视频问答）上评估了我们的方法。结果表明，我们的方法显著优于监督微调和现有RLT基线，且仅需少量数据即可实现更优性能。这些结果凸显了奖励设计和数据选择在提升基于MLLMs的推理导向视频理解中的关键作用。值得注意的是，最初发布的代码（两个月前）现已更新，包括优化的奖励机制和新增的数据集。最新版本可访问：https://github.com/appletea233/Temporal-R1。


> Understanding real-world videos with complex semantics and long temporal dependencies remains a fundamental challenge in computer vision. Recent progress in multimodal large language models (MLLMs) has demonstrated strong capabilities in vision-language tasks, while reinforcement learning tuning (RLT) has further improved their reasoning abilities. In this work, we explore RLT as a post-training strategy to enhance the video-specific reasoning capabilities of MLLMs. Built upon the Group Relative Policy Optimization (GRPO) framework, we propose a dual-reward formulation that supervises both semantic and temporal reasoning through discrete and continuous reward signals. To facilitate effective preference-based optimization, we introduce a variance-aware data selection strategy based on repeated inference to identify samples that provide informative learning signals. We evaluate our approach across eight representative video understanding tasks, including VideoQA, Temporal Video Grounding, and Grounded VideoQA. Our method consistently outperforms supervised fine-tuning and existing RLT baselines, achieving superior performance with significantly less training data. These results underscore the importance of reward design and data selection in advancing reasoning-centric video understanding with MLLMs. Notably, The initial code release (two months ago) has now been expanded with updates, including optimized reward mechanisms and additional datasets. The latest version is available at https://github.com/appletea233/Temporal-R1 .

[Arxiv](https://arxiv.org/abs/2506.01908)