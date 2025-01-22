# 持续集成中的管道感知回归测试优化实践

发布时间：2025年01月20日

`其他

**理由**：这篇论文主要讨论的是持续集成（CI）中的测试优化问题，特别是如何通过强化学习模型来优化测试流程。虽然提到了多语言环境和代码质量，但核心内容并不涉及大型语言模型（LLM）、检索增强生成（RAG）或智能体（Agent）等主题。因此，将其分类为“其他”更为合适。` `软件开发` `持续集成`

> Practical Pipeline-Aware Regression Test Optimization for Continuous Integration

# 摘要

> # 摘要
大规模、多语言、单一代码库是现代复杂软件系统的核心。为了在快速开发的同时确保代码质量，持续集成（CI）被广泛应用。然而，大规模CI不仅容易成为开发者的单点故障，还可能导致计算资源不足和反馈延迟。为此，开发者通常将测试分散到多个流水线中：提交前运行小而快的测试，提交后执行长时间和不稳定的测试。由于许多流水线运行时间长且通过率高达98%（提交前流水线），通过优先排序和选择测试来优化测试流程不仅必要，而且潜力巨大。然而，许多现有的回归优化技术并不适合工业环境，原因在于：（1）它们依赖复杂且难以获取的特征（如代码覆盖率），这在多语言环境中难以实现；（2）无法自动适应快速变化的系统，新测试频繁添加或修改；（3）未能区分提交前和提交后流水线的目标：提交前应优先检测失败测试，而提交后应优先检测从通过到失败或反之的测试，以捕捉非不稳定的变化。为此，我们提出了一种轻量级、流水线感知的回归测试优化方法，采用基于语言无关特征的强化学习模型。我们在一个20周的CI测试执行数据集上进行了评估，结果表明...

> Massive, multi-language, monolithic repositories form the backbone of many modern, complex software systems. To ensure consistent code quality while still allowing fast development cycles, Continuous Integration (CI) is commonly applied. However, operating CI at such scale not only leads to a single point of failure for many developers, but also requires computational resources that may reach feasibility limits and cause long feedback latencies. To address these issues, developers commonly split test executions across multiple pipelines, running small and fast tests in pre-submit stages while executing long-running and flaky tests in post-submit pipelines. Given the long runtimes of many pipelines and the substantial proportion of passing test executions (98% in our pre-submit pipelines), there not only a need but also potential for further improvements by prioritizing and selecting tests. However, many previously proposed regression optimization techniques are unfit for an industrial context, because they (1) rely on complex and difficult-to-obtain features like per-test code coverage that are not feasible in large, multi-language environments, (2) do not automatically adapt to rapidly changing systems where new tests are continuously added or modified, and (3) are not designed to distinguish the different objectives of pre- and post-submit pipelines: While pre-submit testing should prioritize failing tests, post-submit pipelines should prioritize tests that indicate non-flaky changes by transitioning from pass to fail outcomes or vice versa. To overcome these issues, we developed a lightweight and pipeline-aware regression test optimization approach that employs Reinforcement Learning models trained on language-agnostic features. We evaluated our approach on a large industry dataset collected over a span of 20 weeks of CI test executions. When predicting...

[Arxiv](https://arxiv.org/abs/2501.11550)