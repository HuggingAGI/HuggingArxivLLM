# 分析大型语言模型在自动化漏洞注入与修复中的不稳定性

发布时间：2025年09月08日

`LLM应用` `工业与制造`

> Analyzing the Instability of Large Language Models in Automated Bug Injection and Correction

# 摘要

> 大型语言模型（LLMs）在软件工程任务中的应用日益广泛，尤其在漏洞修复与代码生成领域。然而，这些模型的输出结果常不稳定：即便输入相同，在不同时间运行也可能生成差异极大的代码。尽管文献中已对代码生成场景下的这种不稳定性有所讨论，但LLMs在漏洞修复任务中的一致性尚未得到深入评估。本研究旨在探究ChatGPT等LLM在代码漏洞修复中的不稳定程度。我们利用包含不同错误类型的代码样本，分析针对相同提示生成的多个修复建议在结构、语法及功能上的差异。此外，我们还评估了模型确定性运行时的温度设置（0、0.5和1）对不稳定性的影响。实验分析共涉及20个问题，模型在每个温度下为每个问题生成3个修复建议，从而每个问题对应9个不同输出进行比较。研究采用语法相似度和输出等效率（OER）指标，评估输出的结构一致性与功能一致性。结果显示，随着温度升高，模型输出的不稳定性和变异性显著增加，高温下尤其表现出极高的功能失效率。语法相似度分析表明，建议的修复方案在高温下结构差异显著，而在低温下则较为相似。本研究不仅为基于LLM的错误纠正系统如何在软件开发流程中更一致地应用提供了重要的方法学启示，同时也对其可靠性提出了质疑。

> The use of Large Language Models (LLMs) in software engineering tasks is growing, especially in the areas of bug fixing and code generation. Nevertheless, these models often yield unstable results; when executed at different times with the same input, they can generate radically different code. The consistency of LLMs in bug-fixing tasks has not yet been thoroughly assessed, despite the fact that this instability has typically been discussed in the literature in relation to code generation. The purpose of this study is to look into how unstable an LLM like ChatGPT is when it comes to fixing code bugs. We examine the structural, syntactic, and functional variations among several fix recommendations made in response to the same prompt using code samples with various error types. Additionally, we assess how instability is affected by the temperature settings (0, 0.5, and 1) used for the model's deterministic operation. For a total of 20 problems in the experimental analysis, the model produced three fix suggestions at each temperature value, comparing nine distinct outputs for each problem. The Syntax Similarity and Output Equivalence Rate (OER) metrics were used to assess the outputs' structural and functional consistency. The results demonstrate that the model's outputs become much more unstable and variable as the temperature rises, with high temperatures showing especially high rates of functional failure. According to syntax similarity analyses, the suggested fixes show notable structural differences at high temperatures but are fairly similar at low temperatures. The purpose of this study is to provide important methodological insights into how LLM-based error correction systems can be applied more consistently in software development processes while also casting doubt on their dependability.

[Arxiv](https://arxiv.org/abs/2509.06429)