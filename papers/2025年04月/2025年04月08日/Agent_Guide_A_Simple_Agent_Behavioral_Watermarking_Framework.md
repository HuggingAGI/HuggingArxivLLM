# Agent Guide：简单易用的智能体行为水印框架

发布时间：2025年04月08日

`Agent` `社交媒体` `网络安全`

> Agent Guide: A Simple Agent Behavioral Watermarking Framework

# 摘要

> 智能体在社交媒体等数字生态系统中的广泛应用引发了关于可追溯性和问责制的担忧，尤其是在网络安全和数字内容保护方面。传统的大型语言模型（LLM）水印技术由于依赖令牌级别的操作，难以应用于智能体，因为行为令牌化和行为到动作转换过程中的信息丢失带来了挑战。为了解决这些问题，我们提出了Agent Guide，这是一种新颖的行为水印框架。它通过引导智能体的高层决策（行为）来嵌入水印，同时保留特定执行（动作）的自然性。我们的方法将智能体行为分解为两个级别：行为（例如选择收藏）和动作（例如使用特定标签收藏），并在行为概率分布中应用水印引导的偏差。我们采用基于z统计量的统计分析来检测水印，确保在多轮中可靠提取。在具有多样化智能体配置文件的社交媒体场景中的实验表明，Agent Guide实现了有效的水印检测，且误报率较低。我们的框架为智能体水印提供了一种实用且健壮的解决方案，可用于识别恶意智能体和保护专有智能体系统。

> The increasing deployment of intelligent agents in digital ecosystems, such as social media platforms, has raised significant concerns about traceability and accountability, particularly in cybersecurity and digital content protection. Traditional large language model (LLM) watermarking techniques, which rely on token-level manipulations, are ill-suited for agents due to the challenges of behavior tokenization and information loss during behavior-to-action translation. To address these issues, we propose Agent Guide, a novel behavioral watermarking framework that embeds watermarks by guiding the agent's high-level decisions (behavior) through probability biases, while preserving the naturalness of specific executions (action). Our approach decouples agent behavior into two levels, behavior (e.g., choosing to bookmark) and action (e.g., bookmarking with specific tags), and applies watermark-guided biases to the behavior probability distribution. We employ a z-statistic-based statistical analysis to detect the watermark, ensuring reliable extraction over multiple rounds. Experiments in a social media scenario with diverse agent profiles demonstrate that Agent Guide achieves effective watermark detection with a low false positive rate. Our framework provides a practical and robust solution for agent watermarking, with applications in identifying malicious agents and protecting proprietary agent systems.

[Arxiv](https://arxiv.org/abs/2504.05871)