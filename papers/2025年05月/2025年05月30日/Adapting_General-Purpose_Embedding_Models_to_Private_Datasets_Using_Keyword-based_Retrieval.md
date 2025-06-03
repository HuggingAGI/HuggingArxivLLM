# # 适应通用嵌入模型到私人数据集的关键词检索方法
基于关键词检索的通用嵌入模型在私人数据集上的适应方法。

发布时间：2025年05月30日

`LLM应用`

> Adapting General-Purpose Embedding Models to Private Datasets Using Keyword-based Retrieval

# 摘要

> 文本嵌入模型是AI应用的基石，尤其在检索增强生成（RAG）领域表现突出。然而，尽管通用文本嵌入模型在通用检索任务中表现出色，但面对包含专业术语的私有数据集（如公司专有数据）时，其效果往往不尽如人意。为此，我们提出了BMEmbed——一种将通用文本嵌入模型适应私有数据集的创新方法。通过结合成熟的基于关键词的检索技术（BM25），我们从关键词检索结果的排名中提取监督信号，助力模型适应特定领域。我们对BMEmbed进行了跨领域、数据集和模型的全面评估，结果表明其在检索性能上实现了显著提升。此外，我们通过实证分析揭示了基于BM25的信号如何通过增强对齐和一致性来优化嵌入效果，进一步凸显了该方法在适应领域特定数据方面的独特优势。我们已将BMEmbed的源代码开源，供研究界参考和使用，访问地址为https://github.com/BaileyWei/BMEmbed。

> Text embedding models play a cornerstone role in AI applications, such as retrieval-augmented generation (RAG). While general-purpose text embedding models demonstrate strong performance on generic retrieval benchmarks, their effectiveness diminishes when applied to private datasets (e.g., company-specific proprietary data), which often contain specialized terminology and lingo. In this work, we introduce BMEmbed, a novel method for adapting general-purpose text embedding models to private datasets. By leveraging the well-established keyword-based retrieval technique (BM25), we construct supervisory signals from the ranking of keyword-based retrieval results to facilitate model adaptation. We evaluate BMEmbed across a range of domains, datasets, and models, showing consistent improvements in retrieval performance. Moreover, we provide empirical insights into how BM25-based signals contribute to improving embeddings by fostering alignment and uniformity, highlighting the value of this approach in adapting models to domain-specific data. We release the source code available at https://github.com/BaileyWei/BMEmbed for the research community.

[Arxiv](https://arxiv.org/abs/2506.00363)