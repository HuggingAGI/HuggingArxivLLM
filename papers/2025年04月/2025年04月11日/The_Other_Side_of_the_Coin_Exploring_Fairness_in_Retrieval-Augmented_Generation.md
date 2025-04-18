# 硬币的另一面：检索增强生成的公平性探索

发布时间：2025年04月11日

`RAG` `人工智能`

> The Other Side of the Coin: Exploring Fairness in Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）通过从外部知识源检索相关文档来增强大型语言模型（LLMs）。它通过参考外部知识有效减少了生成错误事实内容，并解决了大型语言模型中的幻觉问题。最近，研究者们从不同角度致力于提升RAG系统的性能和效率。尽管取得显著进展，但RAG在社会影响领域应用引发了一个关键问题：引入RAG范式对大型语言模型的公平性有何影响？我们通过改变LLMs、检索器和检索来源进行了广泛实验。实验结果表明，LLMs的规模在RAG框架内对公平性结果有重要影响。当模型规模小于8B时，检索机制往往会加剧小型LLMs（如LLaMA3.2-1B、Mistral-7B和LLaMA3-8B）的不公平性。为此，我们针对小型LLMs提出了两种方法：FairFT和FairFilter。在FairFT中，我们使检索器与LLM在公平性方面保持一致，使其能够检索有助于更公平输出的文档。在FairFilter中，我们提出了一种公平性过滤机制，用于在检索后过滤掉有偏见的内容。最后，我们在真实世界数据集上验证了方法的有效性，证明了它们在提升公平性的同时保持了性能。

> Retrieval-Augmented Generation (RAG) enhances Large Language Models (LLMs) by retrieving relevant document from external knowledge sources. By referencing this external knowledge, RAG effectively reduces the generation of factually incorrect content and addresses hallucination issues within LLMs. Recently, there has been growing attention to improving the performance and efficiency of RAG systems from various perspectives. While these advancements have yielded significant results, the application of RAG in domains with considerable societal implications raises a critical question about fairness: What impact does the introduction of the RAG paradigm have on the fairness of LLMs? To address this question, we conduct extensive experiments by varying the LLMs, retrievers, and retrieval sources. Our experimental analysis reveals that the scale of the LLMs plays a significant role in influencing fairness outcomes within the RAG framework. When the model scale is smaller than 8B, the integration of retrieval mechanisms often exacerbates unfairness in small-scale LLMs (e.g., LLaMA3.2-1B, Mistral-7B, and LLaMA3-8B). To mitigate the fairness issues introduced by RAG for small-scale LLMs, we propose two approaches, FairFT and FairFilter. Specifically, in FairFT, we align the retriever with the LLM in terms of fairness, enabling it to retrieve documents that facilitate fairer model outputs. In FairFilter, we propose a fairness filtering mechanism to filter out biased content after retrieval. Finally, we validate our proposed approaches on real-world datasets, demonstrating their effectiveness in improving fairness while maintaining performance.

[Arxiv](https://arxiv.org/abs/2504.12323)