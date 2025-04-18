# 基于自方面检索增强生成的方面摘要方法

发布时间：2025年04月17日

`LLM应用

分类理由：这篇论文探讨了基于方面的摘要生成问题，提出了一种结合检索和大型语言模型的方法，以解决上下文学习中的挑战。虽然涉及检索机制，但主要目的是优化大型语言模型的应用，属于LLM应用类别。` `文本摘要生成`

> Aspect-Based Summarization with Self-Aspect Retrieval Enhanced Generation

# 摘要

> 基于方面的摘要生成旨在为特定方面定制摘要，解决了传统方法的资源限制和泛化能力不足的问题。最近，大型语言模型在这一任务中展现出潜力，无需额外训练。然而，它们过度依赖提示工程，并在上下文学习中面临令牌限制和幻觉挑战。为应对这些挑战，本文提出了一种新型框架：基于自我方面检索的摘要生成框架。与仅依赖上下文学习不同，给定一个方面，我们采用基于嵌入的检索机制来识别相关文本段落。这种方法提取相关内容，避免冗余细节，从而缓解了令牌限制的挑战。此外，我们的框架通过删除无关文本部分，并确保模型仅根据给定方面生成输出，优化了令牌使用。通过在基准数据集上的大量实验，我们证明了我们的框架不仅性能优越，还有效缓解了令牌限制问题。

> Aspect-based summarization aims to generate summaries tailored to specific aspects, addressing the resource constraints and limited generalizability of traditional summarization approaches. Recently, large language models have shown promise in this task without the need for training. However, they rely excessively on prompt engineering and face token limits and hallucination challenges, especially with in-context learning. To address these challenges, in this paper, we propose a novel framework for aspect-based summarization: Self-Aspect Retrieval Enhanced Summary Generation. Rather than relying solely on in-context learning, given an aspect, we employ an embedding-driven retrieval mechanism to identify its relevant text segments. This approach extracts the pertinent content while avoiding unnecessary details, thereby mitigating the challenge of token limits. Moreover, our framework optimizes token usage by deleting unrelated parts of the text and ensuring that the model generates output strictly based on the given aspect. With extensive experiments on benchmark datasets, we demonstrate that our framework not only achieves superior performance but also effectively mitigates the token limitation problem.

[Arxiv](https://arxiv.org/abs/2504.13054)