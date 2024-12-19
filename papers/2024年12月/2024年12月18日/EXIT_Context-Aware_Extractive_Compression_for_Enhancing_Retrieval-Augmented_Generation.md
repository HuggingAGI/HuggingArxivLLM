# EXIT：用于提升检索增强生成效果的上下文感知提取式压缩

发布时间：2024年12月18日

`RAG`

> EXIT: Context-Aware Extractive Compression for Enhancing Retrieval-Augmented Generation

# 摘要

> 我们推出了 EXIT 这一提取式上下文压缩框架，旨在提升问答（QA）中检索增强生成（RAG）的成效与效率。当下的 RAG 系统在检索模型无法给最相关文档排序时，往往会陷入困境，致使为纳入更多上下文而牺牲了延迟和准确性。抽象压缩方法虽能大幅削减标记数量，但其逐个标记的生成过程却显著延长了端到端的延迟。反之，现有的提取方法虽降低了延迟，却依赖于独立、非自适应的句子选择，难以充分利用上下文信息。EXIT 通过对检索文档中的句子进行分类（同时保留其上下文依赖关系）来化解这些局限，达成了可并行化、具备上下文感知能力的提取，能够适应查询的复杂程度和检索质量。我们在单跳和多跳 QA 任务中的评估显示，EXIT 在 QA 准确性上始终超越现有的压缩方法，甚至优于未压缩的基线，同时还大幅缩短了推理时间、减少了标记数量。凭借对有效性和效率的双重提升，EXIT 为在 RAG 管道中开发可扩展的高品质 QA 解决方案指明了一条充满希望的道路。我们的代码可在 https://github.com/ThisIsHwang/EXIT 获取。

> We introduce EXIT, an extractive context compression framework that enhances both the effectiveness and efficiency of retrieval-augmented generation (RAG) in question answering (QA). Current RAG systems often struggle when retrieval models fail to rank the most relevant documents, leading to the inclusion of more context at the expense of latency and accuracy. While abstractive compression methods can drastically reduce token counts, their token-by-token generation process significantly increases end-to-end latency. Conversely, existing extractive methods reduce latency but rely on independent, non-adaptive sentence selection, failing to fully utilize contextual information. EXIT addresses these limitations by classifying sentences from retrieved documents - while preserving their contextual dependencies - enabling parallelizable, context-aware extraction that adapts to query complexity and retrieval quality. Our evaluations on both single-hop and multi-hop QA tasks show that EXIT consistently surpasses existing compression methods and even uncompressed baselines in QA accuracy, while also delivering substantial reductions in inference time and token count. By improving both effectiveness and efficiency, EXIT provides a promising direction for developing scalable, high-quality QA solutions in RAG pipelines. Our code is available at https://github.com/ThisIsHwang/EXIT

[Arxiv](https://arxiv.org/abs/2412.12559)