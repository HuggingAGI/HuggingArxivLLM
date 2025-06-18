# SANGAM：基于蒙特卡洛树自我优化的SystemVerilog断言生成系统

发布时间：2025年06月11日

`LLM应用

论文摘要：大型语言模型（LLMs）在推理领域的最新进展，为复杂硬件断言生成技术带来了新的可能性。本文提出了一种名为SANGAM的框架，它通过LLM引导的蒙特卡洛树搜索，实现了从行业规范到系统Verilog断言（SVAs）的自动化生成。该框架采用三阶段方法：第一阶段利用Signal Mapper、SPEC Analyzer和Waveform Analyzer等LLM代理进行多模态规范处理；第二阶段借助蒙特卡洛树自我优化（MCTSr）算法，对每个信号的SVAs进行自动推理；第三阶段则整合MCTSr生成的推理轨迹，为每个信号生成最终的SVA断言。实验结果表明，SANGAM框架能够生成一套稳健的SVAs，在评估中表现优于现有方法。

LLM应用` `硬件设计` `电子设计自动化（EDA）`

> SANGAM: SystemVerilog Assertion Generation via Monte Carlo Tree Self-Refine

# 摘要

> 大型语言模型（LLMs）在推理领域的最新进展，为复杂硬件断言生成技术带来了新的可能性。本文提出了一种名为SANGAM的框架，它通过LLM引导的蒙特卡洛树搜索，实现了从行业规范到系统Verilog断言（SVAs）的自动化生成。该框架采用三阶段方法：第一阶段利用Signal Mapper、SPEC Analyzer和Waveform Analyzer等LLM代理进行多模态规范处理；第二阶段借助蒙特卡洛树自我优化（MCTSr）算法，对每个信号的SVAs进行自动推理；第三阶段则整合MCTSr生成的推理轨迹，为每个信号生成最终的SVA断言。实验结果表明，SANGAM框架能够生成一套稳健的SVAs，在评估中表现优于现有方法。

> Recent advancements in the field of reasoning using Large Language Models (LLMs) have created new possibilities for more complex and automatic Hardware Assertion Generation techniques. This paper introduces SANGAM, a SystemVerilog Assertion Generation framework using LLM-guided Monte Carlo Tree Search for the automatic generation of SVAs from industry-level specifications. The proposed framework utilizes a three-stage approach: Stage 1 consists of multi-modal Specification Processing using Signal Mapper, SPEC Analyzer, and Waveform Analyzer LLM Agents. Stage 2 consists of using the Monte Carlo Tree Self-Refine (MCTSr) algorithm for automatic reasoning about SVAs for each signal, and finally, Stage 3 combines the MCTSr-generated reasoning traces to generate SVA assertions for each signal. The results demonstrated that our framework, SANGAM, can generate a robust set of SVAs, performing better in the evaluation process in comparison to the recent methods.

[Arxiv](https://arxiv.org/abs/2506.13983)