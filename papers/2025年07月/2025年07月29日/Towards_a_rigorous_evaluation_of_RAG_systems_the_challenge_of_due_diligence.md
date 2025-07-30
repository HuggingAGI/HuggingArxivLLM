# RAG 系统评估的严格性挑战：深入探讨尽职调查

发布时间：2025年07月29日

`RAG`

> Towards a rigorous evaluation of RAG systems: the challenge of due diligence

# 摘要

> 生成式AI的崛起推动了医疗、金融等高风险领域的重大进展。其中，检索增强生成（RAG）架构通过结合语言模型（LLMs）和搜索引擎，特别擅长从文档语料库中生成响应。尽管潜力巨大，但RAG系统在关键场景中的可靠性仍存疑虑，幻觉问题尤为突出。本研究评估了某投资基金尽职调查中使用的RAG系统。我们提出了一种结合人工标注和LLM-Judge标注的稳健评估协议，用于识别系统故障，如幻觉、跑题、引用失败和拒绝回答。受预测驱动推理（PPI）方法启发，我们实现了具有统计保证的精准性能测量。我们提供了一个全面的数据集供进一步分析。我们的贡献旨在提升RAG系统评估协议在工业应用中的可靠性和可扩展性。

> The rise of generative AI, has driven significant advancements in high-risk sectors like healthcare and finance. The Retrieval-Augmented Generation (RAG) architecture, combining language models (LLMs) with search engines, is particularly notable for its ability to generate responses from document corpora. Despite its potential, the reliability of RAG systems in critical contexts remains a concern, with issues such as hallucinations persisting. This study evaluates a RAG system used in due diligence for an investment fund. We propose a robust evaluation protocol combining human annotations and LLM-Judge annotations to identify system failures, like hallucinations, off-topic, failed citations, and abstentions. Inspired by the Prediction Powered Inference (PPI) method, we achieve precise performance measurements with statistical guarantees. We provide a comprehensive dataset for further analysis. Our contributions aim to enhance the reliability and scalability of RAG systems evaluation protocols in industrial applications.

[Arxiv](https://arxiv.org/abs/2507.21753)