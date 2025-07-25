# TimelyHLS：基于大语言模型的时间敏感与架构相关FPGA HLS优化

发布时间：2025年07月23日

`LLM应用` `FPGA` `自动化设计`

> TimelyHLS: LLM-Based Timing-Aware and Architecture-Specific FPGA HLS Optimization

# 摘要

> FPGA目标的高阶综合（HLS）面临时序收敛和设计优化的双重挑战，主要源于架构约束、资源利用率以及缺乏平台特定pragma自动化支持的复杂交互。我们提出了一种创新框架——TimelyHLS，该框架将大型语言模型（LLMs）与检索增强生成（RAG）相结合，专注于自动生成并优化符合FPGA特定时序和性能需求的HLS代码。TimelyHLS基于一个结构化的架构知识库，整合了FPGA特定功能、综合指令和pragma模板。针对输入内核，TimelyHLS自动生成注释了时序关键及设计特定pragma的HLS代码。通过商业工具链评估综合后的RTL，并借助自定义测试台与参考输出对比验证仿真正确性。当检测到功能性差异时，TimelyHLS将综合日志与性能报告反馈至LLM引擎进行迭代优化。实验结果覆盖10种FPGA架构及多种基准测试，表明TimelyHLS将手动调优需求降低了70%，同时实现最高4倍的时延加速（如矩阵乘法提升3.85倍，比特onic排序加速3.7倍），并在某些场景下节省超过50%的面积（如维特比算法中减少57%的触发器数量）。TimelyHLS在不同平台上均实现了时序收敛与功能正确性，充分证明了基于LLM、架构感知的综合方法在自动化FPGA设计中的显著优势。

> Achieving timing closure and design-specific optimizations in FPGA-targeted High-Level Synthesis (HLS) remains a significant challenge due to the complex interaction between architectural constraints, resource utilization, and the absence of automated support for platform-specific pragmas. In this work, we propose TimelyHLS, a novel framework integrating Large Language Models (LLMs) with Retrieval-Augmented Generation (RAG) to automatically generate and iteratively refine HLS code optimized for FPGA-specific timing and performance requirements. TimelyHLS is driven by a structured architectural knowledge base containing FPGA-specific features, synthesis directives, and pragma templates. Given a kernel, TimelyHLS generates HLS code annotated with both timing-critical and design-specific pragmas. The synthesized RTL is then evaluated using commercial toolchains, and simulation correctness is verified against reference outputs via custom testbenches. TimelyHLS iteratively incorporates synthesis logs and performance reports into the LLM engine for refinement in the presence of functional discrepancies. Experimental results across 10 FPGA architectures and diverse benchmarks show that TimelyHLS reduces the need for manual tuning by up to 70%, while achieving up to 4x latency speedup (e.g., 3.85x for Matrix Multiplication, 3.7x for Bitonic Sort) and over 50% area savings in certain cases (e.g., 57% FF reduction in Viterbi). TimelyHLS consistently achieves timing closure and functional correctness across platforms, highlighting the effectiveness of LLM-driven, architecture-aware synthesis in automating FPGA design.

[Arxiv](https://arxiv.org/abs/2507.17962)