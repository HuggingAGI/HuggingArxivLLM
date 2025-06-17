# 迈向电子病历的可视化：通过自然语言查询实现

发布时间：2025年06月15日

`LLM应用` `数据可视化`

> Towards Visualizing Electronic Medical Records via Natural Language Queries

# 摘要

> 电子医疗记录（EMRs）是患者护理和临床研究的核心数据来源。面对电子健康记录（EHR）中结构化与非结构化数据的复杂性，数据可视化成为管理和解析这些信息的有力工具。然而，医学可视化数据的稀缺性以及标注成本高昂，严重制约了该领域的发展。为突破这一瓶颈，我们提出了一种基于大型语言模型（LLMs）的开创性方法，无需繁琐的人工标注即可生成可视化数据。我们构建了一个适用于电子医疗记录的文本到可视化基准管道，使用户能够通过自然语言查询（NLQs）直观呈现EMR统计数据。本文介绍的MedicalVis数据集包含35,374个配对文本医疗记录、NLQs及其对应可视化，是首个大规模电子医疗记录信息文本到视觉数据集。此外，我们提出了一种基于LLM的MedCodeT5方法，展示了其在NLQs生成EMR可视化方面的卓越性能，超越了多种强劲的基线模型。我们的研究不仅为EMR可视化方法提供了标准化的评估框架，更为推动这一重要应用领域的进步提供了有力工具。总之，这项研究和数据集有望为通过可视化技术解锁医学洞见带来重要突破。

> Electronic medical records (EMRs) contain essential data for patient care and clinical research. With the diversity of structured and unstructured data in EHR, data visualization is an invaluable tool for managing and explaining these complexities. However, the scarcity of relevant medical visualization data and the high cost of manual annotation required to develop such datasets pose significant challenges to advancing medical visualization techniques. To address this issue, we propose an innovative approach using large language models (LLMs) for generating visualization data without labor-intensive manual annotation. We introduce a new pipeline for building text-to-visualization benchmarks suitable for EMRs, enabling users to visualize EMR statistics through natural language queries (NLQs). The dataset presented in this paper primarily consists of paired text medical records, NLQs, and corresponding visualizations, forming the first large-scale text-to-visual dataset for electronic medical record information called MedicalVis with 35,374 examples. Additionally, we introduce an LLM-based approach called MedCodeT5, showcasing its viability in generating EMR visualizations from NLQs, outperforming various strong text-to-visualization baselines. Our work facilitates standardized evaluation of EMR visualization methods while providing researchers with tools to advance this influential field of application. In a nutshell, this study and dataset have the potential to promote advancements in eliciting medical insights through visualization.

[Arxiv](https://arxiv.org/abs/2506.12837)