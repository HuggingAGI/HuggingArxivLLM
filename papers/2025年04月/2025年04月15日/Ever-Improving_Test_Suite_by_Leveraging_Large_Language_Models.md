# # 借助大型语言模型，打造不断优化的测试套件

发布时间：2025年04月15日

`LLM应用

理由：这篇论文展示了如何将大型语言模型应用于软件测试领域，通过增强测试套件来提高软件质量。它具体讨论了E-Test方法，该方法利用LLM来识别测试不足的行为并优化测试套件。这属于将LLM技术应用到实际任务中的案例，因此归类为LLM应用。` `软件工程`

> Ever-Improving Test Suite by Leveraging Large Language Models

# 摘要

> 为维持长期软件系统的质量，增强测试套件以包含反映软件实际使用情况的测试用例至关重要。本文提出E-Test方法，该方法能够逐步增强测试套件，添加那些在生产环境中出现且尚未被测试的行为的测试用例。E-Test利用大型语言模型来识别已测试、尚未测试以及容易出错的单元执行场景，并相应地增强测试套件。实验评估表明，E-Test在识别测试不足的行为和优化测试套件方面优于现有的主要先进方法。

> Augmenting test suites with test cases that reflect the actual usage of the software system is extremely important to sustain the quality of long lasting software systems. In this paper, we propose E-Test, an approach that incrementally augments a test suite with test cases that exercise behaviors that emerge in production and that are not been tested yet. E-Test leverages Large Language Models to identify already-tested, not-yet-tested, and error-prone unit execution scenarios, and augment the test suite accordingly. Our experimental evaluation shows that E-Test outperforms the main state-of-the-art approaches to identify inadequately tested behaviors and optimize test suites.

[Arxiv](https://arxiv.org/abs/2506.11000)