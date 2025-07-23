# RealBench：基于真实IP设计的Verilog生成模型基准测试

发布时间：2025年07月21日

`LLM应用` `硬件设计自动化` `EDA工具`

> RealBench: Benchmarking Verilog Generation Models with Real-World IP Designs

# 摘要

> 大型语言模型（LLMs）在硬件设计自动化中自动生成Verilog代码引起了广泛关注。然而，现有的用于评估LLMs在Verilog生成方面的基准测试由于设计简单、设计规范不充分以及验证环境不够严格，无法很好地模拟真实的设计工作流程。为了解决这些问题，我们提出了RealBench，这是首个专注于真实IP级Verilog生成任务的基准测试。RealBench拥有复杂的真实开源IP设计、多模式和格式化的规范，以及严格的验证环境，包括100%覆盖率的测试台和正式检查器。它支持模块级和系统级任务，能够全面评估LLMs的能力。在各种LLMs和代理上的评估表明，即使是表现最佳的LLMs之一o1-preview，在模块级任务上也只有13.3%的通过率，系统级任务更是0%。这凸显了未来需要更强大的Verilog生成模型。该基准测试在GitHub上开源，链接为https://github.com/IPRC-DIP/RealBench。

> The automatic generation of Verilog code using Large Language Models (LLMs) has garnered significant interest in hardware design automation. However, existing benchmarks for evaluating LLMs in Verilog generation fall short in replicating real-world design workflows due to their designs' simplicity, inadequate design specifications, and less rigorous verification environments. To address these limitations, we present RealBench, the first benchmark aiming at real-world IP-level Verilog generation tasks. RealBench features complex, structured, real-world open-source IP designs, multi-modal and formatted design specifications, and rigorous verification environments, including 100% line coverage testbenches and a formal checker. It supports both module-level and system-level tasks, enabling comprehensive assessments of LLM capabilities. Evaluations on various LLMs and agents reveal that even one of the best-performing LLMs, o1-preview, achieves only a 13.3% pass@1 on module-level tasks and 0% on system-level tasks, highlighting the need for stronger Verilog generation models in the future. The benchmark is open-sourced at https://github.com/IPRC-DIP/RealBench.

[Arxiv](https://arxiv.org/abs/2507.16200)