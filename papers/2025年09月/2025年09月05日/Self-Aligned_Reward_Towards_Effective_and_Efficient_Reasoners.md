# 自对齐奖励：迈向高效能推理器

发布时间：2025年09月05日

`强化学习` `基础理论`

> Self-Aligned Reward: Towards Effective and Efficient Reasoners

# 摘要

> 基于可验证奖励的强化学习已显著提升大型语言模型（LLMs）的推理能力，但这类信号仍较为粗糙，仅能提供二元的正确性反馈。这种局限常引发低效问题，如推理冗长、计算成本高，而现有解决方案又往往以牺牲准确性为代价。为此，我们提出自对齐奖励（SAR）——一种自引导信号，作为可验证奖励的补充，旨在同时提升推理的准确性与效率。SAR的定义为：以查询为条件的答案与独立答案之间的相对困惑度差异，因此更青睐简洁且紧扣查询的回答。定量分析显示，SAR能可靠区分答案质量：简洁正确的答案得分高于冗余答案，部分正确的答案得分高于完全错误的答案。在4个模型和7个基准上的评估结果显示，将SAR与PPO、GRPO等主流强化学习算法结合后，准确率提升4%，推理成本降低30%。进一步分析表明，相较于基于长度或自我置信度的奖励信号，SAR在正确性与效率间达成了帕累托最优平衡。我们还发现，SAR在缩短回答长度的同时保留了高级推理能力，证明其能在不丢失关键推理的前提下抑制冗余阐述。这些结果凸显了自对齐奖励作为可验证奖励的细粒度补充的潜力，为更高效、更优质的LLM训练奠定了基础。

> Reinforcement learning with verifiable rewards has significantly advanced reasoning in large language models (LLMs), but such signals remain coarse, offering only binary correctness feedback. This limitation often results in inefficiencies, including overly verbose reasoning and high computational cost, while existing solutions often compromise accuracy. To address this, we introduce self-aligned reward (SAR), a self-guided signal that complements verifiable rewards to encourage both reasoning accuracy and efficiency. SAR is defined as the relative perplexity difference between an answer conditioned on the query and the standalone answer, thereby favoring responses that are concise and query-specific. Quantitative analysis reveals that SAR reliably distinguishes answer quality: concise, correct answers score higher than redundant ones, and partially correct answers score higher than entirely incorrect ones. Evaluation on 4 models across 7 benchmarks shows that integrating SAR with prevalent RL algorithms like PPO and GRPO improves accuracy by 4%, while reducing inference cost by 30%. Further analysis demonstrates that SAR achieves a Pareto-optimal trade-off between correctness and efficiency compared to reward signals based on length or self-confidence. We also show that SAR shortens responses while preserving advanced reasoning behaviors, demonstrating its ability to suppress unnecessary elaboration without losing critical reasoning. These results highlight the promise of self-aligned reward as a fine-grained complement to verifiable rewards, paving the way for more efficient and effective LLM training.

[Arxiv](https://arxiv.org/abs/2509.05489)