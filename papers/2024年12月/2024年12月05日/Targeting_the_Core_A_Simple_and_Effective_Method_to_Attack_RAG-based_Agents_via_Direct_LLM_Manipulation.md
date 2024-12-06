# 针对核心：一种通过直接操控 LLM 来攻击基于 RAG 的代理的简单且有效的方法

发布时间：2024年12月05日

`Agent` `人工智能` `人机交互`

> Targeting the Core: A Simple and Effective Method to Attack RAG-based Agents via Direct LLM Manipulation

# 摘要

> AI 代理由大型语言模型（LLMs）驱动，实现了无缝、自然且能感知上下文的通信，从而变革了人机交互。尽管这些进展带来了极大的效用，但也继承并放大了诸如偏见、公平性问题、幻觉、隐私泄露以及缺乏透明度等固有安全风险。本文探究了一个关键漏洞：针对 AI 代理中 LLM 核心的对抗性攻击。具体而言，我们测试了这样一种假设，即像	extit{Ignore the document}这样看似简单的对抗性前缀，能够绕过其上下文保障措施，迫使 LLMs 生成危险或非预期的输出。通过实验，我们展示出了高攻击成功率（ASR），揭示了现有 LLM 防御的脆弱性。这些发现凸显出迫切需要为减轻 LLM 层面以及更广泛的基于代理的架构中的漏洞，量身定制强大的多层安全措施。

> AI agents, powered by large language models (LLMs), have transformed human-computer interactions by enabling seamless, natural, and context-aware communication. While these advancements offer immense utility, they also inherit and amplify inherent safety risks such as bias, fairness, hallucinations, privacy breaches, and a lack of transparency. This paper investigates a critical vulnerability: adversarial attacks targeting the LLM core within AI agents. Specifically, we test the hypothesis that a deceptively simple adversarial prefix, such as \textit{Ignore the document}, can compel LLMs to produce dangerous or unintended outputs by bypassing their contextual safeguards. Through experimentation, we demonstrate a high attack success rate (ASR), revealing the fragility of existing LLM defenses. These findings emphasize the urgent need for robust, multi-layered security measures tailored to mitigate vulnerabilities at the LLM level and within broader agent-based architectures.

[Arxiv](https://arxiv.org/abs/2412.04415)