# 大型语言模型能否正确解读存在错误的方程？

发布时间：2025年05月16日

`LLM应用` `计算机科学`

> Can Large Language Models Correctly Interpret Equations with Errors?

# 摘要

> 本文研究了大型语言模型在将澳大利亚物理奥赛学生书写的方程转换为标准格式方面的潜力。我们利用大型语言模型从学生的回答中提取方程，并将其转换为计算机代数系统可用的标准格式。然而，具有超过140亿参数的模型未能在规定时间内完成任务。在资源受限的情况下，没有开源模型能够达到理想的准确率以完成考试评分。为提升准确率，我们采用了LLM-modulo和共识框架，并报告了相关结果。未来研究可以通过将任务分解为更小的组件后再进行模型解析，从而进一步提高性能。

> This paper explores the potential of Large Language Models to accurately translate student written equations from the Australian Physics Olympiads into a standard format. Large Language Models were used to extract equations from student responses and convert these into a standardised format for a computer algebra system. Models with more than fourteen billion parameters were unable to complete the task in the required timeframe. No open source model was able to achieve the desired level of accuracy given resource constraints available for marking the exam. To improve the accuracy, we implement LLM-modulo and consensus frameworks and report on the results. Future work to improve performance could involve breaking the task into smaller components before parsing to the models.

[Arxiv](https://arxiv.org/abs/2505.10966)