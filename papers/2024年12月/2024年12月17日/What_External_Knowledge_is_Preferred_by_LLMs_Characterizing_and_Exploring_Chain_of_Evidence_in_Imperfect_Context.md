# LLMs 更青睐何种外部知识？在不完美的情境中对证据链进行刻画与探索

发布时间：2024年12月17日

`LLM应用` `问答系统`

> What External Knowledge is Preferred by LLMs? Characterizing and Exploring Chain of Evidence in Imperfect Context

# 摘要

> 将外部知识融入大型语言模型（LLMs）已成为缓解LLMs中知识过时和幻觉问题的颇具前景的手段。然而，外部知识通常并不完美。除了有用的知识，外部知识在相关语境中还充斥着大量不相关或错误的信息，这可能会降低LLM回答的可靠性。本文聚焦于LLMs在处理多跳问答时于不完美语境下所偏好的外部知识。受刑事诉讼法中的证据链（CoE）启发，我们指出LLMs所偏好的知识应同时具备与问题的相关性以及知识片段之间的相互支持。据此，我们提出了一种自动的CoE判别方法，并从有效性、忠实性、鲁棒性以及在一个基础的检索增强生成（RAG）案例中CoE的可用性来探究LLMs的偏好。对五个LLMs的评估显示，CoE通过更精准的生成、更强的答案忠实度、更出色的抗知识冲突鲁棒性以及在热门的RAG案例中更优的性能来增强LLMs。

> Incorporating external knowledge into large language models (LLMs) has emerged as a promising approach to mitigate outdated knowledge and hallucination in LLMs. However, external knowledge is often imperfect. In addition to useful knowledge, external knowledge is rich in irrelevant or misinformation in the context that can impair the reliability of LLM responses. This paper focuses on LLMs' preferred external knowledge in imperfect contexts when handling multi-hop QA. Inspired by criminal procedural law's Chain of Evidence (CoE), we characterize that knowledge preferred by LLMs should maintain both relevance to the question and mutual support among knowledge pieces. Accordingly, we propose an automated CoE discrimination approach and explore LLMs' preferences from their effectiveness, faithfulness and robustness, as well as CoE's usability in a naive Retrieval-Augmented Generation (RAG) case. The evaluation on five LLMs reveals that CoE enhances LLMs through more accurate generation, stronger answer faithfulness, better robustness against knowledge conflict, and improved performance in a popular RAG case.

[Arxiv](https://arxiv.org/abs/2412.12632)