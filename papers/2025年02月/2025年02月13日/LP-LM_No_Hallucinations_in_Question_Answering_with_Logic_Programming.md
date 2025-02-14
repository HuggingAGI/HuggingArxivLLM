# LP-LM：问答无幻觉，逻辑编程来助力

发布时间：2025年02月13日

`LLM应用` `问答系统`

> LP-LM: No Hallucinations in Question Answering with Logic Programming

# 摘要

> 大型语言模型（LLMs）能够生成类人化的用户查询响应。然而，LLMs存在固有局限性，尤其是因为它们容易产生不真实的信息。本文介绍了一种名为LP-LM的系统，它通过在Prolog中进行语义解析，将答案接地在知识库（KB）中的已知事实，并始终生成可靠的回答。

LP-LM通过Prolog确定子句文法（DCG）解析，为输入问题生成一个最可能的句法分析树及其对应的Prolog项。随后，该系统将此项与表示为Prolog项的知识库中的自然语言句子进行匹配，以回答问题。通过利用DCG和表驱动技术，LP-LM在输入句子规模足够大且语法规则充分时，能够在与输入句子规模成线性关系的时间内运行。通过与当前知名LLMs在准确性上的对比实验，我们发现，LLMs即使在面对简单问题时也会产生不真实的信息，而LP-LM则不会如此。


> Large language models (LLMs) are able to generate human-like responses to user queries. However, LLMs exhibit inherent limitations, especially because they hallucinate. This paper introduces LP-LM, a system that grounds answers to questions in known facts contained in a knowledge base (KB), facilitated through semantic parsing in Prolog, and always produces answers that are reliable.
  LP-LM generates a most probable constituency parse tree along with a corresponding Prolog term for an input question via Prolog definite clause grammar (DCG) parsing. The term is then executed against a KB of natural language sentences also represented as Prolog terms for question answering. By leveraging DCG and tabling, LP-LM runs in linear time in the size of input sentences for sufficiently many grammar rules. Performing experiments comparing LP-LM with current well-known LLMs in accuracy, we show that LLMs hallucinate on even simple questions, unlike LP-LM.

[Arxiv](https://arxiv.org/abs/2502.09212)