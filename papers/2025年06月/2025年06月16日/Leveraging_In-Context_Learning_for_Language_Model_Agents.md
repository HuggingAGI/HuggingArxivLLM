# # 驾驭上下文学习，赋能语言模型代理

发布时间：2025年06月16日

`Agent` `智能体` `人工智能`

> Leveraging In-Context Learning for Language Model Agents

# 摘要

> 上下文学习（ICL）通过动态选择示例，将提示大型语言模型的灵活性与利用训练数据提升性能的能力完美结合。尽管ICL在预测和生成任务中表现卓越，但将其应用于需要顺序决策的智能体任务更具挑战性。不仅要考虑如何大规模标注长轨迹、如何选择示例，还需明确示例的构成，以及何时何地展示它们。

为应对这一挑战，我们首先提出了一种结合重试机制与示例的算法，利用大型语言模型（LLM）自动高效地为智能体任务标注解决方案轨迹。随后，我们发现，将相似任务的轨迹集合作为示例，能显著提升LLM智能体的性能、可靠性、鲁棒性和效率。然而，轨迹示例带来了较大的推理成本开销。我们发现，通过在每一步使用小片段轨迹示例而非额外轨迹，这一问题可以得到缓解。

我们还发现，标注阶段从较大模型获得的示例也能提升较小模型，并且ICL智能体甚至可以与更昂贵的训练智能体相媲美。因此，我们的研究结果表明，只要谨慎使用，ICL在智能体任务中同样可以非常强大。


> In-context learning (ICL) with dynamically selected demonstrations combines the flexibility of prompting large language models (LLMs) with the ability to leverage training data to improve performance. While ICL has been highly successful for prediction and generation tasks, leveraging it for agentic tasks that require sequential decision making is challenging -- one must think not only about how to annotate long trajectories at scale and how to select demonstrations, but also what constitutes demonstrations, and when and where to show them. To address this, we first propose an algorithm that leverages an LLM with retries along with demonstrations to automatically and efficiently annotate agentic tasks with solution trajectories. We then show that set-selection of trajectories of similar tasks as demonstrations significantly improves performance, reliability, robustness, and efficiency of LLM agents. However, trajectory demonstrations have a large inference cost overhead. We show that this can be mitigated by using small trajectory snippets at every step instead of an additional trajectory. We find that demonstrations obtained from larger models (in the annotation phase) also improve smaller models, and that ICL agents can even rival costlier trained agents. Thus, our results reveal that ICL, with careful use, can be very powerful for agentic tasks as well.

[Arxiv](https://arxiv.org/abs/2506.13109)