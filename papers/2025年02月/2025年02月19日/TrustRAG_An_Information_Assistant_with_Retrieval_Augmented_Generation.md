# TrustRAG：检索增强生成的信息助手

发布时间：2025年02月19日

`RAG` `问答系统` `信息检索`

> TrustRAG: An Information Assistant with Retrieval Augmented Generation

# 摘要

> \Ac{RAG} 是一种增强大型模型实时和领域特定知识的关键技术。尽管已有诸多改进和开源工具被提出以优化c{RAG}框架的准确性，但提升生成结果的可信度却鲜少受到关注。为此，我们推出了TrustRAG框架，从索引、检索和生成三个维度对c{RAG}进行全面增强。具体而言，在索引阶段，我们采用了一种结合层次索引的语义增强分块策略，为每个分块补充上下文信息，确保语义完整。在检索阶段，我们引入了基于效用的过滤机制，精准识别高质量信息，支持答案生成的同时缩短输入长度。在生成阶段，我们提出细粒度引用增强策略，能够检测响应中的观点性句子，并在句子级别推断引用关系，从而提升引用准确性。我们已开源TrustRAG框架，并提供了一个专注于基于摘录的问题回答任务的演示工作室ootnote{https://huggingface.co/spaces/golaxy/TrustRAG}。通过这些努力，我们希望助力研究人员：1）系统性地提升c{RAG}系统的可信度；2）开发具有更可靠输出的自定义c{RAG}系统。

> \Ac{RAG} has emerged as a crucial technique for enhancing large models with real-time and domain-specific knowledge. While numerous improvements and open-source tools have been proposed to refine the \ac{RAG} framework for accuracy, relatively little attention has been given to improving the trustworthiness of generated results. To address this gap, we introduce TrustRAG, a novel framework that enhances \ac{RAG} from three perspectives: indexing, retrieval, and generation. Specifically, in the indexing stage, we propose a semantic-enhanced chunking strategy that incorporates hierarchical indexing to supplement each chunk with contextual information, ensuring semantic completeness. In the retrieval stage, we introduce a utility-based filtering mechanism to identify high-quality information, supporting answer generation while reducing input length. In the generation stage, we propose fine-grained citation enhancement, which detects opinion-bearing sentences in responses and infers citation relationships at the sentence-level, thereby improving citation accuracy. We open-source the TrustRAG framework and provide a demonstration studio designed for excerpt-based question answering tasks \footnote{https://huggingface.co/spaces/golaxy/TrustRAG}. Based on these, we aim to help researchers: 1) systematically enhancing the trustworthiness of \ac{RAG} systems and (2) developing their own \ac{RAG} systems with more reliable outputs.

[Arxiv](https://arxiv.org/abs/2502.13719)