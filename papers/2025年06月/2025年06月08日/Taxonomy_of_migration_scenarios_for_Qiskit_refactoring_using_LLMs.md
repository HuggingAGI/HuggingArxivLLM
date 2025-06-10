# Qiskit重构的迁移场景分类法，使用LLMs

发布时间：2025年06月08日

`LLM应用

论文摘要：量子计算的快速发展带来了新的挑战。量子编程库的异构性和持续演变使得软件开发者在面对频繁更新时需要不断重构代码，这为本就复杂的开发环境增添了更多难度。由于量子计算软件的独特性质，这些重构挑战与经典软件工程中的问题大不相同。本研究通过建立量子电路重构问题的分类体系，提供了一个结构化的框架来分析和比较不同的重构方法。大型语言模型（LLMs）在经典软件开发中已显示出巨大价值，但其在量子软件工程中的潜力尚未被挖掘。本研究利用LLMs对不同Qiskit版本之间的迁移场景进行分类，以识别重构需求。通过深入分析Qiskit文档和发布说明，我们创建了一个初始分类法，用于描述在不同Qiskit版本之间迁移所需的重构类型。最终，我们整合了专家开发人员和LLM生成的两个分类法，形成一个统一的分类体系，既反映了专家见解，又体现了AI的独特视角。这一统一分类法不仅为未来AI辅助迁移的研究奠定了基础，还为评估自动化重构技术提供了更严谨的框架。此外，本研究通过优化软件开发流程、提升语言兼容性以及推广量子编程的最佳实践，为量子软件工程（QSE）的发展做出了重要贡献。` `量子计算` `软件工程`

> Taxonomy of migration scenarios for Qiskit refactoring using LLMs

# 摘要

> 量子计算的快速发展带来了新的挑战。量子编程库的异构性和持续演变使得软件开发者在面对频繁更新时需要不断重构代码，这为本就复杂的开发环境增添了更多难度。由于量子计算软件的独特性质，这些重构挑战与经典软件工程中的问题大不相同。本研究通过建立量子电路重构问题的分类体系，提供了一个结构化的框架来分析和比较不同的重构方法。大型语言模型（LLMs）在经典软件开发中已显示出巨大价值，但其在量子软件工程中的潜力尚未被挖掘。本研究利用LLMs对不同Qiskit版本之间的迁移场景进行分类，以识别重构需求。通过深入分析Qiskit文档和发布说明，我们创建了一个初始分类法，用于描述在不同Qiskit版本之间迁移所需的重构类型。最终，我们整合了专家开发人员和LLM生成的两个分类法，形成一个统一的分类体系，既反映了专家见解，又体现了AI的独特视角。这一统一分类法不仅为未来AI辅助迁移的研究奠定了基础，还为评估自动化重构技术提供了更严谨的框架。此外，本研究通过优化软件开发流程、提升语言兼容性以及推广量子编程的最佳实践，为量子软件工程（QSE）的发展做出了重要贡献。

> As quantum computing advances, quantum programming libraries' heterogeneity and steady evolution create new challenges for software developers. Frequent updates in software libraries break working code that needs to be refactored, thus adding complexity to an already complex landscape. These refactoring challenges are, in many cases, fundamentally different from those known in classical software engineering due to the nature of quantum computing software. This study addresses these challenges by developing a taxonomy of quantum circuit's refactoring problems, providing a structured framework to analyze and compare different refactoring approaches. Large Language Models (LLMs) have proven valuable tools for classic software development, yet their value in quantum software engineering remains unexplored. This study uses LLMs to categorize refactoring needs in migration scenarios between different Qiskit versions. Qiskit documentation and release notes were scrutinized to create an initial taxonomy of refactoring required for migrating between Qiskit releases. Two taxonomies were produced: one by expert developers and one by an LLM. These taxonomies were compared, analyzing differences and similarities, and were integrated into a unified taxonomy that reflects the findings of both methods. By systematically categorizing refactoring challenges in Qiskit, the unified taxonomy is a foundation for future research on AI-assisted migration while enabling a more rigorous evaluation of automated refactoring techniques. Additionally, this work contributes to quantum software engineering (QSE) by enhancing software development workflows, improving language compatibility, and promoting best practices in quantum programming.

[Arxiv](https://arxiv.org/abs/2506.07135)