# # 摘要  
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月22日

`Agent

理由：这篇论文主要探讨了基于大型语言模型的多智能体规划系统在面对虚假信息时的风险评估和解决方案。虽然提到了大型语言模型，但核心内容集中在多智能体系统的规划、欺诈评估和反欺诈策略上，因此归类为Agent。` `互联网`

> Is Your LLM-Based Multi-Agent a Reliable Real-World Planner? Exploring Fraud Detection in Travel Planning

# 摘要

> 基于大型语言模型的多智能体规划的兴起，借助先进框架实现了自主与协作任务执行。然而，某些系统过度依赖于容易被虚假信息污染的平台，如评论网站和社交媒体，这些平台充斥着虚假评价或误导性描述。这种依赖性带来了潜在风险，可能导致经济损失并损害用户体验。为了评估规划系统在实际应用中的风险，我们提出了	extbf{WandaPlan}，一个模拟现实数据并注入欺骗性内容的评估环境。我们针对三种欺诈场景评估系统表现：虚假信息欺诈、团队协同多人欺诈，以及层级递进多轮欺诈。研究发现，现有框架在优先考虑任务效率时忽视了数据真实性的关键问题。同时，我们验证了WandaPlan的通用性，能够有效评估真实世界开源规划框架的风险。为降低欺诈风险，我们建议引入反欺诈代理，为可靠规划提供解决方案。


> The rise of Large Language Model-based Multi-Agent Planning has leveraged advanced frameworks to enable autonomous and collaborative task execution. Some systems rely on platforms like review sites and social media, which are prone to fraudulent information, such as fake reviews or misleading descriptions. This reliance poses risks, potentially causing financial losses and harming user experiences. To evaluate the risk of planning systems in real-world applications, we introduce \textbf{WandaPlan}, an evaluation environment mirroring real-world data and injected with deceptive content. We assess system performance across three fraud cases: Misinformation Fraud, Team-Coordinated Multi-Person Fraud, and Level-Escalating Multi-Round Fraud. We reveal significant weaknesses in existing frameworks that prioritize task efficiency over data authenticity. At the same time, we validate WandaPlan's generalizability, capable of assessing the risks of real-world open-source planning frameworks. To mitigate the risk of fraud, we propose integrating an anti-fraud agent, providing a solution for reliable planning.

[Arxiv](https://arxiv.org/abs/2505.16557)