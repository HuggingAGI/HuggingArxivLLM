# LLMs 在无服务器架构组件生成中的应用：一项探索性实证研究

发布时间：2025年02月04日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLMs）来自动生成架构组件，特别是函数即服务（FaaS）架构组件。这属于LLM在实际应用中的使用，旨在通过LLM的能力来加速开发过程并提高代码生成的质量。因此，它应被归类为“LLM应用”。` `软件开发` `云计算`

> LLMs for Generation of Architectural Components: An Exploratory Empirical Study in the Serverless World

# 摘要

> # 摘要
近期，大型语言模型（LLMs）能力的飞速发展和广泛应用，推动了代码生成领域的重大进展。然而，目前的生成仅限于代码片段。我们的目标是更进一步，自动生成架构组件。这不仅将大幅缩短开发时间，还能让我们直接从设计决策跳转到部署，彻底跳过开发阶段。为此，我们探索了LLMs在生成函数即服务（FaaS，即无服务器函数）架构组件方面的能力。相比单体架构和微服务，FaaS的架构组件规模较小，更适合当前LLMs的生成能力。我们通过系统筛选开源无服务器仓库、屏蔽无服务器函数，并利用不同上下文信息的最先进LLMs来生成被屏蔽的函数。通过仓库中的现有测试评估正确性，并采用软件工程（SE）和自然语言处理（NLP）领域的指标，分别评估代码质量以及人类与LLM生成代码的相似度。除了研究结果，我们还探讨了生成式AI在架构组件生成中的未来发展方向。

> Recently, the exponential growth in capability and pervasiveness of Large Language Models (LLMs) has led to significant work done in the field of code generation. However, this generation has been limited to code snippets. Going one step further, our desideratum is to automatically generate architectural components. This would not only speed up development time, but would also enable us to eventually completely skip the development phase, moving directly from design decisions to deployment. To this end, we conduct an exploratory study on the capability of LLMs to generate architectural components for Functions as a Service (FaaS), commonly known as serverless functions. The small size of their architectural components make this architectural style amenable for generation using current LLMs compared to other styles like monoliths and microservices. We perform the study by systematically selecting open source serverless repositories, masking a serverless function and utilizing state of the art LLMs provided with varying levels of context information about the overall system to generate the masked function. We evaluate correctness through existing tests present in the repositories and use metrics from the Software Engineering (SE) and Natural Language Processing (NLP) domains to evaluate code quality and the degree of similarity between human and LLM generated code respectively. Along with our findings, we also present a discussion on the path forward for using GenAI in architectural component generation.

[Arxiv](https://arxiv.org/abs/2502.02539)