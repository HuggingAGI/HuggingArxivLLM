# # 从查询到解释：Uni-RAG为STEM领域的多模态检索增强学习提供解决方案

发布时间：2025年07月04日

`RAG` `教育技术`

> From Query to Explanation: Uni-RAG for Multi-Modal Retrieval-Augmented Learning in STEM

# 摘要

> 在AI辅助教学中，多样的查询风格是实现有效学习体验的关键。然而，现有系统在处理教育场景的多样性和复杂性方面存在局限。为此，我们开发了Uni-Retrieval模块，通过动态匹配和持续更新的提示库，提升系统对多样化查询的适应能力。结合紧凑的语言模型，我们构建了Uni-RAG系统，能够从风格化的查询中生成高质量的教育内容。实验结果显示，Uni-RAG在检索和生成能力上均优于现有方法，同时保持了高效性。这一框架为智能教育系统提供了一个灵活且实用的解决方案，支持个性化、可解释的助学服务，适用于多种STEM场景。

> In AI-facilitated teaching, leveraging various query styles to interpret abstract educational content is crucial for delivering effective and accessible learning experiences. However, existing retrieval systems predominantly focus on natural text-image matching and lack the capacity to address the diversity and ambiguity inherent in real-world educational scenarios. To address this limitation, we develop a lightweight and efficient multi-modal retrieval module, named Uni-Retrieval, which extracts query-style prototypes and dynamically matches them with tokens from a continually updated Prompt Bank. This Prompt Bank encodes and stores domain-specific knowledge by leveraging a Mixture-of-Expert Low-Rank Adaptation (MoE-LoRA) module and can be adapted to enhance Uni-Retrieval's capability to accommodate unseen query types at test time. To enable natural language educational content generation, we integrate the original Uni-Retrieval with a compact instruction-tuned language model, forming a complete retrieval-augmented generation pipeline named Uni-RAG. Given a style-conditioned query, Uni-RAG first retrieves relevant educational materials and then generates human-readable explanations, feedback, or instructional content aligned with the learning objective. Experimental results on SER and other multi-modal benchmarks show that Uni-RAG outperforms baseline retrieval and RAG systems in both retrieval accuracy and generation quality, while maintaining low computational cost. Our framework provides a scalable, pedagogically grounded solution for intelligent educational systems, bridging retrieval and generation to support personalized, explainable, and efficient learning assistance across diverse STEM scenarios.

[Arxiv](https://arxiv.org/abs/2507.03868)