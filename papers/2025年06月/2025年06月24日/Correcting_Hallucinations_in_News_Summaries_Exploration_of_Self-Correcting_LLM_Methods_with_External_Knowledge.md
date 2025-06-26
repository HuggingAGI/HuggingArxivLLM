# 新闻摘要中的幻觉校正：结合外部知识研究自我校正的大语言模型方法

发布时间：2025年06月24日

`LLM应用`

> Correcting Hallucinations in News Summaries: Exploration of Self-Correcting LLM Methods with External Knowledge

# 摘要

> 大型语言模型（LLMs）虽然擅长生成连贯文本，但“幻觉问题”一直是其痛点——即生成事实不准确的陈述。在众多解决幻觉问题的方法中，自我纠正方法尤为值得关注。这些方法通过利用LLMs的多轮对话特性，生成验证问题，要求提供更多证据，并结合内部或外部知识回答这些问题，进而不断优化原始回答。尽管这些方法在百科全书式文本生成中已有探索，但在新闻摘要等领域的应用却相对较少。本研究将两种最新的自我纠正系统应用于修正幻觉生成的新闻摘要，并借助三个搜索引擎提供的证据进行分析，揭示了搜索结果片段和少量示例提示的实用价值，同时发现G-Eval评估与人工评价的高度一致性。

> While large language models (LLMs) have shown remarkable capabilities to generate coherent text, they suffer from the issue of hallucinations -- factually inaccurate statements. Among numerous approaches to tackle hallucinations, especially promising are the self-correcting methods. They leverage the multi-turn nature of LLMs to iteratively generate verification questions inquiring additional evidence, answer them with internal or external knowledge, and use that to refine the original response with the new corrections. These methods have been explored for encyclopedic generation, but less so for domains like news summarization. In this work, we investigate two state-of-the-art self-correcting systems by applying them to correct hallucinated summaries using evidence from three search engines. We analyze the results and provide insights into systems' performance, revealing interesting practical findings on the benefits of search engine snippets and few-shot prompts, as well as high alignment of G-Eval and human evaluation.

[Arxiv](https://arxiv.org/abs/2506.19607)