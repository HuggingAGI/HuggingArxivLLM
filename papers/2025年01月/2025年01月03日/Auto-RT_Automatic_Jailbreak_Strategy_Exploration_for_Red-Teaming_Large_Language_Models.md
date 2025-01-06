# Auto-RT: 自动探索红队策略，对抗大型语言模型的越狱

发布时间：2025年01月03日

`LLM应用

理由：这篇论文主要讨论了自动化红队测试框架Auto-RT，用于揭示大型语言模型（LLMs）的漏洞。虽然涉及强化学习等技术，但其核心目标是优化攻击策略以检测LLMs的安全漏洞，属于LLM在实际应用中的安全性和漏洞检测问题。因此，将其归类为LLM应用。` `人工智能` `网络安全`

> Auto-RT: Automatic Jailbreak Strategy Exploration for Red-Teaming Large Language Models

# 摘要

> 自动化红队测试是揭示大型语言模型（LLMs）漏洞的重要手段。然而，现有方法多局限于孤立的安全缺陷，难以应对动态防御和高效发现复杂漏洞。为此，我们提出了Auto-RT，一个基于强化学习的框架，能够自动探索并优化复杂攻击策略，通过恶意查询有效揭示安全漏洞。我们引入了两大机制：1）早期终止探索，聚焦高潜力攻击策略以加速探索；2）渐进奖励跟踪算法结合中间降级模型，动态优化搜索轨迹，确保成功利用漏洞。在多种LLMs上的实验表明，Auto-RT显著提升了探索效率，自动优化攻击策略，检测到更广泛的漏洞，检测速度更快，成功率比现有方法高出16.63%。

> Automated red-teaming has become a crucial approach for uncovering vulnerabilities in large language models (LLMs). However, most existing methods focus on isolated safety flaws, limiting their ability to adapt to dynamic defenses and uncover complex vulnerabilities efficiently. To address this challenge, we propose Auto-RT, a reinforcement learning framework that automatically explores and optimizes complex attack strategies to effectively uncover security vulnerabilities through malicious queries. Specifically, we introduce two key mechanisms to reduce exploration complexity and improve strategy optimization: 1) Early-terminated Exploration, which accelerate exploration by focusing on high-potential attack strategies; and 2) Progressive Reward Tracking algorithm with intermediate downgrade models, which dynamically refine the search trajectory toward successful vulnerability exploitation. Extensive experiments across diverse LLMs demonstrate that, by significantly improving exploration efficiency and automatically optimizing attack strategies, Auto-RT detects a boarder range of vulnerabilities, achieving a faster detection speed and 16.63\% higher success rates compared to existing methods.

[Arxiv](https://arxiv.org/abs/2501.01830)