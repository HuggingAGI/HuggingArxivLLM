# 故事基准：一个多轮动态基准，用于评估长期记忆

发布时间：2025年06月16日

`LLM理论` `人工智能`

> StoryBench: A Dynamic Benchmark for Evaluating Long-Term Memory with Multi Turns

# 摘要

> 在复杂多变的环境中，长期记忆（LTM）是大型语言模型（LLMs）实现自主智能的关键所在。尽管记忆增强和基于检索的架构研究日益深入，但系统性评估LLMs长期记忆能力的标准化基准仍付之阙如。现有基准在知识保留、动态推理以及自身灵活性方面仍存挑战，限制了其对模型LTM能力的评估效果。为填补这一空白，我们推出了一款基于互动小说游戏的新型基准框架，其特色在于动态分支的情节线和复杂推理结构。这些结构通过要求LLMs在分层决策树中导航，模拟现实场景，每个决策都会引发多轮交互中的连锁反应。我们的基准设计了两种测试推理复杂性的独特场景：一种是错误决策即时反馈，另一种则要求模型在失败后独立追溯并修正先前选择。作为该基准的一部分，我们还打造了一个专为测试LLMs在叙事驱动环境中的长期记忆能力而设计的新数据集。通过详实的实验，我们验证了这一方法的有效性。实验结果证实，该基准能够稳健且可靠地评估LLMs的长期记忆能力。

> Long-term memory (LTM) is essential for large language models (LLMs) to achieve autonomous intelligence in complex, evolving environments. Despite increasing efforts in memory-augmented and retrieval-based architectures, there remains a lack of standardized benchmarks to systematically evaluate LLMs' long-term memory abilities. Existing benchmarks still face challenges in evaluating knowledge retention and dynamic sequential reasoning, and in their own flexibility, all of which limit their effectiveness in assessing models' LTM capabilities. To address these gaps, we propose a novel benchmark framework based on interactive fiction games, featuring dynamically branching storylines with complex reasoning structures. These structures simulate real-world scenarios by requiring LLMs to navigate hierarchical decision trees, where each choice triggers cascading dependencies across multi-turn interactions. Our benchmark emphasizes two distinct settings to test reasoning complexity: one with immediate feedback upon incorrect decisions, and the other requiring models to independently trace back and revise earlier choices after failure. As part of this benchmark, we also construct a new dataset designed to test LLMs' LTM within narrative-driven environments. We further validate the effectiveness of our approach through detailed experiments. Experimental results demonstrate the benchmark's ability to robustly and reliably assess LTM in LLMs.

[Arxiv](https://arxiv.org/abs/2506.13356)