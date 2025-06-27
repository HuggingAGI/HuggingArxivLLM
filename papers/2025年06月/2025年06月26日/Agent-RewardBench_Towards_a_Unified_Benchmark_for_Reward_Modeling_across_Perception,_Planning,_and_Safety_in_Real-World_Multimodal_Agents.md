# Agent-RewardBench: 面向真实世界多模态智能体的感知、规划与安全领域，构建奖励建模统一基准测试

发布时间：2025年06月26日

`Agent` `人工智能` `多模态代理`

> Agent-RewardBench: Towards a Unified Benchmark for Reward Modeling across Perception, Planning, and Safety in Real-World Multimodal Agents

# 摘要

> # 摘要
随着多模态大型语言模型（MLLMs）的发展，多模态代理在网页导航和具身智能等现实任务中展现出巨大潜力。然而，由于缺乏外部反馈的限制，这些代理在自我纠错和泛化方面面临挑战。使用奖励模型作为外部反馈是一种有前景的方法，但目前尚无明确的奖励模型选择标准。因此，迫切需要构建一个针对代理的奖励基准。

为了解决这些挑战，我们提出了Agent-RewardBench，这是一个旨在评估MLLMs奖励建模能力的基准。该基准具有三个关键特点：(1) 多维度和现实场景评估。涵盖感知、规划和安全，共7个场景；(2) 分步奖励评估。允许在任务的各个步骤中评估代理能力，提供规划过程中更细致的性能视图；(3) 难度适中且高质量。我们从10个多样化模型中精心采样，控制难度以保持任务挑战性，并通过人工验证确保数据完整性。

实验表明，即使是先进的多模态模型也表现出有限的性能，凸显了在代理奖励建模中进行专门训练的必要性。代码可在github上获取。

> As Multimodal Large Language Models (MLLMs) advance, multimodal agents show promise in real-world tasks like web navigation and embodied intelligence. However, due to limitations in a lack of external feedback, these agents struggle with self-correction and generalization. A promising approach is to use reward models as external feedback, but there is no clear on how to select reward models for agents. Thus, there is an urgent need to build a reward bench targeted at agents. To address these challenges, we propose Agent-RewardBench, a benchmark designed to evaluate reward modeling ability in MLLMs. The benchmark is characterized by three key features: (1) Multiple dimensions and real-world agent scenarios evaluation. It covers perception, planning, and safety with 7 scenarios; (2) Step-level reward evaluation. It allows for the assessment of agent capabilities at the individual steps of a task, providing a more granular view of performance during the planning process; and (3) Appropriately difficulty and high-quality. We carefully sample from 10 diverse models, difficulty control to maintain task challenges, and manual verification to ensure the integrity of the data. Experiments demonstrate that even state-of-the-art multimodal models show limited performance, highlighting the need for specialized training in agent reward modeling. Code is available at github.

[Arxiv](https://arxiv.org/abs/2506.21252)