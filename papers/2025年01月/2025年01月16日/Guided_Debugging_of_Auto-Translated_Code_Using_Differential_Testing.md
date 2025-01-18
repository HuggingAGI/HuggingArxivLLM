# 基于差分测试的自动翻译代码调试指南

发布时间：2025年01月16日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）进行代码翻译任务，并提出了一种调试工具tHinter来定位翻译错误。论文的核心是LLM在代码翻译中的应用，因此应归类为LLM应用。` `软件开发` `调试工具`

> Guided Debugging of Auto-Translated Code Using Differential Testing

# 摘要

> 大型语言模型（LLMs）在代码翻译任务中潜力巨大，但缺乏可解释性使得识别翻译错误变得复杂。本文提出tHinter，一款用于定位自动翻译代码中错误的调试工具。tHinter的核心思想是：若翻译正确，源代码与翻译后的代码应功能一致，输入相同则输出相同。因此，翻译代码中导致输出差异的行可能是错误所在。tHinter首先通过模糊测试生成多样化测试用例，全面覆盖翻译代码；随后，利用启发式算法结合覆盖信息和差异测试结果，精确定位翻译错误。该算法融合了统计数据和开发者经验。实验表明，tHinter显著提升了调试效率，减少了71%的代码审查量，并将LLM单次修复错误的成功率提高了59%。开发者普遍认为tHinter实用且高效。

> Large Language Models (LLMs) hold great promise in the task of code translation. However, the lack of explainability complicates the identification of the inevitable translation errors. In this paper, we propose tHinter, a debugging tool to locate translation errors in auto-translated code. The core idea of tHinter is that correctly translated, the source and translated code should present the same functionalities, giving the same output for the same input. Hence, lines in the translated code responsible for output differences are possibly translation errors. First, tHinter employs fuzzing to generate diverse test cases that thoroughly explore the translated code. Then, tHinter relies on a heuristic algorithm to pinpoint translation errors from coverage information and differential testing execution results of those test cases. This heuristic algorithm is designed to leverage both the statistics and the expertise of developers. Comprehensive experiments with real code show its effectiveness. It reduces 71% lines developers need to review during debugging and increases the likelihood of the LLM fixing translation errors in a single query by 59%. Developers generally consider it satisfactory and helpful.

[Arxiv](https://arxiv.org/abs/2501.09475)