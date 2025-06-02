# 基于可信度评分的抗攻击多智能体大语言模型系统

发布时间：2025年05月30日

`LLM应用` `多智能体` `问答系统`

> An Adversary-Resistant Multi-Agent LLM System via Credibility Scoring

# 摘要

> 多智能体LLM系统在各领域表现强劲，但极易受到对抗性和低效代理的影响。为解决这一问题，本文提出了一种基于可信度评分的通用抗对抗多智能体LLM框架。我们通过迭代游戏建模协作式问答过程，智能体在此过程中沟通协作，共同完成最终输出。系统为每个智能体分配可信度评分，用于整合团队输出。这些评分基于智能体在过往问答中的贡献逐步学习获得。实验结果表明，我们的系统在多个任务和设置下，尤其是对抗性代理占多数的情况下，有效缓解了对抗性影响，增强了多智能体协作的韧性。

> While multi-agent LLM systems show strong capabilities in various domains, they are highly vulnerable to adversarial and low-performing agents. To resolve this issue, in this paper, we introduce a general and adversary-resistant multi-agent LLM framework based on credibility scoring. We model the collaborative query-answering process as an iterative game, where the agents communicate and contribute to a final system output. Our system associates a credibility score that is used when aggregating the team outputs. The credibility scores are learned gradually based on the past contributions of each agent in query answering. Our experiments across multiple tasks and settings demonstrate our system's effectiveness in mitigating adversarial influence and enhancing the resilience of multi-agent cooperation, even in the adversary-majority settings.

[Arxiv](https://arxiv.org/abs/2505.24239)