# LLM生成的代码是否比人工编写的代码更可靠且易于维护？

发布时间：2025年08月01日

`LLM应用` `软件工程` `软件开发`

> Is LLM-Generated Code More Maintainable \& Reliable than Human-Written Code?

# 摘要

> 背景：大型语言模型（LLMs）在软件开发领域的崛起，为代码生成开辟了新的可能性。尽管这项技术被广泛应用，但LLMs生成代码在软件质量方面的表现如何，以及它们与人工编写的代码相比如何，仍然不明确。

目标：本研究旨在比较LLM生成代码与人工编写代码的内部质量属性。

方法：我们的实证研究整合了编码任务的数据集、三种LLM配置（零样本、少样本和微调），并使用SonarQube评估软件质量。数据集包含Python代码解决方案，涵盖三个难度级别：入门级、面试级和竞赛级。我们分析了关键的代码质量指标，包括可维护性和可靠性，以及修复代码问题所需的估计工作量。

结果：我们的分析表明，LLM生成的代码总体上具有更少的错误，并且修复它们所需的 effort 更少。有趣的是，微调模型减少了严重问题（如 blocker 和 critical 错误）的出现频率，并将它们转移到较低严重性类别，但降低了模型的性能。在竞赛级别的问题中，LLM解决方案有时会引入人工编写代码中不存在的结构性问题。

结论：我们的研究结果为LLM生成代码的质量提供了有价值的见解；然而，在更复杂的场景中引入关键问题，突显了对LLM解决方案进行系统评估和验证的必要性。我们的工作深化了对LLMs在代码生成方面的优势和局限性的理解。

> Background: The rise of Large Language Models (LLMs) in software development has opened new possibilities for code generation. Despite the widespread use of this technology, it remains unclear how well LLMs generate code solutions in terms of software quality and how they compare to human-written code. Aims: This study compares the internal quality attributes of LLM-generated and human-written code. Method: Our empirical study integrates datasets of coding tasks, three LLM configurations (zero-shot, few-shot, and fine-tuning), and SonarQube to assess software quality. The dataset comprises Python code solutions across three difficulty levels: introductory, interview, and competition. We analyzed key code quality metrics, including maintainability and reliability, and the estimated effort required to resolve code issues. Results: Our analysis shows that LLM-generated code has fewer bugs and requires less effort to fix them overall. Interestingly, fine-tuned models reduced the prevalence of high-severity issues, such as blocker and critical bugs, and shifted them to lower-severity categories, but decreased the model's performance. In competition-level problems, the LLM solutions sometimes introduce structural issues that are not present in human-written code. Conclusion: Our findings provide valuable insights into the quality of LLM-generated code; however, the introduction of critical issues in more complex scenarios highlights the need for a systematic evaluation and validation of LLM solutions. Our work deepens the understanding of the strengths and limitations of LLMs for code generation.

[Arxiv](https://arxiv.org/abs/2508.00700)