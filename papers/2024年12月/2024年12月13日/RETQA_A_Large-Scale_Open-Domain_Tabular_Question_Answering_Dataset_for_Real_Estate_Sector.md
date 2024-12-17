# RETQA：一个适用于房地产领域的大规模开放域表格问答数据集

发布时间：2024年12月13日

`LLM应用` `房地产` `问答系统`

> RETQA: A Large-Scale Open-Domain Tabular Question Answering Dataset for Real Estate Sector

# 摘要

> 房地产市场高度依赖诸如房产详情、市场趋势和价格波动之类的结构化数据。然而，此领域中专门的表格问答数据集的缺失限制了自动问答系统的发展。为弥补这一空缺，我们推出了 RETQA，这是首个面向房地产的大规模开放域中文表格问答数据集。RETQA 包含 4932 个表格和 20762 个问答对，横跨房产信息、房地产公司财务信息和土地拍卖信息这三个主要领域的 16 个子领域。和现有的表格问答数据集相比，由于长表结构、开放域检索和多领域查询这三个关键因素，RETQA 带来了更大的挑战。为应对这些挑战，我们提出了 SLUTQA 框架，它将大型语言模型与口语语言理解任务相融合，以提升检索和回答的准确性。大量实验表明，通过上下文学习，SLUTQA 显著提高了大型语言模型在 RETQA 上的表现。RETQA 和 SLUTQA 为推动房地产领域的表格问答研究提供了重要资源，解决了开放域和长表问答中的关键难题。数据集和代码在 url{https://github.com/jensen-w/RETQA} 可公开获取。

> The real estate market relies heavily on structured data, such as property details, market trends, and price fluctuations. However, the lack of specialized Tabular Question Answering datasets in this domain limits the development of automated question-answering systems. To fill this gap, we introduce RETQA, the first large-scale open-domain Chinese Tabular Question Answering dataset for Real Estate. RETQA comprises 4,932 tables and 20,762 question-answer pairs across 16 sub-fields within three major domains: property information, real estate company finance information and land auction information. Compared with existing tabular question answering datasets, RETQA poses greater challenges due to three key factors: long-table structures, open-domain retrieval, and multi-domain queries. To tackle these challenges, we propose the SLUTQA framework, which integrates large language models with spoken language understanding tasks to enhance retrieval and answering accuracy. Extensive experiments demonstrate that SLUTQA significantly improves the performance of large language models on RETQA by in-context learning. RETQA and SLUTQA provide essential resources for advancing tabular question answering research in the real estate domain, addressing critical challenges in open-domain and long-table question-answering. The dataset and code are publicly available at \url{https://github.com/jensen-w/RETQA}.

[Arxiv](https://arxiv.org/abs/2412.10104)