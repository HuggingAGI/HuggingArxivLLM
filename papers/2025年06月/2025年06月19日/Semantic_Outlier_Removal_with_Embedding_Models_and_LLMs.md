# 基于嵌入模型和大语言模型的语义离群点识别

发布时间：2025年06月19日

`LLM应用

摘要中提到，论文提出了一种名为SORE（语义离群值去除）的方法，用于去除冗余内容并保留文档的核心信息。该方法利用多语言句子嵌入和近似最近邻搜索来识别并删除不需要的文本片段。虽然提到了大型语言模型（LLMs）的效果，但SORE本身并不是直接应用LLM，而是通过嵌入方法来替代LLM的高计算成本。这种方法在实际应用中表现出色，已经在生产环境中运行，并处理了大量多语言文档。因此，这篇论文属于LLM应用类别。` `文本处理` `信息提取`

> Semantic Outlier Removal with Embedding Models and LLMs

# 摘要

> 现代文本处理管道需要强大的方法来去除冗余内容，同时保留文档的核心信息。传统方法如 HTML 模板提取或关键词过滤在多语言环境中经常失效，并且难以处理语境敏感的细微差别，而大型语言模型 (LLMs) 虽然提供了更高的质量，但计算成本高昂。我们引入了 SORE（语义离群值去除），这是一种成本效益高且透明的方法，通过利用多语言句子嵌入和近似最近邻搜索来识别并删除不需要的文本片段。通过首先使用元数据嵌入识别核心内容，然后标记与预定义离群组密切匹配或与核心内容显著偏离的段落，SORE以极低的成本实现了接近LLM的提取精度。在HTML数据集上的实验表明，SORE在多种场景下比结构化方法表现更优，且具有高精度。我们的系统目前在生产环境中运行，每天处理多种语言的数百万份文档，同时保持高效和准确。为了促进可重复性和进一步研究，我们发布了我们的实现和评估数据集。

> Modern text processing pipelines demand robust methods to remove extraneous content while preserving a document's core message. Traditional approaches such as HTML boilerplate extraction or keyword filters often fail in multilingual settings and struggle with context-sensitive nuances, whereas Large Language Models (LLMs) offer improved quality at high computational cost. We introduce SORE (Semantic Outlier Removal), a cost-effective, transparent method that leverages multilingual sentence embeddings and approximate nearest-neighbor search to identify and excise unwanted text segments. By first identifying core content via metadata embedding and then flagging segments that either closely match predefined outlier groups or deviate significantly from the core, SORE achieves near-LLM extraction precision at a fraction of the cost. Experiments on HTML datasets demonstrate that SORE outperforms structural methods and yield high precision in diverse scenarios. Our system is currently deployed in production, processing millions of documents daily across multiple languages while maintaining both efficiency and accuracy. To facilitate reproducibility and further research, we release our implementation and evaluation datasets.

[Arxiv](https://arxiv.org/abs/2506.16644)