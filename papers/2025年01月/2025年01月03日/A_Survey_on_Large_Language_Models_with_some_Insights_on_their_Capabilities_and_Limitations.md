# 大型语言模型综述：能力与局限性的深入探讨

发布时间：2025年01月03日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）的基础组件、扩展机制、架构策略以及它们在多样化任务中的泛化能力、规划和推理能力等理论问题。论文还特别关注了LLMs中的CoT（思维链）和PoT（思维计划）能力，以及预训练数据对其涌现的影响。这些内容都属于对LLMs的理论研究和分析，因此将其分类为“LLM理论”。` `人工智能`

> A Survey on Large Language Models with some Insights on their Capabilities and Limitations

# 摘要

> # 摘要
人工智能的迅猛发展，尤其是基于Transformer架构的大型语言模型（LLMs）的崛起，彻底改变了自然语言处理的能力。这些模型在文本生成、问答、翻译和摘要等语言任务中表现出色，甚至能与人类的理解力相媲美。更令人惊叹的是，LLMs还展现出超越其核心功能的涌现能力，如常识推理、代码生成和算术等。本文深入探讨了这些能力背后的基础组件、扩展机制和架构策略，重点分析了GPT和LLaMA等模型。我们研究了数据和计算资源的指数级增长对LLM性能的影响，并探讨了扩展带来的权衡。此外，我们还展示了LLM在医疗、金融、教育和法律等领域的广泛应用，凸显了其解决特定领域挑战的潜力。本文的核心问题在于：LLMs如何在多样化任务中泛化？它们如何展示规划和推理能力？这些涌现能力能否被系统性地激发或增强？我们特别关注了LLMs中的CoT（思维链）和PoT（思维计划）能力，探讨了预训练数据对其涌现的影响。同时，我们还研究了LLM-modulo框架，这些框架通过集成外部系统，使LLMs能够处理复杂、动态的任务。通过分析这些因素，本文旨在推动关于LLMs能力和局限性的讨论，促进其在复杂环境中的负责任开发与应用。

> The rapid advancement of artificial intelligence, particularly with the development of Large Language Models (LLMs) built on the transformer architecture, has redefined the capabilities of natural language processing. These models now exhibit remarkable performance across various language-related tasks, such as text generation, question answering, translation, and summarization, often rivaling human-like comprehension. More intriguingly, LLMs have demonstrated emergent abilities extending beyond their core functions, showing proficiency in tasks like commonsense reasoning, code generation, and arithmetic. This survey paper explores the foundational components, scaling mechanisms, and architectural strategies that drive these capabilities. Emphasizing models like GPT and LLaMA, we analyze the impact of exponential data and computational growth on LLM performance, while also addressing the trade-offs associated with scaling. We also examine LLM applications across sectors, such as healthcare, finance, education, and law, highlighting their adaptability and potential to solve domain-specific challenges. Central to this work are the questions of how LLMs generalize across diverse tasks, exhibit planning, and reasoning abilities, and whether these emergent abilities can be systematically elicited or enhanced. In particular, we provide some insights into the CoT (Chain of Thought) and PoT (Plan of Thought) abilities within LLMs, focusing on how pre-training data influences their emergence. Additionally, we investigate LLM-modulo frameworks that integrate external systems, allowing LLMs to handle complex, dynamic tasks. By analyzing these factors, this paper aims to foster the ongoing discussion on the capabilities and limits of LLMs, promoting their responsible development and application in novel and increasingly complex environments.

[Arxiv](https://arxiv.org/abs/2501.04040)