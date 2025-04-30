# ComplexVCoder：基于LLM的框架，系统化生成复杂Verilog代码

发布时间：2025年04月29日

`LLM应用

理由：这篇论文探讨了大型语言模型在生成复杂Verilog代码方面的应用，属于LLM的具体应用场景，因此归类为LLM应用。` `电子设计自动化` `硬件设计`

> ComplexVCoder: An LLM-Driven Framework for Systematic Generation of Complex Verilog Code

# 摘要

> 近期研究表明，大型语言模型（LLMs）在生成寄存器传输级（RTL）代码（如Verilog）方面展现出巨大潜力。然而，现有基于LLM的框架在处理真实世界复杂RTL设计时仍面临重大挑战，尤其是大规模且包含多级模块实例的设计。为解决这一问题，我们推出了开源框架ComplexVCoder，专注于提升复杂Verilog代码的生成质量和效率。我们创新性地引入了两阶段生成机制，通过中间表示实现从自然语言描述到复杂Verilog设计的精准转换。此外，我们还开发了基于规则的对齐方法和领域特定的增强生成（RAG）方法，通过整合相关设计知识，进一步提升生成代码的正确性。为验证我们的方法，我们构建了一个包含55个复杂Verilog设计的综合数据集，所有设计均源自真实世界应用。同时，我们开源了一个基准测试套件，与ComplexVCoder框架一并发布，用于系统化评估自动生成RTL代码的质量。实验结果表明，在复杂Verilog基准测试中，ComplexVCoder在功能正确性方面分别比现有最优框架CodeV和RTLCoder高出14.6%和22.2%。值得注意的是，使用轻量级32B模型（Qwen2.5）的ComplexVCoder在功能正确性方面也达到了与GPT-3.5和DeepSeek-V3等大规模模型相媲美的生成性能。

> Recent advances have demonstrated the promising capabilities of large language models (LLMs) in generating register-transfer level (RTL) code, such as Verilog. However, existing LLM-based frameworks still face significant challenges in accurately handling the complexity of real-world RTL designs, particularly those that are large-scale and involve multi-level module instantiations. To address this issue, we present ComplexVCoder, an open-source LLM-driven framework that enhances both the generation quality and efficiency of complex Verilog code. Specifically, we introduce a two-stage generation mechanism, which leverages an intermediate representation to enable a more accurate and structured transition from natural language descriptions to intricate Verilog designs. In addition, we introduce a rule-based alignment method and a domain-specific retrieval-augmented generation (RAG) to further improve the correctness of the synthesized code by incorporating relevant design knowledge during generation. To evaluate our approach, we construct a comprehensive dataset comprising 55 complex Verilog designs derived from real-world implementations. We also release an open-source benchmark suite for systematically assessing the quality of auto-generated RTL code together with the ComplexVCoder framework. Experimental results show that ComplexVCoder outperforms SOTA frameworks such as CodeV and RTLCoder by 14.6% and 22.2%, respectively, in terms of function correctness on complex Verilog benchmarks. Furthermore, ComplexVcoder achieves comparable generation performances in terms of functionality correctness using a lightweight 32B model (Qwen2.5), rivaling larger-scale models such as GPT-3.5 and DeepSeek-V3.

[Arxiv](https://arxiv.org/abs/2504.20653)