# CS-Sum：一个多语言对话摘要基准测试，揭示大型语言模型的局限性

发布时间：2025年05月19日

`LLM应用`

> CS-Sum: A Benchmark for Code-Switching Dialogue Summarization and the Limits of Large Language Models

# 摘要

> 代码切换（CS）对大型语言模型（LLMs）提出了重大挑战，但其可理解性研究仍显不足。我们推出CS-Sum，通过代码切换对话到英文的摘要任务，首次全面评估LLMs的代码切换理解能力。CS-Sum涵盖中英（EN-ZH）、泰米尔英（EN-TA）和马来英（EN-MS）三种语言对，每种语言对包含900-1300个高质量人工标注对话。我们对十种LLMs（包括开源与闭源模型）进行了多维度评估，涵盖少样本学习、翻译-摘要以及基于合成数据的微调（LoRA、QLoRA）等方法。研究发现，尽管自动化评估指标表现优异，LLMs在处理代码切换内容时仍会出现改变对话原意的细微错误。我们总结了LLMs在处理代码切换输入时最常见的三种错误类型。值得注意的是，不同代码切换语言对和不同LLMs的错误率存在显著差异，某些模型在特定语言对上表现出更高的错误频率，这表明在代码切换数据上进行专门训练的重要性。

> Code-switching (CS) poses a significant challenge for Large Language Models (LLMs), yet its comprehensibility remains underexplored in LLMs. We introduce CS-Sum, to evaluate the comprehensibility of CS by the LLMs through CS dialogue to English summarization. CS-Sum is the first benchmark for CS dialogue summarization across Mandarin-English (EN-ZH), Tamil-English (EN-TA), and Malay-English (EN-MS), with 900-1300 human-annotated dialogues per language pair. Evaluating ten LLMs, including open and closed-source models, we analyze performance across few-shot, translate-summarize, and fine-tuning (LoRA, QLoRA on synthetic data) approaches. Our findings show that though the scores on automated metrics are high, LLMs make subtle mistakes that alter the complete meaning of the dialogue. To this end, we introduce 3 most common type of errors that LLMs make when handling CS input. Error rates vary across CS pairs and LLMs, with some LLMs showing more frequent errors on certain language pairs, underscoring the need for specialized training on code-switched data.

[Arxiv](https://arxiv.org/abs/2505.13559)