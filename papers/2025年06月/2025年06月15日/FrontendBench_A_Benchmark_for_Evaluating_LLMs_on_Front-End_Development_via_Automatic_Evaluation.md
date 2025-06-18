# FrontendBench: 一个通过自动评估方法，用于衡量大型语言模型在前端开发领域表现的基准测试

发布时间：2025年06月15日

`LLM应用` `前端开发` `软件工程`

> FrontendBench: A Benchmark for Evaluating LLMs on Front-End Development via Automatic Evaluation

# 摘要

> 大型语言模型（LLMs）在前端代码生成领域取得了显著进展，但现有基准测试存在诸多不足：任务过于简单、测试用例缺乏严谨性、缺乏端到端验证。这些问题阻碍了对模型性能的准确评估。为解决这些问题，我们提出了FrontendBench，这是一个由人类与LLMs共同开发的基准测试。它根据代码功能对任务进行分类，并引入交互式测试场景，从而能够更全面、更实际地评估前端代码生成能力。FrontendBench包含148个精心设计的提示-测试用例对，涵盖从基本UI元素到复杂交互功能的五个Web组件级别，每个任务都反映了现实中的前端开发挑战。此外，我们开发了一个自动评估框架，它在沙盒环境中执行生成的代码，并使用预定义的测试脚本进行评估，与专家人工评估的符合率达到90.54%，证明了其高度可靠性。我们在FrontendBench上对多个最先进的LLMs进行了基准测试，发现它们在处理真实世界前端任务时存在显著性能差异。这些结果凸显了FrontendBench作为可靠且可扩展基准测试的价值，它支持一致的多模态评估，并为未来前端代码生成研究提供了坚实的基础。我们的数据和代码即将发布。

> Large Language Models (LLMs) have made significant strides in front-end code generation. However, existing benchmarks exhibit several critical limitations: many tasks are overly simplistic, test cases often lack rigor, and end-to-end validation is absent. These issues hinder the accurate assessment of model performance. To address these challenges, we present FrontendBench, a benchmark co-developed by humans and LLMs. FrontendBench categorizes tasks based on code functionality and incorporates interactive test scenarios, enabling a more comprehensive and practical evaluation of front-end code generation capabilities. The benchmark comprises 148 meticulously crafted prompt-test case pairs spanning five levels of web components, from basic UI elements to complex interactive features. Each task reflects realistic front-end development challenges. Furthermore, we introduce an automatic evaluation framework that executes generated code within a sandbox environment and assesses outcomes using predefined test scripts. This framework achieves a 90.54% agreement rate with expert human evaluations, demonstrating high reliability. We benchmark several state-of-the-art LLMs on FrontendBench and observe substantial performance disparities in handling real-world front-end tasks. These results highlight FrontendBench as a reliable and scalable benchmark, supporting consistent multimodal evaluation and providing a robust foundation for future research in front-end code generation. Our data and code will be released soon.

[Arxiv](https://arxiv.org/abs/2506.13832)