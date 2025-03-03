# 利用两步检索增强的文本到SQL生成方法，从电子健康记录中构建患者队列

发布时间：2025年02月28日

`LLM应用` `健康数据`

> Generating patient cohorts from electronic health records using two-step retrieval-augmented text-to-SQL generation

# 摘要

> 临床队列定义对患者招募和观察性研究至关重要，但将入排标准转化为SQL查询仍具挑战且繁琐。我们提出了一种基于大型语言模型的自动化系统，该系统结合了标准解析、分层检索增强生成、医学概念标准化和SQL生成，利用患者漏斗检索患者队列。该系统在电子健康记录数据上的队列识别F1得分为0.75，能够有效捕获复杂的时序和逻辑关系。这些结果证明了自动化队列生成在流行病学研究中的可行性。

> Clinical cohort definition is crucial for patient recruitment and observational studies, yet translating inclusion/exclusion criteria into SQL queries remains challenging and manual. We present an automated system utilizing large language models that combines criteria parsing, two-level retrieval augmented generation with specialized knowledge bases, medical concept standardization, and SQL generation to retrieve patient cohorts with patient funnels. The system achieves 0.75 F1-score in cohort identification on EHR data, effectively capturing complex temporal and logical relationships. These results demonstrate the feasibility of automated cohort generation for epidemiological research.

[Arxiv](https://arxiv.org/abs/2502.21107)