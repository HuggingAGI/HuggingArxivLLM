# RetroLLM：让大型语言模型在生成时也能精准检索证据

发布时间：2024年12月16日

`RAG

理由：这篇论文提出了一个名为RetroLLM的框架，旨在通过将检索和生成无缝整合来解决大型语言模型（LLMs）的幻觉问题。具体来说，RetroLLM通过引入分层FM-Index约束和前瞻性受限解码策略，直接从语料库中生成细粒度的证据，从而减少检索文本块中的冗余输入标记，并优化检索和生成的联合过程。这些方法明显属于检索增强生成（RAG）的范畴，因此将这篇论文分类为RAG是合适的。` `问答系统`

> RetroLLM: Empowering Large Language Models to Retrieve Fine-grained Evidence within Generation

# 摘要

> 大型语言模型（LLMs）虽然生成能力强大，但常伴有幻觉问题。检索增强生成（RAG）通过引入外部知识提供了一种有效的解决方案，但现有方法仍存在一些不足：独立检索器的额外部署成本、检索文本块中的冗余输入标记，以及检索和生成缺乏联合优化。为此，我们提出了 	extbf{RetroLLM}，一个将检索和生成无缝整合的框架，使LLMs能够通过受限解码直接从语料库中生成细粒度的证据。此外，为了减少受限证据生成中的错误剪枝，我们引入了（1）分层FM-Index约束，在证据生成前生成语料库约束的线索，识别相关文档子集，减少无关解码空间；以及（2）前瞻性受限解码策略，通过考虑未来序列的相关性提升证据准确性。在五个开放域QA数据集上的实验表明，RetroLLM在域内和域外任务中均表现出色。代码可在url{https://github.com/sunnynexus/RetroLLM}获取。

> Large language models (LLMs) exhibit remarkable generative capabilities but often suffer from hallucinations. Retrieval-augmented generation (RAG) offers an effective solution by incorporating external knowledge, but existing methods still face several limitations: additional deployment costs of separate retrievers, redundant input tokens from retrieved text chunks, and the lack of joint optimization of retrieval and generation. To address these issues, we propose \textbf{RetroLLM}, a unified framework that integrates retrieval and generation into a single, cohesive process, enabling LLMs to directly generate fine-grained evidence from the corpus with constrained decoding. Moreover, to mitigate false pruning in the process of constrained evidence generation, we introduce (1) hierarchical FM-Index constraints, which generate corpus-constrained clues to identify a subset of relevant documents before evidence generation, reducing irrelevant decoding space; and (2) a forward-looking constrained decoding strategy, which considers the relevance of future sequences to improve evidence accuracy. Extensive experiments on five open-domain QA datasets demonstrate RetroLLM's superior performance across both in-domain and out-of-domain tasks. The code is available at url{https://github.com/sunnynexus/RetroLLM}.

[Arxiv](https://arxiv.org/abs/2412.11919)