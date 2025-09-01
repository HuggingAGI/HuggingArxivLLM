# CAMB：面向民航维修的综合性行业大型语言模型基准

发布时间：2025年08月28日

`LLM应用` `交通运输`

> CAMB: A comprehensive industrial LLM benchmark on civil aviation maintenance

# 摘要

> 民用航空维修领域有着严苛的行业标准。在该领域中，维修流程与故障排查是知识密集型关键任务，对复杂推理能力要求极高。针对这一垂直领域缺乏大型语言模型（LLMs）专用评估工具的现状，我们提出并开发了一套工业级民用航空维修专用基准。该基准具备双重功能：一是提供标准化工具评估民用航空维修领域的LLM能力，二是精准定位领域知识与复杂推理中的具体短板。通过明确这些短板，该基准为定向改进工作（如领域专用微调、RAG优化或定制化提示工程）奠定基础，助力民用航空维修领域开发更智能的解决方案。当前LLM评估多聚焦于数学和编码推理任务，我们的研究填补了这一重要空白。此外，考虑到检索增强生成（RAG）系统是当前实际应用的主流方案，我们借助该基准评估了现有主流向量嵌入模型及LLMs在民用航空维修场景下的表现。通过实验探索与分析，我们验证了该基准在评估该领域模型性能上的有效性，并已开源相关评估基准及代码，以推动后续研究与开发：https://github.com/CamBenchmark/cambenchmark

> Civil aviation maintenance is a domain characterized by stringent industry standards. Within this field, maintenance procedures and troubleshooting represent critical, knowledge-intensive tasks that require sophisticated reasoning. To address the lack of specialized evaluation tools for large language models (LLMs) in this vertical, we propose and develop an industrial-grade benchmark specifically designed for civil aviation maintenance. This benchmark serves a dual purpose: It provides a standardized tool to measure LLM capabilities within civil aviation maintenance, identifying specific gaps in domain knowledge and complex reasoning. By pinpointing these deficiencies, the benchmark establishes a foundation for targeted improvement efforts (e.g., domain-specific fine-tuning, RAG optimization, or specialized prompt engineering), ultimately facilitating progress toward more intelligent solutions within civil aviation maintenance. Our work addresses a significant gap in the current LLM evaluation, which primarily focuses on mathematical and coding reasoning tasks. In addition, given that Retrieval-Augmented Generation (RAG) systems are currently the dominant solutions in practical applications , we leverage this benchmark to evaluate existing well-known vector embedding models and LLMs for civil aviation maintenance scenarios. Through experimental exploration and analysis, we demonstrate the effectiveness of our benchmark in assessing model performance within this domain, and we open-source this evaluation benchmark and code to foster further research and development:https://github.com/CamBenchmark/cambenchmark

[Arxiv](https://arxiv.org/abs/2508.20420)