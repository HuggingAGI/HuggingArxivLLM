# 探索大型语言模型的逻辑能力：基于上下文外表示学习的方法

发布时间：2025年03月13日

`LLM理论

理由：这篇论文探讨了大型语言模型在逻辑推理任务中的能力，并提出了一种新的学习方法“出上下文表示学习”，这属于对模型本身的理论分析和方法论的创新，因此归类为LLM理论。` `人工智能` `逻辑推理`

> Understanding the Logical Capabilities of Large Language Models via Out-of-Context Representation Learning

# 摘要

> 我们深入探讨了大型语言模型 (LLM) 在二元关系上的能力，这一概念几乎贯穿所有推理、数学和逻辑基准测试。研究重点放在等式、不等式和包含关系，及其自反性/非自反性、对称性/非对称性、传递性等性质，以及逻辑复杂度（如推理所需步骤数）上。我们提出了一种全新的替代方案——出上下文表示学习，仅需训练新引入标记的表示。这种方法不仅减少了模型中的语言偏见，还无需依赖外部信息或示例，与传统的上下文学习截然不同。我们主张，出上下文表示学习是评估 LLM 在逻辑任务上的能力的更优选择，这些任务正是构建更复杂推理基准的基石。

> We study the capabilities of Large Language Models (LLM) on binary relations, a ubiquitous concept in math employed in most reasoning, math and logic benchmarks. This work focuses on equality, inequality, and inclusion, along with the properties they satisfy, such as ir/reflexivity, a/symmetry, transitivity, and logical complexity (e.g., number of reasoning ``hops''). We propose an alternative to in-context learning that trains only the representations of newly introduced tokens, namely out-of-context representation learning. This method mitigates linguistic biases already present in a model and, differently from in-context learning, does not rely on external information or illustrations. We argue out-of-context representation learning as a better alternative to in-context learning and fine-tuning to evaluate the capabilities of LLMs on logic tasks that are the building blocks of more complex reasoning benchmarks.

[Arxiv](https://arxiv.org/abs/2503.10408)