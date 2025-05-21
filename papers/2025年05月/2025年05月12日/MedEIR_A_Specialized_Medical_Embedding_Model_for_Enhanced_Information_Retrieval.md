# MedEIR：专为优化医学信息检索设计的专业嵌入模型

发布时间：2025年05月12日

`LLM应用` `信息检索`

> MedEIR: A Specialized Medical Embedding Model for Enhanced Information Retrieval

# 摘要

> 嵌入模型在检索增强生成 (RAG)、语义聚类和文本重排序等领域发挥着重要作用。然而，尽管嵌入模型的应用日益广泛，但它们仍存在诸多局限性。例如，Jina 未能准确捕获医学文档的语义内容，而 MiniLM 等模型在处理长文档时表现通常不尽如人意。领域适应型模型虽然经过专门训练，但在通用任务中往往表现欠佳，限制了它们的广泛应用。通用领域分词器常会误解医学词汇。当前嵌入模型的局限性，无论是分词精度、领域理解能力，还是处理长序列的能力，都凸显了对更灵活解决方案的需求。在本研究中，我们提出了 MedEIR，这是一种专为医疗和通用 NLP 任务联合优化的新型嵌入模型和分词器，采用基于 ALiBi 的长上下文处理技术，支持长达 8,192 个标记的序列。MedEIR 仅在 60 亿个标记上进行预训练（远少于 Jina 的预训练规模），随后在 300 万个句子对上进行微调。在 MTEB 基准测试中，MedEIR 一致超越 Jina V2 和 MiniLM，取得了 ArguAna (55.24)、NFCorpus (38.44)、MedicalQARetrieval (74.25)、SciFact (72.04) 和 TRECCOVID (79.56) 等任务的最高分。这些结果凸显了 MedEIR 作为高效嵌入模型的潜力，不仅在通用任务中表现出色，在特定领域任务中也超越了现有模型，在多个基准测试中取得了优异成绩。

> Embedding models have become essential for retrieval-augmented generation (RAG) tasks, semantic clustering, and text re-ranking. But despite their growing use, many of these come with notable limitations. For example, Jina fails to capture the semantic content of medical documents, while models such as MiniLM often perform poorly on long-form documents. Domain-adapted models, while specialized, often underperform in general-purpose tasks, reducing their overall applicability. General-domain tokenizers often misinterpret medical vocabulary. The limitations of current embedding models, whether in tokenization accuracy, domain comprehension, or handling long sequences, highlight the need for more versatile solutions. In this work, we present MedEIR, a novel embedding model and tokenizer jointly optimized for both medical and general NLP tasks, incorporating ALiBi-based long-context processing to support sequences of up to 8,192 tokens. MedEIR was pre-trained on only 6 billion tokens, significantly fewer than Jina's, followed by fine-tuning on 3 million sentence pairs. MedEIR consistently outperforms Jina V2 and MiniLM across MTEB benchmarks, achieving top scores on ArguAna (55.24), NFCorpus (38.44), MedicalQARetrieval (74.25), SciFact (72.04), and TRECCOVID (79.56). These results highlight the potential of MedEIR as a highly effective embedding model, demonstrating strong performance across both general-purpose and domain-specific tasks and outperforming existing models on multiple benchmarks.

[Arxiv](https://arxiv.org/abs/2505.13482)