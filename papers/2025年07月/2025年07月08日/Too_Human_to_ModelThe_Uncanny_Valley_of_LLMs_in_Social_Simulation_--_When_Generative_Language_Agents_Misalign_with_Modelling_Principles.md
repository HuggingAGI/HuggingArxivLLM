# 过于人性化的LLMs难以建模：大型语言模型在社会模拟中的“恐怖谷”现象——生成式语言智能体与建模原则的冲突

发布时间：2025年07月08日

`LLM应用` `社交模拟` `智能体`

> Too Human to Model:The Uncanny Valley of LLMs in Social Simulation -- When Generative Language Agents Misalign with Modelling Principles

# 摘要

> 大型语言模型（LLMs）凭借其生成流利、上下文连贯对话的能力，正越来越多地被用于构建社交模拟中的智能体。这种能力虽然增强了模型的现实感，但也带来了一个重要悖论：当LLM智能体被误用时，它们的现实感可能会模糊而非阐明社会动态。我们主张，LLM智能体在许多方面过于“人性化”，难以进行建模：它们过于表达、详细且难以处理，与建模通常要求的抽象性、简化性和可解释性不符。通过将Bass扩散模型转换为基于LLM的变体，我们揭示了五个核心困境：自然对话与抽象时间步骤之间的时间分辨率不匹配；在对话中进行干预以避免破坏智能体自发输出的需求；在提示中引入规则式指令以保持对话自然性的诱惑；角色一致性与角色随时间演变之间的张力；以及理解涌现性——系统级模式被冗长的微观文本输出所掩盖的挑战。这些困境将LLM智能体推向了一个“恐怖谷”：它们既不够抽象以阐明潜在的社会机制，又不够自然以代表现实的人类行为。我们探讨了LLM智能体最理想的适用条件：当系统级涌现不是关注焦点，语言细微差别和意义是核心，交互在自然时间中展开，稳定的角色身份比长期行为演变更重要时。我们呼吁在未来应用中重新定位LLM智能体在社交模拟生态系统中的位置。

> Large language models (LLMs) have been increasingly used to build agents in social simulation because of their impressive abilities to generate fluent, contextually coherent dialogues. Such abilities can enhance the realism of models. However, the pursuit of realism is not necessarily compatible with the epistemic foundation of modelling. We argue that LLM agents, in many regards, are too human to model: they are too expressive, detailed and intractable to be consistent with the abstraction, simplification, and interpretability typically demanded by modelling. Through a model-building thought experiment that converts the Bass diffusion model to an LLM-based variant, we uncover five core dilemmas: a temporal resolution mismatch between natural conversation and abstract time steps; the need for intervention in conversations while avoiding undermining spontaneous agent outputs; the temptation to introduce rule-like instructions in prompts while maintaining conversational naturalness; the tension between role consistency and role evolution across time; and the challenge of understanding emergence, where system-level patterns become obscured by verbose micro textual outputs. These dilemmas steer the LLM agents towards an uncanny valley: not abstract enough to clarify underlying social mechanisms, while not natural enough to represent realistic human behaviour. This exposes an important paradox: the realism of LLM agents can obscure, rather than clarify, social dynamics when misapplied. We tease out the conditions in which LLM agents are ideally suited: where system-level emergence is not the focus, linguistic nuances and meaning are central, interactions unfold in natural time, and stable role identity is more important than long-term behavioural evolution. We call for repositioning LLM agents in the ecosystem of social simulation for future applications.

[Arxiv](https://arxiv.org/abs/2507.06310)