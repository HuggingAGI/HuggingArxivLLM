# 构建动态斯塔克伯格博弈框架，用于智能体AI防御大型语言模型越狱攻击

发布时间：2025年07月10日

`Agent` `模型安全`

> A Dynamic Stackelberg Game Framework for Agentic AI Defense Against LLM Jailbreaking

# 摘要

> 随着大型语言模型 (LLMs) 在关键应用中的广泛应用，攻击者操纵模型以绕过安全机制的越狱攻击已成为重要问题。本文提出了一种动态 Stackelberg 博弈框架，用于建模 LLM 越狱攻击中攻击者与防御者的交互。框架将提示-响应动态视为一种序贯扩展形式博弈，其中作为领导者的防御者将承诺一种策略，同时预判攻击者的最优响应。我们提出了一种新型的智能体 AI 解决方案——"Purple Agent"，它通过快速探索随机树 (RRT) 集成对抗性探索与防御策略。Purple Agent 主动模拟潜在攻击轨迹并积极干预，以防止有害输出。该方法为分析对抗动态提供了一种系统化的方法，并为缓解越狱风险奠定了基础。

> As large language models (LLMs) are increasingly deployed in critical applications, the challenge of jailbreaking, where adversaries manipulate the models to bypass safety mechanisms, has become a significant concern. This paper presents a dynamic Stackelberg game framework to model the interactions between attackers and defenders in the context of LLM jailbreaking. The framework treats the prompt-response dynamics as a sequential extensive-form game, where the defender, as the leader, commits to a strategy while anticipating the attacker's optimal responses. We propose a novel agentic AI solution, the "Purple Agent," which integrates adversarial exploration and defensive strategies using Rapidly-exploring Random Trees (RRT). The Purple Agent actively simulates potential attack trajectories and intervenes proactively to prevent harmful outputs. This approach offers a principled method for analyzing adversarial dynamics and provides a foundation for mitigating the risk of jailbreaking.

[Arxiv](https://arxiv.org/abs/2507.08207)