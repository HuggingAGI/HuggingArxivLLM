# CyGATE：基于博弈论的网络攻防引擎，优化补丁策略

发布时间：2025年08月01日

`LLM应用` `网络安全` `安全博弈`

> CyGATE: Game-Theoretic Cyber Attack-Defense Engine for Patch Strategy Optimization

# 摘要

> 现代网络攻击通常经过多个阶段，要求防御者在不确定条件下动态调整防御策略。虽然博弈论模型可以模拟攻击者与防御者的互动，但现有方法往往基于静态假设，且未能与实时威胁情报有效结合，限制了其灵活性。本文提出CyGATE框架，这是一个基于博弈论的模型，结合大型语言模型（LLMs）与检索增强生成（RAG）技术，优化攻击策略选择和补丁优先级排序。在双智能体场景下，CyGATE将网络冲突建模为跨网络杀伤链阶段的部分可观测随机博弈（POSG）。双方智能体均利用信念状态应对不确定性，攻击者根据风险变化和观察到的对手行为调整策略，而防御者则重新评估补丁优先级。该框架的灵活架构支持扩展至多智能体场景，涵盖协同攻击者、协作防御者或涉及多方利益相关者的复杂企业环境。在动态补丁调度场景下，CyGATE有效识别高风险漏洞，通过整合实时威胁情报提升适应性，借助不确定性条件下的战略预见性增强前瞻性，并通过优化资源使用提高效率。


> Modern cyber attacks unfold through multiple stages, requiring defenders to dynamically prioritize mitigations under uncertainty. While game-theoretic models capture attacker-defender interactions, existing approaches often rely on static assumptions and lack integration with real-time threat intelligence, limiting their adaptability. This paper presents CyGATE, a game-theoretic framework modeling attacker-defender interactions, using large language models (LLMs) with retrieval-augmented generation (RAG) to enhance tactic selection and patch prioritization. Applied to a two-agent scenario, CyGATE frames cyber conflicts as a partially observable stochastic game (POSG) across Cyber Kill Chain stages. Both agents use belief states to navigate uncertainty, with the attacker adapting tactics and the defender re-prioritizing patches based on evolving risks and observed adversary behavior. The framework's flexible architecture enables extension to multi-agent scenarios involving coordinated attackers, collaborative defenders, or complex enterprise environments with multiple stakeholders. Evaluated in a dynamic patch scheduling scenario, CyGATE effectively prioritizes high-risk vulnerabilities, enhancing adaptability through dynamic threat integration, strategic foresight by anticipating attacker moves under uncertainty, and efficiency by optimizing resource use.

[Arxiv](https://arxiv.org/abs/2508.00478)