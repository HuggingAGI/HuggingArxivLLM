# HAPO：巧妙结合历史感知策略优化，训练语言模型实现简洁推理

发布时间：2025年05月16日

`LLM应用`

> HAPO: Training Language Models to Reason Concisely via History-Aware Policy Optimization

# 摘要

> 扩展大型语言模型（LLMs）在测试时的响应长度虽能显著提升其推理能力与性能，但也可能带来冗长输出及高昂推理成本。传统方法通常依赖通用预算约束或查询级长度优化，却忽视了训练过程中与同一问题的历史交互信息。我们推测这限制了模型逐步生成更简洁解决方案的能力。为此，我们提出基于历史感知策略优化（HAPO），为每个问题维护历史状态（如之前正确响应的最小长度）。HAPO采用基于历史状态的新型长度奖励函数，激励模型发现比之前更简洁的正确解决方案。值得注意的是，该奖励机制避免过度惩罚较短错误响应，旨在促进对更高效解决方案的探索。通过结合长度奖励与正确性奖励，HAPO实现了正确性与效率的双重优化。我们使用HAPO训练了DeepSeek-R1-Distill-Qwen-1.5B、DeepScaleR-1.5B-Preview和Qwen-2.5-1.5B-Instruct，并在涵盖不同难度级别的多个数学基准上评估了HAPO。实验结果表明，HAPO有效激发了LLMs的简洁推理能力，实现了33-59%的响应长度缩减，同时仅导致2-5%的准确率下降。

> While scaling the length of responses at test-time has been shown to markedly improve the reasoning abilities and performance of large language models (LLMs), it often results in verbose outputs and increases inference cost. Prior approaches for efficient test-time scaling, typically using universal budget constraints or query-level length optimization, do not leverage historical information from previous encounters with the same problem during training. We hypothesize that this limits their ability to progressively make solutions more concise over time. To address this, we present History-Aware Policy Optimization (HAPO), which keeps track of a history state (e.g., the minimum length over previously generated correct responses) for each problem. HAPO employs a novel length reward function based on this history state to incentivize the discovery of correct solutions that are more concise than those previously found. Crucially, this reward structure avoids overly penalizing shorter incorrect responses with the goal of facilitating exploration towards more efficient solutions. By combining this length reward with a correctness reward, HAPO jointly optimizes for correctness and efficiency. We use HAPO to train DeepSeek-R1-Distill-Qwen-1.5B, DeepScaleR-1.5B-Preview, and Qwen-2.5-1.5B-Instruct, and evaluate HAPO on several math benchmarks that span various difficulty levels. Experiment results demonstrate that HAPO effectively induces LLMs' concise reasoning abilities, producing length reductions of 33-59% with accuracy drops of only 2-5%.

[Arxiv](https://arxiv.org/abs/2505.11225)