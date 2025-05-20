# # 针对对象约束语言优化检索增强生成

发布时间：2025年05月19日

`RAG` `系统工程` `软件工程`

> Optimizing Retrieval Augmented Generation for Object Constraint Language

# 摘要

> 对象约束语言（OCL）在基于模型的系统工程（MBSE）中定义精确约束至关重要。然而，手动编写OCL规则既复杂又耗时。本研究探讨了通过优化检索增强生成（RAG）来实现OCL规则自动生成，重点关注不同检索策略对生成效果的影响。我们评估了三种检索方法——基于词汇的BM25、基于语义的BERT和基于稀疏向量的SPLADE——分析它们在为大型语言模型提供相关上下文方面的有效性。
    为了进一步评估我们的方法，我们将优化后的检索生成结果与基于图的前沿方法PathOCL进行了比较和基准测试。我们直接比较了BM25、BERT和SPLADE检索方法与PathOCL，以了解不同检索方法在统一评估框架下的表现。我们的实验结果专注于检索增强生成，表明虽然检索可以提高生成准确性，但其效果取决于检索方法和检索块的数量（k）。其中BM25的表现低于基准，而BERT和SPLADE等语义方法表现更优，尤其在较低k值时，SPLADE效果最佳。然而，过高的k参数导致检索无关内容，从而降低模型性能。我们的研究结果强调了优化检索配置以平衡上下文相关性和输出一致性的必要性。这项研究为利用RAG改进OCL规则生成提供了见解，并突显了根据具体需求调整检索方法的重要性。

> The Object Constraint Language (OCL) is essential for defining precise constraints within Model-Based Systems Engineering (MBSE). However, manually writing OCL rules is complex and time-consuming. This study explores the optimization of Retrieval-Augmented Generation (RAG) for automating OCL rule generation, focusing on the impact of different retrieval strategies. We evaluate three retrieval approaches $\unicode{x2013}$ BM25 (lexical-based), BERT-based (semantic retrieval), and SPLADE (sparse-vector retrieval) $\unicode{x2013}$ analyzing their effectiveness in providing relevant context for a large language model.
  To further assess our approach, we compare and benchmark our retrieval-optimized generation results against PathOCL, a state-of-the-art graph-based method. We directly compare BM25, BERT, and SPLADE retrieval methods with PathOCL to understand how different retrieval methods perform for a unified evaluation framework. Our experimental results, focusing on retrieval-augmented generation, indicate that while retrieval can enhance generation accuracy, its effectiveness depends on the retrieval method and the number of retrieved chunks (k). BM25 underperforms the baseline, whereas semantic approaches (BERT and SPLADE) achieve better results, with SPLADE performing best at lower k values. However, excessive retrieval with high k parameter can lead to retrieving irrelevant chunks which degrades model performance. Our findings highlight the importance of optimizing retrieval configurations to balance context relevance and output consistency. This research provides insights into improving OCL rule generation using RAG and underscores the need for tailoring retrieval.

[Arxiv](https://arxiv.org/abs/2505.13129)