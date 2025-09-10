# 大型语言模型中的确定性导向推理：动态思维预算方法

发布时间：2025年09月09日

`LLM应用` `基础理论`

> Certainty-Guided Reasoning in Large Language Models: A Dynamic Thinking Budget Approach

# 摘要

> 大型推理语言模型（LRLMs）的崛起为解决复杂任务注入了新活力。这类模型的运行受限于“思考配额”——即预留给推理过程的标记数量上限。我们借鉴生成对抗网络中生成器/判别器的框架思路，提出一种创新方法：让评判模块定期审视自身推理轨迹，判断是否已形成可靠结论。若未形成，则继续推理，直至满足目标确定性阈值。该机制能自适应平衡效率与可靠性：信心充足时提前终止，不确定性未消除时则深入推理。

在AIME2024和AIME2025数据集上的实验证实，确定性引导推理（CGR）在提升基线准确率的同时，还能降低标记消耗。值得注意的是，经过64次多种子扩展实验验证，CGR稳定性优异——不仅降低了种子间差异，还在惩罚制评分体系下提升了类考试场景表现。此外，标记节约分析显示，CGR累计可节省数百万标记，且支持确定性阈值与效率的灵活权衡。

总之，这些发现证实确定性是衡量推理充分性的关键指标。通过将信心信号融入推理流程，CGR让大型推理语言模型在适应性、可信度和资源效率上均有提升，为准确性与计算成本并重的领域实际落地奠定了基础。

> The rise of large reasoning language models (LRLMs) has unlocked new potential for solving complex tasks. These models operate with a thinking budget, that is, a predefined number of reasoning tokens used to arrive at a solution. We propose a novel approach, inspired by the generator/discriminator framework in generative adversarial networks, in which a critic model periodically probes its own reasoning to assess whether it has reached a confident conclusion. If not, reasoning continues until a target certainty threshold is met. This mechanism adaptively balances efficiency and reliability by allowing early termination when confidence is high, while encouraging further reasoning when uncertainty persists. Through experiments on the AIME2024 and AIME2025 datasets, we show that Certainty-Guided Reasoning (CGR) improves baseline accuracy while reducing token usage. Importantly, extended multi-seed evaluations over 64 runs demonstrate that CGR is stable, reducing variance across seeds and improving exam-like performance under penalty-based grading. Additionally, our token savings analysis shows that CGR can eliminate millions of tokens in aggregate, with tunable trade-offs between certainty thresholds and efficiency. Together, these findings highlight certainty as a powerful signal for reasoning sufficiency. By integrating confidence into the reasoning process, CGR makes large reasoning language models more adaptive, trustworthy, and resource efficient, paving the way for practical deployment in domains where both accuracy and computational cost matter.

[Arxiv](https://arxiv.org/abs/2509.07820)