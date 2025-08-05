# # BlockA2A：实现安全可验证的智能体间互操作性

发布时间：2025年08月02日

`Agent` `区块链`

> BlockA2A: Towards Secure and Verifiable Agent-to-Agent Interoperability

# 摘要

> 基于大型语言模型（LLMs）的智能体AI正在迅速改变企业生态系统，通过自主智能体执行复杂工作流。然而，我们发现LLM驱动的多智能体系统（MASes）面临多重安全威胁：分散的身份框架、不安全的通信渠道，以及缺乏针对拜占庭智能体和对抗性提示的防护。本文首次系统性分析了这些新兴的多智能体风险，并揭示传统安全策略为何难以应对这些威胁。我们提出BlockA2A，首个统一的多智能体信任框架，实现安全且可验证的智能体间互操作性。BlockA2A采用去中心化标识符（DIDs）实现跨域智能体精细认证，基于区块链的账本确保不可变审计，智能合约动态执行情境感知访问控制策略。BlockA2A消除了中心化信任瓶颈，保障消息真实性和执行完整性，并在智能体交互中实现问责。此外，我们提出防御编排引擎（DOE），通过实时机制主动中和攻击，包括拜占庭智能体标记、反应式执行终止和即时权限撤销。实证评估表明BlockA2A在抵御基于提示、通信、行为和系统性MAS攻击方面表现卓越。我们展示了其在现有MAS中的集成，并实现了在Google A2A协议中的实际应用。实验结果表明，BlockA2A和DOE的运行开销在亚秒级别，支持在基于LLM的生产MAS环境中进行可扩展部署。

> The rapid adoption of agentic AI, powered by large language models (LLMs), is transforming enterprise ecosystems with autonomous agents that execute complex workflows. Yet we observe several key security vulnerabilities in LLM-driven multi-agent systems (MASes): fragmented identity frameworks, insecure communication channels, and inadequate defenses against Byzantine agents or adversarial prompts. In this paper, we present the first systematic analysis of these emerging multi-agent risks and explain why the legacy security strategies cannot effectively address these risks. Afterwards, we propose BlockA2A, the first unified multi-agent trust framework that enables secure and verifiable and agent-to-agent interoperability. At a high level, BlockA2A adopts decentralized identifiers (DIDs) to enable fine-grained cross-domain agent authentication, blockchain-anchored ledgers to enable immutable auditability, and smart contracts to dynamically enforce context-aware access control policies. BlockA2A eliminates centralized trust bottlenecks, ensures message authenticity and execution integrity, and guarantees accountability across agent interactions. Furthermore, we propose a Defense Orchestration Engine (DOE) that actively neutralizes attacks through real-time mechanisms, including Byzantine agent flagging, reactive execution halting, and instant permission revocation. Empirical evaluations demonstrate BlockA2A's effectiveness in neutralizing prompt-based, communication-based, behavioral and systemic MAS attacks. We formalize its integration into existing MAS and showcase a practical implementation for Google's A2A protocol. Experiments confirm that BlockA2A and DOE operate with sub-second overhead, enabling scalable deployment in production LLM-based MAS environments.

[Arxiv](https://arxiv.org/abs/2508.01332)