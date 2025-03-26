# # 标题
仅靠先天推理能力远远不够：上下文学习通过减少过度思考，助力提升大型语言模型的推理能力。

发布时间：2025年03月25日

`LLM理论` `人工智能`

> Innate Reasoning is Not Enough: In-Context Learning Enhances Reasoning Large Language Models with Less Overthinking

# 摘要

> 大语言模型（LLMs）的最新进展催生了推理型大语言模型（RLLMs），这些模型通过具备反思与自我修正能力的扩展思维过程，展示了推理时扩展的有效性。RLLMs在训练中获得了内在的Chain-of-Thought（CoT）推理能力，这引出了一个关键问题：作为一种流行的用于聊天LLMs的In-Context Learning（ICL）方法，CoT提示是否有必要来增强RLLMs的推理能力？本研究首次全面分析了零样本CoT和少样本CoT对RLLMs在数学推理任务中的影响，考察了从1.5B到32B参数规模的模型。研究发现，与人们的担忧相反，CoT提示在大多数情况下显著提升了RLLMs的表现。研究结果揭示了不同模式：大容量模型在简单任务上改进有限，但在复杂问题上获得了显著提升；而较小的模型则表现出相反的行为。进一步分析表明，CoT提示有效控制了思考标记和推理步骤的数量分布，在某些情况下减少了过度反思约90%。此外，注意力权重分析显示，RLLMs过度拟合与反思相关的词汇，而外部的CoT引导则缓解了这一问题。值得注意的是，实验表明，对于RLLMs而言，单样本CoT始终优于少样本CoT方法。这些发现为通过适当的提示策略优化RLLMs的表现提供了重要见解。

> Recent advances in Large Language Models (LLMs) have introduced Reasoning Large Language Models (RLLMs), which employ extended thinking processes with reflection and self-correction capabilities, demonstrating the effectiveness of test-time scaling. RLLMs exhibit innate Chain-of-Thought (CoT) reasoning capability obtained from training, leading to a natural question: "Is CoT prompting, a popular In-Context Learning (ICL) method for chat LLMs, necessary to enhance the reasoning capability of RLLMs?" In this work, we present the first comprehensive analysis of the impacts of Zero-shot CoT and Few-shot CoT on RLLMs across mathematical reasoning tasks. We examine models ranging from 1.5B to 32B parameters, finding that contrary to concerns, CoT prompting significantly enhances RLLMs' performance in most scenarios. Our results reveal distinct patterns: large-capacity models show minimal improvement on simple tasks but substantial gains on complex problems, while smaller models exhibit the opposite behavior. Further analysis demonstrates that CoT prompting effectively controls the distribution of the numbers of thinking tokens and reasoning steps, reducing excessive reflections by approximately 90% in some cases. Moreover, attention logits analysis reveals the RLLMs' overfitting to reflection-related words, which is mitigated by external CoT guidance. Notably, our experiments indicate that for RLLMs, one-shot CoT consistently yields superior performance compared to Few-shot CoT approaches. Our findings provide important insights for optimizing RLLMs' performance through appropriate prompting strategies.

[Arxiv](https://arxiv.org/abs/2503.19602)