# 回溯与否：序列搜索限制模型推理的边界

发布时间：2025年04月09日

`LLM应用` `人工智能` `计算机科学`

> To Backtrack or Not to Backtrack: When Sequential Search Limits Model Reasoning

# 摘要

> 大型语言模型的推理能力近期取得显著提升，尤其是通过搜索与回溯技术。回溯通过生成长链式思维链，自然扩展推理计算，但并非唯一策略：并行采样结合最优选择提供同时生成多种方案的替代方案。尽管顺序搜索应用广泛，但其相对于并行采样的优势——尤其在固定计算预算下——尚未明确。本文在 CountDown 和 Sudoku 两个挑战性推理任务上系统对比这两种方法。令人意外的是，顺序搜索在 CountDown 中表现 inferior 于并行采样，但在 Sudoku 中则更优，表明回溯并非普遍有益。我们发现，回溯性能下降可能源于：（1）固定搜索轨迹训练使模型陷入次优策略；（2）显式思维链监督抑制隐式推理。进一步分析强化学习，发现具备回溯能力的模型显著受益于 RL 微调，而缺乏回溯的模型仅获有限提升。这些发现挑战了回溯普遍提升推理能力的假设，揭示了任务结构、训练数据、模型规模及学习范式间的复杂交互。

> Recent advancements in large language models have significantly improved their reasoning abilities, particularly through techniques involving search and backtracking. Backtracking naturally scales test-time compute by enabling sequential, linearized exploration via long chain-of-thought (CoT) generation. However, this is not the only strategy for scaling test-time compute: parallel sampling with best-of-n selection provides an alternative that generates diverse solutions simultaneously. Despite the growing adoption of sequential search, its advantages over parallel sampling--especially under a fixed compute budget remain poorly understood. In this paper, we systematically compare these two approaches on two challenging reasoning tasks: CountDown and Sudoku. Surprisingly, we find that sequential search underperforms parallel sampling on CountDown but outperforms it on Sudoku, suggesting that backtracking is not universally beneficial. We identify two factors that can cause backtracking to degrade performance: (1) training on fixed search traces can lock models into suboptimal strategies, and (2) explicit CoT supervision can discourage "implicit" (non-verbalized) reasoning. Extending our analysis to reinforcement learning (RL), we show that models with backtracking capabilities benefit significantly from RL fine-tuning, while models without backtracking see limited, mixed gains. Together, these findings challenge the assumption that backtracking universally enhances LLM reasoning, instead revealing a complex interaction between task structure, training data, model scale, and learning paradigm.

[Arxiv](https://arxiv.org/abs/2504.07052)