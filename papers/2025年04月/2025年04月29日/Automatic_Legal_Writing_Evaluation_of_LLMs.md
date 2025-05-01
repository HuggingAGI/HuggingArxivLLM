# 大型语言模型的自动法律写作评估

发布时间：2025年04月29日

`LLM应用`

> Automatic Legal Writing Evaluation of LLMs

# 摘要

> 尽管大型语言模型取得了显著进展，但用于评估法律写作的基准仍然稀缺。这主要源于法律写作领域开放性回答的复杂性。在特定领域任务中评估语言模型的关键挑战在于找到公开的、经常更新的且包含全面评估指南的测试数据集。巴西律师资格考试恰好满足这些要求。

我们引入了oab-bench，这是一个包含来自 recent editions of the exam 的七个法律领域的105个问题的基准。该基准不仅包含全面的评估指南，还包含了人类考官使用的参考材料，以确保评分的一致性。

我们评估了四个 LLM 在 oab-bench 上的表现。结果显示，Claude-3.5 Sonnet 以平均 7.93 分（满分10分）取得了最佳成绩，成功通过了所有21门考试。此外，我们还研究了 LLM 是否可以作为可靠的自动评分系统来评估法律写作。

实验结果表明，像 OpenAI 的 o1 这样的前沿模型在评估通过考试时与人工评分具有很强的相关性。尽管法律写作评估本质上具有主观性，但这一发现表明它们有潜力成为可靠的自动评估工具。

包含问题、评估指南、模型生成的回答及其相应的自动评估的源代码和基准已公开发布。

> Despite the recent advances in Large Language Models, benchmarks for evaluating legal writing remain scarce due to the inherent complexity of assessing open-ended responses in this domain. One of the key challenges in evaluating language models on domain-specific tasks is finding test datasets that are public, frequently updated, and contain comprehensive evaluation guidelines. The Brazilian Bar Examination meets these requirements. We introduce oab-bench, a benchmark comprising 105 questions across seven areas of law from recent editions of the exam. The benchmark includes comprehensive evaluation guidelines and reference materials used by human examiners to ensure consistent grading. We evaluate the performance of four LLMs on oab-bench, finding that Claude-3.5 Sonnet achieves the best results with an average score of 7.93 out of 10, passing all 21 exams. We also investigated whether LLMs can serve as reliable automated judges for evaluating legal writing. Our experiments show that frontier models like OpenAI's o1 achieve a strong correlation with human scores when evaluating approved exams, suggesting their potential as reliable automated evaluators despite the inherently subjective nature of legal writing assessment. The source code and the benchmark -- containing questions, evaluation guidelines, model-generated responses, and their respective automated evaluations -- are publicly available.

[Arxiv](https://arxiv.org/abs/2504.21202)