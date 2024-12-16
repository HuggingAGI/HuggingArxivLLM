# 论语言模型作为规划形式化工具的局限性

发布时间：2024年12月13日

`LLM应用` `语言模型`

> On the Limit of Language Models as Planning Formalizers

# 摘要

> 大型语言模型已被证实无法在实际环境中制定出可执行、可验证的计划。不过，新的研究成果显示，将LLM用作形式化工具，为规划领域生成正式表示（比如PDDL）是可行的，这样就能确定性地找到解决方案。我们在填补一些主要空缺的同时，对这种方法进行了系统性评估。此前的工作在给定模板化且不切实际的环境描述时，只能生成部分PDDL表示，而我们在给定各种自然程度的描述时，能够生成完整的表示。在一系列对提升LLM正式规划能力至关重要的观察中，我们发现足够大的模型能有效地将描述形式化为PDDL，其表现优于直接生成计划的模型，且对词汇干扰具有较强的稳定性。随着描述变得更自然，我们观察到性能有所下降，并提供了详细的错误分析。

> Large Language Models have been shown to fail to create executable and verifiable plans in grounded environments. An emerging line of work shows success in using LLM as a formalizer to generate a formal representation (e.g., PDDL) of the planning domain, which can be deterministically solved to find a plan. We systematically evaluate this methodology while bridging some major gaps. While previous work only generates a partial PDDL representation given templated and thus unrealistic environment descriptions, we generate the complete representation given descriptions of various naturalness levels. Among an array of observations critical to improve LLMs' formal planning ability, we note that large enough models can effectively formalize descriptions as PDDL, outperforming those directly generating plans, while being robust to lexical perturbation. As the descriptions become more natural-sounding, we observe a decrease in performance and provide detailed error analysis.

[Arxiv](https://arxiv.org/abs/2412.09879)