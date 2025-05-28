# IRCopilot：基于大型语言模型的自动化事件响应系统

发布时间：2025年05月27日

`LLM应用` `网络安全` `事件响应`

> IRCopilot: Automated Incident Response with Large Language Models

# 摘要

> 事件响应在应对网络攻击中至关重要。然而，随着全球网络威胁的日益加剧，传统方法在复杂环境中的效果大打折扣。虽然大型语言模型（LLMs）在威胁检测方面表现突出，但其在事件响应自动化方面的能力仍显不足。为填补这一空白，我们建立了一个基于真实任务的评估基准，深入分析了LLMs在事件响应中的局限性，包括上下文丢失、幻觉现象、隐私问题以及建议能力的不足。针对这些挑战，我们开发了IRCopilot框架，通过四个协作组件模拟真实团队的响应流程，有效解决了现有模型的痛点。我们的方法通过多样化设计和责任分割，显著提升了系统的实用性和效率。实验数据显示，IRCopilot在各项任务中均超越传统模型，完成率提升显著。此外，其在实际场景中的表现也验证了其强大的应用价值。

> Incident response plays a pivotal role in mitigating the impact of cyber attacks. In recent years, the intensity and complexity of global cyber threats have grown significantly, making it increasingly challenging for traditional threat detection and incident response methods to operate effectively in complex network environments. While Large Language Models (LLMs) have shown great potential in early threat detection, their capabilities remain limited when it comes to automated incident response after an intrusion. To address this gap, we construct an incremental benchmark based on real-world incident response tasks to thoroughly evaluate the performance of LLMs in this domain. Our analysis reveals several key challenges that hinder the practical application of contemporary LLMs, including context loss, hallucinations, privacy protection concerns, and their limited ability to provide accurate, context-specific recommendations. In response to these challenges, we propose IRCopilot, a novel framework for automated incident response powered by LLMs. IRCopilot mimics the three dynamic phases of a real-world incident response team using four collaborative LLM-based session components. These components are designed with clear divisions of responsibility, reducing issues such as hallucinations and context loss. Our method leverages diverse prompt designs and strategic responsibility segmentation, significantly improving the system's practicality and efficiency. Experimental results demonstrate that IRCopilot outperforms baseline LLMs across key benchmarks, achieving sub-task completion rates of 150%, 138%, 136%, 119%, and 114% for various response tasks. Moreover, IRCopilot exhibits robust performance on public incident response platforms and in real-world attack scenarios, showcasing its strong applicability.

[Arxiv](https://arxiv.org/abs/2505.20945)