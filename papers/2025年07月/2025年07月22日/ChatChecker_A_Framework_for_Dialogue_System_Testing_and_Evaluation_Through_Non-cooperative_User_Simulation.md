# ChatChecker：一个用于通过非协作用户模拟进行对话系统测试与评估的框架

发布时间：2025年07月22日

`LLM应用

理由：这篇论文主要探讨了如何在实际应用中使用大型语言模型（LLMs）来构建和测试对话系统。ChatChecker是一个用于复杂对话系统自动化评估和测试的框架，它利用LLMs模拟用户互动，识别问题，并评估对话质量。论文的重点在于如何将LLMs应用于对话系统的整体测试和优化，而不是深入探讨LLMs的理论或机制。因此，这篇论文属于LLM应用类别。` `人工智能` `软件工程`

> ChatChecker: A Framework for Dialogue System Testing and Evaluation Through Non-cooperative User Simulation

# 摘要

> 尽管现代对话系统高度依赖大型语言模型（LLMs），但其实际应用远不止于此——开发者往往会整合多个LLMs、外部工具和数据库。因此，仅评估LLM本身是不够的，对话系统必须作为一个整体进行测试和评估。然而，这一过程仍然充满挑战。由于此前研究多聚焦于逐轮分析，对整体对话质量的把控显得相对薄弱。为此，我们推出ChatChecker，一个用于复杂对话系统自动化评估与测试的框架。ChatChecker借助LLMs模拟多样化用户互动，识别对话中的问题，并评估其质量。与传统方法相比，我们的设计不仅减少了前期准备工作，还具备更强的通用性——无需参考对话，且与目标对话系统的具体实现完全解耦。通过在提示中引入错误分类法，我们显著提升了故障检测的性能。此外，我们还提出了一种基于具有挑战性人设的新型非合作用户模拟器，能够更有效地揭示目标对话系统的潜在弱点。通过这些创新，ChatChecker为对话系统的全面测试和扩展提供了有力支持，助力研究人员与实践者加速开发更 robust 的对话系统。

> While modern dialogue systems heavily rely on large language models (LLMs), their implementation often goes beyond pure LLM interaction. Developers integrate multiple LLMs, external tools, and databases. Therefore, assessment of the underlying LLM alone does not suffice, and the dialogue systems must be tested and evaluated as a whole. However, this remains a major challenge. With most previous work focusing on turn-level analysis, less attention has been paid to integrated dialogue-level quality assurance. To address this, we present ChatChecker, a framework for automated evaluation and testing of complex dialogue systems. ChatChecker uses LLMs to simulate diverse user interactions, identify dialogue breakdowns, and evaluate quality. Compared to previous approaches, our design reduces setup effort and is generalizable, as it does not require reference dialogues and is decoupled from the implementation of the target dialogue system. We improve breakdown detection performance over a prior LLM-based approach by including an error taxonomy in the prompt. Additionally, we propose a novel non-cooperative user simulator based on challenging personas that uncovers weaknesses in target dialogue systems more effectively. Through this, ChatChecker contributes to thorough and scalable testing. This enables both researchers and practitioners to accelerate the development of robust dialogue systems.

[Arxiv](https://arxiv.org/abs/2507.16792)