# # 基于压缩文档表示的重排序方法

发布时间：2025年05月21日

`RAG` `信息检索`

> Reranking with Compressed Document Representation

# 摘要

> 重排序是对第一阶段检索结果的优化过程，通常被认为在计算上非常昂贵，尤其是在使用大型语言模型时。我们借鉴了文档压缩技术（用于RAG）的最新进展，通过将文档压缩为固定大小的嵌入表示来减少输入规模。然后，我们通过蒸馏方法教导重排序器使用这些压缩后的输入。尽管基于一个十亿规模的模型，但我们的重排序器在使用这种压缩输入的情况下，无论是在有效性还是效率上，都能与更小的重排序器相抗衡，尤其是在处理长文档时。考虑到文本压缩器仍处于早期开发阶段，我们认为这一方法具有很大的潜力。

> Reranking, the process of refining the output of a first-stage retriever, is often considered computationally expensive, especially with Large Language Models. Borrowing from recent advances in document compression for RAG, we reduce the input size by compressing documents into fixed-size embedding representations. We then teach a reranker to use compressed inputs by distillation. Although based on a billion-size model, our trained reranker using this compressed input can challenge smaller rerankers in terms of both effectiveness and efficiency, especially for long documents. Given that text compressors are still in their early development stages, we view this approach as promising.

[Arxiv](https://arxiv.org/abs/2505.15394)