# AutoRedTeamer：自主红队测试，持续攻击整合

发布时间：2025年03月19日

`LLM应用` `安全评估` `AI系统`

> AutoRedTeamer: Autonomous Red Teaming with Lifelong Attack Integration

# 摘要

> 大型语言模型（LLMs）能力日益增强，安全性和安全性评估变得至关重要。当前红队测试方法虽在评估 LLM 漏洞方面有所进展，但依赖人工输入且未能全面覆盖新兴攻击向量。本文推出 AutoRedTeamer，一款针对 LLM 的全自动端到端红队测试框架。AutoRedTeamer 结合多智能体架构与记忆引导攻击选择机制，持续发现和整合新攻击向量。其双智能体框架包含一个红队测试智能体，可基于高级风险类别生成和执行测试用例，以及一个策略提案智能体，通过分析最新研究自主发现并实现新攻击。这种模块化设计使 AutoRedTeamer 能够适应新兴威胁，同时保持在现有攻击向量上的强劲性能。我们在多种评估设置中展示了 AutoRedTeamer 的有效性，其在 HarmBench 上针对 Llama-3.1-70B 的攻击成功率比现有方法高出 20%，同时将计算成本降低了 46%。AutoRedTeamer 在生成测试用例时也达到了与人工策划基准相当的多样性，提供了一个全面、可扩展且持续演进的框架，用于评估 AI 系统的安全性。

> As large language models (LLMs) become increasingly capable, security and safety evaluation are crucial. While current red teaming approaches have made strides in assessing LLM vulnerabilities, they often rely heavily on human input and lack comprehensive coverage of emerging attack vectors. This paper introduces AutoRedTeamer, a novel framework for fully automated, end-to-end red teaming against LLMs. AutoRedTeamer combines a multi-agent architecture with a memory-guided attack selection mechanism to enable continuous discovery and integration of new attack vectors. The dual-agent framework consists of a red teaming agent that can operate from high-level risk categories alone to generate and execute test cases and a strategy proposer agent that autonomously discovers and implements new attacks by analyzing recent research. This modular design allows AutoRedTeamer to adapt to emerging threats while maintaining strong performance on existing attack vectors. We demonstrate AutoRedTeamer's effectiveness across diverse evaluation settings, achieving 20% higher attack success rates on HarmBench against Llama-3.1-70B while reducing computational costs by 46% compared to existing approaches. AutoRedTeamer also matches the diversity of human-curated benchmarks in generating test cases, providing a comprehensive, scalable, and continuously evolving framework for evaluating the security of AI systems.

[Arxiv](https://arxiv.org/abs/2503.15754)