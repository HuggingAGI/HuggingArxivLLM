# 量子-RAG 与 PunGPT2：助力低资源语言生成与检索，推动旁遮普语发展

发布时间：2025年08月03日

`RAG` `资源匮乏语言`

> Quantum-RAG and PunGPT2: Advancing Low-Resource Language Generation and Retrieval for the Punjabi Language

# 摘要

> 尽管大型语言模型（LLMs）发展迅速，资源匮乏语言却仍被排除在自然语言处理领域之外。我们推出首个完全开源的旁遮普语大型语言模型套件 PunGPT2，基于涵盖文学、宗教文本、新闻和社会讨论的35GB多领域多样化语料库从零开始训练。与之前的多语言方法不同，PunGPT2 通过基于字节配对编码优化的分词器和语言对齐的预训练目标，捕捉了旁遮普语独特的丰富句法和形态特征。

为了提升事实依据和领域召回率，我们引入了 Pun-RAG，一个结合 PunGPT2 和基于精选旁遮普语知识库的密集 FAISS 检索器的增强生成框架。我们进一步开发了 Pun-Instruct，一个使用 QLoRA 的参数高效指令微调变体，实现了强大的零样本和指令遵循性能，同时显著降低了计算需求。

作为关键创新，我们提出了 Quantum-RAG，一种融合稀疏（BM25）和密集方法并结合量子启发语义匹配的新型混合检索系统。通过使用基于幅度的嵌入编码查询，并借助量子核相似性进行检索，Quantum-RAG 实现了上下文相关性的提升，同时仅带来极小的内存开销，标志着量子表示在资源匮乏语言生成中的首次实用整合。我们的模型在困惑度、事实性和流利性方面显著超越了强大的多语言基线（mBERT、mT5、MuRIL）。这项工作为扩展 LLM 能力到代表性不足的语言提供了一个可扩展且可重复的蓝图，并在资源匮乏的 NLP 中开创了量子感知检索的先河。

> Despite the rapid advancement of large language models (LLMs), low-resource languages remain largely excluded from the NLP landscape. We present PunGPT2, the first fully open-source suite of Punjabi large language models, trained from scratch on a 35GB domain-diverse corpus encompassing literature, religious texts, news, and social discourse. Unlike prior multilingual approaches, PunGPT2 captures rich syntactic and morphological features unique to Punjabi through a tokenizer optimised with byte pair encoding and linguistically aligned pretraining objectives. To improve factual grounding and domain recall, we introduce Pun-RAG, a retrieval-augmented generation framework combining PunGPT2 with a dense FAISS retriever over a curated Punjabi knowledge base. We further develop Pun-Instruct, a parameter-efficient, instruction-tuned variant using QLoRA, enabling robust zero-shot and instruction-following performance with significantly reduced compute needs.
  As a key innovation, we propose Quantum-RAG, a novel hybrid retrieval system that fuses sparse (BM25) and dense methods with quantum-inspired semantic matching. By encoding queries using amplitude-based embeddings and retrieving via quantum kernel similarity, Quantum-RAG achieves improved contextual relevance with minimal memory overhead marking the first practical integration of quantum representations in low-resource language generation. Our models significantly outperform strong multilingual baselines (mBERT, mT5, MuRIL) in perplexity, factuality, and fluency. This work provides a scalable, reproducible blueprint for extending LLM capabilities to underrepresented languages and pioneers quantum-aware retrieval in low-resource NLP

[Arxiv](https://arxiv.org/abs/2508.01918)