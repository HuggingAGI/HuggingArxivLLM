# 系统1与系统2推理方法在零样本时间序列预测中的对比评估：基准测试与见解分享

发布时间：2025年02月27日

`LLM应用` `时间序列预测` `零样本学习`

> Evaluating System 1 vs. 2 Reasoning Approaches for Zero-Shot Time-Series Forecasting: A Benchmark and Insights

# 摘要

> 推理能力是解决复杂任务的关键。随着大型语言模型（LLMs）等基础模型的发展，人们提出了多种推理策略，包括测试时增强（如Chain-of-Thought）和后训练优化（如DeepSeek-R1）。尽管这些策略在语言和视觉任务中表现出色，但它们在时间序列预测（TSF）尤其是零样本TSF中的应用和效果尚未得到充分探索。特别是，零样本TSF是否受益于推理以及哪种推理策略最有效仍不清楚。为了解决这一问题，我们提出了ReC4TS，这是首个系统评估推理策略在零样本TSF任务中效果的基准。ReC4TS在涵盖八个领域的数据集上进行了全面测试，包括单模态和多模态的短期和长期预测任务。更重要的是，ReC4TS揭示了以下关键点：（1）自洽性是测试时推理策略中表现最佳的；（2）基于组的相对策略优化是激励后训练推理能力的更有效方法；（3）多模态TSF比单模态TSF更能从推理策略中获益。除了这些发现，ReC4TS还为未来的零样本TSF推理研究奠定了两个开创性的基础：（1）一个新型数据集TimeThinking，其中包含标注了来自多个先进LLMs的推理轨迹的预测样本；（2）一种新的测试时缩放定律，该定律通过自洽性推理策略在基础TSF模型上得到验证。所有数据和代码均可在以下链接公开获取：https://github.com/AdityaLab/OpenTimeR

> Reasoning ability is crucial for solving challenging tasks. With the advancement of foundation models, such as the emergence of large language models (LLMs), a wide range of reasoning strategies has been proposed, including test-time enhancements, such as Chain-ofThought, and post-training optimizations, as used in DeepSeek-R1. While these reasoning strategies have demonstrated effectiveness across various challenging language or vision tasks, their applicability and impact on time-series forecasting (TSF), particularly the challenging zero-shot TSF, remain largely unexplored. In particular, it is unclear whether zero-shot TSF benefits from reasoning and, if so, what types of reasoning strategies are most effective. To bridge this gap, we propose ReC4TS, the first benchmark that systematically evaluates the effectiveness of popular reasoning strategies when applied to zero-shot TSF tasks. ReC4TS conducts comprehensive evaluations across datasets spanning eight domains, covering both unimodal and multimodal with short-term and longterm forecasting tasks. More importantly, ReC4TS provides key insights: (1) Self-consistency emerges as the most effective test-time reasoning strategy; (2) Group-relative policy optimization emerges as a more suitable approach for incentivizing reasoning ability during post-training; (3) Multimodal TSF benefits more from reasoning strategies compared to unimodal TSF. Beyond these insights, ReC4TS establishes two pioneering starting blocks to support future zero-shot TSF reasoning research: (1) A novel dataset, TimeThinking, containing forecasting samples annotated with reasoning trajectories from multiple advanced LLMs, and (2) A new and simple test-time scaling-law validated on foundational TSF models enabled by self-consistency reasoning strategy. All data and code are publicly accessible at: https://github.com/AdityaLab/OpenTimeR

[Arxiv](https://arxiv.org/abs/2503.01895)