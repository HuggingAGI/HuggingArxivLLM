# 基于多样化解题视角的多模态数学推理

发布时间：2025年07月03日

`LLM应用` `数学教育`

> Multimodal Mathematical Reasoning with Diverse Solving Perspective

# 摘要

> 大规模强化学习 (RL) 的最新进展显著提升了大型语言模型 (LLMs) 的推理能力，尤其是在数学领域。然而，当前用于数学推理的多模态 LLMs (MLLMs) 通常依赖于一对一的图像-文本配对和单一解决方案的监督，忽视了有效推理视角的多样性和内部反思。为此，我们引入了 MathV-DP 数据集，为每个图像-问题对提供多个多样化的解决方案轨迹，从而丰富推理监督。我们还提出了 Qwen-VL-DP 模型，该模型基于 Qwen-VL，通过监督学习进行微调，并结合群体相对策略优化 (GRPO) 进行增强。GRPO 是一种基于规则的强化学习方法，集成了正确性区分和多样性感知奖励函数。我们的方法着重于从多样化推理视角中学习，并能够区分正确但不同的解决方案。在 MathVista 的 minitest 和 Math-V 基准上的大量实验表明，Qwen-VL-DP 在准确性和生成多样性方面均显著优于之前的基线 MLLMs，这凸显了在多模态数学推理中纳入多样化视角和反思推理的重要性。

> Recent progress in large-scale reinforcement learning (RL) has notably enhanced the reasoning capabilities of large language models (LLMs), especially in mathematical domains. However, current multimodal LLMs (MLLMs) for mathematical reasoning often rely on one-to-one image-text pairs and single-solution supervision, overlooking the diversity of valid reasoning perspectives and internal reflections. In this work, we introduce MathV-DP, a novel dataset that captures multiple diverse solution trajectories for each image-question pair, fostering richer reasoning supervision. We further propose Qwen-VL-DP, a model built upon Qwen-VL, fine-tuned with supervised learning and enhanced via group relative policy optimization (GRPO), a rule-based RL approach that integrates correctness discrimination and diversity-aware reward functions. Our method emphasizes learning from varied reasoning perspectives and distinguishing between correct yet distinct solutions. Extensive experiments on the MathVista's minitest and Math-V benchmarks demonstrate that Qwen-VL-DP significantly outperforms prior base MLLMs in both accuracy and generative diversity, highlighting the importance of incorporating diverse perspectives and reflective reasoning in multimodal mathematical reasoning.

[Arxiv](https://arxiv.org/abs/2507.02804)