# 大型语言模型推理前沿综述：推理扩展、学习推理与智能体系统

发布时间：2025年04月11日

`LLM应用` `人工智能` `智能体`

> A Survey of Frontiers in LLM Reasoning: Inference Scaling, Learning to Reason, and Agentic Systems

# 摘要

> 推理是逻辑推理、问题解决和决策的基础认知过程。随着大型语言模型（LLMs）的快速发展，推理已成为区分先进AI系统与传统赋能聊天机器人的核心能力。本综述从两个相互独立的维度对现有方法进行分类：（1）范式，定义推理实现的阶段（要么在推理时，要么通过专门的训练）；（2）架构，决定推理过程中涉及的组件，区分独立的LLMs与集成外部工具的智能体复合系统，以及多智能体协作。在每个维度下，我们从输入和输出两个层面进行分析：输入层面专注于构建高质量提示的技术，输出层面则通过优化多个采样候选来提升推理质量。这种分类为理解LLM推理领域的发展提供了系统性的视角，突显了从推理扩展到学习推理（如DeepSeek-R1）的转变，以及向智能体工作流（如OpenAI Deep Research、Manus Agent）的过渡等新兴趋势。此外，我们涵盖了从监督微调到强化学习（如PPO和GRPO）以及训练推理器和验证器的广泛学习算法。我们还探讨了智能体工作流的关键设计，从已建立的生成器-评估器和LLM辩论模式到最近的创新。

> Reasoning is a fundamental cognitive process that enables logical inference, problem-solving, and decision-making. With the rapid advancement of large language models (LLMs), reasoning has emerged as a key capability that distinguishes advanced AI systems from conventional models that empower chatbots. In this survey, we categorize existing methods along two orthogonal dimensions: (1) Regimes, which define the stage at which reasoning is achieved (either at inference time or through dedicated training); and (2) Architectures, which determine the components involved in the reasoning process, distinguishing between standalone LLMs and agentic compound systems that incorporate external tools, and multi-agent collaborations. Within each dimension, we analyze two key perspectives: (1) Input level, which focuses on techniques that construct high-quality prompts that the LLM condition on; and (2) Output level, which methods that refine multiple sampled candidates to enhance reasoning quality. This categorization provides a systematic understanding of the evolving landscape of LLM reasoning, highlighting emerging trends such as the shift from inference-scaling to learning-to-reason (e.g., DeepSeek-R1), and the transition to agentic workflows (e.g., OpenAI Deep Research, Manus Agent). Additionally, we cover a broad spectrum of learning algorithms, from supervised fine-tuning to reinforcement learning such as PPO and GRPO, and the training of reasoners and verifiers. We also examine key designs of agentic workflows, from established patterns like generator-evaluator and LLM debate to recent innovations. ...

[Arxiv](https://arxiv.org/abs/2504.09037)