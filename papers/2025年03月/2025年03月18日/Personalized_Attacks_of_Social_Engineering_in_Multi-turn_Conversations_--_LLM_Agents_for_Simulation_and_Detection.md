# 个性化社交工程攻击在多轮对话中的应用——LLM智能体用于模拟与检测

发布时间：2025年03月18日

`Agent` `社交媒体` `信息安全`

> Personalized Attacks of Social Engineering in Multi-turn Conversations -- LLM Agents for Simulation and Detection

# 摘要

> 对话代理，特别是基于大型语言模型（LLMs）的聊天机器人，的快速发展为社交媒体平台带来了显著的社会工程（SE）攻击风险。由于对话的动态性，多轮、基于聊天的SE检测比单实例检测复杂得多。缓解这一威胁的关键在于理解SE攻击的运行机制，特别是攻击者如何利用漏洞以及受害者的人格特质如何导致他们易受攻击。本研究提出了一种基于LLM的智能体框架SE-VSim，通过生成多轮对话来模拟SE攻击机制。我们设计了具有不同人格特质的受害者智能体，以评估心理档案如何影响易受操纵性。基于1000多场模拟对话的数据集，我们分析了攻击者伪装成招聘人员、资助机构和记者等身份，试图获取敏感信息的攻击场景。基于此分析，我们提出了一个概念验证方案SE-OmniGuard，通过利用对受害者人格的先验知识、评估攻击策略以及监控对话中的信息交换，为用户提供个性化保护，识别潜在的SE攻击尝试。

> The rapid advancement of conversational agents, particularly chatbots powered by Large Language Models (LLMs), poses a significant risk of social engineering (SE) attacks on social media platforms. SE detection in multi-turn, chat-based interactions is considerably more complex than single-instance detection due to the dynamic nature of these conversations. A critical factor in mitigating this threat is understanding the mechanisms through which SE attacks operate, specifically how attackers exploit vulnerabilities and how victims' personality traits contribute to their susceptibility. In this work, we propose an LLM-agentic framework, SE-VSim, to simulate SE attack mechanisms by generating multi-turn conversations. We model victim agents with varying personality traits to assess how psychological profiles influence susceptibility to manipulation. Using a dataset of over 1000 simulated conversations, we examine attack scenarios in which adversaries, posing as recruiters, funding agencies, and journalists, attempt to extract sensitive information. Based on this analysis, we present a proof of concept, SE-OmniGuard, to offer personalized protection to users by leveraging prior knowledge of the victims personality, evaluating attack strategies, and monitoring information exchanges in conversations to identify potential SE attempts.

[Arxiv](https://arxiv.org/abs/2503.15552)