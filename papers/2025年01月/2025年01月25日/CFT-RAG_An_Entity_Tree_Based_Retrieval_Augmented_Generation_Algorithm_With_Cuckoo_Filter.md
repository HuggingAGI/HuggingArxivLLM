# CFT-RAG: 基于实体树和布谷鸟过滤器的检索增强生成算法

发布时间：2025年01月25日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）在涉及树状结构的任务中的性能优化问题，提出了一种基于改进Cuckoo Filter的Tree-RAG加速方法。因此，它属于RAG（Retrieval-Augmented Generation）领域的研究。` `信息检索`

> CFT-RAG: An Entity Tree Based Retrieval Augmented Generation Algorithm With Cuckoo Filter

# 摘要

> 尽管检索增强生成（RAG）通过整合外部知识库显著提升了生成质量，但在涉及树状结构的Tree-RAG任务中，计算效率成为瓶颈。本文提出了一种基于改进Cuckoo Filter的Tree-RAG加速方法，优化了检索中的实体定位，大幅提升了性能。Tree-RAG通过层次树结构高效组织实体，而Cuckoo Filter则支持快速查询和动态更新。实验表明，我们的方法在保持高质量生成的同时，速度远超原始Tree-RAG，尤其在树数量庞大时，速度提升可达数百倍。详情请访问https://github.com/TUPYP7180/CFT-RAG-2025。

> Although retrieval-augmented generation(RAG) significantly improves generation quality by retrieving external knowledge bases and integrating generated content, it faces computational efficiency bottlenecks, particularly in knowledge retrieval tasks involving hierarchical structures for Tree-RAG. This paper proposes a Tree-RAG acceleration method based on the improved Cuckoo Filter, which optimizes entity localization during the retrieval process to achieve significant performance improvements. Tree-RAG effectively organizes entities through the introduction of a hierarchical tree structure, while the Cuckoo Filter serves as an efficient data structure that supports rapid membership queries and dynamic updates. The experiment results demonstrate that our method is much faster than naive Tree-RAG while maintaining high levels of generative quality. When the number of trees is large, our method is hundreds of times faster than naive Tree-RAG. Our work is available at https://github.com/TUPYP7180/CFT-RAG-2025.

[Arxiv](https://arxiv.org/abs/2501.15098)