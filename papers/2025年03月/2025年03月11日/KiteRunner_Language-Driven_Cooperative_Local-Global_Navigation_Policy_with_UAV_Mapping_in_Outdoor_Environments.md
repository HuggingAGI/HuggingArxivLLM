# 风筝奔跑者：基于语言的无人机协同全局-局部导航策略，适用于户外环境

发布时间：2025年03月11日

`LLM应用` `机器人` `自主导航`

> KiteRunner: Language-Driven Cooperative Local-Global Navigation Policy with UAV Mapping in Outdoor Environments

# 摘要

> 开放世界户外环境中的自主导航面临整合动态条件、长距离空间推理和语义理解的挑战。传统方法难以在局部规划、全局规划和语义任务执行之间取得平衡，而现有大型语言模型（LLMs）虽增强了语义理解，却缺乏空间推理能力。尽管扩散模型在局部优化方面表现出色，但难以胜任大规模长距离导航。为解决这些难题，我们提出了KiteRunner——一种语言驱动的协作式局部-全局导航策略。该方法结合基于UAV正射影像的全局规划和扩散模型驱动的局部路径生成，专为开放世界场景下的长距离导航而设计。我们的创新之处在于利用实时UAV正射影像构建全局概率图，为局部规划器提供可通行性指导，同时整合CLIP和GPT等大型模型来解释自然语言指令。实验结果表明，与现有方法相比，KiteRunner在结构化和非结构化环境中分别实现了5.6%和12.8%的路径效率提升，且大幅减少了人工干预和执行时间。

> Autonomous navigation in open-world outdoor environments faces challenges in integrating dynamic conditions, long-distance spatial reasoning, and semantic understanding. Traditional methods struggle to balance local planning, global planning, and semantic task execution, while existing large language models (LLMs) enhance semantic comprehension but lack spatial reasoning capabilities. Although diffusion models excel in local optimization, they fall short in large-scale long-distance navigation. To address these gaps, this paper proposes KiteRunner, a language-driven cooperative local-global navigation strategy that combines UAV orthophoto-based global planning with diffusion model-driven local path generation for long-distance navigation in open-world scenarios. Our method innovatively leverages real-time UAV orthophotography to construct a global probability map, providing traversability guidance for the local planner, while integrating large models like CLIP and GPT to interpret natural language instructions. Experiments demonstrate that KiteRunner achieves 5.6% and 12.8% improvements in path efficiency over state-of-the-art methods in structured and unstructured environments, respectively, with significant reductions in human interventions and execution time.

[Arxiv](https://arxiv.org/abs/2503.08330)