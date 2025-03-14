# 基于源的多轮对话助力大型语言模型实现文档翻译

发布时间：2025年03月13日

`LLM应用` `机器翻译`

> Source-primed Multi-turn Conversation Helps Large Language Models Translate Documents

# 摘要

> 大型语言模型 (LLMs) 使简单易行的文档级机器翻译成为可能，但遗漏错误等问题仍待解决。本文提出了一种基于多轮对话的文档级机器翻译方法，通过充分利用先前的上下文来提升翻译质量。具体来说，该方法将文档分解为多个段落，并在保持前后文连贯性的基础上进行迭代翻译。这种方法无需额外训练，同时能够复用之前的 KV 缓存，从而有效降低计算成本。此外，我们还提出了一种“源文本预加载”技术，即在多轮翻译开始前先加载整个源文档。实验结果表明，在多个自动评估指标下，该多轮方法在代表性 LLM 中的表现优于单轮翻译整个文档和独立翻译每个段落，为基于 LLM 的文档级翻译树立了新的基准。


> LLMs have paved the way for truly simple document-level machine translation, but challenges such as omission errors remain. In this paper, we study a simple method for handling document-level machine translation, by leveraging previous contexts in a multi-turn conversational manner. Specifically, by decomposing documents into segments and iteratively translating them while maintaining previous turns, this method ensures coherent translations without additional training, and can fully re-use the KV cache of previous turns thus minimizing computational overhead. We further propose a `source-primed' method that first provides the whole source document before multi-turn translation. We empirically show this multi-turn method outperforms both translating entire documents in a single turn and translating each segment independently according to multiple automatic metrics in representative LLMs, establishing a strong baseline for document-level translation using LLMs.

[Arxiv](https://arxiv.org/abs/2503.10494)