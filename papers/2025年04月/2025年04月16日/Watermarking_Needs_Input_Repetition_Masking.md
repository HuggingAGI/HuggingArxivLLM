# # 水印技术：输入重复掩码不可或缺

发布时间：2025年04月16日

`LLM应用

理由：这篇论文探讨了大型语言模型生成文本的检测和水印技术，属于应用层面的研究，旨在解决生成文本识别的实际问题。` `内容安全` `信息真实性`

> Watermarking Needs Input Repetition Masking

# 摘要

> 近期，大型语言模型（LLMs）的快速发展引发了担忧，尤其是在传播虚假信息方面的潜在滥用。为此，两种对策应运而生：基于机器学习的检测器用于预测文本是否为合成，以及通过LLM水印技术在生成文本中 subtlely 标记以实现识别和归属。同时，人类在与对话伙伴交流时，会从语法和词汇层面调整语言。这意味着人类或未标记的LLMs可能无意中模仿LLM生成文本的特性，导致对策不可靠。本研究旨在探讨这种对话适应现象的发生程度。我们将其概念化为【数学公式】，并证明人类和LLMs最终都会进行模仿，甚至在看似不可能的场景中模仿水印信号。这一发现挑战了当前的学术假设，表明为了实现长期可靠的水印技术，误报率需要显著降低，同时应采用更长的单词序列作为水印机制的种子。

> Recent advancements in Large Language Models (LLMs) raised concerns over potential misuse, such as for spreading misinformation. In response two counter measures emerged: machine learning-based detectors that predict if text is synthetic, and LLM watermarking, which subtly marks generated text for identification and attribution. Meanwhile, humans are known to adjust language to their conversational partners both syntactically and lexically. By implication, it is possible that humans or unwatermarked LLMs could unintentionally mimic properties of LLM generated text, making counter measures unreliable. In this work we investigate the extent to which such conversational adaptation happens. We call the concept $\textit{mimicry}$ and demonstrate that both humans and LLMs end up mimicking, including the watermarking signal even in seemingly improbable settings. This challenges current academic assumptions and suggests that for long-term watermarking to be reliable, the likelihood of false positives needs to be significantly lower, while longer word sequences should be used for seeding watermarking mechanisms.

[Arxiv](https://arxiv.org/abs/2504.12229)