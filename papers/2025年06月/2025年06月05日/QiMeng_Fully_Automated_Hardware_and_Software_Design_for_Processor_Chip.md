# 启明：处理器芯片软硬件设计的全自动解决方案

发布时间：2025年06月05日

`LLM应用

理由：这篇论文讨论了大型语言模型（LLMs）在处理器芯片设计自动化中的应用，属于LLMs的实际应用领域。` `计算机硬件` `自动化`

> QiMeng: Fully Automated Hardware and Software Design for Processor Chip

# 摘要

> 处理器芯片设计技术作为计算机科学的关键前沿，推动了多项突破性进展。然而，随着信息技术的快速发展，传统设计范式面临三大挑战：制造技术的物理限制、设计资源需求激增，以及生态系统多样性增加。为应对这些挑战，自动化处理器芯片设计应运而生。

近年来，人工智能特别是大型语言模型（LLMs）技术的突破为完全自动化的处理器芯片设计开辟了新途径。然而，建立特定领域的LLMs用于处理器芯片设计仍面临重大挑战。

本文提出了一种名为“齐 Meng”的全新系统，旨在实现处理器芯片硬件和软件设计的完全自动化。该系统由三个层级构成：底层是特定领域的大型处理器芯片模型（LPCM），中层是硬件和软件设计代理，顶层是各种应用。目前，齐 Meng 的多个组件已成功开发并在实际应用中展现出显著优势，为高效、完全自动化的处理器芯片设计提供了可行方案。未来，我们将致力于整合所有组件，通过迭代式的自顶向下和自底向上的设计流程，构建一个全面的齐 Meng 系统。

> Processor chip design technology serves as a key frontier driving breakthroughs in computer science and related fields. With the rapid advancement of information technology, conventional design paradigms face three major challenges: the physical constraints of fabrication technologies, the escalating demands for design resources, and the increasing diversity of ecosystems. Automated processor chip design has emerged as a transformative solution to address these challenges. While recent breakthroughs in Artificial Intelligence (AI), particularly Large Language Models (LLMs) techniques, have opened new possibilities for fully automated processor chip design, substantial challenges remain in establishing domain-specific LLMs for processor chip design.
  In this paper, we propose QiMeng, a novel system for fully automated hardware and software design of processor chips. QiMeng comprises three hierarchical layers. In the bottom-layer, we construct a domain-specific Large Processor Chip Model (LPCM) that introduces novel designs in architecture, training, and inference, to address key challenges such as knowledge representation gap, data scarcity, correctness assurance, and enormous solution space. In the middle-layer, leveraging the LPCM's knowledge representation and inference capabilities, we develop the Hardware Design Agent and the Software Design Agent to automate the design of hardware and software for processor chips. Currently, several components of QiMeng have been completed and successfully applied in various top-layer applications, demonstrating significant advantages and providing a feasible solution for efficient, fully automated hardware/software design of processor chips. Future research will focus on integrating all components and performing iterative top-down and bottom-up design processes to establish a comprehensive QiMeng system.

[Arxiv](https://arxiv.org/abs/2506.05007)