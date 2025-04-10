# LLM-IFT：为安全硬件设计的基于LLM的信息流追踪技术

发布时间：2025年04月09日

`LLM应用

理由：这篇论文将大型语言模型（LLM）应用于硬件设计中的信息流追踪（IFT），展示了LLM在分析复杂硬件设计中的实际应用，并取得了成功的结果。因此，它属于LLM应用类别。` `硬件设计` `集成电路`

> LLM-IFT: LLM-Powered Information Flow Tracking for Secure Hardware

# 摘要

> 现代硬件设计日益复杂化和规模化，保障保密性、完整性和可用性（CIA三元组）的安全性面临严峻挑战。信息流追踪（IFT）作为追踪数据传播、识别硬件中潜在威胁的重要方法，却因传统方法的局限性在大规模硬件中难以施展。本文提出LLM-IFT，将大型语言模型（LLM）融入IFT流程，通过LLM驱动的结构化推理实现层次化依赖分析，系统性地解构复杂设计。框架借助多步骤LLM调用，全面解析模块内外依赖关系，完成精准的IFT评估。实验结果表明，针对IP级和系统级芯片（SoC）级的Trust-Hub漏洞测试用例，LLM-IFT在硬件保密性和完整性分析中达到了100%的成功率，充分展示了基于变压器模型在集成电路设计中的巨大潜力。

> As modern hardware designs grow in complexity and size, ensuring security across the confidentiality, integrity, and availability (CIA) triad becomes increasingly challenging. Information flow tracking (IFT) is a widely-used approach to tracing data propagation, identifying unauthorized activities that may compromise confidentiality or/and integrity in hardware. However, traditional IFT methods struggle with scalability and adaptability, particularly in high-density and interconnected architectures, leading to tracing bottlenecks that limit applicability in large-scale hardware. To address these limitations and show the potential of transformer-based models in integrated circuit (IC) design, this paper introduces LLM-IFT that integrates large language models (LLM) for the realization of the IFT process in hardware. LLM-IFT exploits LLM-driven structured reasoning to perform hierarchical dependency analysis, systematically breaking down even the most complex designs. Through a multi-step LLM invocation, the framework analyzes both intra-module and inter-module dependencies, enabling comprehensive IFT assessment. By focusing on a set of Trust-Hub vulnerability test cases at both the IP level and the SoC level, our experiments demonstrate a 100\% success rate in accurate IFT analysis for confidentiality and integrity checks in hardware.

[Arxiv](https://arxiv.org/abs/2504.07015)