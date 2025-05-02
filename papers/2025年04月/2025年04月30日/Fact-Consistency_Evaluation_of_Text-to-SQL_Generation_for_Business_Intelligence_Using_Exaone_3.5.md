# 基于 Exaone 3.5 的商务智能文本转 SQL 生成的事实一致性评估

发布时间：2025年04月30日

`LLM应用` `商业智能` `数据分析`

> Fact-Consistency Evaluation of Text-to-SQL Generation for Business Intelligence Using Exaone 3.5

# 摘要

> 大型语言模型（LLMs）在通过文本到SQL生成实现结构化数据查询的自然语言接口方面展现出潜力，但其在现实世界商业智能（BI）环境中的应用仍受限于语义幻觉、结构错误及缺乏领域特定评估框架。本研究提出了一种事实一致性评估框架，采用针对企业任务优化的指令微调双语LLM——Exaone 3.5，评估LLM生成SQL输出的语义准确性。我们构建了一个包含219个自然语言商业问题的领域特定基准测试集，这些问题基于LG电子内部BigQuery环境的销售数据，涵盖五个SQL复杂度级别。每个问题均配有一个黄金标准SQL查询和一个经过验证的地面真实答案。我们通过答案准确性、执行成功率、语义错误率和无响应率评估模型性能。实验结果显示，Exaone 3.5在简单聚合任务（L1级准确率为93%）上表现良好，但在算术推理（H1级准确率为4%）和分组排名任务（H4级准确率为31%）上表现明显下降，语义错误和无响应集中在复杂案例中。定性错误分析识别出常见失败类型，包括误用算术逻辑、过滤不完整和分组操作错误。我们的研究发现凸显了LLMs在关键业务环境中的局限性，并强调了事实一致性验证层和混合推理方法的必要性。这项工作为推进可靠的自然语言接口到结构化企业数据系统提供了一个可复现的基准和评估方法论。

> Large Language Models (LLMs) have shown promise in enabling natural language interfaces for structured data querying through text-to-SQL generation. However, their application in real-world Business Intelligence (BI) contexts remains limited due to semantic hallucinations, structural errors, and a lack of domain-specific evaluation frameworks. In this study, we propose a Fact-Consistency Evaluation Framework for assessing the semantic accuracy of LLM-generated SQL outputs using Exaone 3.5--an instruction-tuned, bilingual LLM optimized for enterprise tasks. We construct a domain-specific benchmark comprising 219 natural language business questions across five SQL complexity levels, derived from actual sales data in LG Electronics' internal BigQuery environment. Each question is paired with a gold-standard SQL query and a validated ground-truth answer. We evaluate model performance using answer accuracy, execution success rate, semantic error rate, and non-response rate. Experimental results show that while Exaone 3.5 performs well on simple aggregation tasks (93% accuracy in L1), it exhibits substantial degradation in arithmetic reasoning (4% accuracy in H1) and grouped ranking tasks (31% in H4), with semantic errors and non-responses concentrated in complex cases. Qualitative error analysis further identifies common failure types such as misapplied arithmetic logic, incomplete filtering, and incorrect grouping operations. Our findings highlight the current limitations of LLMs in business-critical environments and underscore the need for fact-consistency validation layers and hybrid reasoning approaches. This work contributes a reproducible benchmark and evaluation methodology for advancing reliable natural language interfaces to structured enterprise data systems.

[Arxiv](https://arxiv.org/abs/2505.00060)