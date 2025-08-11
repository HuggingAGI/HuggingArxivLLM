# UR$^2$: 通过强化学习，统一 RAG 与推理：UR²

发布时间：2025年08月08日

`LLM理论

理由：这篇论文探讨了大语言模型（LLMs）中检索增强生成（RAG）和强化学习（RLVR）的整合，提出了一种新的框架UR2。研究重点在于理论层面的创新，旨在统一检索与推理，提升模型的泛化能力。因此，归类为LLM理论。` `人工智能`

> UR$^2$: Unify RAG and Reasoning through Reinforcement Learning

# 摘要

> 大语言模型（LLMs）通过两种互补的范式展现出了卓越的能力：检索增强生成（RAG）提升了知识基础，而基于可验证奖励的强化学习（RLVR）优化了复杂推理能力。然而，这两种能力通常在孤立的环境中开发，现有的统一尝试范围仍然较为狭窄——通常局限于固定检索设置和特定任务假设的开放领域问答。这种缺乏整合的局面限制了泛化能力，并限制了RAG-RL方法在更广泛领域中的应用。为了解决这一问题，我们提出了UR2（统一的RAG与推理），一个通过强化学习统一检索与推理的一般性框架。UR2带来了两个关键贡献：一种难度感知的课程训练，仅针对具有挑战性的问题调用检索；以及一种结合领域特定的离线语料库与大语言模型生成摘要的混合知识访问策略。这些组件旨在实现检索与推理之间的动态协调，提升在多样化任务中的适应能力。在开放领域问答、MMLU-Pro、医学推理和数学推理任务上的实验表明，基于Qwen2.5-3/7B和LLaMA-3.1-8B构建的UR2显著优于现有的RAG和RL方法，在多个基准测试中，其性能可与GPT-4o-mini和GPT-4.1-mini相媲美。我们已在https://github.com/Tsinghua-dhy/UR2上开源了所有代码、模型和数据。

> Large Language Models (LLMs) have shown remarkable capabilities through two complementary paradigms: Retrieval-Augmented Generation (RAG), which enhances knowledge grounding, and Reinforcement Learning from Verifiable Rewards (RLVR), which optimizes complex reasoning abilities. However, these two capabilities are often developed in isolation, and existing efforts to unify them remain narrow in scope-typically limited to open-domain QA with fixed retrieval settings and task-specific assumptions. This lack of integration constrains generalization and limits the applicability of RAG-RL methods to broader domains. To bridge this gap, we propose UR2 (Unified RAG and Reasoning), a general framework that unifies retrieval and reasoning through reinforcement learning. UR2 introduces two key contributions: a difficulty-aware curriculum training that selectively invokes retrieval only for challenging problems, and a hybrid knowledge access strategy combining domain-specific offline corpora with LLM-generated summaries. These components are designed to enable dynamic coordination between retrieval and reasoning, improving adaptability across a diverse range of tasks. Experiments across open-domain QA, MMLU-Pro, medical, and mathematical reasoning tasks demonstrate that UR2 (built on Qwen2.5-3/7B and LLaMA-3.1-8B) significantly outperforms existing RAG and RL methods, achieving comparable performance to GPT-4o-mini and GPT-4.1-mini on several benchmarks. We have released all code, models, and data at https://github.com/Tsinghua-dhy/UR2.

[Arxiv](https://arxiv.org/abs/2508.06165)