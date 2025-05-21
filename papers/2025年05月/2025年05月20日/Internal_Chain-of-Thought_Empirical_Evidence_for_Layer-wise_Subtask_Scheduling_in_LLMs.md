# 大型语言模型中的内部思维链：分层子任务调度的经验证据

发布时间：2025年05月20日

`LLM理论` `模型机制`

> Internal Chain-of-Thought: Empirical Evidence for Layer-wise Subtask Scheduling in LLMs

# 摘要

> 我们发现，大型语言模型 (LLMs) 拥有 $	extit{内部的思考链路}$，能够按层逐步分解并执行复合任务。我们的研究基于两个核心观点：(i) 不同子任务在不同网络深度被学习，以及 (ii) 这些子任务在各层间依次执行。在包含15个两步复合任务的基准测试中，我们采用层间上下文掩码方法，并提出了一种跨任务修补技术，证实了观点 (i)。为验证观点 (ii)，我们运用LogitLens解码隐藏状态，揭示了一种一致的分层执行模式。进一步在现实世界的 $	ext{TRACE}$ 基准测试中，我们观察到了相同的逐步动态。我们的研究结果通过展示 LLMs 在内部规划和执行子任务（或指令）的能力，增强了模型的透明度，并为实现精细的、基于指令级别的激活引导开辟了新途径。

> We show that large language models (LLMs) exhibit an $\textit{internal chain-of-thought}$: they sequentially decompose and execute composite tasks layer-by-layer. Two claims ground our study: (i) distinct subtasks are learned at different network depths, and (ii) these subtasks are executed sequentially across layers. On a benchmark of 15 two-step composite tasks, we employ layer-from context-masking and propose a novel cross-task patching method, confirming (i). To examine claim (ii), we apply LogitLens to decode hidden states, revealing a consistent layerwise execution pattern. We further replicate our analysis on the real-world $\text{TRACE}$ benchmark, observing the same stepwise dynamics. Together, our results enhance LLMs transparency by showing their capacity to internally plan and execute subtasks (or instructions), opening avenues for fine-grained, instruction-level activation steering.

[Arxiv](https://arxiv.org/abs/2505.14530)