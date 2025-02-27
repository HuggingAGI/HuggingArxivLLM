# # 纽exus：轻量级、可扩展的多智能体框架，实现复杂任务自动化

发布时间：2025年02月26日

`LLM应用` `人工智能` `软件工程`

> Nexus: A Lightweight and Scalable Multi-Agent Framework for Complex Tasks Automation

# 摘要

> 大型语言模型（LLMs）的最新进展显著提升了多智能体系统（MASs）的能力，使其不仅能够自动化任务，还能利用接近人类的推理能力。为了实现这一点，基于LLMs的MAS需要围绕两个关键原则构建：(i) 一个强大的架构，能够充分挖掘LLMs在特定任务或相关任务集中的潜力；(ii) 一种有效的方法，为LLMs配备必要的能力，以高效完成任务和管理信息。不言而喻，预先设计的架构可能会限制特定MAS的可扩展性和领域适应性。

为了解决这些挑战，本文引入了Nexus：一个轻量级的Python框架，旨在轻松构建和管理基于LLMs的MAS。Nexus带来了以下创新：(i) 灵活的多监督层次结构；(ii) 简化的流程设计；(iii) 方便的安装和开源灵活性：Nexus可通过pip安装，并采用宽松的开源许可证分发，允许用户自由修改和扩展其功能。

实验结果表明，使用Nexus构建的架构在不同领域均表现出色。在编码任务中，Nexus驱动的MAS在HumanEval上的通过率达到了99%，并在VerilogEval-Human上实现了完美的100%，超越了前沿的推理语言模型如o3-mini和DeepSeek-R1。此外，这些架构在复杂推理和数学问题解决方面表现出色，成功解决了从MATH数据集中随机选择的所有问题。在多目标优化领域，基于Nexus的架构成功解决了VTR基准套件设计中的复杂时序收敛任务，同时平均节省了近30%的功耗。

> Recent advancements in Large Language Models (LLMs) have substantially evolved Multi-Agent Systems (MASs) capabilities, enabling systems that not only automate tasks but also leverage near-human reasoning capabilities. To achieve this, LLM-based MASs need to be built around two critical principles: (i) a robust architecture that fully exploits LLM potential for specific tasks -- or related task sets -- and ($ii$) an effective methodology for equipping LLMs with the necessary capabilities to perform tasks and manage information efficiently. It goes without saying that a priori architectural designs can limit the scalability and domain adaptability of a given MAS.
  To address these challenges, in this paper we introduce Nexus: a lightweight Python framework designed to easily build and manage LLM-based MASs. Nexus introduces the following innovations: (i) a flexible multi-supervisor hierarchy, (ii) a simplified workflow design, and (iii) easy installation and open-source flexibility: Nexus can be installed via pip and is distributed under a permissive open-source license, allowing users to freely modify and extend its capabilities.
  Experimental results demonstrate that architectures built with Nexus exhibit state-of-the-art performance across diverse domains. In coding tasks, Nexus-driven MASs achieve a 99% pass rate on HumanEval and a flawless 100% on VerilogEval-Human, outperforming cutting-edge reasoning language models such as o3-mini and DeepSeek-R1. Moreover, these architectures display robust proficiency in complex reasoning and mathematical problem solving, achieving correct solutions for all randomly selected problems from the MATH dataset. In the realm of multi-objective optimization, Nexus-based architectures successfully address challenging timing closure tasks on designs from the VTR benchmark suite, while guaranteeing, on average, a power saving of nearly 30%.

[Arxiv](https://arxiv.org/abs/2502.19091)