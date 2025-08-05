# # 标题
通过预判难度感知的干预方法提升小型LLM模型的数学推理能力

发布时间：2025年08月03日

`LLM应用` `人工智能`

> Enhancing Math Reasoning in Small-sized LLMs via Preview Difficulty-Aware Intervention

# 摘要

> 强化学习缩放技术显著提升了大型语言模型的推理能力，其中强化学习作为关键手段，能够挖掘出模型的复杂推理能力。然而，当前最先进推理型大型语言模型（如OpenAI O系列、Claude 3系列、DeepMind的Gemini 2.5系列和Grok 3系列）的核心技术细节尚未公开，这使得研究界难以复现它们的强化学习训练成果。因此，我们从基于开源GRPO框架构建的早期预览强化学习（EPRLI）算法出发，融入了针对数学问题的难度感知干预机制。该方法应用于一个15亿参数规模的大型语言模型后，在AIME24测试集上达到了50.0%，Math500测试集上达到了89.2%，AMC测试集上达到了77.1%，Minerva测试集上达到了35.3%，以及OBench测试集上达到了51.9%的优异成绩，不仅超越了O1-Preview版本，而且在标准学校实验室环境下与O1-mini版本表现相当。

> Reinforcement learning scaling enhances the reasoning capabilities of large language models, with reinforcement learning serving as the key technique to draw out complex reasoning. However, key technical details of state-of-the-art reasoning LLMs, such as those in the OpenAI O series, Claude 3 series, DeepMind's Gemini 2.5 series, and Grok 3 series, remain undisclosed, making it difficult for the research community to replicate their reinforcement learning training results. Therefore, we start our study from an Early Preview Reinforcement Learning (EPRLI) algorithm built on the open-source GRPO framework, incorporating difficulty-aware intervention for math problems. Applied to a 1.5B-parameter LLM, our method achieves 50.0% on AIME24, 89.2% on Math500, 77.1% on AMC, 35.3% on Minerva, and 51.9% on OBench, superpass O1-Preview and is comparable to O1-mini within standard school-lab settings.

[Arxiv](https://arxiv.org/abs/2508.01604)