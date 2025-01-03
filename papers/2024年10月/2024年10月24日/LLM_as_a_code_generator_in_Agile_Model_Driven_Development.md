# LLM 在敏捷模型驱动开发中担任代码生成器的角色

发布时间：2024年10月24日

`LLM应用

理由：这篇论文主要讨论了如何利用GPT4等大型语言模型（LLM）在代码自动生成中的应用，特别是通过模型驱动开发（MDD）策略来克服软件自然语言描述中的模糊性问题。论文还展示了如何通过集成OCL和FIPA本体语言来减少模型的模糊性，并生成与JADE和PADE框架兼容的代码。这些内容都属于LLM在实际应用中的具体实现和优化，因此分类为“LLM应用”。` `软件工程` `无人驾驶`

> LLM as a code generator in Agile Model Driven Development

# 摘要

> # 摘要
GPT4 等大型语言模型（LLM）在代码自动生成中的应用取得了显著进展，但也面临挑战。软件自然语言描述中的模糊性对生成可部署的结构化代码构成了障碍。本研究提出了一种基于 GPT4 的敏捷模型驱动开发（AMDD）方法，通过模型驱动开发（MDD）策略克服这些挑战。该方法不仅提升了代码自动生成的灵活性和可扩展性，还能无缝适应模型或部署环境的变化。我们以多智能体无人车舰队（UVF）系统为例，使用 UML 进行建模，并通过集成 OCL 和 FIPA 本体语言分别进行代码结构和通信语义的元建模，显著减少了模型的模糊性。利用 GPT4 的自动生成能力，我们生成了与 JADE 和 PADE 框架兼容的 Java 和 Python 代码。通过对生成代码的全面评估，我们验证了其与预期行为的一致性，并改进了智能体交互。结构上，我们比较了仅受 OCL 元模型约束的代码与同时受 OCL 和 FIPA 本体元模型约束的代码的复杂性。结果显示，受本体约束的元模型生成的代码虽然更复杂，但其圈复杂度仍处于可控范围内，表明可以引入更多元模型约束而不会显著增加复杂性风险。

> Leveraging Large Language Models (LLM) like GPT4 in the auto generation of code represents a significant advancement, yet it is not without its challenges. The ambiguity inherent in natural language descriptions of software poses substantial obstacles to generating deployable, structured artifacts. This research champions Model Driven Development (MDD) as a viable strategy to overcome these challenges, proposing an Agile Model Driven Development (AMDD) approach that employs GPT4 as a code generator. This approach enhances the flexibility and scalability of the code auto generation process and offers agility that allows seamless adaptation to changes in models or deployment environments. We illustrate this by modeling a multi agent Unmanned Vehicle Fleet (UVF) system using the Unified Modeling Language (UML), significantly reducing model ambiguity by integrating the Object Constraint Language (OCL) for code structure meta modeling, and the FIPA ontology language for communication semantics meta modeling. Applying GPT4 auto generation capabilities yields Java and Python code that is compatible with the JADE and PADE frameworks, respectively. Our thorough evaluation of the auto generated code verifies its alignment with expected behaviors and identifies enhancements in agent interactions. Structurally, we assessed the complexity of code derived from a model constrained solely by OCL meta models, against that influenced by both OCL and FIPA ontology meta models. The results indicate that the ontology constrained meta model produces inherently more complex code, yet its cyclomatic complexity remains within manageable levels, suggesting that additional meta model constraints can be incorporated without exceeding the high risk threshold for complexity.

[Arxiv](https://arxiv.org/abs/2410.18489)