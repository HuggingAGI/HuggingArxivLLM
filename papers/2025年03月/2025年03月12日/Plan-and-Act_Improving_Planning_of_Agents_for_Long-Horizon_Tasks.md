# 规划与行动：优化智能体在长周期任务中的规划能力

发布时间：2025年03月12日

`LLM应用` `智能体`

> Plan-and-Act: Improving Planning of Agents for Long-Horizon Tasks

# 摘要

> 大型语言模型（LLMs）在处理简单任务方面取得了显著进步，但对于复杂、多步骤、长周期的任务仍具挑战性。近期研究通过分离高层规划与低层执行取得成功，使模型能有效平衡规划目标与执行细节。然而，生成准确计划仍具难度，因LLMs未针对此任务训练。为此，我们提出Plan-and-Act框架，将显式规划纳入LLM代理，并通过创新的合成数据生成方法提升计划生成能力。Plan-and-Act由规划器模型和执行器模型组成，前者生成结构化高层计划，后者将其转化为具体环境动作。为有效训练规划器，我们开发了一种合成数据生成方法，通过标注真实轨迹的可行计划并增加多样化示例，提升模型泛化能力。我们采用网络导航作为长周期规划环境评估Plan-and-Act，在WebArena-Lite基准上实现了54%的成功率，达到目前领先水平。

> Large language models (LLMs) have shown remarkable advancements in enabling language agents to tackle simple tasks. However, applying them for complex, multi-step, long-horizon tasks remains a challenge. Recent work have found success by separating high-level planning from low-level execution, which enables the model to effectively balance high-level planning objectives and low-level execution details. However, generating accurate plans remains difficult since LLMs are not inherently trained for this task. To address this, we propose Plan-and-Act, a novel framework that incorporates explicit planning into LLM-based agents and introduces a scalable method to enhance plan generation through a novel synthetic data generation method. Plan-and-Act consists of a Planner model which generates structured, high-level plans to achieve user goals, and an Executor model that translates these plans into environment-specific actions. To train the Planner effectively, we introduce a synthetic data generation method that annotates ground-truth trajectories with feasible plans, augmented with diverse and extensive examples to enhance generalization. We evaluate Plan-and-Act using web navigation as a representative long-horizon planning environment, demonstrating a state-of the-art 54% success rate on the WebArena-Lite benchmark.

[Arxiv](https://arxiv.org/abs/2503.09572)