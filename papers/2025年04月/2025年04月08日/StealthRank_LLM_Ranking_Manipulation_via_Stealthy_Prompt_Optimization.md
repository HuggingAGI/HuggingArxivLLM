# StealthRank：通过隐秘提示工程优化LLM排名效果

发布时间：2025年04月08日

`LLM应用` `信息安全` `推荐系统`

> StealthRank: LLM Ranking Manipulation via Stealthy Prompt Optimization

# 摘要

> 将大型语言模型 (LLMs) 引入信息检索系统，为系统带来了新的安全挑战，尤其是对抗排序操控方面。我们提出了一种名为StealthRank的新型对抗排序攻击方法，能够在保持文本流畅性的同时，隐秘地操控基于LLM的产品推荐系统。与现有方法通常会引入可检测的异常不同，StealthRank采用了一种结合能量优化框架和Langevin动力学的独特机制，生成StealthRank提示 (SRPs)——这些嵌入在产品描述中的对抗文本序列能够微妙但有效地影响LLM的排序机制。通过在多个LLMs上的评估，我们发现StealthRank能够在不留下明显操控痕迹的情况下，显著提升目标产品的排名。实验结果表明，StealthRank在效果和隐秘性方面均优于现有最先进对抗排序基准，揭示了基于LLM的推荐系统中存在的关键性漏洞。

> The integration of large language models (LLMs) into information retrieval systems introduces new attack surfaces, particularly for adversarial ranking manipulations. We present StealthRank, a novel adversarial ranking attack that manipulates LLM-driven product recommendation systems while maintaining textual fluency and stealth. Unlike existing methods that often introduce detectable anomalies, StealthRank employs an energy-based optimization framework combined with Langevin dynamics to generate StealthRank Prompts (SRPs)-adversarial text sequences embedded within product descriptions that subtly yet effectively influence LLM ranking mechanisms. We evaluate StealthRank across multiple LLMs, demonstrating its ability to covertly boost the ranking of target products while avoiding explicit manipulation traces that can be easily detected. Our results show that StealthRank consistently outperforms state-of-the-art adversarial ranking baselines in both effectiveness and stealth, highlighting critical vulnerabilities in LLM-driven recommendation systems.

[Arxiv](https://arxiv.org/abs/2504.05804)