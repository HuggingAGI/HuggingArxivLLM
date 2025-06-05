# SuperWriter：利用大型语言模型实现反思驱动的长文本生成

发布时间：2025年06月04日

`LLM应用` `内容生成`

> SuperWriter: Reflection-Driven Long-Form Generation with Large Language Models

# 摘要

> 长文本生成是大型语言模型（LLMs）面临的一个重大挑战，尤其在保持连贯性、确保逻辑一致性以及维持文本质量方面。为了解决这些问题，我们提出了SuperWriter-Agent，一个基于代理的框架，旨在提升长文本生成的质量和一致性。该框架通过在生成过程中引入规划和精炼阶段，引导模型遵循一种更加深思熟虑且以认知为基础的生成流程，类似于专业作家的创作方式。基于此框架，我们构建了一个监督微调数据集，用于训练一个70亿参数的SuperWriter-LM。我们还开发了一种分层直接偏好优化（DPO）流程，利用蒙特卡洛树搜索（MCTS）将最终质量评估传递到每一步生成，并优化每个生成步骤。在多种基准测试中的实证结果表明，SuperWriter-LM达到了最先进的性能水平，甚至在自动评估和人工评估中超越了更大规模的基线模型。此外，全面的消融研究验证了分层DPO的有效性，并强调了在长文本生成中融入结构化思维步骤的价值。

> Long-form text generation remains a significant challenge for large language models (LLMs), particularly in maintaining coherence, ensuring logical consistency, and preserving text quality as sequence length increases. To address these limitations, we propose SuperWriter-Agent, an agent-based framework designed to enhance the quality and consistency of long-form text generation. SuperWriter-Agent introduces explicit structured thinking-through planning and refinement stages into the generation pipeline, guiding the model to follow a more deliberate and cognitively grounded process akin to that of a professional writer. Based on this framework, we construct a supervised fine-tuning dataset to train a 7B SuperWriter-LM. We further develop a hierarchical Direct Preference Optimization (DPO) procedure that uses Monte Carlo Tree Search (MCTS) to propagate final quality assessments and optimize each generation step accordingly. Empirical results across diverse benchmarks demonstrate that SuperWriter-LM achieves state-of-the-art performance, surpassing even larger-scale baseline models in both automatic evaluation and human evaluation. Furthermore, comprehensive ablation studies demonstrate the effectiveness of hierarchical DPO and underscore the value of incorporating structured thinking steps to improve the quality of long-form text generation.

[Arxiv](https://arxiv.org/abs/2506.04180)