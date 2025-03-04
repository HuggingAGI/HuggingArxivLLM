# 没有正确答案，正确选项不多：人类与大语言模型在多选题回答中的并行模式

发布时间：2025年03月03日

`LLM应用` `教育测验` `教育评估`

> None of the Above, Less of the Right: Parallel Patterns between Humans and LLMs on Multi-Choice Questions Answering

# 摘要

> 包含“None of the above”（NA）选项的多项选择题在教育测验领域已有大量研究，现有研究表明，这种题型更能有效评估考生的真实知识水平。然而，NA选项对大型语言模型（LLMs）评估的影响仍未得到充分探索。通过在MMLU基准测试中对28个LLMs进行系统性实验，我们研究了NA选项如何影响模型的性能和置信度校准。分析结果表明，当NA选项作为正确答案时，会导致所有模型的性能一致下降30-50%，这一现象与模型规模无关，说明LLMs缺乏在无正确选项时系统性评估并拒绝所有给定选项的元认知能力。这种性能下降表现出强烈的领域依赖性，在数学推理任务中影响较小（14.6%的性能下降），但在需要处理不确定性的任务（如商业伦理）中影响则非常显著（48.1%的性能下降）。我们的研究结果对基准测试设计具有重要启示，并引发了关于LLMs在现实世界应用中处理不确定性的能力的疑问。

> Multiple-choice exam questions with "None of the above" (NA) options have been extensively studied in educational testing, in which existing research suggests that they better assess true knowledge. However, their impact on Large Language Models (LLMs) evaluation remains underexplored. Through systematic experiments with 28 LLMs on the MMLU benchmark, we examine how NA options affect model performance and confidence calibration. Our analysis reveals that NA options, when used as the correct answer, lead to a consistent 30-50\% performance drop across models regardless of scale--suggesting that LLMs lack the meta-cognitive ability to systematically evaluate and reject all given options when none are correct. This degradation shows strong domain dependence, with minimal impact on mathematical reasoning (14.6\% drop) but severe effects on tasks requiring uncertainty handling like business ethics (48.1\% drop). Our results highlight important implications for benchmark design and raise questions about LLMs' ability to handle uncertainty in real-world applications.

[Arxiv](https://arxiv.org/abs/2503.01550)