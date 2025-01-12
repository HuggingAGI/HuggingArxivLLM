# 效率与准确性的博弈：通过多头早期退出优化RAG增强的LLM推荐系统

发布时间：2025年01月03日

`RAG

理由：这篇论文主要讨论了在推荐系统中使用LLMs预测点击率（CTR）时，如何通过结合检索增强生成（RAG）与多头早期退出架构来优化计算效率和预测准确性。论文的核心内容涉及RAG技术的应用，因此将其分类为RAG。` `推荐系统` `计算效率`

> The Efficiency vs. Accuracy Trade-off: Optimizing RAG-Enhanced LLM Recommender Systems Using Multi-Head Early Exit

# 摘要

> 在推荐系统中使用LLMs预测点击率（CTR）时，计算效率与预测准确性之间的平衡至关重要。本文提出了一种结合检索增强生成（RAG）与多头早期退出架构的优化框架，旨在同时提升这两方面。通过引入图卷积网络（GCNs）作为高效检索机制，我们大幅缩短了数据检索时间，同时保持了模型的高性能。早期退出策略基于多头的实时预测置信度评估，动态终止模型推理，不仅加快了LLMs的响应速度，还确保或提升了其准确性，非常适合实时应用场景。实验表明，该架构在不牺牲推荐准确性的前提下显著减少了计算时间，为商业系统中高效、实时的LLM部署树立了新标杆。

> The deployment of Large Language Models (LLMs) in recommender systems for predicting Click-Through Rates (CTR) necessitates a delicate balance between computational efficiency and predictive accuracy. This paper presents an optimization framework that combines Retrieval-Augmented Generation (RAG) with an innovative multi-head early exit architecture to concurrently enhance both aspects. By integrating Graph Convolutional Networks (GCNs) as efficient retrieval mechanisms, we are able to significantly reduce data retrieval times while maintaining high model performance. The early exit strategy employed allows for dynamic termination of model inference, utilizing real-time predictive confidence assessments across multiple heads. This not only quickens the responsiveness of LLMs but also upholds or improves their accuracy, making it ideal for real-time application scenarios. Our experiments demonstrate how this architecture effectively decreases computation time without sacrificing the accuracy needed for reliable recommendation delivery, establishing a new standard for efficient, real-time LLM deployment in commercial systems.

[Arxiv](https://arxiv.org/abs/2501.02173)