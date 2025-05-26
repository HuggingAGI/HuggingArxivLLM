# T$^2$：一种用于上下文问答的自适应测试时间缩放策略

发布时间：2025年05月22日

`LLM应用` `问答系统`

> T$^2$: An Adaptive Test-Time Scaling Strategy for Contextual Question Answering

# 摘要

> 大型语言模型（LLMs）在上下文问答（CQA）领域展现了非凡的能力。然而，传统方法不管问题难度如何，都采用复杂的推理策略，导致适应性不足。近期的高效推理扩展方法虽然通过预算限制或提前终止机制避免了对简单问题的过度思考，但这些方法却引入了人为偏见，并未充分利用模型自身的推理潜力。为了解决这些问题，我们提出了T²：Think-to-Think，这是一种基于问题复杂度动态调整推理深度的创新框架。T²的核心理念是：若一个LLM能用特定策略有效解决类似问题，它也能将该策略应用到原问题上。这一理念使得T²既能对简单问题采用简洁推理，又能在处理复杂问题时保持细致分析。T²通过四个关键步骤实现这一目标：分解问题结构、生成候选策略示例、多维度评估策略、应用最优策略。在七个不同CQA基准上的实验表明，T²不仅在准确性上超越了传统方法，还将计算开销降低了25.2%。

> Recent advances in Large Language Models (LLMs) have demonstrated remarkable performance in Contextual Question Answering (CQA). However, prior approaches typically employ elaborate reasoning strategies regardless of question complexity, leading to low adaptability. Recent efficient test-time scaling methods introduce budget constraints or early stop mechanisms to avoid overthinking for straightforward questions. But they add human bias to the reasoning process and fail to leverage models' inherent reasoning capabilities. To address these limitations, we present T$^2$: Think-to-Think, a novel framework that dynamically adapts reasoning depth based on question complexity. T$^2$ leverages the insight that if an LLM can effectively solve similar questions using specific reasoning strategies, it can apply the same strategy to the original question. This insight enables to adoption of concise reasoning for straightforward questions while maintaining detailed analysis for complex problems. T$^2$ works through four key steps: decomposing questions into structural elements, generating similar examples with candidate reasoning strategies, evaluating these strategies against multiple criteria, and applying the most appropriate strategy to the original question. Experimental evaluation across seven diverse CQA benchmarks demonstrates that T$^2$ not only achieves higher accuracy than baseline methods but also reduces computational overhead by up to 25.2\%.

[Arxiv](https://arxiv.org/abs/2505.17427)