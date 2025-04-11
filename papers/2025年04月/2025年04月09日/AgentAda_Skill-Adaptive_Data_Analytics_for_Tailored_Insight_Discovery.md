# AgentAda: 技能自适应数据分析，助力定制化洞察发现

发布时间：2025年04月09日

`Agent` `数据分析` `数据科学`

> AgentAda: Skill-Adaptive Data Analytics for Tailored Insight Discovery

# 摘要

> 我们很高兴推出AgentAda——首个能够学习并运用新分析技能提取更专业见解的LLM驱动分析代理。与现有方法不同，AgentAda无需用户手动选择分析方法，而是能自动从技能库中识别并调用最适合的分析技能。该库集成了多种分析方法，包括聚类、预测建模以及BERT等NLP技术，让AgentAda能够灵活应对各种复杂分析任务。AgentAda的分析流程包含三大核心步骤：(I) 智能问题生成器，精准生成与用户目标和角色相关的问题；(II) 混合检索增强生成（RAG）技能匹配器，从技能库中挑选最优分析技能；(III) 自动代码生成器，根据技能文档生成可执行代码以提取关键模式。为评估AgentAda的表现，我们创建了涵盖多领域的精选笔记本基准测试KaggleBench。人工评估结果显示，AgentAda的分析见解更具深度，48.78%的评估者更倾向于其分析结果，远超无技能代理的27.67%。此外，我们还提出了一种将LLM作为评估者的自动化方法，该方法与人工评估高度一致，为大规模分析质量评估提供了新思路。

> We introduce AgentAda, the first LLM-powered analytics agent that can learn and use new analytics skills to extract more specialized insights. Unlike existing methods that require users to manually decide which data analytics method to apply, AgentAda automatically identifies the skill needed from a library of analytical skills to perform the analysis. This also allows AgentAda to use skills that existing LLMs cannot perform out of the box. The library covers a range of methods, including clustering, predictive modeling, and NLP techniques like BERT, which allow AgentAda to handle complex analytics tasks based on what the user needs. AgentAda's dataset-to-insight extraction strategy consists of three key steps: (I) a question generator to generate queries relevant to the user's goal and persona, (II) a hybrid Retrieval-Augmented Generation (RAG)-based skill matcher to choose the best data analytics skill from the skill library, and (III) a code generator that produces executable code based on the retrieved skill's documentation to extract key patterns. We also introduce KaggleBench, a benchmark of curated notebooks across diverse domains, to evaluate AgentAda's performance. We conducted a human evaluation demonstrating that AgentAda provides more insightful analytics than existing tools, with 48.78% of evaluators preferring its analyses, compared to 27.67% for the unskilled agent. We also propose a novel LLM-as-a-judge approach that we show is aligned with human evaluation as a way to automate insight quality evaluation at larger scale.

[Arxiv](https://arxiv.org/abs/2504.07421)