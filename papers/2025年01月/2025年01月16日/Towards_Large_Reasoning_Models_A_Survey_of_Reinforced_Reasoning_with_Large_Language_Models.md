# # 迈向大型推理模型：基于大语言模型的强化推理综述

发布时间：2025年01月16日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）在推理任务中的应用和发展，特别是通过引入“思维”概念和强化学习（RL）来扩展LLMs的推理能力。论文还探讨了训练时与测试时的扩展技术，并展望了未来的研究挑战与方向。这些内容主要涉及LLMs的理论基础和技术发展，因此将其分类为“LLM理论”。` `人工智能`

> Towards Large Reasoning Models: A Survey of Reinforced Reasoning with Large Language Models

# 摘要

> # 摘要
语言长久以来被视为人类推理的核心工具。随着大型语言模型（LLMs）的突破，利用这些模型解决复杂推理任务的研究兴趣激增。研究人员通过引入“思维”概念——即代表推理中间步骤的标记序列，超越了传统的自回归标记生成。这一创新使LLMs能够模拟复杂的推理过程，如树搜索和反思思维。最近，强化学习（RL）被应用于训练LLMs掌握推理过程，通过试错搜索算法自动生成高质量推理轨迹，大幅扩展了LLMs的推理能力。此外，研究表明，在测试时推理中鼓励LLMs使用更多标记进行“思考”可以显著提升推理准确性。训练时与测试时的扩展相结合，开辟了通向大型推理模型的新研究前沿。OpenAI的o1系列标志着这一方向的重要里程碑。本文综述了LLM推理的最新进展，从基础背景出发，探讨了推动大型推理模型发展的关键技术，包括自动化数据构建、学习推理技术和测试时扩展。我们还分析了相关开源项目，并展望了未来的研究挑战与方向。

> Language has long been conceived as an essential tool for human reasoning. The breakthrough of Large Language Models (LLMs) has sparked significant research interest in leveraging these models to tackle complex reasoning tasks. Researchers have moved beyond simple autoregressive token generation by introducing the concept of "thought" -- a sequence of tokens representing intermediate steps in the reasoning process. This innovative paradigm enables LLMs' to mimic complex human reasoning processes, such as tree search and reflective thinking. Recently, an emerging trend of learning to reason has applied reinforcement learning (RL) to train LLMs to master reasoning processes. This approach enables the automatic generation of high-quality reasoning trajectories through trial-and-error search algorithms, significantly expanding LLMs' reasoning capacity by providing substantially more training data. Furthermore, recent studies demonstrate that encouraging LLMs to "think" with more tokens during test-time inference can further significantly boost reasoning accuracy. Therefore, the train-time and test-time scaling combined to show a new research frontier -- a path toward Large Reasoning Model. The introduction of OpenAI's o1 series marks a significant milestone in this research direction. In this survey, we present a comprehensive review of recent progress in LLM reasoning. We begin by introducing the foundational background of LLMs and then explore the key technical components driving the development of large reasoning models, with a focus on automated data construction, learning-to-reason techniques, and test-time scaling. We also analyze popular open-source projects at building large reasoning models, and conclude with open challenges and future research directions.

[Arxiv](https://arxiv.org/abs/2501.09686)