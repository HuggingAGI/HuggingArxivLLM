# 借助解决方案指导微调来提升小型语言模型的推理能力

发布时间：2024年12月13日

`LLM应用` `语言模型` `推理任务`

> Enhancing the Reasoning Capabilities of Small Language Models via Solution Guidance Fine-Tuning

# 摘要

> 大型语言模型（LLMs）在众多任务中展现出非凡的性能。提示工程与微调技术的进步，进一步提升了其应对复杂推理挑战的能力。然而，这些先进能力通常只存在于参数超 1000 亿的模型中。虽然针对较小模型（参数小于 100 亿）已探索了思维链（CoT）微调方法，但它们通常依赖大量的 CoT 训练数据，这可能引发不一致，并在低数据场景中限制效果。为突破这些局限，本文引入了一种新的推理策略——解决方案指导（SG）以及一种即插即用的训练范式——解决方案指导微调（SGFT），以增强小型语言模型的推理能力。SG 侧重于语义和逻辑层面的问题理解与分解，而非特定计算，能有效提升 SLMs 的泛化和推理能力。仅需少量 SG 训练数据，SGFT 就能微调 SLM 生成准确的问题解决指导，而后能灵活地将其作为提示提供给任何 SLM，使其直接生成正确答案。实验结果表明，我们的方法显著提升了 SLMs 在各类推理任务中的性能，在资源受限的环境中增强了其实用性和效率。

> Large language models (LLMs) have demonstrated remarkable performance across a wide range of tasks. Advances in prompt engineering and fine-tuning techniques have further enhanced their ability to address complex reasoning challenges. However, these advanced capabilities are often exclusive to models exceeding 100 billion parameters. Although Chain-of-Thought (CoT) fine-tuning methods have been explored for smaller models (under 10 billion parameters), they typically depend on extensive CoT training data, which can introduce inconsistencies and limit effectiveness in low-data settings. To overcome these limitations, this paper introduce a new reasoning strategy Solution Guidance (SG) and a plug-and-play training paradigm Solution-Guidance Fine-Tuning (SGFT) for enhancing the reasoning capabilities of small language models. SG focuses on problem understanding and decomposition at the semantic and logical levels, rather than specific computations, which can effectively improve the SLMs' generalization and reasoning abilities. With only a small amount of SG training data, SGFT can fine-tune a SLM to produce accurate problem-solving guidances, which can then be flexibly fed to any SLM as prompts, enabling it to generate correct answers directly. Experimental results demonstrate that our method significantly improves the performance of SLMs on various reasoning tasks, enhancing both their practicality and efficiency within resource-constrained environments.

[Arxiv](https://arxiv.org/abs/2412.09906)