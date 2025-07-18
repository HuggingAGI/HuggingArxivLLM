# # 检索器与生成器的相遇：代码注释生成联合模型

发布时间：2025年07月16日

`LLM应用

理由：这篇论文提出了一种结合检索和生成的新方法RAGSum，用于自动为源代码生成注释。虽然提到了RAG（检索增强生成）的概念，但其主要目标是注释生成的自动化，属于大型语言模型的具体应用。因此，更适合归类为LLM应用。` `软件工程`

> When Retriever Meets Generator: A Joint Model for Code Comment Generation

# 摘要

> 自动为源代码生成简洁、信息丰富的注释，不仅能够减轻文档编写负担，还能加速程序理解。传统的检索增强方法通过先获取带注释的代码片段，再综合生成新注释，但检索和生成通常独立优化，容易引入噪声。为解决这一问题，我们提出了一种名为RAGSum的新方法，旨在实现高效且精准的注释生成。RAGSum基于单个CodeT5主干模型，结合了检索与生成功能。我们在基于CodeT5的统一框架上进行了初步实验。通过对比预训练阶段塑造代码嵌入，优化最近邻搜索；随后采用复合损失函数，既奖励准确的top-k检索，又最小化注释生成误差。更重要的是，引入了轻量级自我优化循环，提升最终输出质量。我们在Java、Python、C三个跨语言基准测试中评估了该框架，与现有基线相比，在BLEU、METEOR和ROUTE-L指标上均表现优异。这表明，将检索与生成紧密结合能够显著提升注释自动化的上限，为未来研究提供了重要参考。

> Automatically generating concise, informative comments for source code can lighten documentation effort and accelerate program comprehension. Retrieval-augmented approaches first fetch code snippets with existing comments and then synthesize a new comment, yet retrieval and generation are typically optimized in isolation, allowing irrelevant neighbors topropagate noise downstream. To tackle the issue, we propose a novel approach named RAGSum with the aim of both effectiveness and efficiency in recommendations. RAGSum is built on top offuse retrieval and generation using a single CodeT5 backbone. We report preliminary results on a unified retrieval-generation framework built on CodeT5. A contrastive pre-training phase shapes code embeddings for nearest-neighbor search; these weights then seed end-to-end training with a composite loss that (i) rewards accurate top-k retrieval; and (ii) minimizes comment-generation error. More importantly, a lightweight self-refinement loop is deployed to polish the final output. We evaluated theframework on three cross-language benchmarks (Java, Python, C), and compared it with three well-established baselines. The results show that our approach substantially outperforms thebaselines with respect to BLEU, METEOR, and ROUTE-L. These findings indicate that tightly coupling retrieval and generationcan raise the ceiling for comment automation and motivateforthcoming replications and qualitative developer studies.

[Arxiv](https://arxiv.org/abs/2507.12558)