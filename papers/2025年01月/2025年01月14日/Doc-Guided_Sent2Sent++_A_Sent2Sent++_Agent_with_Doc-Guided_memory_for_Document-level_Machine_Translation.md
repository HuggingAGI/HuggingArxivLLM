# Doc-Guided Sent2Sent++：具备文档引导记忆的 Sent2Sent++ 代理，专为文档级机器翻译设计

发布时间：2025年01月14日

`Agent

理由：这篇论文主要介绍了一种名为 Doc-Guided Sent2Sent++ 的智能体，该智能体采用增量句子级强制解码策略来解决文档级机器翻译（DocMT）中的挑战。论文的核心内容围绕智能体的设计、实现及其在翻译任务中的应用，因此应归类为Agent。` `机器翻译`

> Doc-Guided Sent2Sent++: A Sent2Sent++ Agent with Doc-Guided memory for Document-level Machine Translation

# 摘要

> 人工智能领域在自然语言处理方面取得了显著进展，这主要得益于大型语言模型（LLMs）的强大能力。这些模型构成了解决长上下文依赖问题的智能体的核心，尤其是在文档级机器翻译（DocMT）中。DocMT 面临独特的挑战，质量、一致性和流畅性是评估的关键指标。现有方法如 Doc2Doc 和 Doc2Sent 要么省略句子，要么牺牲流畅性。本文提出了 Doc-Guided Sent2Sent++，这是一种采用增量句子级强制解码策略的智能体，**确保每个句子都被翻译，同时提升相邻句子的流畅性。** 我们的智能体利用 Doc-Guided Memory，仅关注摘要及其翻译，这是一种保持一致性高效的方法。通过在多种语言和领域中的广泛测试，我们证明了 Sent2Sent++ 在质量、一致性和流畅性方面优于其他方法。结果表明，我们的方法在 s-COMET、d-COMET、LTCR-$1_f$ 和文档级困惑度（d-ppl）等指标上取得了显著提升。本文的贡献包括对当前 DocMT 研究的详细分析、Sent2Sent++ 解码方法的介绍、Doc-Guided Memory 机制以及其在跨语言和跨领域中的有效性验证。

> The field of artificial intelligence has witnessed significant advancements in natural language processing, largely attributed to the capabilities of Large Language Models (LLMs). These models form the backbone of Agents designed to address long-context dependencies, particularly in Document-level Machine Translation (DocMT). DocMT presents unique challenges, with quality, consistency, and fluency being the key metrics for evaluation. Existing approaches, such as Doc2Doc and Doc2Sent, either omit sentences or compromise fluency. This paper introduces Doc-Guided Sent2Sent++, an Agent that employs an incremental sentence-level forced decoding strategy \textbf{to ensure every sentence is translated while enhancing the fluency of adjacent sentences.} Our Agent leverages a Doc-Guided Memory, focusing solely on the summary and its translation, which we find to be an efficient approach to maintaining consistency. Through extensive testing across multiple languages and domains, we demonstrate that Sent2Sent++ outperforms other methods in terms of quality, consistency, and fluency. The results indicate that, our approach has achieved significant improvements in metrics such as s-COMET, d-COMET, LTCR-$1_f$, and document-level perplexity (d-ppl). The contributions of this paper include a detailed analysis of current DocMT research, the introduction of the Sent2Sent++ decoding method, the Doc-Guided Memory mechanism, and validation of its effectiveness across languages and domains.

[Arxiv](https://arxiv.org/abs/2501.08523)