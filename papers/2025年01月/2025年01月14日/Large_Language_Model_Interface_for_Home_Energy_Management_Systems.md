# 家庭能源管理系统的大型语言模型接口

发布时间：2025年01月14日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLM）来改进家庭能源管理系统（HEMS）的用户界面，使其能够更好地理解用户的需求并生成相应的参数。论文中提到了使用ReAct方法和少量提示来提升LLM的性能，并提出了利用另一个LLM模拟用户的方法来评估界面性能。这些内容都属于LLM在实际应用中的使用，因此将其分类为LLM应用。` `能源管理` `智能家居`

> Large Language Model Interface for Home Energy Management Systems

# 摘要

> # 家庭能源管理系统（HEMSs）帮助家庭根据电力系统信号（如能源价格）优化用电。这项技术不仅降低了能源账单，还增强了需求侧灵活性，助力电力系统稳定。然而，缺乏技术背景的居民往往难以有效使用HEMSs，因为HEMSs需要精确的参数化，以反映能源资源、房屋和用户需求的特征。最近，大型语言模型（LLMs）在语言理解方面表现出色。受此启发，我们提出了一种基于LLM的界面，通过与用户互动，理解并参数化其“格式不良的答案”，进而输出格式良好的参数以实现HEMS。我们还采用了Reason and Act方法（ReAct）和少量提示来提升LLM的性能。为了评估界面性能，通常需要多次用户与LLM的互动。为了避免寻找志愿者用户的麻烦并缩短评估时间，我们提出了一种方法，利用另一个LLM模拟不同专业水平的用户，从专家到非技术人员。通过综合评估，基于LLM的HEMS界面实现了88%的平均参数检索准确率，优于未使用ReAct和/或少量提示的基准模型。

> Home Energy Management Systems (HEMSs) help households tailor their electricity usage based on power system signals such as energy prices. This technology helps to reduce energy bills and offers greater demand-side flexibility that supports the power system stability. However, residents who lack a technical background may find it difficult to use HEMSs effectively, because HEMSs require well-formatted parameterization that reflects the characteristics of the energy resources, houses, and users' needs. Recently, Large-Language Models (LLMs) have demonstrated an outstanding ability in language understanding. Motivated by this, we propose an LLM-based interface that interacts with users to understand and parameterize their ``badly-formatted answers'', and then outputs well-formatted parameters to implement an HEMS. We further use Reason and Act method (ReAct) and few-shot prompting to enhance the LLM performance. Evaluating the interface performance requires multiple user--LLM interactions. To avoid the efforts in finding volunteer users and reduce the evaluation time, we additionally propose a method that uses another LLM to simulate users with varying expertise, ranging from knowledgeable to non-technical. By comprehensive evaluation, the proposed LLM-based HEMS interface achieves an average parameter retrieval accuracy of 88\%, outperforming benchmark models without ReAct and/or few-shot prompting.

[Arxiv](https://arxiv.org/abs/2501.07919)