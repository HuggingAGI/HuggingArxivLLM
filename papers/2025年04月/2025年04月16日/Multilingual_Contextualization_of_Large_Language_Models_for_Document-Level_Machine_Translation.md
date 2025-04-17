# 大型语言模型的多语言上下文化及其在文档级机器翻译中的应用

发布时间：2025年04月16日

`LLM应用` `机器翻译`

> Multilingual Contextualization of Large Language Models for Document-Level Machine Translation

# 摘要

> 大型语言模型（LLMs）在句子级机器翻译中表现优异，但在文档级翻译中仍面临挑战，尤其是在处理跨句子和段落的长程依赖关系和语篇现象方面。针对这一问题，我们提出了一种通过在高质量文档级数据上进行针对性微调来提升LLM支持的长文档翻译性能的方法，并整理和引入了名为DocBlocks的数据集。我们的方法支持多种翻译范式，包括直接文档到文档和分块级翻译，通过结合使用上下文和不使用上下文的指令进行集成。这使模型能够更好地捕捉跨句子的依赖关系，同时保持强大的句子级翻译性能。实验结果表明，整合多种翻译范式相较于传统的提示和基于代理的方法，能显著提升文档级翻译质量和推理速度。

> Large language models (LLMs) have demonstrated strong performance in sentence-level machine translation, but scaling to document-level translation remains challenging, particularly in modeling long-range dependencies and discourse phenomena across sentences and paragraphs. In this work, we propose a method to improve LLM-based long-document translation through targeted fine-tuning on high-quality document-level data, which we curate and introduce as DocBlocks. Our approach supports multiple translation paradigms, including direct document-to-document and chunk-level translation, by integrating instructions both with and without surrounding context. This enables models to better capture cross-sentence dependencies while maintaining strong sentence-level translation performance. Experimental results show that incorporating multiple translation paradigms improves document-level translation quality and inference speed compared to prompting and agent-based methods.

[Arxiv](https://arxiv.org/abs/2504.12140)