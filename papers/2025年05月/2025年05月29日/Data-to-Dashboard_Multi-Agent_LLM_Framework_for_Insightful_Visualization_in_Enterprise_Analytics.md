# 数据可视化：多智能体LLM框架实现企业分析中的深入数据可视化

发布时间：2025年05月29日

`Agent` `数据分析` `业务分析`

> Data-to-Dashboard: Multi-Agent LLM Framework for Insightful Visualization in Enterprise Analytics

# 摘要

> 大型语言模型（LLMs）的迅猛发展催生了多种智能体系统，应用于数据分析领域，通过利用LLMs的能力来提升洞察生成和可视化效果。本文提出了一种智能体系统，通过具备领域识别、概念提取、多角度分析生成和迭代自我反思能力的模块化LLM智能体，实现了从数据到仪表盘的自动化流程。与现有图表问答系统不同，我们的框架通过检索与领域相关的知识并适应多样化数据集，模拟了业务分析师的分析推理过程，而无需依赖封闭的本体或问题模板。我们在三个不同领域的数据集上对系统进行了评估。与基于GPT-4的单提示基线相比，我们的方法在洞察力、领域相关性和分析深度方面表现更优，这一结论通过定制评估指标和定性的人工评估得到了验证。这项研究为从原始数据到可视化的路径提供了一种新颖的模块化流水线，并为业务分析领域的专家提供了通过人机协同进行验证的新机遇。所有代码均可在此找到：https://github.com/77luvC/D2D_Data2Dashboard

> The rapid advancement of LLMs has led to the creation of diverse agentic systems in data analysis, utilizing LLMs' capabilities to improve insight generation and visualization. In this paper, we present an agentic system that automates the data-to-dashboard pipeline through modular LLM agents capable of domain detection, concept extraction, multi-perspective analysis generation, and iterative self-reflection. Unlike existing chart QA systems, our framework simulates the analytical reasoning process of business analysts by retrieving domain-relevant knowledge and adapting to diverse datasets without relying on closed ontologies or question templates.
  We evaluate our system on three datasets across different domains. Benchmarked against GPT-4o with a single-prompt baseline, our approach shows improved insightfulness, domain relevance, and analytical depth, as measured by tailored evaluation metrics and qualitative human assessment.
  This work contributes a novel modular pipeline to bridge the path from raw data to visualization, and opens new opportunities for human-in-the-loop validation by domain experts in business analytics. All code can be found here: https://github.com/77luvC/D2D_Data2Dashboard

[Arxiv](https://arxiv.org/abs/2505.23695)