# ClickSight：利用LLMs解析学生行为，洞察学习策略的奥秘
# 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现。

发布时间：2025年05月21日

`LLM应用` `数据分析`

> ClickSight: Interpreting Student Clickstreams to Reveal Insights on Learning Strategies via LLMs

# 摘要

> 数字学习环境中的Clickstream数据为解析学生学习行为提供了独特视角，但其高维度和细粒度特性使其解读充满挑战。传统方法主要依赖手工特征提取、专家标注、聚类或监督模型，往往难以兼顾泛化性和可扩展性。为此，我们开发了ClickSight——一个基于大语言模型（LLM）的上下文解读管道，旨在从Clickstream数据中揭示学生学习策略。该工具接收原始Clickstream数据及学习策略列表作为输入，输出学生在学习过程中的行为解释。我们对比了四种不同的提示策略，并分析了自我优化对解释质量的影响。实验覆盖了两个开放学习环境，并采用基于评分标准的专家评估。结果显示，LLMs能够合理解释Clickstream数据中的学习策略，但解释质量因提示策略而异，自我优化对提升质量作用有限。ClickSight的成功应用，展现了LLMs在从教育交互数据中挖掘理论驱动见解方面的潜力。


> Clickstream data from digital learning environments offer valuable insights into students' learning behaviors, but are challenging to interpret due to their high dimensionality and granularity. Prior approaches have relied mainly on handcrafted features, expert labeling, clustering, or supervised models, therefore often lacking generalizability and scalability. In this work, we introduce ClickSight, an in-context Large Language Model (LLM)-based pipeline that interprets student clickstreams to reveal their learning strategies. ClickSight takes raw clickstreams and a list of learning strategies as input and generates textual interpretations of students' behaviors during interaction. We evaluate four different prompting strategies and investigate the impact of self-refinement on interpretation quality. Our evaluation spans two open-ended learning environments and uses a rubric-based domain-expert evaluation. Results show that while LLMs can reasonably interpret learning strategies from clickstreams, interpretation quality varies by prompting strategy, and self-refinement offers limited improvement. ClickSight demonstrates the potential of LLMs to generate theory-driven insights from educational interaction data.

[Arxiv](https://arxiv.org/abs/2505.15410)