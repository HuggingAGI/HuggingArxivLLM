# # 教LLM学会推理：从算法问题中进行无代码强化学习
教LLM学会推理：从算法问题中进行无代码强化学习
通过强化学习，让大型语言模型（LLM）无需代码即可掌握算法问题的推理能力。

发布时间：2025年07月14日

`LLM理论

理由：这篇论文提出了一种新的方法TeaR，通过数据整理和强化学习来提升大型语言模型的推理能力。研究的重点在于改进模型的推理机制，属于LLM理论层面的研究。` `人工智能`

> Teaching LLM to Reason: Reinforcement Learning from Algorithmic Problems without Code

# 摘要

> 提升推理能力一直是大型语言模型（LLM）研究领域的核心关注点。一个有前景的方向是通过逐步模拟代码执行来生成输出，然而，这种方法在简单情况下也容易陷入复杂数据结构和算法的泥潭，导致模型更关注算法模式而非核心推理结构。为了解决这一问题，我们提出了TeaR，旨在教会LLM更好地进行推理。TeaR通过精心整理数据和强化学习，引导模型通过与代码相关的任务发现最优推理路径，从而提升通用推理能力。我们使用两个基础模型和三个长CoT蒸馏模型进行了大量实验，模型参数规模从15亿到320亿不等，并在涵盖数学、知识、代码和逻辑推理的17个基准测试中进行评估。实验结果一致显示显著的性能提升。值得注意的是，TeaR在Qwen2.5-7B上实现了35.9%的性能提升，在R1-Distilled-7B上实现了5.9%的提升。

> Enhancing reasoning capabilities remains a central focus in the LLM reasearch community. A promising direction involves requiring models to simulate code execution step-by-step to derive outputs for given inputs. However, as code is often designed for large-scale systems, direct application leads to over-reliance on complex data structures and algorithms, even for simple cases, resulting in overfitting to algorithmic patterns rather than core reasoning structures. To address this, we propose TeaR, which aims at teaching LLMs to reason better. TeaR leverages careful data curation and reinforcement learning to guide models in discovering optimal reasoning paths through code-related tasks, thereby improving general reasoning abilities. We conduct extensive experiments using two base models and three long-CoT distillation models, with model sizes ranging from 1.5 billion to 32 billion parameters, and across 17 benchmarks spanning Math, Knowledge, Code, and Logical Reasoning. The results consistently show significant performance improvements. Notably, TeaR achieves a 35.9% improvement on Qwen2.5-7B and 5.9% on R1-Distilled-7B.

[Arxiv](https://arxiv.org/abs/2507.07498)