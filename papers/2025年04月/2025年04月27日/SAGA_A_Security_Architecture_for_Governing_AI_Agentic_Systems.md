# SAGA：一种治理AI自主系统的安全架构

发布时间：2025年04月27日

`Agent` `智能体系统`

> SAGA: A Security Architecture for Governing AI Agentic Systems

# 摘要

> 基于大型语言模型（LLM）的智能体正越来越多地实现自主交互、协作与任务分配，几乎无需人工干预。行业指南强调，用户需对智能体保持全面控制，以防范恶意智能体带来的潜在风险。尽管已有多种智能体系统设计方案涉及身份认证、权限管理和任务委托，但它们仍停留在理论层面，缺乏实际应用与评估。更重要的是，这些方案未提供用户对智能体管理的控制能力。为填补这一空白，我们提出了SAGA（用于治理智能体系统的安全架构），为用户提供对其智能体生命周期的全面监督。在我们的设计中，用户将智能体注册至中央管理实体——提供者（Provider），该实体负责维护智能体的联系方式、用户自定义的访问控制策略，并协助智能体在与其他智能体通信时执行这些策略。我们引入了一种用于生成访问控制令牌的加密机制，对智能体与其他智能体的交互提供精细控制，同时平衡了安全性和性能需求。我们在多个智能体任务上对SAGA进行了评估，使用了分布在不同地理位置的智能体以及多个设备端和云端的LLM，结果显示在各种条件下，SAGA的性能开销极小，且不影响底层任务的效用。我们的架构使自主智能体的部署更加安全可靠，加速了这一技术在敏感环境中的负责任应用。

> Large Language Model (LLM)-based agents increasingly interact, collaborate, and delegate tasks to one another autonomously with minimal human interaction. Industry guidelines for agentic system governance emphasize the need for users to maintain comprehensive control over their agents, mitigating potential damage from malicious agents. Several proposed agentic system designs address agent identity, authorization, and delegation, but remain purely theoretical, without concrete implementation and evaluation. Most importantly, they do not provide user-controlled agent management. To address this gap, we propose SAGA, a Security Architecture for Governing Agentic systems, that offers user oversight over their agents' lifecycle. In our design, users register their agents with a central entity, the Provider, that maintains agents contact information, user-defined access control policies, and helps agents enforce these policies on inter-agent communication. We introduce a cryptographic mechanism for deriving access control tokens, that offers fine-grained control over an agent's interaction with other agents, balancing security and performance consideration. We evaluate SAGA on several agentic tasks, using agents in different geolocations, and multiple on-device and cloud LLMs, demonstrating minimal performance overhead with no impact on underlying task utility in a wide range of conditions. Our architecture enables secure and trustworthy deployment of autonomous agents, accelerating the responsible adoption of this technology in sensitive environments.

[Arxiv](https://arxiv.org/abs/2504.21034)