# LLM助力代码审查流程的再思考：实证研究

发布时间：2025年05月22日

`LLM应用` `软件开发` `人工智能`

> Rethinking Code Review Workflows with LLM Assistance: An Empirical Study

# 摘要

> 代码审查是现代软件开发中不可或缺但耗时的部分，面对日益复杂的系统和更快交付的需求，这一环节正面临严峻挑战。本文以WirelessCar Sweden AB公司的研究为例，结合对现有代码审查实践的探索性研究，以及两种版本的LLM辅助代码审查工具的现场实验，深入探讨了这一问题。研究发现，传统代码审查存在频繁上下文切换和信息不足等痛点，同时揭示了LLM技术的应用潜力与风险——例如，复杂拉取请求的自动摘要虽便利，但误报和信任问题仍需解决。实验中，我们开发了两种原型工具：一种在审查初期提供AI生成的评论，另一种支持按需交互式审查。两者均采用基于检索增强生成的语义搜索技术，为审查提供相关上下文信息，有效缓解了上述挑战。实际应用中，开发人员更倾向于AI主导的审查方式，但其效果仍受审查者对代码熟悉程度及拉取请求严重性的影响。

> Code reviews are a critical yet time-consuming aspect of modern software development, increasingly challenged by growing system complexity and the demand for faster delivery. This paper presents a study conducted at WirelessCar Sweden AB, combining an exploratory field study of current code review practices with a field experiment involving two variations of an LLM-assisted code review tool. The field study identifies key challenges in traditional code reviews, including frequent context switching, insufficient contextual information, and highlights both opportunities (e.g., automatic summarization of complex pull requests) and concerns (e.g., false positives and trust issues) in using LLMs. In the field experiment, we developed two prototype variations: one offering LLM-generated reviews upfront and the other enabling on-demand interaction. Both utilize a semantic search pipeline based on retrieval-augmented generation to assemble relevant contextual information for the review, thereby tackling the uncovered challenges. Developers evaluated both variations in real-world settings: AI-led reviews are overall more preferred, while still being conditional on the reviewers' familiarity with the code base, as well as on the severity of the pull request.

[Arxiv](https://arxiv.org/abs/2505.16339)