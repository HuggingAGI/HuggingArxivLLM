# RACE-Align: 增强检索与强化链式思维的大型语言模型偏好对齐方法研究

发布时间：2025年06月03日

`LLM应用` `中医药`

> RACE-Align: Retrieval-Augmented and Chain-of-Thought Enhanced Preference Alignment for Large Language Models

# 摘要

> 大型语言模型（LLMs）在垂直领域面临着准确性、领域特定推理和可解释性方面的挑战。传统偏好对齐方法如基于人类反馈的强化学习（RLHF）和直接偏好优化（DPO）往往忽视了知识来源和推理逻辑。本文提出了一种名为RACE-Align（检索增强和链式推理增强对齐）的新型框架，旨在解决这些局限性。RACE-Align通过系统性地构建包含外部知识支持和显式链式推理（CoT）的二元偏好数据集，并结合DPO算法对LLMs进行对齐。其核心创新在于偏好数据构建策略：通过AI驱动的检索实现事实基础的增强，提升知识性和准确性，并强调领域特定链式推理的优化，将推理过程本身视为关键偏好维度。通过多阶段、AI驱动的精炼管道以较低成本生成这些偏好对。实验以中医药领域为对象，使用Qwen3-1.7B作为基础模型，结果显示RACE-Align显著优于原始基础模型和仅使用监督微调（SFT）微调的模型。在答案准确性、信息丰富性、中医药思维模式应用、推理的逻辑性和深度以及可解释性等多个维度均观察到显著改进。这些发现表明，RACE-Align为增强LLMs在复杂垂直领域中的知识应用能力、推理可靠性和过程透明性提供了一种有效途径。

> Large Language Models (LLMs) struggle with accuracy, domain-specific reasoning, and interpretability in vertical domains. Traditional preference alignment methods like Reinforcement Learning from Human Feedback (RLHF) and Direct Preference Optimization (DPO) often overlook the underlying knowledge sources and reasoning logic. This paper introduces RACE-Align (Retrieval-Augmented and Chain-of-Thought Enhanced Alignment), a novel framework designed to address these limitations. RACE-Align systematically constructs a binary preference dataset incorporating external knowledge support and explicit Chain-of-Thought (CoT) reasoning, then aligns LLMs using the DPO algorithm. The core innovation lies in its preference data construction strategy: it integrates AI-driven retrieval for factual grounding, enhancing knowledgeability and accuracy, and emphasizes the optimization of domain-specific CoT, treating the reasoning process itself as a key preference dimension. A multi-stage, AI-driven refinement pipeline cost-effectively generates these preference pairs. Experimental validation in Traditional Chinese Medicine (TCM) using Qwen3-1.7B as the base model demonstrates that RACE-Align significantly outperforms the original base model and a model fine-tuned only with Supervised Fine-Tuning (SFT). Improvements were observed across multiple dimensions, including answer accuracy, information richness, application of TCM thinking patterns, logicality and depth of reasoning, and interpretability. These findings suggest RACE-Align offers an effective pathway to enhance LLMs' knowledge application, reasoning reliability, and process transparency in complex vertical domains.

[Arxiv](https://arxiv.org/abs/2506.02726)