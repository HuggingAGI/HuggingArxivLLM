# DS-Bench：数据科学代码生成的真实基准测试

发布时间：2025年05月21日

`LLM应用

摘要中提到的DS-bench是一个基准测试平台，用于评估大型语言模型在数据科学代码生成任务中的表现。这属于对LLM的实际应用进行评估和基准测试，因此归类为LLM应用。` `数据科学`

> DS-Bench: A Realistic Benchmark for Data Science Code Generation

# 摘要

> 我们很高兴推出DS-bench，一个全新的基准测试平台，专注于评估大型语言模型（LLMs）在复杂现实数据科学代码生成任务中的表现。DS-bench精心挑选了1,000个问题，这些问题均来源于GitHub上广泛使用的十种Python数据科学库中的实际案例。与现有最先进基准DS-1000相比，DS-bench在多个维度上实现了显著提升：更具挑战性和代表性的测试环境、更长的代码解决方案、更全面的数据科学库覆盖、更清晰且结构更合理的问题描述，以及更强大的测试套件支持。为构建DS-bench，我们开发了一套完整的流水线，涵盖了任务范围选择、代码构建、测试用例生成和问题描述合成等关键环节，并辅以严格的人工校对，确保评估的准确性和可靠性。实验结果表明，DS-bench展现出稳健的缩放行为：模型规模越大，性能越优，这充分验证了其在区分模型能力方面的有效性。在我们的测试中，GPT-4o表现最佳，通过率@1达到0.202，这表明当前LLMs在现实数据科学代码生成任务中仍有巨大的提升空间。我们坚信，DS-bench将成为推进LLM数据科学编程研究的重要且可信的基准平台。

> We introduce DS-bench, a new benchmark designed to evaluate large language models (LLMs) on complicated and realistic data science code generation tasks. DS-bench consists of 1,000 carefully constructed problems sourced from realistic problems from GitHub across ten widely used Python data science libraries. Compared to the current state-of-the-art benchmark DS-1000, DS-bench offers a more challenging and representative testbed, longer code solutions, more comprehensive data science libraries, clearer and better structured problem descriptions, and stronger test suites. To construct the DS-bench, we develop a robust pipeline that combines task scope selection, code construction, test case generation, and problem description synthesis. The process is paired with rigorous manual editing to ensure alignment and enhance evaluation reliability. Experimental result shows that DS-bench exhibits robust scaling behavior, where larger models systematically outperform smaller ones, validating its ability to distinguish model capabilities. The best LLM we test, GPT-4o, has a pass@1 of 0.202, indicating that LLMs still have a large room to improve for realistic data science code generation tasks. We believe DS-bench will serve as a rigorous and trustworthy foundation for advancing LLM-based data science programming.

[Arxiv](https://arxiv.org/abs/2505.15621)