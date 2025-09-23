# 强化学习中LLM引导的任务级与可供性级探索

发布时间：2025年09月20日

`强化学习` `工业与制造`

> LLM-Guided Task- and Affordance-Level Exploration in Reinforcement Learning

# 摘要

> 强化学习（RL）在机器人操作领域前景广阔，但存在样本效率低的问题，且需要对庞大的状态-动作空间进行大量探索。近期方法借助大型语言模型（LLMs）的常识知识与推理能力，将探索引向更有意义的状态。然而，LLMs生成的计划可能语义合理却物理不可行，导致行为不可靠。为此，我们提出LLM-TALE框架，利用LLMs的规划能力直接引导RL探索。该框架整合了任务级与功能级规划，通过引导智能体执行语义有意义的动作来提升学习效率。与以往假设LLM生成的计划或奖励最优的方法不同，LLM-TALE能在线纠正次优问题，并在无需人工监督的情况下探索多模态功能级计划。我们在标准RL基准的拾取放置任务中对LLM-TALE进行评估，结果显示其样本效率和成功率均优于强基线模型。真实机器人实验表明，该框架在零样本仿真到现实迁移方面表现出良好前景。代码及补充材料详见网站：https://llm-tale.github.io。

> Reinforcement learning (RL) is a promising approach for robotic manipulation, but it can suffer from low sample efficiency and requires extensive exploration of large state-action spaces. Recent methods leverage the commonsense knowledge and reasoning abilities of large language models (LLMs) to guide exploration toward more meaningful states. However, LLMs can produce plans that are semantically plausible yet physically infeasible, yielding unreliable behavior. We introduce LLM-TALE, a framework that uses LLMs' planning to directly steer RL exploration. LLM-TALE integrates planning at both the task level and the affordance level, improving learning efficiency by directing agents toward semantically meaningful actions. Unlike prior approaches that assume optimal LLM-generated plans or rewards, LLM-TALE corrects suboptimality online and explores multimodal affordance-level plans without human supervision. We evaluate LLM-TALE on pick-and-place tasks in standard RL benchmarks, observing improvements in both sample efficiency and success rates over strong baselines. Real-robot experiments indicate promising zero-shot sim-to-real transfer. Code and supplementary material are available at https://llm-tale.github.io.

[Arxiv](https://arxiv.org/abs/2509.16615)