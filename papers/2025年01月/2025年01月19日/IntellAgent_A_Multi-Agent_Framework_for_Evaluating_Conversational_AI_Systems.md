# IntellAgent: 对话AI系统评估的多智能体框架

发布时间：2025年01月19日

`Agent

理由：这篇论文主要介绍了一个名为IntellAgent的多智能体框架，旨在评估对话式AI系统。该框架通过结合政策驱动的图建模、真实事件生成和交互式用户-智能体模拟，自动化生成多样化的合成基准，并提供了细粒度的诊断。论文的核心内容围绕智能体的评估和优化，因此应归类为Agent。` `人工智能` `对话系统`

> IntellAgent: A Multi-Agent Framework for Evaluating Conversational AI Systems

# 摘要

> # 摘要
大型语言模型（LLMs）正在重塑人工智能，逐渐进化为能够自主规划和执行任务的系统。对话式AI系统是LLMs的主要应用之一，它们需要处理多轮对话、集成领域特定的API，并严格遵守政策约束。然而，评估这些智能体仍面临巨大挑战，传统方法难以捕捉现实交互的复杂性和多样性。为此，我们推出了IntellAgent，一个可扩展的开源多智能体框架，旨在全面评估对话式AI系统。IntellAgent通过结合政策驱动的图建模、真实事件生成和交互式用户-智能体模拟，自动化生成多样化的合成基准。这一创新方法提供了细粒度的诊断，弥补了静态和手动策划基准测试中粗粒度指标的不足。IntellAgent代表了对话式AI评估的范式转变。通过模拟不同复杂度的真实多政策场景，它捕捉了智能体能力与政策约束之间的微妙互动。与传统方法不同，IntellAgent采用基于图的政策模型，精确描述政策交互的关系、可能性和复杂性，从而实现高度详细的诊断。此外，IntellAgent还能识别关键性能差距，为优化提供可操作的见解。其模块化、开源设计支持无缝集成新领域、政策和API，促进了可重复性和社区协作。我们的研究结果表明，IntellAgent作为一个有效框架，通过解决研究与部署之间的挑战，推动了对话式AI的发展。该框架可在https://github.com/plurai-ai/intellagent获取。

> Large Language Models (LLMs) are transforming artificial intelligence, evolving into task-oriented systems capable of autonomous planning and execution. One of the primary applications of LLMs is conversational AI systems, which must navigate multi-turn dialogues, integrate domain-specific APIs, and adhere to strict policy constraints. However, evaluating these agents remains a significant challenge, as traditional methods fail to capture the complexity and variability of real-world interactions. We introduce IntellAgent, a scalable, open-source multi-agent framework designed to evaluate conversational AI systems comprehensively. IntellAgent automates the creation of diverse, synthetic benchmarks by combining policy-driven graph modeling, realistic event generation, and interactive user-agent simulations. This innovative approach provides fine-grained diagnostics, addressing the limitations of static and manually curated benchmarks with coarse-grained metrics. IntellAgent represents a paradigm shift in evaluating conversational AI. By simulating realistic, multi-policy scenarios across varying levels of complexity, IntellAgent captures the nuanced interplay of agent capabilities and policy constraints. Unlike traditional methods, it employs a graph-based policy model to represent relationships, likelihoods, and complexities of policy interactions, enabling highly detailed diagnostics. IntellAgent also identifies critical performance gaps, offering actionable insights for targeted optimization. Its modular, open-source design supports seamless integration of new domains, policies, and APIs, fostering reproducibility and community collaboration. Our findings demonstrate that IntellAgent serves as an effective framework for advancing conversational AI by addressing challenges in bridging research and deployment. The framework is available at https://github.com/plurai-ai/intellagent

[Arxiv](https://arxiv.org/abs/2501.11067)