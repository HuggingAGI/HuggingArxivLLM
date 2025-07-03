# MobileRAG：设备端RAG的快速、内存高效、能源高效方法

发布时间：2025年07月01日

`RAG` `移动应用` `资源优化`

> MobileRAG: A Fast, Memory-Efficient, and Energy-Efficient Method for On-Device RAG

# 摘要

> 检索增强生成（RAG）在服务器端表现出色，但受限于资源，其在移动端的应用尚未充分探索。现有解决方案多基于丰富计算资源，难以适用于设备端。本文提出MobileRAG，一个完全基于设备的流水线，结合移动端友好的向量搜索算法EcoVector和轻量级的SCR方法，突破了这一限制。通过划分和部分加载索引数据，EcoVector大幅降低了内存和CPU使用率，而SCR方法通过过滤无关文本，减少LM输入规模，同时保持准确性。实验表明，与传统方法相比，MobileRAG在延迟、内存使用和功耗方面均表现更优，同时保持准确性，并支持离线操作，保护隐私。

> Retrieval-Augmented Generation (RAG) has proven effective on server infrastructures, but its application on mobile devices is still underexplored due to limited memory and power resources. Existing vector search and RAG solutions largely assume abundant computation resources, making them impractical for on-device scenarios. In this paper, we propose MobileRAG, a fully on-device pipeline that overcomes these limitations by combining a mobile-friendly vector search algorithm, \textit{EcoVector}, with a lightweight \textit{Selective Content Reduction} (SCR) method. By partitioning and partially loading index data, EcoVector drastically reduces both memory footprint and CPU usage, while the SCR method filters out irrelevant text to diminish Language Model (LM) input size without degrading accuracy. Extensive experiments demonstrated that MobileRAG significantly outperforms conventional vector search and RAG methods in terms of latency, memory usage, and power consumption, while maintaining accuracy and enabling offline operation to safeguard privacy in resource-constrained environments.

[Arxiv](https://arxiv.org/abs/2507.01079)