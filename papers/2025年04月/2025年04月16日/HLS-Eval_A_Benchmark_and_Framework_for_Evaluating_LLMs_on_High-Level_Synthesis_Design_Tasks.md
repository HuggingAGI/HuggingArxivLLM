# HLS-Eval：评估大型语言模型在高级综合设计任务中的基准与框架

发布时间：2025年04月16日

`LLM应用` `半导体设计` `电子设计自动化`

> HLS-Eval: A Benchmark and Framework for Evaluating LLMs on High-Level Synthesis Design Tasks

# 摘要

> 大型语言模型（LLM）的快速扩展正在改变半导体设计领域。尽管传统研究多聚焦于使用硬件描述语言（HDL）评估LLM，但设计者正越来越多地转向高级综合（HLS）来构建高效硬件系统。然而，针对HLS设计任务的LLM评估工具和基准仍十分匮乏。

为填补这一空白，我们推出了HLS-Eval——首个专为LLM驱动HLS设计打造的完整框架。它专注于两大核心任务：（1）将自然语言转化为HLS代码；（2）优化代码以提升性能和硬件效率。基准包含94个独特设计，每个都经过精心准备，确保"LLM就绪"。

HLS-Eval不仅提供基准测试，还内置模块化Python框架，支持对本地和云LLM的并行评估。其功能包括并行引擎、工具集成和灵活的交互抽象层，便于快速开发新基准和方法。

通过在Vitis HLS上对开源LLM的基线评估，我们验证了HLS-Eval的有效性。评估结果涵盖可解析性、可编译性、可运行性和可综合性四大关键指标，并提供了pass@k评估标准，为LLM硬件应用社区提供了重要参考。

所有资源均已开源，欢迎访问https://github.com/stefanpie/hls-eval获取。


> The rapid scaling of large language model (LLM) training and inference has driven their adoption in semiconductor design across academia and industry. While most prior work evaluates LLMs on hardware description language (HDL) tasks, particularly Verilog, designers are increasingly using high-level synthesis (HLS) to build domain-specific accelerators and complex hardware systems. However, benchmarks and tooling to comprehensively evaluate LLMs for HLS design tasks remain scarce.
  To address this, we introduce HLS-Eval, the first complete benchmark and evaluation framework for LLM-driven HLS design. HLS-Eval targets two core tasks: (1) generating HLS code from natural language descriptions, and (2) performing HLS-specific code edits to optimize performance and hardware efficiency. The benchmark includes 94 unique designs drawn from standard HLS benchmarks and novel sources. Each case is prepared via a semi-automated flow that produces a natural language description and a paired testbench for C-simulation and synthesis validation, ensuring each task is "LLM-ready."
  Beyond the benchmark, HLS-Eval offers a modular Python framework for automated, parallel evaluation of both local and hosted LLMs. It includes a parallel evaluation engine, direct HLS tool integration, and abstractions for to support different LLM interaction paradigms, enabling rapid prototyping of new benchmarks, tasks, and LLM methods.
  We demonstrate HLS-Eval through baseline evaluations of open-source LLMs on Vitis HLS, measuring outputs across four key metrics - parseability, compilability, runnability, and synthesizability - reflecting the iterative HLS design cycle. We also report pass@k metrics, establishing clear baselines and reusable infrastructure for the broader LLM-for-hardware community.
  All benchmarks, framework code, and results are open-sourced at https://github.com/stefanpie/hls-eval.

[Arxiv](https://arxiv.org/abs/2504.12268)