# LLM中的对抗测试：洞察决策机制中的潜在风险

发布时间：2025年05月19日

`LLM理论` `AI安全` `对齐研究`

> Adversarial Testing in LLMs: Insights into Decision-Making Vulnerabilities

# 摘要

> 大型语言模型（LLMs）正逐步融入现实世界的决策系统，但理解其行为漏洞仍是AI安全与对齐领域的重大挑战。现有评估指标虽关注推理准确性和事实正确性，却忽视了LLMs在对抗性操控下的稳健性及动态环境中的策略适应能力。本文提出了一种对抗性评估框架，旨在系统性地对LLMs在交互式和对抗性条件下的决策过程进行压力测试。我们借鉴认知心理学与博弈论的方法，重点考察了模型在双臂老虎机任务与多轮信任任务中的表现。这些任务涵盖了探索与开发权衡、社会合作以及策略灵活性等关键方面。通过将该框架应用于GPT-3.5、GPT-4、Gemini-1.5和DeepSeek-V3等先进LLMs，我们揭示了模型在对抗性操控下的特异性弱点以及策略适应性中的僵化问题。研究发现凸显了不同模型间的行为模式差异，并强调了适应性与公平性识别对于可靠AI部署的重要性。本研究并非旨在提供性能基准，而是提出了一种诊断LLM代理决策弱点的方法论，为对齐与安全研究提供了可操作的洞见。

> As Large Language Models (LLMs) become increasingly integrated into real-world decision-making systems, understanding their behavioural vulnerabilities remains a critical challenge for AI safety and alignment. While existing evaluation metrics focus primarily on reasoning accuracy or factual correctness, they often overlook whether LLMs are robust to adversarial manipulation or capable of using adaptive strategy in dynamic environments. This paper introduces an adversarial evaluation framework designed to systematically stress-test the decision-making processes of LLMs under interactive and adversarial conditions. Drawing on methodologies from cognitive psychology and game theory, our framework probes how models respond in two canonical tasks: the two-armed bandit task and the Multi-Round Trust Task. These tasks capture key aspects of exploration-exploitation trade-offs, social cooperation, and strategic flexibility. We apply this framework to several state-of-the-art LLMs, including GPT-3.5, GPT-4, Gemini-1.5, and DeepSeek-V3, revealing model-specific susceptibilities to manipulation and rigidity in strategy adaptation. Our findings highlight distinct behavioral patterns across models and emphasize the importance of adaptability and fairness recognition for trustworthy AI deployment. Rather than offering a performance benchmark, this work proposes a methodology for diagnosing decision-making weaknesses in LLM-based agents, providing actionable insights for alignment and safety research.

[Arxiv](https://arxiv.org/abs/2505.13195)