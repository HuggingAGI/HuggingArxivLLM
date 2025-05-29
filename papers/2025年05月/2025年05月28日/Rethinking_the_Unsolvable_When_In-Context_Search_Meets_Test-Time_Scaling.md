# 重新审视无法解决的难题：上下文搜索与测试时间缩放的结合

发布时间：2025年05月28日

`LLM理论` `人工智能`

> Rethinking the Unsolvable: When In-Context Search Meets Test-Time Scaling

# 摘要

> 近期研究指出，大型语言模型（LLMs）在处理复杂推理问题时仍面临重大挑战，即使经过冗长推理步骤的训练也不例外。然而，现有文献多依赖简单的上下文学习示例进行直接提示评估，这忽视了激发LLMs深思熟虑推理的高级技术。本文系统性地探索了在超复杂推理任务中，上下文搜索与推理时扩展的结合潜力。我们发现，通过运用结合内部扩展增强的LLMs进行高级上下文搜索提示，可以实现对先前被认为“不可解”任务（如成功率低于5%）的突破性性能提升。我们从实证和理论两方面分析了这一组合如何释放LLMs推理能力：i) 实证上，针对受控NP难任务和复杂现实世界规划基准，与先前报道的结果相比，我们的方法在无需任何外部机制的情况下，成功率提升了高达30倍；ii) 理论上，我们证明，当上下文搜索提示与内部扩展结合时，显著扩展了可解推理问题的复杂度类别。这些发现挑战了关于LLMs在复杂任务上局限性的传统假设，表明当前评估范式系统性低估了其真实潜力。我们的研究呼吁对LLMs推理基准进行批判性重新评估，并提出一种更稳健的评估策略，以充分捕捉当代LLMs的真实能力，从而更好地理解其在实际部署中的推理边界。

> Recent research has highlighted that Large Language Models (LLMs), even when trained to generate extended long reasoning steps, still face significant challenges on hard reasoning problems. However, much of the existing literature relies on direct prompting with simple in-context learning examples for evaluation, which largely overlooks advanced techniques to elicit LLMs' deliberate reasoning before drawing conclusions that LLMs hit a performance ceiling. In this paper, we systematically explore the combined potential of in-context search and test-time scaling on super hard reasoning tasks. We find that by employing advanced in-context search prompting to LLMs augmented with internal scaling, one can achieve transformative performance breakthroughs on tasks previously deemed "unsolvable" (e.g., reported success rates below 5%). We provide both empirical results and theoretical analysis of how this combination can unleash LLM reasoning capabilities: i) Empirically, on controlled NP-hard tasks and complex real-world planning benchmarks, our approach achieves up to a 30x improvement in success rates compared to previously reported results without any external mechanisms; ii) Theoretically, we show that in-context search prompting, when combined with internal scaling, significantly extends the complexity class of solvable reasoning problems. These findings challenge prevailing assumptions about the limitations of LLMs on complex tasks, indicating that current evaluation paradigms systematically underestimate their true potential. Our work calls for a critical reassessment of how LLM reasoning is benchmarked and a more robust evaluation strategy that fully captures the true capabilities of contemporary LLMs, which can lead to a better understanding of their operational reasoning boundaries in real-world deployments.

[Arxiv](https://arxiv.org/abs/2505.22290)