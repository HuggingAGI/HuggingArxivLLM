# GEE-OPs：由大型语言模型驱动的、用于谷歌地球引擎平台地理空间代码生成的操作符知识库

发布时间：2024年12月07日

`LLM应用` `地理信息` `时空数据`

> GEE-OPs: An Operator Knowledge Base for Geospatial Code Generation on the Google Earth Engine Platform Powered by Large Language Models

# 摘要

> 随着时空数据的规模和复杂程度迅速增长，在 Google Earth Engine（GEE）平台运用地理空间建模，给领域专家提高编码效率和跨学科用户增强编码能力带来了双重挑战。为应对这些挑战，提升大型语言模型（LLMs）在地理空间代码生成任务中的表现，我们提出了一个针对 GEE JavaScript API 构建地理空间操作符知识库的框架。此框架涵盖操作符语法知识表、操作符关系频率表、操作符频繁模式知识表以及操作符关系链知识表。借助抽象语法树（AST）技术和频繁项集挖掘，我们从 185,236 个真实的 GEE 脚本和语法文档中系统地抽取操作符知识，构建起结构化的知识库。实验结果显示，该框架在操作符知识提取方面的准确率、召回率和 F1 分数均超 90%。当与基于 LLM 的地理空间代码生成任务的检索增强生成（RAG）策略相结合时，知识库能将性能提升 20 - 30%。消融研究进一步明确了知识库构建中每个知识表的必要性。此项工作为地理空间代码建模技术的发展和应用给予了有力支撑，为构建特定领域的知识库以增强 LLMs 的代码生成能力提供了创新途径，推动了生成式 AI 技术在地理信息学领域更深度的融合。

> As the scale and complexity of spatiotemporal data continue to grow rapidly, the use of geospatial modeling on the Google Earth Engine (GEE) platform presents dual challenges: improving the coding efficiency of domain experts and enhancing the coding capabilities of interdisciplinary users. To address these challenges and improve the performance of large language models (LLMs) in geospatial code generation tasks, we propose a framework for building a geospatial operator knowledge base tailored to the GEE JavaScript API. This framework consists of an operator syntax knowledge table, an operator relationship frequency table, an operator frequent pattern knowledge table, and an operator relationship chain knowledge table. By leveraging Abstract Syntax Tree (AST) techniques and frequent itemset mining, we systematically extract operator knowledge from 185,236 real GEE scripts and syntax documentation, forming a structured knowledge base. Experimental results demonstrate that the framework achieves over 90% accuracy, recall, and F1 score in operator knowledge extraction. When integrated with the Retrieval-Augmented Generation (RAG) strategy for LLM-based geospatial code generation tasks, the knowledge base improves performance by 20-30%. Ablation studies further quantify the necessity of each knowledge table in the knowledge base construction. This work provides robust support for the advancement and application of geospatial code modeling techniques, offering an innovative approach to constructing domain-specific knowledge bases that enhance the code generation capabilities of LLMs, and fostering the deeper integration of generative AI technologies within the field of geoinformatics.

[Arxiv](https://arxiv.org/abs/2412.05587)