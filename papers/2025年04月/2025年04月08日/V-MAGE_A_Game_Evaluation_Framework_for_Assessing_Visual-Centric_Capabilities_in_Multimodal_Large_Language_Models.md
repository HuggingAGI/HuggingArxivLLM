# V-MAGE：用于评估多模态大型语言模型视觉能力的游戏化评估框架

发布时间：2025年04月08日

`LLM应用` `多模态模型` `视觉推理`

> V-MAGE: A Game Evaluation Framework for Assessing Visual-Centric Capabilities in Multimodal Large Language Models

# 摘要

> # 摘要  
多模态大型语言模型（MLLMs）的最新进展在各种多模态基准测试中带来了显著提升。然而，随着评估从静态数据集转向开放世界的动态环境，现有基于游戏的基准测试仍显不足，因为它们缺乏视觉核心任务，也无法评估现实世界决策所需的多样化推理技能。为了解决这一问题，我们引入了视觉中心多能力游戏评估（V-MAGE），这是一个基于游戏的评估框架，旨在评估多模态大型语言模型的视觉推理能力。V-MAGE包含五个多样化的游戏和30多个手工设计的关卡，测试模型的核心视觉技能，如定位、轨迹追踪、时机掌握和视觉记忆，以及更高层次的推理能力，如长期规划和权衡思考。我们利用V-MAGE对领先的MLLMs进行了评估，揭示了它们在视觉感知和推理方面面临的重要挑战。在所有游戏环境中，根据 Elo 等级比较确定的顶级MLLMs的表现与人类相比存在显著差距。我们的研究结果强调了关键限制，包括模型在感知过程中出现的各种错误，并从以智能体为中心的视角提出了潜在的改进方向，如优化智能体策略和解决感知不准确的问题。代码可在 https://github.com/CSU-JPG/V-MAGE 获取。

> Recent advancements in Multimodal Large Language Models (MLLMs) have led to significant improvements across various multimodal benchmarks. However, as evaluations shift from static datasets to open-world, dynamic environments, current game-based benchmarks remain inadequate because they lack visual-centric tasks and fail to assess the diverse reasoning skills required for real-world decision-making. To address this, we introduce Visual-centric Multiple Abilities Game Evaluation (V-MAGE), a game-based evaluation framework designed to assess visual reasoning capabilities of MLLMs. V-MAGE features five diverse games with 30+ handcrafted levels, testing models on core visual skills such as positioning, trajectory tracking, timing, and visual memory, alongside higher-level reasoning like long-term planning and deliberation. We use V-MAGE to evaluate leading MLLMs, revealing significant challenges in their visual perception and reasoning. In all game environments, the top-performing MLLMs, as determined by Elo rating comparisons, exhibit a substantial performance gap compared to humans. Our findings highlight critical limitations, including various types of perceptual errors made by the models, and suggest potential avenues for improvement from an agent-centric perspective, such as refining agent strategies and addressing perceptual inaccuracies. Code is available at https://github.com/CSU-JPG/V-MAGE.

[Arxiv](https://arxiv.org/abs/2504.06148)