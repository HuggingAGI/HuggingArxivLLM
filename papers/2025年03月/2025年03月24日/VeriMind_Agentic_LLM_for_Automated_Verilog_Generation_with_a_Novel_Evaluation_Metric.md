# VeriMind：智能体大型语言模型，助力Verilog代码自动生成，搭配创新评估指标。

发布时间：2025年03月24日

`LLM应用` `硬件设计` `电子工程`

> VeriMind: Agentic LLM for Automated Verilog Generation with a Novel Evaluation Metric

# 摘要

> 设计 Verilog 模块需要细致关注正确性、效率及设计规范。然而，手动编写 Verilog 代码仍然是一项复杂且耗时的任务，需要专业知识和反复打磨。我们提出了 VeriMind，一个用于 Verilog 代码生成的智能体 LLM 框架，它能够显著自动化和优化综合过程。与传统基于 LLM 的代码生成器不同，VeriMind 采用结构化推理方法：在用户提供的描述设计需求的提示语基础上，系统首先形成详细的推理过程，随后生成最终的 Verilog 代码。这种多步骤的方法提升了硬件设计中的可解释性、准确性和适应性。此外，我们引入了一个新的评估指标——pass@ARC，它结合了传统的 pass@k 度量与平均迭代周期（ARC），以捕捉成功率和迭代优化的效率。在多样化的硬件设计任务上的实验结果表明，我们的方法在 pass@k 指标上实现了高达 $8.3\%$ 的提升，在 pass@ARC 指标上达到了 $8.1\%$ 的提升。这些发现凸显了智能体 LLM 在自动化硬件设计、RTL 开发和数字系统综合中的变革潜力。

> Designing Verilog modules requires meticulous attention to correctness, efficiency, and adherence to design specifications. However, manually writing Verilog code remains a complex and time-consuming task that demands both expert knowledge and iterative refinement. Leveraging recent advancements in large language models (LLMs) and their structured text generation capabilities, we propose VeriMind, an agentic LLM framework for Verilog code generation that significantly automates and optimizes the synthesis process. Unlike traditional LLM-based code generators, VeriMind employs a structured reasoning approach: given a user-provided prompt describing design requirements, the system first formulates a detailed train of thought before the final Verilog code is generated. This multi-step methodology enhances interpretability, accuracy, and adaptability in hardware design. In addition, we introduce a novel evaluation metric-pass@ARC-which combines the conventional pass@k measure with Average Refinement Cycles (ARC) to capture both success rate and the efficiency of iterative refinement. Experimental results on diverse hardware design tasks demonstrated that our approach achieved up to $8.3\%$ improvement on pass@k metric and $8.1\%$ on pass@ARC metric. These findings underscore the transformative potential of agentic LLMs in automated hardware design, RTL development, and digital system synthesis.

[Arxiv](https://arxiv.org/abs/2503.16514)