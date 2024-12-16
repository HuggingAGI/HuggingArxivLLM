# “你命名它，我运行它”：一个能执行任意项目测试的 LLM 代理

发布时间：2024年12月13日

`Agent` `软件开发` `项目测试`

> You Name It, I Run It: An LLM Agent to Execute Tests of Arbitrary Projects

# 摘要

> 在众多场景中，执行项目测试套件的能力极为关键，比如评估代码质量与代码覆盖率，验证开发人员或自动化工具所做的代码变更，以及保证与依赖项的兼容性。尽管其意义重大，但在实际操作中执行项目测试套件颇具挑战，因为不同项目运用不同的编程语言、软件生态系统、构建系统、测试框架及其他工具。这些难题致使创建一种可靠且通用、适用于不同项目的测试执行方法困难重重。本文呈现了 ExecutionAgent，这是一种自动化技术，能够安装任意项目，对其进行配置以运行测试用例，并生成项目专属脚本来重现设置。受人类开发人员处理此任务方式的启发，我们的方法是基于大型语言模型的代理，它能自主执行命令并与主机系统交互。该代理利用元提示收集与给定项目相关的最新技术指南，并依据前几步的反馈迭代优化其流程。我们的评估将 ExecutionAgent 应用于 50 个使用 14 种不同编程语言以及众多不同构建和测试工具的开源项目。该方法成功执行了 33/55 个项目的测试套件，同时与真实测试套件执行的测试结果匹配，偏差仅为 7.5％。这些成果较之前最佳的可用技术提升了 6.6 倍。该方法产生的成本合理，平均每个项目的执行时间为 74 分钟，LLM 成本为 0.16 美元。我们期望 ExecutionAgent 能成为开发人员、自动化编程工具以及需要在各类项目中执行测试的研究人员的得力工具。

> The ability to execute the test suite of a project is essential in many scenarios, e.g., to assess code quality and code coverage, to validate code changes made by developers or automated tools, and to ensure compatibility with dependencies. Despite its importance, executing the test suite of a project can be challenging in practice because different projects use different programming languages, software ecosystems, build systems, testing frameworks, and other tools. These challenges make it difficult to create a reliable, universal test execution method that works across different projects. This paper presents ExecutionAgent, an automated technique that installs arbitrary projects, configures them to run test cases, and produces project-specific scripts to reproduce the setup. Inspired by the way a human developer would address this task, our approach is a large language model-based agent that autonomously executes commands and interacts with the host system. The agent uses meta-prompting to gather guidelines on the latest technologies related to the given project, and it iteratively refines its process based on feedback from the previous steps. Our evaluation applies ExecutionAgent to 50 open-source projects that use 14 different programming languages and many different build and testing tools. The approach successfully executes the test suites of 33/55 projects, while matching the test results of ground truth test suite executions with a deviation of only 7.5\%. These results improve over the best previously available technique by 6.6x. The costs imposed by the approach are reasonable, with an execution time of 74 minutes and LLM costs of 0.16 dollars, on average per project. We envision ExecutionAgent to serve as a valuable tool for developers, automated programming tools, and researchers that need to execute tests across a wide variety of projects.

[Arxiv](https://arxiv.org/abs/2412.10133)