# MIND方法用于推理：上下文演绎推理中的元学习方法

发布时间：2025年05月20日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的推理能力，特别是如何通过元学习方法提升模型的泛化能力。研究重点在于提出一种创新的微调方法（MIND），以优化模型在推理任务中的表现，这涉及模型的训练方法和优化策略，属于LLM的理论研究。` `元学习`

> A MIND for Reasoning: Meta-learning for In-context Deduction

# 摘要

> 随着大型语言模型（LLMs）在正式任务上的广泛应用，推理能力已成为衡量技术水平的关键指标。然而，模型在处理分布外问题时的泛化能力仍存在局限。本文聚焦于LLMs如何系统性掌握演绎规则，特别是从知识库中精准筛选用于推导假设的前提子集这一任务。为突破这一技术瓶颈，我们提出了一种创新的少样本元学习微调方法——基于上下文演绎的元学习（MIND）。该方法旨在提升模型对未见过知识库的适应能力，并实现推理规则的系统化应用。实验结果表明，MIND显著增强了参数规模从1.5B到7B的小型LLMs的泛化性能，尤其在小型模型和数据量有限的场景下表现尤为突出。令人惊喜的是，经过MIND微调的小型模型在该任务上的表现甚至超越了GPT-4o和o3-mini等先进LLMs。

> Large language models (LLMs) are increasingly evaluated on formal tasks, where strong reasoning abilities define the state of the art. However, their ability to generalize to out-of-distribution problems remains limited. In this paper, we investigate how LLMs can achieve a systematic understanding of deductive rules. Our focus is on the task of identifying the appropriate subset of premises within a knowledge base needed to derive a given hypothesis. To tackle this challenge, we propose Meta-learning for In-context Deduction (MIND), a novel few-shot meta-learning fine-tuning approach. The goal of MIND is to enable models to generalize more effectively to unseen knowledge bases and to systematically apply inference rules. Our results show that MIND significantly improves generalization in small LMs ranging from 1.5B to 7B parameters. The benefits are especially pronounced in smaller models and low-data settings. Remarkably, small models fine-tuned with MIND outperform state-of-the-art LLMs, such as GPT-4o and o3-mini, on this task.

[Arxiv](https://arxiv.org/abs/2505.14313)