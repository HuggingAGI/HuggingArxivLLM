# 通过通信攻击红队测试 LLM 多智能体系统

发布时间：2025年02月20日

`Agent` `多智能体系统`

> Red-Teaming LLM Multi-Agent Systems via Communication Attacks

# 摘要

> 基于大型语言模型的多智能体系统（LLM-MAS）带来了复杂问题解决能力的革命性提升，通过基于消息的通信实现了智能体间的高效协作。然而，这一系统的通信框架在提升协作能力的同时，也引入了一个关键且尚未被深入研究的安全漏洞。本研究提出了一种名为中间人攻击（AiTM）的新型攻击手段，该攻击通过拦截和操纵智能体间的消息，利用了LLM-MAS中基础的通信机制。与现有仅针对单个智能体的攻击不同，AiTM展示了攻击者如何通过操控智能体间传递的消息，对整个多智能体系统发起攻击。为应对控制有限和通信格式受限的挑战，我们开发了一个基于LLM的对抗智能体，并为其配备了反射机制，使其能够生成语境感知的恶意指令。通过在多种框架、通信结构和现实世界应用场景中的全面评估，我们发现LLM-MAS系统易受基于通信的攻击，这凸显了在多智能体系统中建立强大安全措施的迫切需求。

> Large Language Model-based Multi-Agent Systems (LLM-MAS) have revolutionized complex problem-solving capability by enabling sophisticated agent collaboration through message-based communications. While the communication framework is crucial for agent coordination, it also introduces a critical yet unexplored security vulnerability. In this work, we introduce Agent-in-the-Middle (AiTM), a novel attack that exploits the fundamental communication mechanisms in LLM-MAS by intercepting and manipulating inter-agent messages. Unlike existing attacks that compromise individual agents, AiTM demonstrates how an adversary can compromise entire multi-agent systems by only manipulating the messages passing between agents. To enable the attack under the challenges of limited control and role-restricted communication format, we develop an LLM-powered adversarial agent with a reflection mechanism that generates contextually-aware malicious instructions. Our comprehensive evaluation across various frameworks, communication structures, and real-world applications demonstrates that LLM-MAS is vulnerable to communication-based attacks, highlighting the need for robust security measures in multi-agent systems.

[Arxiv](https://arxiv.org/abs/2502.14847)