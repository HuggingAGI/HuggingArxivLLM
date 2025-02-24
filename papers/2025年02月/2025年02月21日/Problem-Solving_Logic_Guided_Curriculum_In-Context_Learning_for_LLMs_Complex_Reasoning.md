# # 问题解决逻辑引导的大型语言模型复杂推理上下文学习

发布时间：2025年02月21日

`LLM应用` `人工智能`

> Problem-Solving Logic Guided Curriculum In-Context Learning for LLMs Complex Reasoning

# 摘要

> ICL 能显著提升 LLMs 的复杂推理能力，关键在于演示示例的选择与排序。传统方法依赖简单特征衡量示例关联性，但这些特征难以反映示例间的深层联系。本研究提出了一种基于问题解决逻辑的课程式 ICL 策略。我们通过分析问题解决逻辑选择演示示例，并基于课程学习原则进行排序。具体而言，我们基于 BREAK 数据集构建了问题解决逻辑指令集，微调语言模型以分析示例的逻辑结构。随后，根据问题解决逻辑选择合适示例，并通过步骤数量评估难度。遵循课程学习原则，我们将示例按难度从低到高排序，作为上下文提示。在多个基准测试中，我们的方法在性能和效率上均优于传统 ICL 方法，显著提升了 LLMs 的复杂推理能力。我们的研究成果将择期公开。

> In-context learning (ICL) can significantly enhance the complex reasoning capabilities of large language models (LLMs), with the key lying in the selection and ordering of demonstration examples. Previous methods typically relied on simple features to measure the relevance between examples. We argue that these features are not sufficient to reflect the intrinsic connections between examples. In this study, we propose a curriculum ICL strategy guided by problem-solving logic. We select demonstration examples by analyzing the problem-solving logic and order them based on curriculum learning. Specifically, we constructed a problem-solving logic instruction set based on the BREAK dataset and fine-tuned a language model to analyze the problem-solving logic of examples. Subsequently, we selected appropriate demonstration examples based on problem-solving logic and assessed their difficulty according to the number of problem-solving steps. In accordance with the principles of curriculum learning, we ordered the examples from easy to hard to serve as contextual prompts. Experimental results on multiple benchmarks indicate that our method outperforms previous ICL approaches in terms of performance and efficiency, effectively enhancing the complex reasoning capabilities of LLMs. Our project will be publicly available subsequently.

[Arxiv](https://arxiv.org/abs/2502.15401)