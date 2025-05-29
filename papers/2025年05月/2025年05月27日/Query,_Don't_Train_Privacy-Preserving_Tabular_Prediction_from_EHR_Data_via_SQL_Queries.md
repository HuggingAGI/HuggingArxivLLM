# 查询，而非训练——保护隐私的电子健康记录数据表格预测，通过SQL查询实现。

发布时间：2025年05月27日

`LLM应用` `隐私保护`

> Query, Don't Train: Privacy-Preserving Tabular Prediction from EHR Data via SQL Queries

# 摘要

> 电子健康记录 (EHRs) 包含丰富的结构化、纵向数据，对于预测建模至关重要。然而，严格的隐私法规（如 HIPAA、GDPR）通常限制了对个体级别记录的访问。我们介绍了一种名为 Query, Don't Train (QDT) 的方法，这是一种基于结构化数据的基础模型接口，通过 LLM 生成的 SQL 实现对 EHRs 的表格推理。与传统方法不同，QDT 不需要在个体级别示例上进行训练或直接访问数据，而是利用一个大型语言模型 (LLM) 作为了解模式的查询规划器，从自然语言任务描述和测试时输入生成符合隐私的 SQL 查询。通过这些 SQL 查询，模型提取汇总级别的总体统计数据，LLM 对结果进行链式推理以完成预测。这种方法具有四大优势：(1) 无需监督模型训练或直接数据访问，(2) 通过符号化、可审核的查询确保可解释性，(3) 自然处理缺失特征而无需插补或预处理，(4) 有效管理高维数值数据以增强分析能力。我们在 2 型糖尿病患者的 30 天医院再入院预测任务上验证了 QDT，使用 MIMIC 风格的 EHR 队列，实现了 F1 = 0.70 的优异性能，优于 TabPFN (F1 = 0.68)。据我们所知，这是首次展示仅使用模式元数据和聚合统计信息的 LLM 驱动的隐私保护结构化预测，为传统基础模型管道提供了一种可扩展、可解释且符合法规的替代方案。

> Electronic health records (EHRs) contain richly structured, longitudinal data essential for predictive modeling, yet stringent privacy regulations (e.g., HIPAA, GDPR) often restrict access to individual-level records. We introduce Query, Don't Train (QDT): a structured-data foundation-model interface enabling tabular inference via LLM-generated SQL over EHRs. Instead of training on or accessing individual-level examples, QDT uses a large language model (LLM) as a schema-aware query planner to generate privacy-compliant SQL queries from a natural language task description and a test-time input. The model then extracts summary-level population statistics through these SQL queries and the LLM performs, chain-of-thought reasoning over the results to make predictions. This inference-time-only approach (1) eliminates the need for supervised model training or direct data access, (2) ensures interpretability through symbolic, auditable queries, (3) naturally handles missing features without imputation or preprocessing, and (4) effectively manages high-dimensional numerical data to enhance analytical capabilities. We validate QDT on the task of 30-day hospital readmission prediction for Type 2 diabetes patients using a MIMIC-style EHR cohort, achieving F1 = 0.70, which outperforms TabPFN (F1 = 0.68). To our knowledge, this is the first demonstration of LLM-driven, privacy-preserving structured prediction using only schema metadata and aggregate statistics - offering a scalable, interpretable, and regulation-compliant alternative to conventional foundation-model pipelines.

[Arxiv](https://arxiv.org/abs/2505.21801)