# 混合方法用于监管文本的信息检索与答案生成

发布时间：2025年02月23日

`LLM应用

摘要中提到了使用大型语言模型（LLMs）通过检索增强生成（RAG）框架来生成回答，这属于LLM的应用。尽管RAG是其中的一部分，但整体论文更侧重于LLM在合规任务中的应用，因此归类为LLM应用。` `信息检索`

> A Hybrid Approach to Information Retrieval and Answer Generation for Regulatory Texts

# 摘要

> 法规文本冗长复杂，为支持合规任务的信息检索系统带来巨大挑战。本文提出了一种结合词汇与语义搜索技术的混合信息检索系统，旨在从大规模法规文本库中提取相关信息。该系统巧妙融合了微调后的句子转换模型与传统BM25算法，兼顾语义精度与词汇覆盖。通过检索增强生成（RAG）框架，系统利用大型语言模型（LLMs）对检索到的段落进行合成，以生成准确且全面的回答。实验结果表明，该混合系统在Recall@10和MAP@10指标上显著优于单纯采用词汇或语义方法的系统。我们公开分享微调模型和方法论，旨在推动合规驱动应用中稳健自然语言处理工具的发展，特别是在监管领域。

> Regulatory texts are inherently long and complex, presenting significant challenges for information retrieval systems in supporting regulatory officers with compliance tasks. This paper introduces a hybrid information retrieval system that combines lexical and semantic search techniques to extract relevant information from large regulatory corpora. The system integrates a fine-tuned sentence transformer model with the traditional BM25 algorithm to achieve both semantic precision and lexical coverage. To generate accurate and comprehensive responses, retrieved passages are synthesized using Large Language Models (LLMs) within a Retrieval Augmented Generation (RAG) framework. Experimental results demonstrate that the hybrid system significantly outperforms standalone lexical and semantic approaches, with notable improvements in Recall@10 and MAP@10. By openly sharing our fine-tuned model and methodology, we aim to advance the development of robust natural language processing tools for compliance-driven applications in regulatory domains.

[Arxiv](https://arxiv.org/abs/2502.16767)