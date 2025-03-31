# LLM驱动的实例建模

发布时间：2025年03月28日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在生成实例模型中的应用，具体是从Ecore元模型和自然语言规范中生成基于XMI的实例模型。论文中提出了一种两步走的策略来解决LLMs直接生成有效XMI模型的困难，并验证了该方法的可行性。因此，这篇论文属于LLM应用的范畴。` `基于模型的工程` `软件工程`

> LLM-enabled Instance Model Generation

# 摘要

> 在基于模型的工程领域中，模型是实现系统设计与分析的关键组件。传统上，这些模型的创建是一个需要深厚建模专业知识以及目标系统领域知识的繁琐手动过程。随着生成式人工智能的迅速发展，大型语言模型（LLMs）展现出自动进行模型生成的潜力。本研究探讨了利用LLMs生成实例模型的方法，重点关注从Ecore元模型和自然语言规范中生成基于XMI的实例模型。我们发现，当前的LLMs难以直接生成有效的XMI模型。为了解决这一问题，我们提出了一种两步走策略：首先，利用LLMs生成一个包含所有必要实例模型信息的简化结构化输出，即概念实例模型；然后，将这一中间表示编译为有效的XMI文件。概念实例模型不依赖于特定格式，可以通过不同的编译器转换为多种建模格式。我们使用包括GPT-4o、o1-preview以及Llama 3.1（8B和70B）在内的多个LLMs验证了该方法的可行性。实验结果表明，所提出的方法显著提升了LLMs在实例模型生成任务中的实用性。值得注意的是，在本框架下，开源小型模型Llama 3.1 70B的表现可与专有GPT模型相媲美。

> In the domain of model-based engineering, models are essential components that enable system design and analysis. Traditionally, the creation of these models has been a manual process requiring not only deep modeling expertise but also substantial domain knowledge of target systems. With the rapid advancement of generative artificial intelligence, large language models (LLMs) show potential for automating model generation. This work explores the generation of instance models using LLMs, focusing specifically on producing XMI-based instance models from Ecore metamodels and natural language specifications. We observe that current LLMs struggle to directly generate valid XMI models. To address this, we propose a two-step approach: first, using LLMs to produce a simplified structured output containing all necessary instance model information, namely a conceptual instance model, and then compiling this intermediate representation into a valid XMI file. The conceptual instance model is format-independent, allowing it to be transformed into various modeling formats via different compilers. The feasibility of the proposed method has been demonstrated using several LLMs, including GPT-4o, o1-preview, Llama 3.1 (8B and 70B). Results show that the proposed method significantly improves the usability of LLMs for instance model generation tasks. Notably, the smaller open-source model, Llama 3.1 70B, demonstrated performance comparable to proprietary GPT models within the proposed framework.

[Arxiv](https://arxiv.org/abs/2503.22587)