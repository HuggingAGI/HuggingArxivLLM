# KG4Diagnosis：一个用于医疗诊断、具备知识图谱增强功能的分层多智能体 LLM 框架

发布时间：2024年12月21日

`Agent` `诊断系统`

> KG4Diagnosis: A Hierarchical Multi-Agent LLM Framework with Knowledge Graph Enhancement for Medical Diagnosis

# 摘要

> 在医疗诊断中融入大型语言模型（LLMs），需要能应对复杂医疗场景并保持专业水准的系统框架。我们推出了 KG4Diagnosis，这一全新的分层多智能体框架将 LLMs 与自动知识图谱构建相融合，涵盖了医学专业内的 362 种常见疾病。我们的框架通过两层架构来映照现实中的医疗系统：有用于初步评估和分诊的全科医生（GP）代理，它与专业代理协同进行特定领域的深度诊断。其核心创新在于端到端的知识图谱生成方法，包含：（1）针对医学术语优化的语义驱动实体和关系提取；（2）从非结构化医疗文本重建多维决策关系；（3）用于知识拓展的人类引导推理。KG4Diagnosis 是专门医疗诊断系统的可扩展基石，能够纳入新的疾病和医学知识。该框架的模块化设计能够无缝整合特定领域的增强功能，对于开发针对性的医疗诊断系统极具价值。我们提供架构指南和协议，以推动其在医疗环境中的应用。

> Integrating Large Language Models (LLMs) in healthcare diagnosis demands systematic frameworks that can handle complex medical scenarios while maintaining specialized expertise. We present KG4Diagnosis, a novel hierarchical multi-agent framework that combines LLMs with automated knowledge graph construction, encompassing 362 common diseases across medical specialties. Our framework mirrors real-world medical systems through a two-tier architecture: a general practitioner (GP) agent for initial assessment and triage, coordinating with specialized agents for in-depth diagnosis in specific domains. The core innovation lies in our end-to-end knowledge graph generation methodology, incorporating: (1) semantic-driven entity and relation extraction optimized for medical terminology, (2) multi-dimensional decision relationship reconstruction from unstructured medical texts, and (3) human-guided reasoning for knowledge expansion. KG4Diagnosis serves as an extensible foundation for specialized medical diagnosis systems, with capabilities to incorporate new diseases and medical knowledge. The framework's modular design enables seamless integration of domain-specific enhancements, making it valuable for developing targeted medical diagnosis systems. We provide architectural guidelines and protocols to facilitate adoption across medical contexts.

[Arxiv](https://arxiv.org/abs/2412.16833)