# ArchXBench：面向LLM驱动RTL综合的复杂数字系统基准测试套件

发布时间：2025年08月08日

`LLM应用` `芯片设计` `电子设计自动化`

> ArchXBench: A Complex Digital Systems Benchmark Suite for LLM Driven RTL Synthesis

# 摘要

> 现代SoC的数据路径设计中，深度流水线和领域特定加速器已成标配，但 RTL 实现与验证环节仍主要依赖手工完成。尽管大型语言模型（LLMs）在 Python 等编程语言的代码生成方面表现优异，但其在类似 Verilog 的 RTL 领域的应用尚处于起步阶段。这一点在现有基准测试中用于评估生成能力的简单算术和控制电路中可见一斑。

本文推出 ArchXBench，一个包含六级的基准套件，涵盖了来自密码学、图像处理、机器学习和信号处理等领域的复杂算术电路和其他先进数字子系统。从架构上看，其中一些设计是纯组合逻辑，另一些是多周期或流水线设计，许多需要模块的层次化组合。对于每个基准，我们提供了问题描述、设计规范和测试台，以支持基于 LLM 的智能方法在复杂数字系统设计领域的快速研究。

通过 Claude Sonnet 4、GPT 4.1、o4-mini-high 和 DeepSeek R1 在 pass@5 标准下的零样本提示测试，我们发现 o4-mini-high 成功解决了最多数量的基准测试，共 30 个中的 16 个，涵盖了 Level 1、2 和 3。然而，从 Level 4 开始，所有模型均未能通过，这凸显了当前最先进的 LLMs 和提示/智能方法能力之间的明显差距。

> Modern SoC datapaths include deeply pipelined, domain-specific accelerators, but their RTL implementation and verification are still mostly done by hand. While large language models (LLMs) exhibit advanced code-generation abilities for programming languages like Python, their application to Verilog-like RTL remains in its nascent stage. This is reflected in the simple arithmetic and control circuits currently used to evaluate generative capabilities in existing benchmarks. In this paper, we introduce ArchXBench, a six-level benchmark suite that encompasses complex arithmetic circuits and other advanced digital subsystems drawn from domains such as cryptography, image processing, machine learning, and signal processing. Architecturally, some of these designs are purely combinational, others are multi-cycle or pipelined, and many require hierarchical composition of modules. For each benchmark, we provide a problem description, design specification, and testbench, enabling rapid research in the area of LLM-driven agentic approaches for complex digital systems design.
  Using zero-shot prompting with Claude Sonnet 4, GPT 4.1, o4-mini-high, and DeepSeek R1 under a pass@5 criterion, we observed that o4-mini-high successfully solves the largest number of benchmarks, 16 out of 30, spanning Levels 1, 2, and 3. From Level 4 onward, however, all models consistently fail, highlighting a clear gap in the capabilities of current state-of-the-art LLMs and prompting/agentic approaches.

[Arxiv](https://arxiv.org/abs/2508.06047)