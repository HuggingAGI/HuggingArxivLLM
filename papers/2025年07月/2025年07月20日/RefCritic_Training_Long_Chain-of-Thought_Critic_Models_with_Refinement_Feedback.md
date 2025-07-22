# RefCritic: 通过优化反馈打造长链式思考评价模型

发布时间：2025年07月20日

`LLM应用` `人工智能` `计算机科学`

> RefCritic: Training Long Chain-of-Thought Critic Models with Refinement Feedback

# 摘要

> 随着大型语言模型（LLMs）的快速发展，开发有效的批评模块以实现精准指导变得至关重要且具挑战性。本文中，我们首先证明了用于构建批评模块的监督微调（当前解决方案中广泛采用的方法）未能真正提升模型的批判能力，产生的批判往往流于表面，缺乏深入的反思和验证。为了释放前所未有的批判能力，我们提出了RefCritic，这是一种基于强化学习的长链式思考批评模块，采用双规则奖励机制：（1）解决方案判断的实例级别正确性，以及（2）基于批判的策略模型精调准确性，旨在生成具有可操作反馈的高质量评估，从而有效指导模型优化。我们在Qwen2.5-14B-Instruct和DeepSeek-R1-Distill-Qwen-14B模型上，针对五个基准进行了RefCritic的评估。在批判和优化设置下，RefCritic在所有基准中均展现出显著优势，例如在AIME25基准上，两个基础模型分别获得了6.8%和7.2%的提升。值得注意的是，在多数投票机制下，经过RefCritic筛选的策略模型表现出随着投票数量增加而性能提升的特性。此外，尽管RefCritic的训练基于解决方案级别的监督，但在ProcessBench基准（用于识别数学推理中的错误步骤）上，它超越了基于步骤级别的监督方法。

> With the rapid advancement of Large Language Models (LLMs), developing effective critic modules for precise guidance has become crucial yet challenging. In this paper, we initially demonstrate that supervised fine-tuning for building critic modules (which is widely adopted in current solutions) fails to genuinely enhance models' critique abilities, producing superficial critiques with insufficient reflections and verifications. To unlock the unprecedented critique capabilities, we propose RefCritic, a long-chain-of-thought critic module based on reinforcement learning with dual rule-based rewards: (1) instance-level correctness of solution judgments and (2) refinement accuracies of the policy model based on critiques, aiming to generate high-quality evaluations with actionable feedback that effectively guides model refinement. We evaluate RefCritic on Qwen2.5-14B-Instruct and DeepSeek-R1-Distill-Qwen-14B across five benchmarks. On critique and refinement settings, RefCritic demonstrates consistent advantages across all benchmarks, e.g., 6.8\% and 7.2\% gains on AIME25 for the respective base models. Notably, under majority voting, policy models filtered by RefCritic show superior scaling with increased voting numbers. Moreover, despite training on solution-level supervision, RefCritic outperforms step-level supervised approaches on ProcessBench, a benchmark to identify erroneous steps in mathematical reasoning.

[Arxiv](https://arxiv.org/abs/2507.15024)