# # QE-RAG：面向查询输入错误的健壮检索增强生成基准

发布时间：2025年04月05日

`RAG` `信息检索`

> QE-RAG: A Robust Retrieval-Augmented Generation Benchmark for Query Entry Errors

# 摘要

> 检索增强生成（RAG）已成为提升大型语言模型（LLMs）事实准确性的重要方法。现有基准测试从多个角度评估了RAG方法的性能，但都基于一个共同假设：用于检索的用户查询是无误的。然而，在用户与LLMs的实际交互中，由于键盘邻近错误、视觉相似错误和拼写错误等输入错误，查询错误频繁发生。当前RAG方法在面对这些错误时的表现尚未得到充分研究。为填补这一空白，我们提出了QE-RAG，这是首个专门针对查询输入错误设计的鲁棒RAG基准测试。通过在六个常用数据集中随机选取用户查询，并以20%和40%的比例注入三种常见的查询输入错误，我们模拟了真实场景下的典型用户行为。我们分析了这些错误对LLM输出的影响，发现受损查询会降低模型性能，但通过查询校正和训练一个稳健的检索器以检索相关文档，可以有效缓解这一问题。基于这些发现，我们提出了一种基于对比学习的鲁棒检索器训练方法和一种检索增强的查询校正方法。广泛的内部和跨领域实验表明：（1）包括顺序、分支和迭代方法在内的最先进的RAG方法在面对查询输入错误时表现出较差的鲁棒性；（2）我们的方法显著提升了RAG在处理查询输入错误时的鲁棒性，并且与现有RAG方法兼容，进一步增强了其鲁棒性。

> Retriever-augmented generation (RAG) has become a widely adopted approach for enhancing the factual accuracy of large language models (LLMs). While current benchmarks evaluate the performance of RAG methods from various perspectives, they share a common assumption that user queries used for retrieval are error-free. However, in real-world interactions between users and LLMs, query entry errors such as keyboard proximity errors, visual similarity errors, and spelling errors are frequent. The impact of these errors on current RAG methods against such errors remains largely unexplored. To bridge this gap, we propose QE-RAG, the first robust RAG benchmark designed specifically to evaluate performance against query entry errors. We augment six widely used datasets by injecting three common types of query entry errors into randomly selected user queries at rates of 20\% and 40\%, simulating typical user behavior in real-world scenarios. We analyze the impact of these errors on LLM outputs and find that corrupted queries degrade model performance, which can be mitigated through query correction and training a robust retriever for retrieving relevant documents. Based on these insights, we propose a contrastive learning-based robust retriever training method and a retrieval-augmented query correction method. Extensive in-domain and cross-domain experiments reveal that: (1) state-of-the-art RAG methods including sequential, branching, and iterative methods, exhibit poor robustness to query entry errors; (2) our method significantly enhances the robustness of RAG when handling query entry errors and it's compatible with existing RAG methods, further improving their robustness.

[Arxiv](https://arxiv.org/abs/2504.04062)