# AGON：用于从 ISA 文档定制处理器的自动化设计框架

发布时间：2024年12月30日

`LLM应用` `处理器` `硬件设计`

> AGON: Automated Design Framework for Customizing Processors from ISA Documents

# 摘要

> 定制处理器因具备高能效，成为众多特定领域应用的理想之选。然而，按传统流程设计处理器，既费时间又成本高昂。为应对此难题，研究人员探索了不少方法，比如运用 Chisel 或 SpinalHDL 等敏捷开发工具，从 C 或 SystemC 等编程语言进行高级综合（HLS），还有近来借助大型语言模型（LLMs）从自然语言描述生成硬件描述语言（HDL）代码。但每种方法在表达力、正确性和性能上都存在局限，致使自动化程度和设计效果之间一直存在矛盾。总的来说，如何以最少的人力自动设计出高效实用的处理器，仍是个挑战。
    在本文中，我们提出了 AGON 这一全新框架，旨在借助 LLMs 以最少的人力高效设计乱序（OoO）定制处理器。AGON 的核心是基于纳米操作函数（nOP 函数）的中间表示（IR），它在高级描述与硬件实现之间搭建桥梁，同时将功能与性能优化相分离，进而提供了一个兼具表达力和效率、有正确性保障且能实现 PPA（功耗、性能和面积）优化的自动设计框架。
    实验结果显示，相较于之前的 LLM 辅助自动设计流程，AGON 有助于设计一系列定制的 OoO 处理器，与专家设计的通用 CPU BOOM 相比，平均实现 2.35 倍的加速，且设计投入最小。

> Customized processors are attractive solutions for vast domain-specific applications due to their high energy efficiency. However, designing a processor in traditional flows is time-consuming and expensive. To address this, researchers have explored methods including the use of agile development tools like Chisel or SpinalHDL, high-level synthesis (HLS) from programming languages like C or SystemC, and more recently, leveraging large language models (LLMs) to generate hardware description language (HDL) code from natural language descriptions. However, each method has limitations in terms of expressiveness, correctness, and performance, leading to a persistent contradiction between the level of automation and the effectiveness of the design. Overall, how to automatically design highly efficient and practical processors with minimal human effort remains a challenge.
  In this paper, we propose AGON, a novel framework designed to leverage LLMs for the efficient design of out-of-order (OoO) customized processors with minimal human effort. Central to AGON is the nano-operator function (nOP function) based Intermediate Representation (IR), which bridges high-level descriptions and hardware implementations while decoupling functionality from performance optimization, thereby providing an automatic design framework that is expressive and efficient, has correctness guarantees, and enables PPA (Power, Performance, and Area) optimization.
  Experimental results show that superior to previous LLM-assisted automatic design flows, AGON facilitates designing a series of customized OoO processors that achieve on average 2.35 $\times$ speedup compared with BOOM, a general-purpose CPU designed by experts, with minimal design effort.

[Arxiv](https://arxiv.org/abs/2412.20954)