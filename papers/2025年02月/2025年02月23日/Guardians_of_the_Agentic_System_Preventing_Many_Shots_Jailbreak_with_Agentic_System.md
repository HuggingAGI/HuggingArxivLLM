# 智能体系统的守护者：用智能体系统防止多次尝试破解

发布时间：2025年02月23日

`Agent` `人工智能`

> Guardians of the Agentic System: Preventing Many Shots Jailbreak with Agentic System

# 摘要

> 基于大型语言模型的自主AI代理能够为社会各领域创造显著价值，但同时也面临来自恶意攻击者的安全威胁，这些问题亟需解决方案以确保信任与安全。针对多轮越狱攻击和欺骗性对齐等高级威胁，现有监督训练中的静态防护措施已显不足，这凸显了研究动态防御机制的重要性。传统静态防护与动态多代理系统的结合无法有效应对这些新型攻击。我们致力于通过开发新型评估框架，识别并抵御潜在威胁，确保LLM代理的安全运行。我们的研究采用三种审查方法，结合逆图灵测试检测流氓代理，通过多代理模拟分析欺骗性对齐，并在GEMINI 1.5 pro、llama-3.3-70B和deepseek r1等模型上进行工具中介的对抗测试，开发出反越狱系统。该系统展现出强大的检测能力，如对GEMINI 1.5 pro的检测准确率高达94%，但在长时间攻击下仍存在漏洞，提示长度增加导致攻击成功率（ASR）上升，多样性指标失效，暴露出复杂系统故障。这些发现表明，需要一种基于主动监控的灵活安全系统，由代理自身执行监控，同时结合系统管理员的适应性干预，以弥补现有模型的漏洞，防止系统脆弱性。因此，本研究旨在解决这些问题，提出一个全面框架，有效应对安全威胁。

> The autonomous AI agents using large language models can create undeniable values in all span of the society but they face security threats from adversaries that warrants immediate protective solutions because trust and safety issues arise. Considering the many-shot jailbreaking and deceptive alignment as some of the main advanced attacks, that cannot be mitigated by the static guardrails used during the supervised training, points out a crucial research priority for real world robustness. The combination of static guardrails in dynamic multi-agent system fails to defend against those attacks. We intend to enhance security for LLM-based agents through the development of new evaluation frameworks which identify and counter threats for safe operational deployment. Our work uses three examination methods to detect rogue agents through a Reverse Turing Test and analyze deceptive alignment through multi-agent simulations and develops an anti-jailbreaking system by testing it with GEMINI 1.5 pro and llama-3.3-70B, deepseek r1 models using tool-mediated adversarial scenarios. The detection capabilities are strong such as 94\% accuracy for GEMINI 1.5 pro yet the system suffers persistent vulnerabilities when under long attacks as prompt length increases attack success rates (ASR) and diversity metrics become ineffective in prediction while revealing multiple complex system faults. The findings demonstrate the necessity of adopting flexible security systems based on active monitoring that can be performed by the agents themselves together with adaptable interventions by system admin as the current models can create vulnerabilities that can lead to the unreliable and vulnerable system. So, in our work, we try to address such situations and propose a comprehensive framework to counteract the security issues.

[Arxiv](https://arxiv.org/abs/2502.16750)