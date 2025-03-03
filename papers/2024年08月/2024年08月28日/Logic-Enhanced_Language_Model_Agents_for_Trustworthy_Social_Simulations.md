# 逻辑增强型语言模型代理，助力可信社会模拟

发布时间：2024年08月28日

`LLM应用` `人工智能` `社交模拟`

> Logic-Enhanced Language Model Agents for Trustworthy Social Simulations

# 摘要

> 我们推出了LELMA框架，旨在通过结合大型语言模型（LLM）与符号AI，提升社交模拟的可信度。尽管LLM在模拟人类行为方面颇受瞩目，但其应用受限于固有的幻觉和逻辑不一致问题。LELMA通过逻辑验证机制，不仅纠正了LLM的推理错误，还优化了输出。框架由三大核心组件构成：战略推理生成器LLM-Reasoner、自然语言至逻辑查询转换器LLM-Translator，以及逻辑查询评估器Solver。本研究以博弈论决策为例，探讨了LLM在复杂情境下的推理局限，特别是GPT-4 Omni和Gemini 1.0 Pro的表现。实验结果显示，LELMA在错误识别上精准高效，显著提升了LLM的推理质量，尤其是在GPT-4 Omni上取得了显著进步。

> We introduce the Logic-Enhanced Language Model Agents (LELMA) framework, a novel approach to enhance the trustworthiness of social simulations that utilize large language models (LLMs). While LLMs have gained attention as agents for simulating human behaviour, their applicability in this role is limited by issues such as inherent hallucinations and logical inconsistencies. LELMA addresses these challenges by integrating LLMs with symbolic AI, enabling logical verification of the reasoning generated by LLMs. This verification process provides corrective feedback, refining the reasoning output. The framework consists of three main components: an LLM-Reasoner for producing strategic reasoning, an LLM-Translator for mapping natural language reasoning to logic queries, and a Solver for evaluating these queries. This study focuses on decision-making in game-theoretic scenarios as a model of human interaction. Experiments involving the Hawk-Dove game, Prisoner's Dilemma, and Stag Hunt highlight the limitations of state-of-the-art LLMs, GPT-4 Omni and Gemini 1.0 Pro, in producing correct reasoning in these contexts. LELMA demonstrates high accuracy in error detection and improves the reasoning correctness of LLMs via self-refinement, particularly in GPT-4 Omni.

[Arxiv](https://arxiv.org/abs/2408.16081)