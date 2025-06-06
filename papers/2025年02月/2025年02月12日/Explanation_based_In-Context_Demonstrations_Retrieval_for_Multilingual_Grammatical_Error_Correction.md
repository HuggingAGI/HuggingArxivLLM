# Explanation based In-Context Demonstrations Retrieval for Multilingual Grammatical Error Correction 基于解释的上下文示例检索方法针对多语言语法错误纠正

发布时间：2025年02月12日

`LLM应用

理由：这篇论文探讨了如何将大型语言模型（LLMs）应用于语法错误修正（GEC）任务，提出了基于自然语言语法错误解释（GEE）的创新检索方法。该研究专注于LLMs在实际任务中的应用，属于LLM应用类别。` `语言技术`

> Explanation based In-Context Demonstrations Retrieval for Multilingual Grammatical Error Correction

# 摘要

> 语法错误修正（GEC）致力于修正自然语言文本中的语法、拼写和语义错误。随着大型语言模型（LLMs）的崛起，直接文本生成逐渐成为GEC领域的焦点，而少量样本上下文学习则提供了一种经济高效的解决方案。然而，选择有效的上下文示例仍然面临挑战，因为文本相似性并不必然对应相似的语法错误模式。本文提出了一种基于自然语言语法错误解释（GEE）的创新检索方法来解决这一难题。我们的方法通过将测试输入的GEE与预构建数据库样本的GEE进行匹配，检索出合适的少量样本演示，其中错误样本的解释由LLMs生成。我们针对开源和闭源的主要LLMs进行了多语言GEC少量样本实验。实验结果覆盖五种语言，证实了与现有语义和BM25基线方法相比，我们的方法无需额外训练或语言适配，展现出显著优势。这也表明，关键在于匹配错误模式以选择示例。

> Grammatical error correction (GEC) aims to correct grammatical, spelling, and semantic errors in natural language text. With the growing of large language models (LLMs), direct text generation has gradually become the focus of the GEC methods, and few-shot in-context learning presents a cost-effective solution. However, selecting effective in-context examples remains challenging, as the similarity between input texts does not necessarily correspond to similar grammatical error patterns. In this paper, we propose a novel retrieval method based on natural language grammatical error explanations (GEE) to address this issue. Our method retrieves suitable few-shot demonstrations by matching the GEE of the test input with that of pre-constructed database samples, where explanations for erroneous samples are generated by LLMs. We conducted multilingual GEC few-shot experiments on both major open-source and closed-source LLMs. Experiments across five languages show that our method outperforms existing semantic and BM25-based retrieval techniques, without requiring additional training or language adaptation. This also suggests that matching error patterns is key to selecting examples.

[Arxiv](https://arxiv.org/abs/2502.08507)