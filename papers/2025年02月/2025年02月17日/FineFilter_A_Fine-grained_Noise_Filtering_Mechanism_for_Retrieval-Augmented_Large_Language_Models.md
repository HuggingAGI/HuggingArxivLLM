# 细粒度噪声过滤机制：为检索增强型大型语言模型而设计

发布时间：2025年02月17日

`RAG` `生成任务`

> FineFilter: A Fine-grained Noise Filtering Mechanism for Retrieval-Augmented Large Language Models

# 摘要

> 检索增强生成（RAG）依赖于高质量的文档，但包含噪声的文档会严重影响其性能，使其难以检测到有效的答案线索。现有方法虽然通过重新排序或摘要来筛选关键句子，但面对大规模复杂文档时，精准定位答案线索仍是一个难题。

与传统基于文档的操作不同，我们另辟蹊径，将噪声过滤视为一个句子级别的极小化极大优化问题：首先利用上下文信息从多文档中挖掘潜在线索，再根据相关性进行排序，最后通过截断保留最核心的线索。

在此，我们提出了一种全新的细粒度噪声过滤机制——FineFilter，专为RAG设计，包含三大核心组件：线索提取器、重排序器和截断器。针对复杂推理场景，我们对每个模块进行了精心优化：

1. 线索提取器：以包含答案及其相似句子为目标，精准提取潜在线索；
2. 重排序器：根据生成模块的真实反馈，智能筛选有效线索，区分正负样本；
3. 截断器：以最小化线索为目标，实现精准截断，完成细粒度噪声过滤。

实验结果表明，FineFilter在性能和推理效率上均大幅超越现有方法。深入分析各模块表现，充分验证了我们的优化策略在处理复杂推理任务中的显著优势。


> Retrieved documents containing noise will hinder Retrieval-Augmented Generation (RAG) from detecting answer clues, necessitating noise filtering mechanisms to enhance accuracy. Existing methods use re-ranking or summarization to identify the most relevant sentences, but directly and accurately locating answer clues from these large-scale and complex documents remains challenging. Unlike these document-level operations, we treat noise filtering as a sentence-level MinMax optimization problem: first identifying the potential clues from multiple documents using contextual information, then ranking them by relevance, and finally retaining the least clues through truncation. In this paper, we propose FineFilter, a novel fine-grained noise filtering mechanism for RAG consisting of a clue extractor, a re-ranker, and a truncator. We optimize each module to tackle complex reasoning challenges: (1) Clue extractor firstly uses sentences containing the answer and similar ones as fine-tuned targets, aiming at extracting sufficient potential clues; (2) Re-ranker is trained to prioritize effective clues based on the real feedback from generation module, with clues capable of generating correct answer as positive samples and others as negative; (3) Truncator takes the minimum clues needed to answer the question (truncation point) as fine-tuned targets, and performs truncation on the re-ranked clues to achieve fine-grained noise filtering. Experiments on three QA datasets demonstrate that FineFilter significantly outperforms baselines in terms of performance and inference cost. Further analysis on each module shows the effectiveness of our optimizations for complex reasoning.

[Arxiv](https://arxiv.org/abs/2502.11811)