# 面向表格数据问答的智能体大型语言模型

发布时间：2025年09月11日

`LLM应用` `基础理论`

> Agentic LLMs for Question Answering over Tabular Data

# 摘要

> 表格数据问答（Table QA）面临着现实世界表格在结构、规模和数据类型上的多样性带来的独特挑战。SemEval 2025任务8（DataBench）推出了一个包含大规模、跨领域数据集的基准，旨在评估模型准确回答结构化查询的能力。我们提出了一种自然语言转SQL（NL-to-SQL）方法，借助GPT-4o、GPT-4o-mini及DeepSeek v2:16b等大型语言模型（LLMs）动态生成SQL查询。该系统采用多阶段流程，涵盖示例选择、SQL查询生成、答案提取、验证及迭代优化环节。实验结果验证了该方法的有效性：在DataBench QA上准确率达70.5%，在DataBench Lite QA上达71.6%，显著超越了26%和27%的基线分数。本文详细阐述了所提方法、实验结果及替代方案，为LLM驱动的表格问答技术的优势与局限提供了深入见解。

> Question Answering over Tabular Data (Table QA) presents unique challenges due to the diverse structure, size, and data types of real-world tables. The SemEval 2025 Task 8 (DataBench) introduced a benchmark composed of large-scale, domain-diverse datasets to evaluate the ability of models to accurately answer structured queries. We propose a Natural Language to SQL (NL-to-SQL) approach leveraging large language models (LLMs) such as GPT-4o, GPT-4o-mini, and DeepSeek v2:16b to generate SQL queries dynamically. Our system follows a multi-stage pipeline involving example selection, SQL query generation, answer extraction, verification, and iterative refinement. Experiments demonstrate the effectiveness of our approach, achieving 70.5\% accuracy on DataBench QA and 71.6\% on DataBench Lite QA, significantly surpassing baseline scores of 26\% and 27\% respectively. This paper details our methodology, experimental results, and alternative approaches, providing insights into the strengths and limitations of LLM-driven Table QA.

[Arxiv](https://arxiv.org/abs/2509.09234)