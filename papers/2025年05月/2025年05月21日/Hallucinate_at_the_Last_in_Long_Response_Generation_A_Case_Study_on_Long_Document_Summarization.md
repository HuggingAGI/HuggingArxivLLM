# 在长文本生成中延迟幻觉：以长文档摘要为例

发布时间：2025年05月21日

`LLM应用` `文本生成`

> Hallucinate at the Last in Long Response Generation: A Case Study on Long Document Summarization

# 摘要

> 大型语言模型（LLMs）在文本生成领域取得了显著进展，尤其在摘要等任务中常能生成连贯流畅的输出。然而，对原文忠实度的挑战依然存在，主要源于幻觉内容的生成。尽管已有大量研究聚焦于检测和减少这些不准确之处，但对生成文本中幻觉的位置分布，尤其是长文本中的分布，关注较少。本研究以长文档摘要为关键案例，探讨了基于LLM的长响应生成中幻觉现象的发生位置。我们专注于长上下文感知的长响应生成这一具有挑战性的场景，发现了一个一致且令人担忧的现象：幻觉内容往往在生成的长响应的后半部分过度集中。为了理解这一偏见，我们深入探讨了与长序列注意力机制和解码动态相关的潜在影响因素。此外，我们还研究了缓解这种位置性幻觉的方法，旨在特别提升长文本结尾部分的忠实度。

> Large Language Models (LLMs) have significantly advanced text generation capabilities, including tasks like summarization, often producing coherent and fluent outputs. However, faithfulness to source material remains a significant challenge due to the generation of hallucinations. While extensive research focuses on detecting and reducing these inaccuracies, less attention has been paid to the positional distribution of hallucination within generated text, particularly in long outputs. In this work, we investigate where hallucinations occur in LLM-based long response generation, using long document summarization as a key case study. Focusing on the challenging setting of long context-aware long response generation, we find a consistent and concerning phenomenon: hallucinations tend to concentrate disproportionately in the latter parts of the generated long response. To understand this bias, we explore potential contributing factors related to the dynamics of attention and decoding over long sequences. Furthermore, we investigate methods to mitigate this positional hallucination, aiming to improve faithfulness specifically in the concluding segments of long outputs.

[Arxiv](https://arxiv.org/abs/2505.15291)