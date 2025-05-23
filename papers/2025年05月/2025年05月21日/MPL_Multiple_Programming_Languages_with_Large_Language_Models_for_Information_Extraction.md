# 基于大型语言模型的多编程语言信息抽取方法：MPL

发布时间：2025年05月21日

`LLM应用` `软件工程`

> MPL: Multiple Programming Languages with Large Language Models for Information Extraction

# 摘要

> 近期，信息抽取（IE）研究聚焦于通过代码风格的输入来优化结构化输出生成。这一方法的灵感源于编程语言（PLs）相较于自然语言（NLs）更天然的结构优势，使其成为IE任务的理想选择。然而，现有研究多集中于Python的代码风格模拟，忽视了其他广泛使用的PLs（如C++和Java）在监督微调（SFT）阶段的潜力。为此，我们提出了	extbf{M}ultiple 	extbf{P}rogramming 	extbf{L}anguages与大型语言模型结合用于信息抽取（简称	extbf{MPL}），一个探索在SFT阶段融合不同PLs潜力的全新框架。同时，我们引入了带虚拟运行的	exttt{function-prompt}，以更高效地模拟代码风格的输入。在多个数据集上的实验结果验证了MPL的有效性。此外，我们进行了全面的实验分析，并已开源代码以支持未来研究。

> Recent research in information extraction (IE) focuses on utilizing code-style inputs to enhance structured output generation. The intuition behind this is that the programming languages (PLs) inherently exhibit greater structural organization than natural languages (NLs). This structural advantage makes PLs particularly suited for IE tasks. Nevertheless, existing research primarily focuses on Python for code-style simulation, overlooking the potential of other widely-used PLs (e.g., C++ and Java) during the supervised fine-tuning (SFT) phase. In this research, we propose \textbf{M}ultiple \textbf{P}rogramming \textbf{L}anguages with large language models for information extraction (abbreviated as \textbf{MPL}), a novel framework that explores the potential of incorporating different PLs in the SFT phase. Additionally, we introduce \texttt{function-prompt} with virtual running to simulate code-style inputs more effectively and efficiently. Experimental results on a wide range of datasets demonstrate the effectiveness of MPL. Furthermore, we conduct extensive experiments to provide a comprehensive analysis. We have released our code for future research.

[Arxiv](https://arxiv.org/abs/2505.16107)