# AutoRD 是一款创新的全自动端到端系统，它利用了本体增强的大型语言模型技术，专注于高效构建罕见病知识图谱。

发布时间：2024年03月01日

`LLM应用`

> AutoRD: An Automatic and End-to-End System for Rare Disease Knowledge Graph Construction Based on Ontologies-enhanced Large Language Models

# 摘要

> 本次研究旨在打造一款名为 AutoRD 的全流程自动化系统，它可以高效地从有关罕见疾病的临床文本中提取关键信息。我们针对 AutoRD 进行了多方位测试，并在此文中详述了其实力与局限性。运用大规模语言模型和基于开源医学本体论构建的医学知识图谱，我们搭建了 AutoRD 系统，它涵盖了数据预处理、实体识别、关系抽取、实体校准等多个环节，并最终构建知识图谱。我们对其进行定量评测，涉及实体识别、关系抽取和整体知识图谱构建效果等方面。结果显示，AutoRD 总体 F1 分数达到了47.3%，比基础 LLM 提升了14.4个百分点。在细节方面，AutoRD 的实体识别综合 F1 得分为56.1%（罕见疾病识别率高达83.5%，疾病识别率为35.8%，症状和体征识别率为46.1%，代词识别率为67.5%）；关系抽取综合 F1 得分为38.6%（如“引发”关系为34.7%，“增加患病风险”关系为12.4%等）。同时，定性实验表明，AutoRD 在构建知识图谱方面的表现可圈可点。AutoRD 的出色表现为 LLM 在罕见病识别领域的应用开辟了新的可能，其中显著提升得益于融入了本体强化的 LLM 技术。总结来说，AutoRD 是一款能自动从文本中抽提罕见疾病信息以构建知识图谱的端到端解决方案，它借助本体强化的 LLM 构建起强大的医学知识体系。经由实验证明，AutoRD 的卓越性能充分展现了 LLM 在医疗健康行业的巨大应用潜力。

> Objectives Our objective is to create an end-to-end system called AutoRD, which automates extracting information from clinical text about rare diseases. We have conducted various tests to evaluate the performance of AutoRD and highlighted its strengths and limitations in this paper.
  Materials and Methods Our system, AutoRD, is a software pipeline involving data preprocessing, entity extraction, relation extraction, entity calibration, and knowledge graph construction. We implement this using large language models and medical knowledge graphs developed from open-source medical ontologies. We quantitatively evaluate our system on entity extraction, relation extraction, and the performance of knowledge graph construction.
  Results AutoRD achieves an overall F1 score of 47.3%, a 14.4% improvement compared to the base LLM. In detail, AutoRD achieves an overall entity extraction F1 score of 56.1% (rare_disease: 83.5%, disease: 35.8%, symptom_and_sign: 46.1%, anaphor: 67.5%) and an overall relation extraction F1 score of 38.6% (produces: 34.7%, increases_risk_of: 12.4%, is_a: 37.4%, is_acronym: 44.1%, is_synonym: 16.3%, anaphora: 57.5%). Our qualitative experiment also demonstrates that the performance in constructing the knowledge graph is commendable.
  Discussion AutoRD demonstrates the potential of LLM applications in rare disease detection. This improvement is attributed to several design, including the integration of ontologies-enhanced LLMs.
  Conclusion AutoRD is an automated end-to-end system for extracting rare disease information from text to build knowledge graphs. It uses ontologies-enhanced LLMs for a robust medical knowledge base. The superior performance of AutoRD is validated by experimental evaluations, demonstrating the potential of LLMs in healthcare.

[Arxiv](https://arxiv.org/abs/2403.00953)