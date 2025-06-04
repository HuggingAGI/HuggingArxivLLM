# # 大型处理器芯片模型研究

发布时间：2025年06月03日

`LLM应用` `计算机系统架构` `处理器芯片设计`

> Large Processor Chip Model

# 摘要

> 计算机系统架构是软件应用与底层硬件之间的关键纽带，涵盖了编译器、CPU、协处理器和RTL设计等核心组件。从早期的大型机发展到现代的领域专用架构，这一领域始终伴随着计算需求的增长和半导体技术的进步。然而，传统的计算机系统架构设计范式正面临三大挑战：对人工专业知识的过度依赖、软硬件优化的割裂以及设计空间探索的高昂成本。尽管基于优化算法和机器学习的自动化方法在一定程度上提高了效率，但它们仍然受限于单阶段优化、数据资源有限以及缺乏全面的人类领域知识。大型语言模型的出现为计算机系统架构设计带来了革命性的机遇。通过充分发挥LLMs在代码生成、数据分析和性能建模等方面的能力，传统的手动设计流程有望全面转向基于机器的自动化设计方法。为了充分释放这一潜力，我们提出了一种名为大型处理器芯片模型（LPCM）的LLM驱动框架，致力于实现端到端的计算机架构自动化设计。LPCM架构分为三个层次：以人为核心；代理编排；以及模型治理。本文以3D高斯散射作为典型工作负载，结合软硬件协同设计的理念，深入探讨了LPCM第一层的实现方案，充分验证了所提方法的有效性。此外，本文还详细讨论了实现LPCM第二层和第三层的潜在路径，并对当前面临的挑战进行了深入分析。

> Computer System Architecture serves as a crucial bridge between software applications and the underlying hardware, encompassing components like compilers, CPUs, coprocessors, and RTL designs. Its development, from early mainframes to modern domain-specific architectures, has been driven by rising computational demands and advancements in semiconductor technology. However, traditional paradigms in computer system architecture design are confronting significant challenges, including a reliance on manual expertise, fragmented optimization across software and hardware layers, and high costs associated with exploring expansive design spaces. While automated methods leveraging optimization algorithms and machine learning have improved efficiency, they remain constrained by a single-stage focus, limited data availability, and a lack of comprehensive human domain knowledge. The emergence of large language models offers transformative opportunities for the design of computer system architecture. By leveraging the capabilities of LLMs in areas such as code generation, data analysis, and performance modeling, the traditional manual design process can be transitioned to a machine-based automated design approach. To harness this potential, we present the Large Processor Chip Model (LPCM), an LLM-driven framework aimed at achieving end-to-end automated computer architecture design. The LPCM is structured into three levels: Human-Centric; Agent-Orchestrated; and Model-Governed. This paper utilizes 3D Gaussian Splatting as a representative workload and employs the concept of software-hardware collaborative design to examine the implementation of the LPCM at Level 1, demonstrating the effectiveness of the proposed approach. Furthermore, this paper provides an in-depth discussion on the pathway to implementing Level 2 and Level 3 of the LPCM, along with an analysis of the existing challenges.

[Arxiv](https://arxiv.org/abs/2506.02929)