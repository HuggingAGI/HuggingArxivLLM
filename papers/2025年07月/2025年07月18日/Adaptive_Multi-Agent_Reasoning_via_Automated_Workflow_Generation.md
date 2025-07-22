# 基于自动化工作流生成的自适应多智能体推理

发布时间：2025年07月18日

`Agent` `人工智能` `推理系统`

> Adaptive Multi-Agent Reasoning via Automated Workflow Generation

# 摘要

> 大型推理模型（LRMs）的崛起标志着语言模型能力的一次重大飞跃，旨在以空前的效率和准确性应对日益复杂的任务。然而，尽管这些模型表现出色，但近期研究揭示了它们的一个关键问题：在面对全新、未见过的问题时，这些模型往往无法有效泛化，转而依赖记忆中的解决方案，而非真正的推理能力。这种现象凸显了现代 LRMs 的一个重要缺陷，即过度拟合的倾向，导致其问题解决能力的泛化表现不尽如人意。  
    在本文中，我们推出了 Nexus Architect，这是我们多智能体系统框架 Nexus 的增强版。它配备了一种创新的自动化工作流合成机制。只需用户提供一个提示和一组具有代表性的示例，Architect 就能为特定问题类别量身定制推理工作流，通过智能选择策略、工具集成和对抗技术。此外，Architect 还搭载了迭代式提示优化机制，能够不断微调智能体的系统提示，从而最大化系统性能并显著提升泛化能力。  
    我们通过在一套定制的具有挑战性的逻辑问题数据集上，采用现成的非推理模型对 Nexus Architect 进行了实证评估，并将其性能与当前最先进的 LRMs 进行了对比。实验结果表明，Nexus Architect 表现优异，通过率较 Gemini 2.5 Flash Preview 提升高达 66%，较 Claude Sonnet 4 和 DeepSeek-R1 提升近 2.5 倍，较 Llama 4 Scout 提升超过 3 倍。

> The rise of Large Reasoning Models (LRMs) promises a significant leap forward in language model capabilities, aiming to tackle increasingly sophisticated tasks with unprecedented efficiency and accuracy. However, despite their impressive performance, recent studies have highlighted how current reasoning models frequently fail to generalize to novel, unseen problems, often resorting to memorized solutions rather than genuine inferential reasoning. Such behavior underscores a critical limitation in modern LRMs, i.e., their tendency toward overfitting, which in turn results in poor generalization in problem-solving capabilities.
  In this paper, we introduce Nexus Architect, an enhanced iteration of our multi-agent system framework, Nexus, equipped with a novel automated workflow synthesis mechanism. Given a user's prompt and a small set of representative examples, the Architect autonomously generates a tailored reasoning workflow by selecting suitable strategies, tool integrations, and adversarial techniques for a specific problem class. Furthermore, the Architect includes an iterative prompt refinement mechanism that fine-tunes agents' system prompts to maximize performance and improve the generalization capabilities of the system.
  We empirically evaluate Nexus Architect by employing an off-the-shelf, non-reasoning model on a custom dataset of challenging logical questions and compare its performance against state-of-the-art LRMs. Results show that Nexus Architect consistently outperforms existing solutions, achieving up to a 66% increase in pass rate over Gemini 2.5 Flash Preview, nearly 2.5$\times$ against Claude Sonnet 4 and DeepSeek-R1, and over 3$\times$ w.r.t. Llama 4 Scout.

[Arxiv](https://arxiv.org/abs/2507.14393)