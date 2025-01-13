# 语义探索与自适应门控：语言模型的高效问题解决之道

发布时间：2025年01月10日

`LLM应用

理由：这篇论文主要讨论了如何通过改进树搜索方法来提高大型语言模型（LLMs）在复杂任务中的推理效率和准确性。提出的方法（SEAG）通过自适应门控机制和语义探索来优化计算资源的使用，并减少冗余探索。这些改进直接应用于LLMs的推理过程，属于LLM在实际任务中的应用和优化，因此应归类为LLM应用。` `人工智能`

> Semantic Exploration with Adaptive Gating for Efficient Problem Solving with Language Models

# 摘要

> # 摘要
最近大型语言模型（LLMs）的突破性进展在需要多步推理方法（如树搜索）的复杂任务中展现了巨大潜力。然而，现有方法常因计算效率低下和冗余问题而受限。首先，它们忽视了任务难度的多样性，导致对简单任务也进行不必要的广泛搜索。其次，它们忽略了推理路径的语义，导致对语义相同的路径进行冗余探索。为此，我们提出了语义探索与自适应门控（SEAG），一种计算高效的方法。SEAG通过自适应门控机制，根据简单推理方法的答案置信度动态决定是否进行树搜索。此外，其基于树的探索整合了语义相同的推理步骤，减少了冗余探索，同时保持甚至提高了准确性。大量实验表明，在GSM8K和ARC等复杂推理基准测试中，与现有基于树搜索的方法相比，SEAG显著提升了4.3%的平均准确性，同时仅需31%的计算成本，适用于Llama2、Llama3和Mistral等多种语言模型。

> Recent advancements in large language models (LLMs) have shown remarkable potential in various complex tasks requiring multi-step reasoning methods like tree search to explore diverse reasoning paths. However, existing methods often suffer from computational inefficiency and redundancy. First, they overlook the diversity of task difficulties, leading to unnecessarily extensive searches even for easy tasks. Second, they neglect the semantics of reasoning paths, resulting in redundant exploration of semantically identical paths. To address these limitations, we propose Semantic Exploration with Adaptive Gating (SEAG), a computationally efficient method. SEAG employs an adaptive gating mechanism that dynamically decides whether to conduct a tree search, based on the confidence level of answers from a preceding simple reasoning method. Furthermore, its tree-based exploration consolidates semantically identical reasoning steps, reducing redundant explorations while maintaining or even improving accuracy. Our extensive experiments demonstrate that SEAG significantly improves accuracy by 4.3% on average while requiring only 31% of computational costs compared to existing tree search-based methods on complex reasoning benchmarks including GSM8K and ARC with diverse language models such as Llama2, Llama3, and Mistral.

[Arxiv](https://arxiv.org/abs/2501.05752)