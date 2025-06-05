# # 提升基于大型语言模型的故障定位能力，借助外部内存与项目上下文

发布时间：2025年06月04日

`LLM应用` `软件工程` `人工智能`

> Improving LLM-Based Fault Localization with External Memory and Project Context

# 摘要

> 故障定位是识别导致系统故障的软件组件的过程，虽然至关重要，但往往耗时较长。大型语言模型（LLMs）的最新进展使得无需大量缺陷数据集或模型微调即可实现故障定位。然而，现有的基于LLM的方法仅依赖于通用的LLM能力，缺乏项目特定知识的整合，因此效果有限，尤其在处理复杂软件时表现不佳。

我们提出了MemFL，这是一种通过外部记忆整合项目特定知识来增强基于LLM的故障定位的新方法。该记忆包含项目的静态摘要以及从以往尝试中收集的动态、迭代调试见解。通过利用外部记忆，MemFL将调试过程简化为三个流畅的步骤，显著提升了效率和准确性。动态记忆的迭代优化进一步提高了随时间的推理质量。

在Defects4J基准测试中，使用GPT-4o-mini的MemFL比现有基于LLM的方法多定位了12.7%的错误，仅需21%的执行时间（17.4秒/次）和33%的API成本（0.0033美元/次）。在复杂项目中，MemFL的优势提升至27.6%。此外，使用GPT-4.1-mini的MemFL比现有方法高出24.4%，每错误仅需24.7秒和0.0094美元。MemFL通过将项目特定知识有效整合到基于LLM的故障定位中，显著提升了性能，实现了高准确度的同时减少了时间和成本。


> Fault localization, the process of identifying the software components responsible for failures, is essential but often time-consuming. Recent advances in Large Language Models (LLMs) have enabled fault localization without extensive defect datasets or model fine-tuning. However, existing LLM-based methods rely only on general LLM capabilities and lack integration of project-specific knowledge, resulting in limited effectiveness, especially for complex software.
  We introduce MemFL, a novel approach that enhances LLM-based fault localization by integrating project-specific knowledge via external memory. This memory includes static summaries of the project and dynamic, iterative debugging insights gathered from previous attempts. By leveraging external memory, MemFL simplifies debugging into three streamlined steps, significantly improving efficiency and accuracy. Iterative refinement through dynamic memory further enhances reasoning quality over time.
  Evaluated on the Defects4J benchmark, MemFL using GPT-4o-mini localized 12.7% more bugs than current LLM-based methods, achieving this improvement with just 21% of the execution time (17.4 seconds per bug) and 33% of the API cost (0.0033 dollars per bug). On complex projects, MemFL's advantage increased to 27.6%. Additionally, MemFL with GPT-4.1-mini outperformed existing methods by 24.4%, requiring only 24.7 seconds and 0.0094 dollars per bug. MemFL thus demonstrates significant improvements by effectively incorporating project-specific knowledge into LLM-based fault localization, delivering high accuracy with reduced time and cost.

[Arxiv](https://arxiv.org/abs/2506.03585)