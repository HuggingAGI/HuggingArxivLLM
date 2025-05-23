# TrialPanorama：临床试验系统综述与设计数据库及基准

发布时间：2025年05月21日

`LLM应用` `临床试验`

> TrialPanorama: Database and Benchmark for Systematic Review and Design of Clinical Trials

# 摘要

> 开发垂直领域的人工智能（AI）需要稳固的数据根基，用于训练与评估。本文介绍TrialPanorama——一个包含1,657,476条临床试验记录的大型结构化数据库，数据源自15个全球来源。该数据库全面记录了试验设计与执行的关键要素，涵盖试验设置、干预措施、适应症、生物标志物及结果，并将其与DrugBank和MedDRA等标准生物医学本体相关联。这种结构化且基于本体的设计，使TrialPanorama成为临床试验任务的统一资源，支持试验规划、设计及总结等多方面应用。为展示其价值，我们从TrialPanorama数据库中构建了一套基准任务。该基准包含两大类别的八项任务：系统综述类（研究搜索、筛选与证据总结）三项，试验设计类（试验臂设计、入选标准、终点选择、样本量估算及完成评估）五项。实验中使用五种先进的大型语言模型（LLMs）测试发现，尽管通用型LLMs具备一定零样本能力，但其性能仍无法满足高风险临床试验工作流程的需求。我们公开发布TrialPanorama数据库及基准，旨在推动临床试验领域的人工智能研究向前发展。

> Developing artificial intelligence (AI) for vertical domains requires a solid data foundation for both training and evaluation. In this work, we introduce TrialPanorama, a large-scale, structured database comprising 1,657,476 clinical trial records aggregated from 15 global sources. The database captures key aspects of trial design and execution, including trial setups, interventions, conditions, biomarkers, and outcomes, and links them to standard biomedical ontologies such as DrugBank and MedDRA. This structured and ontology-grounded design enables TrialPanorama to serve as a unified, extensible resource for a wide range of clinical trial tasks, including trial planning, design, and summarization. To demonstrate its utility, we derive a suite of benchmark tasks directly from the TrialPanorama database. The benchmark spans eight tasks across two categories: three for systematic review (study search, study screening, and evidence summarization) and five for trial design (arm design, eligibility criteria, endpoint selection, sample size estimation, and trial completion assessment). The experiments using five state-of-the-art large language models (LLMs) show that while general-purpose LLMs exhibit some zero-shot capability, their performance is still inadequate for high-stakes clinical trial workflows. We release TrialPanorama database and the benchmark to facilitate further research on AI for clinical trials.

[Arxiv](https://arxiv.org/abs/2505.16097)