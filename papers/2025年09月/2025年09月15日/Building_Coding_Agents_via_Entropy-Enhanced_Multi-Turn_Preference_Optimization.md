# 基于熵增强多轮偏好优化构建编码智能体

发布时间：2025年09月15日

`Agent` `工业与制造`

> Building Coding Agents via Entropy-Enhanced Multi-Turn Preference Optimization

# 摘要

> 软件工程给大型语言模型（LLMs）带来了复杂的多步骤挑战，不仅需要对庞大代码库进行推理，还需协调工具使用。这类任务的难度在SWE-bench等基准测试中尤为突出——现有LLMs在解决实际问题时依旧力不从心。
  测试时扩展（TTS）是提升性能的潜在方案，但其效果高度依赖模型输出的多样性。
  尽管直接偏好优化（DPO）、卡尼曼-特沃斯基优化（KTO）等标准对齐方法能有效让模型输出贴合人类偏好，却可能导致多样性下降，进而限制TTS的效果。
  此外，现有偏好优化算法多针对单轮任务设计，无法充分应对交互式编码智能体所需的多轮推理与工具集成难题。
  为此，我们提出了\sys——一个熵增强框架，能将现有偏好优化算法适配至多轮工具辅助场景。
  \sys通过增强偏好目标来明确保留策略熵，并将学习范围从单轮响应扩展到多轮交互优化。
  我们对不同家族、不同规模（最大1060亿参数）的多种模型进行微调，以此验证\sys的效果。
  为充分发挥TTS的性能潜力，我们还提出了混合最佳轨迹选择方案，将学习到的验证器模型与无模型方法融合。
  在\swebench排行榜上，我们的方法在开源权重模型中刷新了最先进水平。
  经\sys训练的300亿参数模型在开源权重排行榜中，\lite项目位列第一，erified项目排名第四，仅落后于参数规模超10倍的模型（例如【数学公式】）。

> Software engineering presents complex, multi-step challenges for Large Language Models (LLMs), requiring reasoning over large codebases and coordinated tool use. The difficulty of these tasks is exemplified by benchmarks like SWE-bench, where current LLMs still struggle to resolve real-world issues.
  A promising approach to enhance performance is test-time scaling (TTS), but its gains are heavily dependent on the diversity of model outputs.
  While standard alignment methods such as Direct Preference Optimization (DPO) and Kahneman-Tversky Optimization (KTO) are effective at aligning model outputs with human preferences, this process can come at the cost of reduced diversity, limiting the effectiveness of TTS.
  Additionally, existing preference optimization algorithms are typically designed for single-turn tasks and do not fully address the complexities of multi-turn reasoning and tool integration required for interactive coding agents.
  To bridge this gap, we introduce \sys, an entropy-enhanced framework that adapts existing preference optimization algorithms to the multi-turn, tool-assisted setting.
  \sys augments the preference objective to explicitly preserve policy entropy and generalizes learning to optimize over multi-turn interactions rather than single-turn responses.
  We validate \sys by fine-tuning a diverse suite of models from different families and sizes (up to 106B parameters).
  To maximize performance gains from TTS, we further propose a hybrid best-trajectory selection scheme combining a learned verifier model with model free approaches.
  On the \swebench leaderboard, our approach establishes new state-of-the-art results among open-weight models. A 30B parameter model trained with \sys ranks 1st on \lite and 4th on \verified on the open-weight leaderboard, surpassed only by models with over 10x more parameters(\eg$>$350B).

[Arxiv](https://arxiv.org/abs/2509.12434)