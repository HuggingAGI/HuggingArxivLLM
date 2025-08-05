# # 问对问题：评估大型语言模型在临床咨询模板开发中的表现
大型语言模型在临床咨询中的应用展现出巨大潜力，但如何有效评估其生成咨询模板的能力，仍然是一个关键问题。

发布时间：2025年08月01日

`LLM应用` `医疗信息化`

> Asking the Right Questions: Benchmarking Large Language Models in the Development of Clinical Consultation Templates

# 摘要

> 本研究评估了大型语言模型 (LLMs) 在生成用于电子化临床咨询的结构化临床咨询模板方面的表现。通过使用斯坦福大学 eConsult 团队开发并日常使用的 145 个专家级模板，我们评估了包括 o3、GPT-4o、Kimi K2、Claude 4 Sonnet、Llama 3 70B 和 Gemini 2.5 Pro 在内的前沿模型，考察它们生成临床连贯、简洁且重点突出的临床问题框架的能力。通过结合提示优化、语义自动评分和重点分析的多智能体管道，我们发现尽管像 o3 这样的模型能够实现高达 92.2% 的全面性，但它们生成的模板往往过于冗长，并且在长度限制下无法正确优先考虑最重要的临床问题。不同专业领域表现差异显著，以叙事驱动的领域如精神病学和疼痛医学表现明显下降。我们的研究结果表明，LLMs 可以有效提升医生之间的结构化临床信息交流，同时强调需要更强大的评估方法，以捕捉模型在现实世界医生沟通的时间限制内优先考虑临床相关重要信息的能力。

> This study evaluates the capacity of large language models (LLMs) to generate structured clinical consultation templates for electronic consultation. Using 145 expert-crafted templates developed and routinely used by Stanford's eConsult team, we assess frontier models -- including o3, GPT-4o, Kimi K2, Claude 4 Sonnet, Llama 3 70B, and Gemini 2.5 Pro -- for their ability to produce clinically coherent, concise, and prioritized clinical question schemas. Through a multi-agent pipeline combining prompt optimization, semantic autograding, and prioritization analysis, we show that while models like o3 achieve high comprehensiveness (up to 92.2\%), they consistently generate excessively long templates and fail to correctly prioritize the most clinically important questions under length constraints. Performance varies across specialties, with significant degradation in narrative-driven fields such as psychiatry and pain medicine. Our findings demonstrate that LLMs can enhance structured clinical information exchange between physicians, while highlighting the need for more robust evaluation methods that capture a model's ability to prioritize clinically salient information within the time constraints of real-world physician communication.

[Arxiv](https://arxiv.org/abs/2508.01159)