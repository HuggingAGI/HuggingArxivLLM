# 制造领域中混合推理在感知、解释与自主行动中的应用研究

发布时间：2025年06月10日

`Agent

理由：这篇论文提出了一种视觉-语言-行动（VLA）模型框架CIPHER，用于工业控制，模拟人类推理，整合专家系统和回归模型，支持自主决策和操作，属于智能体（Agent）的应用。`

> Hybrid Reasoning for Perception, Explanation, and Autonomous Action in Manufacturing

# 摘要

> 工业生产流程需要在不可预测的环境中稳健且灵活地运行，同时操作失误往往代价高昂且难以察觉。基于AI的控制系统虽然提供了解决方案，但受限于监督学习对大量标注数据的依赖，难以在多变且数据稀缺的工业环境中实现良好泛化。基础模型虽具备广泛推理和知识整合的潜力，却难以满足工程应用所需的定量精度要求。

在这里，我们推出Control and Interpretation of Production via Hybrid Expertise and Reasoning (CIPHER)：一个视觉-语言-行动（VLA）模型框架，旨在模拟人类推理以实现工业控制。该框架在商用级3D打印机中得到了实际应用。CIPHER整合了过程专家系统和回归模型，能够定量表征工程任务所需的系统状态。同时，它采用检索增强生成技术，可调用外部专家知识，并支持基于物理信息的链式推理。这种创新的混合架构在处理分布外任务时展现出强大的泛化能力。

CIPHER能够解读来自过程监控的视觉或文本输入，阐述其决策依据，并自主生成精准的机器指令，无需人工标注。这一突破性框架为新一代自主系统奠定了基础，这些系统不仅能够精准执行任务，还能够基于上下文进行推理，并透明地沟通决策过程，从而支持在工业环境中安全、可靠地部署。

> Industrial processes must be robust and adaptable, as environments and tasks are often unpredictable, while operational errors remain costly and difficult to detect. AI-based control systems offer a path forward, yet typically depend on supervised learning with extensive labelled datasets, which limits their ability to generalize across variable and data-scarce industrial settings. Foundation models could enable broader reasoning and knowledge integration, but rarely deliver the quantitative precision demanded by engineering applications. Here, we introduceControl and Interpretation of Production via Hybrid Expertise and Reasoning (CIPHER): a vision-language-action (VLA) model framework aiming to replicate human-like reasoning for industrial control, instantiated in a commercial-grade 3D printer. It integrates a process expert, a regression model enabling quantitative characterization of system states required for engineering tasks. CIPHER also incorporates retrieval-augmented generation to access external expert knowledge and support physics-informed, chain-of-thought reasoning. This hybrid architecture exhibits strong generalization to out-of-distribution tasks. It interprets visual or textual inputs from process monitoring, explains its decisions, and autonomously generates precise machine instructions, without requiring explicit annotations. CIPHER thus lays the foundations for autonomous systems that act with precision, reason with context, and communicate decisions transparently, supporting safe and trusted deployment in industrial settings.

[Arxiv](https://arxiv.org/abs/2506.08462)