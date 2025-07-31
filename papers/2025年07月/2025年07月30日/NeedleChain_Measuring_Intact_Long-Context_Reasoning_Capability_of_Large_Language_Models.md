# 针链：评估大型语言模型中的完整长上下文推理能力

发布时间：2025年07月30日

`LLM理论` `基准测试`

> NeedleChain: Measuring Intact Long-Context Reasoning Capability of Large Language Models

# 摘要

> 针在稻草堆中（NIAH）基准广泛用于评估大语言模型（LLMs）理解长上下文（LC）的能力。它主要评估在大量无关段落中精准识别与查询相关上下文的能力。尽管这种方法被广泛认可为评估长上下文理解的标准，但我们的研究发现，它可能高估了LLMs真正的长上下文理解能力。我们发现，即使是像GPT-4o这样最先进的模型，在处理仅包含10个相关句子的上下文时也难以完全整合。针对这一问题，我们提出了一种全新的基准测试——	extbf{NeedleChain}，其中上下文完全由与查询相关的信息组成，要求LLMs全面理解输入才能正确回答。我们的基准测试支持灵活的上下文长度和推理顺序，能够更全面地分析LLMs的表现。此外，我们提出了一种极为简单却极具吸引力的策略来提升LLMs的长上下文理解能力：ROPE Contraction。通过在多种先进LLMs上的实验，我们发现它们处理大量上下文的能力与其全面理解这些上下文的能力之间存在显著差异。源代码和数据集可在https://github.com/hyeonseokk/NeedleChain获取

> The Needle-in-a-Haystack (NIAH) benchmark is widely used to evaluate Large Language Models' (LLMs) ability to understand long contexts (LC). It evaluates the capability to identify query-relevant context within extensive query-irrelevant passages. Although this method serves as a widely accepted standard for evaluating long-context understanding, our findings suggest it may overestimate the true LC capability of LLMs. We demonstrate that even state-of-the-art models such as GPT-4o struggle to intactly incorporate given contexts made up of solely query-relevant ten sentences. In response, we introduce a novel benchmark, \textbf{NeedleChain}, where the context consists entirely of query-relevant information, requiring the LLM to fully grasp the input to answer correctly. Our benchmark allows for flexible context length and reasoning order, offering a more comprehensive analysis of LLM performance. Additionally, we propose an extremely simple yet compelling strategy to improve LC understanding capability of LLM: ROPE Contraction. Our experiments with various advanced LLMs reveal a notable disparity between their ability to process large contexts and their capacity to fully understand them. Source code and datasets are available at https://github.com/hyeonseokk/NeedleChain

[Arxiv](https://arxiv.org/abs/2507.22411)