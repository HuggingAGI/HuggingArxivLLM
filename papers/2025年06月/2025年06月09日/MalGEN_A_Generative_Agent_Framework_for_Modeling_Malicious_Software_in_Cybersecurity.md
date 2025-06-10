# MalGEN：网络安全领域恶意软件建模的生成式智能体框架

发布时间：2025年06月09日

`Agent` `网络安全` `恶意软件`

> MalGEN: A Generative Agent Framework for Modeling Malicious Software in Cybersecurity

# 摘要

> 大型语言模型（LLMs）的双重用途性质给网络安全带来了严峻挑战。虽然LLM增强了防御者的自动化和推理能力，但也带来了被滥用生成规避性AI恶意软件的风险。面对这一新兴威胁，研究社区缺乏有效的工具来模拟此类行为以进行测试和防御准备。为此，我们提出了MalGEN——一个多智能体框架，通过模拟协同对抗行为生成多样化的、基于活动的恶意软件样本。这些智能体在专为道德和防御研究设计的受控环境中协作，模拟攻击者的工作流程，包括载荷规划、能力选择和规避策略。通过MalGEN，我们成功合成了十种新型恶意软件样本，并将其与领先的反病毒和行为检测引擎进行了对比评估。结果显示，多个样本具备隐蔽性和规避性特征，成功绕过了现有防御机制，这充分验证了MalGEN模拟复杂和新型威胁的能力。MalGEN不仅将LLM滥用的威胁转化为主动防御的机会，还为评估和强化网络安全系统提供了一个宝贵框架。它解决了数据稀缺问题，支持严格的测试，并助力开发具有韧性和未来适用性的检测策略。

> The dual use nature of Large Language Models (LLMs) presents a growing challenge in cybersecurity. While LLM enhances automation and reasoning for defenders, they also introduce new risks, particularly their potential to be misused for generating evasive, AI crafted malware. Despite this emerging threat, the research community currently lacks controlled and extensible tools that can simulate such behavior for testing and defense preparation. We present MalGEN, a multi agent framework that simulates coordinated adversarial behavior to generate diverse, activity driven malware samples. The agents work collaboratively to emulate attacker workflows, including payload planning, capability selection, and evasion strategies, within a controlled environment built for ethical and defensive research. Using MalGEN, we synthesized ten novel malware samples and evaluated them against leading antivirus and behavioral detection engines. Several samples exhibited stealthy and evasive characteristics that bypassed current defenses, validating MalGEN's ability to model sophisticated and new threats. By transforming the threat of LLM misuse into an opportunity for proactive defense, MalGEN offers a valuable framework for evaluating and strengthening cybersecurity systems. The framework addresses data scarcity, enables rigorous testing, and supports the development of resilient and future ready detection strategies.

[Arxiv](https://arxiv.org/abs/2506.07586)