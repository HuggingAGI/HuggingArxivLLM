# 基于注意力图拓扑差异的大型语言模型幻觉检测

发布时间：2025年04月14日

`RAG` `事实核查`

> Hallucination Detection in LLMs via Topological Divergence on Attention Graphs

# 摘要

> 幻觉，即生成事实性错误的内容，依然是大型语言模型（LLMs）面临的一个严峻挑战。为此，我们提出了TOHA（基于拓扑的幻觉检测器），该检测器在RAG框架下运行，通过拓扑散度指标量化由注意力矩阵生成的图的结构特性。通过分析提示与响应子图之间的拓扑散度，我们发现了一个显著的模式：特定注意力头的高散度值与幻觉输出密切相关，这一现象与数据集无关。我们的实验涵盖问答和数据到文本任务，结果显示TOHA在多个基准测试中表现优异，其中两个由我们标注的基准测试将公开发布以支持进一步研究。除了在领域内的卓越表现，TOHA还展现出在多个开源LLMs中的出色迁移能力。我们的研究证实，分析注意力矩阵的拓扑结构可作为评估LLMs事实可靠性的高效且稳健的指标。


> Hallucination, i.e., generating factually incorrect content, remains a critical challenge for large language models (LLMs). We introduce TOHA, a TOpology-based HAllucination detector in the RAG setting, which leverages a topological divergence metric to quantify the structural properties of graphs induced by attention matrices. Examining the topological divergence between prompt and response subgraphs reveals consistent patterns: higher divergence values in specific attention heads correlate with hallucinated outputs, independent of the dataset. Extensive experiments, including evaluation on question answering and data-to-text tasks, show that our approach achieves state-of-the-art or competitive results on several benchmarks, two of which were annotated by us and are being publicly released to facilitate further research. Beyond its strong in-domain performance, TOHA maintains remarkable domain transferability across multiple open-source LLMs. Our findings suggest that analyzing the topological structure of attention matrices can serve as an efficient and robust indicator of factual reliability in LLMs.

[Arxiv](https://arxiv.org/abs/2504.10063)