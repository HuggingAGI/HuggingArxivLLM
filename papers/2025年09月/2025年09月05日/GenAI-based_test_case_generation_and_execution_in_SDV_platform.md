# SDV平台中基于GenAI的测试用例生成与执行

发布时间：2025年09月05日

`LLM应用` `工业与制造`

> GenAI-based test case generation and execution in SDV platform

# 摘要

> 本文提出了一种生成式AI驱动的自动化测试用例生成方案，借助大型语言模型与视觉语言模型，将自然语言需求和系统图转化为结构化的Gherkin测试用例。该方案集成车辆信号规范建模，以标准化车辆信号定义、提升汽车子系统间的兼容性，并简化与第三方测试工具的集成流程。生成的测试用例在digital.auto playground（一个开放且厂商中立的环境）中执行，旨在快速验证软件定义车辆的功能。通过儿童存在检测系统用例评估显示，该方案显著减少了手动测试规范工作量，且生成的测试可快速执行。不过，受限于生成式AI流水线的现有瓶颈及digital.auto平台的约束，测试用例与脚本的生成仍需人工介入。

> This paper introduces a GenAI-driven approach for automated test case generation, leveraging Large Language Models and Vision-Language Models to translate natural language requirements and system diagrams into structured Gherkin test cases. The methodology integrates Vehicle Signal Specification modeling to standardize vehicle signal definitions, improve compatibility across automotive subsystems, and streamline integration with third-party testing tools. Generated test cases are executed within the digital.auto playground, an open and vendor-neutral environment designed to facilitate rapid validation of software-defined vehicle functionalities. We evaluate our approach using the Child Presence Detection System use case, demonstrating substantial reductions in manual test specification effort and rapid execution of generated tests. Despite significant automation, the generation of test cases and test scripts still requires manual intervention due to current limitations in the GenAI pipeline and constraints of the digital.auto platform.

[Arxiv](https://arxiv.org/abs/2509.05112)