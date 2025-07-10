# 大型语言模型的隐忧：代理攻击如何实现全面计算机接管

发布时间：2025年07月09日

`Agent` `网络安全` `人工智能`

> The Dark Side of LLMs Agent-based Attacks for Complete Computer Takeover

# 摘要

> 大型语言模型（LLM）代理和多智能体系统的快速采用为自然语言处理和生成带来了前所未有的能力。然而，这些系统不仅带来了前所未有的能力，同时也引入了超越传统提示注入攻击的前所未有的安全漏洞。本文首次全面评估了LLM代理作为攻击向量的能力，这些代理能够通过利用智能体AI系统中自主实体之间交互和影响的信任边界，实现对计算机的完全接管。

我们演示了对手如何利用三种不同的攻击面——直接提示注入、RAG后门攻击和智能体间信任利用——迫使流行的LLM（包括GPT-4o、Claude-4和Gemini-2.5）自主地在受害者机器上安装和执行恶意软件。我们对17个最先进的LLM的评估揭示了一个令人震惊的漏洞等级：尽管41.2%的模型易受直接提示注入攻击，但52.9%的模型易受RAG后门攻击，而高达82.4%的模型可通过智能体间信任利用被攻陷。

值得注意的是，我们发现成功抵御直接恶意命令的LLM会在收到同级智能体的请求时执行相同的恶意负载，这揭示了当前多智能体安全模型中的根本性缺陷。我们的研究结果表明，仅5.9%的测试模型（1/17）对所有攻击向量表现出抵抗力，大多数模型则表现出依赖上下文的安全行为，从而产生可被利用的盲点。我们的发现还凸显了提高对LLM安全风险的认识和研究的必要性，揭示了网络威胁范式的转变，其中AI工具本身成为了复杂的攻击向量。


> The rapid adoption of Large Language Model (LLM) agents and multi-agent systems enables unprecedented capabilities in natural language processing and generation. However, these systems have introduced unprecedented security vulnerabilities that extend beyond traditional prompt injection attacks. This paper presents the first comprehensive evaluation of LLM agents as attack vectors capable of achieving complete computer takeover through the exploitation of trust boundaries within agentic AI systems where autonomous entities interact and influence each other. We demonstrate that adversaries can leverage three distinct attack surfaces - direct prompt injection, RAG backdoor attacks, and inter-agent trust exploitation - to coerce popular LLMs (including GPT-4o, Claude-4 and Gemini-2.5) into autonomously installing and executing malware on victim machines. Our evaluation of 17 state-of-the-art LLMs reveals an alarming vulnerability hierarchy: while 41.2% of models succumb to direct prompt injection, 52.9% are vulnerable to RAG backdoor attacks, and a critical 82.4% can be compromised through inter-agent trust exploitation. Notably, we discovered that LLMs which successfully resist direct malicious commands will execute identical payloads when requested by peer agents, revealing a fundamental flaw in current multi-agent security models. Our findings demonstrate that only 5.9% of tested models (1/17) proved resistant to all attack vectors, with the majority exhibiting context-dependent security behaviors that create exploitable blind spots. Our findings also highlight the need to increase awareness and research on the security risks of LLMs, showing a paradigm shift in cybersecurity threats, where AI tools themselves become sophisticated attack vectors.

[Arxiv](https://arxiv.org/abs/2507.06850)