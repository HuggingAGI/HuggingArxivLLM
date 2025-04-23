# 大型语言模型代码异味检测基准测试：OpenAI GPT-4.0 与 DeepSeek-V3 对比

发布时间：2025年04月22日

`LLM应用` `软件工程` `代码分析`

> Benchmarking LLM for Code Smells Detection: OpenAI GPT-4.0 vs DeepSeek-V3

# 摘要

> 选择最适合代码异味检测的大型语言模型是一项复杂而具有挑战性的任务。本研究提出了一种结构化的 methodology 和 evaluation matrix 来解决这一问题，利用了一个经过精心整理、标注了已知异味的代码样本数据集。该数据集涵盖了 Java、Python、JavaScript 和 C++ 四种主流编程语言，支持跨语言比较。我们对 OpenAI GPT 4.0 和 DeepSeek-V3 两款最先进的 LLM 进行基准测试，采用精确率、召回率和 F1 值作为评估指标。我们的分析涵盖三个层面：整体性能、类别级别性能以及具体代码异味类型的性能。此外，我们还探讨了成本效益，通过比较 GPT 4.0 的基于令牌的检测方法与 DeepSeek V3 采用的模式匹配技术。研究还包括与传统静态分析工具（如 SonarQube）相关的成本分析。研究结果为从业者提供了有价值的指导，帮助他们选择一个高效且经济的解决方案，用于自动化的代码异味检测。

> Determining the most effective Large Language Model for code smell detection presents a complex challenge. This study introduces a structured methodology and evaluation matrix to tackle this issue, leveraging a curated dataset of code samples consistently annotated with known smells. The dataset spans four prominent programming languages Java, Python, JavaScript, and C++; allowing for cross language comparison. We benchmark two state of the art LLMs, OpenAI GPT 4.0 and DeepSeek-V3, using precision, recall, and F1 score as evaluation metrics. Our analysis covers three levels of detail: overall performance, category level performance, and individual code smell type performance. Additionally, we explore cost effectiveness by comparing the token based detection approach of GPT 4.0 with the pattern-matching techniques employed by DeepSeek V3. The study also includes a cost analysis relative to traditional static analysis tools such as SonarQube. The findings offer valuable guidance for practitioners in selecting an efficient, cost effective solution for automated code smell detection

[Arxiv](https://arxiv.org/abs/2504.16027)