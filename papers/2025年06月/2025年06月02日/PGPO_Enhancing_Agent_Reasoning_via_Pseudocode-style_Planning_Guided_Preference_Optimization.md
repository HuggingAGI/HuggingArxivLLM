# <翻译失败>

发布时间：2025年06月02日

`Agent` `人工智能` `自动化`

> PGPO: Enhancing Agent Reasoning via Pseudocode-style Planning Guided Preference Optimization

# 摘要

> 大型语言模型（LLM）代理在处理复杂交互问题方面表现优异。然而，现有的LLM代理主要依赖自然语言计划来指导推理，这种方式不仅冗长低效，还限制了代理在类似任务中的泛化能力。为解决这些问题，我们提出了伪代码式计划（P-code Plan），发现它能显著提升代理的泛化能力和推理效率。基于这一发现，我们开发了名为 PGPO 的规划引导偏好优化方法，通过两个专门设计的规划导向奖励机制，进一步提升了 LLM 代理生成高质量 P-code Plan 和后续推理的能力。实验结果表明，PGPO 在代表性代理基准测试中表现优异，超越了现有领先基线。分析显示，PGPO 在减少推理过程中的动作错误和遗漏方面具有显著优势。

> Large Language Model (LLM) agents have demonstrated impressive capabilities in handling complex interactive problems. Existing LLM agents mainly generate natural language plans to guide reasoning, which is verbose and inefficient. NL plans are also tailored to specific tasks and restrict agents' ability to generalize across similar tasks. To this end, we explore pseudocode-style plans (P-code Plan) to capture the structural logic of reasoning. We find that P-code Plan empowers LLM agents with stronger generalization ability and more efficiency. Inspired by this finding, we propose a pseudocode-style Planning Guided Preference Optimization method called PGPO for effective agent learning. With two planning-oriented rewards, PGPO further enhances LLM agents' ability to generate high-quality P-code Plans and subsequent reasoning. Experiments show that PGPO achieves superior performance on representative agent benchmarks and outperforms the current leading baselines. Analyses reveal the advantage of PGPO in reducing action errors and omissions during reasoning.

[Arxiv](https://arxiv.org/abs/2506.01475)