# # 摘要
CliCARE：将大型语言模型融入临床指南，助力基于纵向癌症电子健康记录的决策支持。

发布时间：2025年07月30日

`LLM应用` `肿瘤学`

> CliCARE: Grounding Large Language Models in Clinical Guidelines for Decision Support over Longitudinal Cancer Electronic Health Records

# 摘要

> 大型语言模型（LLMs）在整合复杂的纵向癌症电子健康记录（EHRs）方面展现出巨大潜力，能够提升临床决策支持并缓解医生的职业倦怠。然而，这一前沿技术在临床应用中面临三大主要挑战：首先，模型难以有效处理患者记录的冗长性和多语言特性，从而影响精准的时间序列分析；其次，传统的基于检索增强生成（RAG）的方法未能充分融合以流程为导向的临床指南，导致临床幻觉的风险显著增加；最后，现有评估指标的可靠性不足，阻碍了AI系统在肿瘤学领域的验证与应用。为应对这些挑战，我们提出了一种名为CliCARE的框架，旨在通过将临床指南与纵向癌症电子健康记录相结合，为临床决策提供坚实支持。该框架通过将非结构化的纵向EHRs转化为个性化的时序知识图谱（TKGs），捕捉长程依赖关系，并通过将真实患者的诊疗轨迹与规范化的指南知识图谱进行对齐，从而为临床决策过程提供可靠依据。这种方法能够为肿瘤科医生生成高保真的临床摘要和切实可行的建议，从而提供基于证据的决策支持。我们利用来自中国某私人癌症数据集和公开的英文MIMIC-IV数据集的大量纵向数据对框架进行了验证。在这些多样化的应用场景中，CliCARE显著超越了现有的强基线模型，包括先进的长上下文LLMs和知识图谱增强的RAG方法。我们的评估结果得到了一套严谨的评估协议的支持，证明了与专家肿瘤科医生评估的高度一致性，充分验证了CliCARE的临床有效性。


> Large Language Models (LLMs) hold significant promise for improving clinical decision support and reducing physician burnout by synthesizing complex, longitudinal cancer Electronic Health Records (EHRs). However, their implementation in this critical field faces three primary challenges: the inability to effectively process the extensive length and multilingual nature of patient records for accurate temporal analysis; a heightened risk of clinical hallucination, as conventional grounding techniques such as Retrieval-Augmented Generation (RAG) do not adequately incorporate process-oriented clinical guidelines; and unreliable evaluation metrics that hinder the validation of AI systems in oncology. To address these issues, we propose CliCARE, a framework for Grounding Large Language Models in Clinical Guidelines for Decision Support over Longitudinal Cancer Electronic Health Records. The framework operates by transforming unstructured, longitudinal EHRs into patient-specific Temporal Knowledge Graphs (TKGs) to capture long-range dependencies, and then grounding the decision support process by aligning these real-world patient trajectories with a normative guideline knowledge graph. This approach provides oncologists with evidence-grounded decision support by generating a high-fidelity clinical summary and an actionable recommendation. We validated our framework using large-scale, longitudinal data from a private Chinese cancer dataset and the public English MIMIC-IV dataset. In these diverse settings, CliCARE significantly outperforms strong baselines, including leading long-context LLMs and Knowledge Graph-enhanced RAG methods. The clinical validity of our results is supported by a robust evaluation protocol, which demonstrates a high correlation with assessments made by expert oncologists.

[Arxiv](https://arxiv.org/abs/2507.22533)