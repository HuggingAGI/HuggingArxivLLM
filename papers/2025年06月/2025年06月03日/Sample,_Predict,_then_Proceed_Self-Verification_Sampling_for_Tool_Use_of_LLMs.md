# 采样、预测、然后继续：用于 LLM 工具使用的自我验证采样

发布时间：2025年06月03日

`LLM应用

摘要中讨论了动态建模（DyMo）和自我验证采样（SVS）在提升LLMs在工具使用场景下的推理能力和规划能力中的应用。这些方法直接针对LLMs的实际应用场景，旨在提高其有效性和可靠性，属于应用层面的改进。因此，这篇论文被分类为LLM应用。` `人工智能`

> Sample, Predict, then Proceed: Self-Verification Sampling for Tool Use of LLMs

# 摘要

> 在有状态环境中，工具使用为大型语言模型（LLMs）带来了独特挑战，现有基于环境重复试验的推理计算策略在此类场景下难以实施。为此，我们提出了动态建模（DyMo），这是一种在模型微调后增强LLMs状态预测能力的方法，使其能够通过内部环境模型预测自身行动的未来状态。在伯克利函数调用排行榜V2上，DyMo显著提升了任务成功率并大幅减少了幻觉现象。我们进一步将内部环境模型整合到自我验证采样（SVS）中，结果表明这大大提高了通过率与试验次数k的关系，并使模型能够拒绝不可靠的输出。结合使用DyMo和SVS，我们显著提升了LLMs在工具使用场景下的有效性和可靠性。我们相信这项工作为开发可扩展的规划强化学习方法奠定了基础，这些方法能够支持LLMs推理而无需反复查询Oracle环境。

> Tool use in stateful environments presents unique challenges for large language models (LLMs), where existing test-time compute strategies relying on repeated trials in the environment are impractical. We propose dynamics modelling (DyMo), a method that augments LLMs with a state prediction capability alongside function calling during post-training. This enables LLMs to predict the future states of their actions through an internal environment model. On the Berkeley Function Calling Leaderboard V2, DyMo improves success rates and significantly reduces hallucinations. We further integrate the internal environment model into self-verification sampling (SVS), and show that this substantially improves pass^k over number of trials k, and allows the model to refuse unreliable outputs. Together, DyMo and SVS greatly enhance the effectiveness and reliability of LLMs for tool use. We believe this work charts a path towards scalable planning RL methods for LLM inference without repeatedly querying the oracle environment.

[Arxiv](https://arxiv.org/abs/2506.02918)