# 难度感知的分阶段强化学习助力提升大语言模型推理能力：初步实验研究

发布时间：2025年04月01日

`LLM理论

摘要讨论了如何通过改进强化学习策略来提升大型语言模型的推理能力，属于理论层面的研究。` `人工智能`

> How Difficulty-Aware Staged Reinforcement Learning Enhances LLMs' Reasoning Capabilities: A Preliminary Experimental Study

# 摘要

> 提升大型语言模型（LLMs）的推理能力在效率和扩展性方面仍然是人工智能研究中的基本挑战。本文通过深入的实验研究，探讨了如何利用难度意识的分阶段强化学习（RL）策略显著提升LLM推理性能。我们发现，根据明确的难度级别战略性选择训练数据，可以显著优化RL过程。此外，我们引入了一种分阶段训练方法，逐步将模型暴露于更具挑战性的任务中，从而进一步增强推理能力。同时在数学推理和代码生成任务上训练模型，能够带来显著的跨领域收益。值得注意的是，我们提出的方法使一个15亿参数规模的模型在AIME-2024基准上达到了42.3%的准确率，在MATH-500基准上达到了89.5%的准确率。这些结果凸显了我们的方法在提升LLM推理能力方面的有效性。我们将在GitHub和Hugging Face上开源我们的数据集。

> Enhancing the reasoning capabilities of Large Language Models (LLMs) with efficiency and scalability remains a fundamental challenge in artificial intelligence research. This paper presents a rigorous experimental investigation into how difficulty-aware staged reinforcement learning (RL) strategies can substantially improve LLM reasoning performance. Through systematic analysis, we demonstrate that strategically selecting training data according to well-defined difficulty levels markedly enhances RL optimization. Moreover, we introduce a staged training methodology, progressively exposing models to increasingly challenging tasks, further amplifying reasoning capabilities. Our findings reveal significant cross-domain benefits when simultaneously training models on mathematical reasoning and code generation tasks. Notably, our proposed approach enables a 1.5B parameter model to achieve an accuracy of 42.3\% on the AIME-2024 benchmark, 89.5\% on the MATH-500 benchmark. These results underscore the efficacy of our method in advancing the reasoning proficiency of LLMs. We will open-source our datasets on GitHub and Hugging Face.

[Arxiv](https://arxiv.org/abs/2504.00829)