# ClaimPKG: 基于轻量级专用LLM的伪子图生成技术提升声明验证能力

发布时间：2025年05月28日

`LLM应用` `声明验证` `信息检索`

> ClaimPKG: Enhancing Claim Verification via Pseudo-Subgraph Generation with Lightweight Specialized LLM

# 摘要

> 将知识图谱（KGs）整合到大型语言模型（LLMs）中以增强其推理能力，是声明验证领域的重要研究挑战。尽管知识图谱提供了结构化且语义丰富的表示，非常适合推理，但现有的验证方法大多依赖非结构化文本，限制了其对知识图谱的有效利用。现代大型语言模型虽然推理能力强，但在处理多步骤模块化管道和无适应的知识图谱推理时仍面临挑战。为应对这些挑战，我们提出了ClaimPKG，一个端到端框架，将大型语言模型的推理能力与知识图谱的结构化知识无缝结合。具体而言，ClaimPKG的核心理念是利用轻量级专用大型语言模型，将输入声明转化为伪子图，从而引导专门的子图检索模块识别相关知识图谱子图。这些检索到的子图随后由通用大型语言模型处理，生成最终的裁决和理由说明。在FactKG数据集上的大量实验表明，ClaimPKG实现了最先进的性能，相比现有强基线模型，在多个类别上高出9-12%的准确率。此外，ClaimPKG在HoVer和FEVEROUS等非结构化数据集上展现出零样本泛化能力，有效结合了知识图谱的结构化知识与大型语言模型的推理能力，适用于多种模型架构。

> Integrating knowledge graphs (KGs) to enhance the reasoning capabilities of large language models (LLMs) is an emerging research challenge in claim verification. While KGs provide structured, semantically rich representations well-suited for reasoning, most existing verification methods rely on unstructured text corpora, limiting their ability to effectively leverage KGs. Additionally, despite possessing strong reasoning abilities, modern LLMs struggle with multi-step modular pipelines and reasoning over KGs without adaptation. To address these challenges, we propose ClaimPKG, an end-to-end framework that seamlessly integrates LLM reasoning with structured knowledge from KGs. Specifically, the main idea of ClaimPKG is to employ a lightweight, specialized LLM to represent the input claim as pseudo-subgraphs, guiding a dedicated subgraph retrieval module to identify relevant KG subgraphs. These retrieved subgraphs are then processed by a general-purpose LLM to produce the final verdict and justification. Extensive experiments on the FactKG dataset demonstrate that ClaimPKG achieves state-of-the-art performance, outperforming strong baselines in this research field by 9%-12% accuracy points across multiple categories. Furthermore, ClaimPKG exhibits zero-shot generalizability to unstructured datasets such as HoVer and FEVEROUS, effectively combining structured knowledge from KGs with LLM reasoning across various LLM backbones.

[Arxiv](https://arxiv.org/abs/2505.22552)