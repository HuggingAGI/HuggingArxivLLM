# # 大型语言模型在识别与修复测试异味中的效能评估：实证研究
大型语言模型在识别与修复测试异味中的效能评估：实证研究

发布时间：2025年06月09日

`LLM应用` `软件工程`

> Evaluating LLMs Effectiveness in Detecting and Correcting Test Smells: An Empirical Study

# 摘要

> 测试异味反映了测试代码中的不良实践，影响了代码的可维护性和可靠性。开发人员在预防和重构这些问题时常常感到困难，而现有的工具大多专注于检测，而非自动重构。大型语言模型（LLMs）在代码理解和转换方面展现了巨大潜力，但其在识别和重构测试异味方面的能力尚未得到充分探索。我们对GPT-4-Turbo、LLaMA 3 70B和Gemini-1.5 Pro进行了评估，分别在Python和Java的测试套件中使用PyNose和TsDetect进行初始异味检测，随后采用LLM驱动的重构方法。结果显示，Gemini在检测准确性上表现最佳（Python 74.35%，Java 80.32%），而LLaMA的表现相对较低。所有模型均能进行重构，但效果差异明显，有时甚至会引入新的异味。值得注意的是，Gemini在提升测试覆盖率方面表现出色，而GPT-4和LLaMA则可能降低覆盖率。这些结果凸显了LLMs在自动重构测试异味方面的潜力，其中Gemini表现尤为突出，尽管在不同语言和异味类型上仍面临挑战。

> Test smells indicate poor development practices in test code, reducing maintainability and reliability. While developers often struggle to prevent or refactor these issues, existing tools focus primarily on detection rather than automated refactoring. Large Language Models (LLMs) have shown strong potential in code understanding and transformation, but their ability to both identify and refactor test smells remains underexplored. We evaluated GPT-4-Turbo, LLaMA 3 70B, and Gemini-1.5 Pro on Python and Java test suites, using PyNose and TsDetect for initial smell detection, followed by LLM-driven refactoring. Gemini achieved the highest detection accuracy (74.35\% Python, 80.32\% Java), while LLaMA was lowest. All models could refactor smells, but effectiveness varied, sometimes introducing new smells. Gemini also improved test coverage, unlike GPT-4 and LLaMA, which often reduced it. These results highlight LLMs' potential for automated test smell refactoring, with Gemini as the strongest performer, though challenges remain across languages and smell types.

[Arxiv](https://arxiv.org/abs/2506.07594)