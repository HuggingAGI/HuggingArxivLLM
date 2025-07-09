# **医疗数据智能评估**：一种基于上下文感知的方法，用于结构化医疗数据的自动化质量评估

发布时间：2025年07月03日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLM）在医疗数据质量评估中的应用。具体来说，论文提出了一种医疗数据啄食方法（MDPT），该方法利用LLM生成测试套件，以识别和解决电子健康记录中的数据质量问题。虽然论文中提到了数据质量评估和测试框架的开发，但核心是基于LLM的应用，因此归类为LLM应用。` `数据质量评估`

> Medical Data Pecking: A Context-Aware Approach for Automated Quality Evaluation of Structured Medical Data

# 摘要

> # 背景
电子健康记录 (EHRs) 在流行病学研究和人工智能 (AI) 训练中的应用日益广泛。研究结果的可靠性取决于 EHR 数据的准确性和完整性。然而，由于 EHR 数据主要为临床和计费目的收集，因此通常包含显著的质量问题，包括亚人群体的不准确表示、偏见和系统性错误。现有的质量评估方法仍然不足，缺乏系统化的流程来评估数据是否适合研究用途。

# 方法
我们提出了医疗数据啄食方法，该方法借鉴了软件工程中的单元测试和覆盖率概念，以识别数据质量问题。我们通过医疗数据啄食工具 (MDPT) 展示了我们的方法，该工具包含两个主要组件: (1) 一个自动化测试生成器，它使用大型语言模型和接地技术从数据和研究描述中创建测试套件; (2) 一个数据测试框架，用于执行这些测试并报告潜在错误和覆盖率。

# 结果
我们在三个数据集上评估了 MDPT: All of Us (AoU)、MIMIC-III 和 SyntheticMass，在四个条件下每个队列生成了 55-73 个测试用例。这些测试正确识别了 20-43 个不一致或不符合标准的数据问题。我们详细分析了 LLM 生成的测试套件在参考接地和值准确性方面的表现。

# 结论
我们的方法整合了外部医学知识，使上下文敏感的数据质量测试成为数据分析工作流程的一部分，从而提高了其结果的有效性。我们的方法从质量保证的角度解决了这些挑战，为未来发展奠定了基础，例如增加数据模式和改进接地方法。

> Background: The use of Electronic Health Records (EHRs) for epidemiological studies and artificial intelligence (AI) training is increasing rapidly. The reliability of the results depends on the accuracy and completeness of EHR data. However, EHR data often contain significant quality issues, including misrepresentations of subpopulations, biases, and systematic errors, as they are primarily collected for clinical and billing purposes. Existing quality assessment methods remain insufficient, lacking systematic procedures to assess data fitness for research.
  Methods: We present the Medical Data Pecking approach, which adapts unit testing and coverage concepts from software engineering to identify data quality concerns. We demonstrate our approach using the Medical Data Pecking Tool (MDPT), which consists of two main components: (1) an automated test generator that uses large language models and grounding techniques to create a test suite from data and study descriptions, and (2) a data testing framework that executes these tests, reporting potential errors and coverage.
  Results: We evaluated MDPT on three datasets: All of Us (AoU), MIMIC-III, and SyntheticMass, generating 55-73 tests per cohort across four conditions. These tests correctly identified 20-43 non-aligned or non-conforming data issues. We present a detailed analysis of the LLM-generated test suites in terms of reference grounding and value accuracy.
  Conclusion: Our approach incorporates external medical knowledge to enable context-sensitive data quality testing as part of the data analysis workflow to improve the validity of its outcomes. Our approach tackles these challenges from a quality assurance perspective, laying the foundation for further development such as additional data modalities and improved grounding methods.

[Arxiv](https://arxiv.org/abs/2507.02628)