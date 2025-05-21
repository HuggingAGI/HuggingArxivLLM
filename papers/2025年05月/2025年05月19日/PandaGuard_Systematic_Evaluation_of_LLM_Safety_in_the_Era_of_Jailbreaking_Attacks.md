# PandaGuard：越狱攻击时代大型语言模型安全的全面评估

发布时间：2025年05月19日

`LLM理论` `网络安全` `人工智能安全`

> PandaGuard: Systematic Evaluation of LLM Safety in the Era of Jailbreaking Attacks

# 摘要

> 大型语言模型（LLMs）虽然能力出众，但仍然容易受到名为 jailbreak 的对抗性提示攻击，这些攻击能绕过安全对齐机制，导致有害输出。尽管LLM安全研究投入不断增加，现有评估仍显零散，多聚焦于孤立的攻击或防御技术，缺乏系统性、可重复的分析。为此，我们推出了PandaGuard——一个统一且模块化的框架，将LLM的越狱安全建模为由攻击者、防御者和裁判组成的多智能体系统。该框架集成了19种攻击方法、12种防御机制及多种裁决策略，依托灵活的插件架构，支持多样化的LLM接口、交互模式及基于配置的实验，显著提升了可重复性和实际应用潜力。基于此框架，我们开发了PandaBench——一个全面基准测试平台，评估49种LLMs中攻击与防御方法的交互效果，涵盖多种裁决方法，实验规模达300亿令牌。通过广泛评估，我们揭示了模型漏洞、防御成本效益及裁判一致性的关键洞见。研究发现，单一防御方案难以在所有维度上最优，而裁判意见分歧会显著影响安全评估结果。我们公开代码、配置及评估数据，助力透明且可重复的LLM安全研究。

> Large language models (LLMs) have achieved remarkable capabilities but remain vulnerable to adversarial prompts known as jailbreaks, which can bypass safety alignment and elicit harmful outputs. Despite growing efforts in LLM safety research, existing evaluations are often fragmented, focused on isolated attack or defense techniques, and lack systematic, reproducible analysis. In this work, we introduce PandaGuard, a unified and modular framework that models LLM jailbreak safety as a multi-agent system comprising attackers, defenders, and judges. Our framework implements 19 attack methods and 12 defense mechanisms, along with multiple judgment strategies, all within a flexible plugin architecture supporting diverse LLM interfaces, multiple interaction modes, and configuration-driven experimentation that enhances reproducibility and practical deployment. Built on this framework, we develop PandaBench, a comprehensive benchmark that evaluates the interactions between these attack/defense methods across 49 LLMs and various judgment approaches, requiring over 3 billion tokens to execute. Our extensive evaluation reveals key insights into model vulnerabilities, defense cost-performance trade-offs, and judge consistency. We find that no single defense is optimal across all dimensions and that judge disagreement introduces nontrivial variance in safety assessments. We release the code, configurations, and evaluation results to support transparent and reproducible research in LLM safety.

[Arxiv](https://arxiv.org/abs/2505.13862)