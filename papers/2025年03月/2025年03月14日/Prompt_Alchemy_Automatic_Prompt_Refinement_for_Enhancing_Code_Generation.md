# 自动提示优化：提升代码生成的炼金术

发布时间：2025年03月14日

`LLM应用` `软件开发` `代码生成`

> Prompt Alchemy: Automatic Prompt Refinement for Enhancing Code Generation

# 摘要

> 代码生成是通过将高层描述转化为可执行代码来实现软件开发自动化的关键任务。大型语言模型（LLMs）在这一领域表现出色，但其性能高度依赖于输入提示的质量。由于手动提示工程耗时且结果不稳定，限制了LLMs的实际效果。本文介绍的Prochemy是一种创新的自动优化提示方法，旨在提升代码生成能力。Prochemy通过自动化优化、保持推理一致性以及支持多智能体系统，克服了手动提示的局限性。它根据模型性能迭代优化提示，并使用最终优化后的提示以提升任务的一致性。我们在基于自然语言的代码生成和翻译任务中，使用三个LLM系列对Prochemy进行了测试。实验结果表明，与零-shot基准相比，Prochemy在HumanEval上的表现优于现有方法，GPT-3.5-Turbo提升了5.0%，GPT-4o提升了1.9%。在先进的LDB框架中，Prochemy + LDB比单独使用的方法高出1.2-1.8%。在代码翻译任务中，Prochemy将GPT-4o的Java到Python（AVATAR）性能从74.5提升至84.1（+12.9%），Python到Java的性能从66.8提升至78.2（+17.1%）。此外，Prochemy与o1-mini模型结合使用时仍保持强劲性能，证明了其在代码任务中的有效性。作为即插即用的解决方案，Prochemy只需少量人工干预即可优化提示，成功弥合了简单提示与复杂框架之间的差距。

> Code generation has emerged as a key task to automate software development by converting high-level descriptions into executable code. Large language models (LLMs) excel at this but depend heavily on input prompt quality.Manual prompt engineering can be time-consuming and inconsistent, limiting LLM effectiveness. This paper introduces Prochemy, an innovative method for automatically refining prompts to boost code generation. Prochemy overcomes manual prompt limitations by automating optimization, ensuring consistency during inference, and supporting multi-agent systems.It iteratively refines prompts based on model performance, using an optimized final prompt for improved consistency across tasks. We tested Prochemy on natural language-based code generation and translation tasks using three LLM series. Results indicate Prochemy enhances existing methods, improving performance by 5.0% for GPT-3.5-Turbo and 1.9% for GPT-4o over zero-shot baselines on HumanEval. In state-of-the-art LDB, Prochemy + LDB surpasses standalone methods by 1.2-1.8%. For code translation, Prochemy boosts GPT-4o's Java-to-Python (AVATAR) performance from 74.5 to 84.1 (+12.9%) and Python-to-Java from 66.8 to 78.2 (+17.1%). Moreover, Prochemy maintains strong performance when integrated with the o1-mini model, validating its efficacy in code tasks. Designed as plug-and-play, Prochemy optimizes prompts with minimal human input, bridging the gap between simple prompts and complex frameworks.

[Arxiv](https://arxiv.org/abs/2503.11085)