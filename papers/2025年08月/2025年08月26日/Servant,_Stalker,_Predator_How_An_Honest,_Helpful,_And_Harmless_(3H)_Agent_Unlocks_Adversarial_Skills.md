# 仆人、跟踪者、捕食者：诚实、有益且无害（3H）的智能体如何解锁对抗性技能

发布时间：2025年08月26日

`Agent` `基础理论`

> Servant, Stalker, Predator: How An Honest, Helpful, And Harmless (3H) Agent Unlocks Adversarial Skills

# 摘要

> 本文揭示并剖析了基于模型上下文协议（MCP）的代理系统中一类新型安全漏洞。这种攻击链揭示了看似无害的独立授权任务如何被精心编排，进而产生有害的突发行为。借助MITRE ATLAS框架的系统分析，我们发现：95个测试代理（可访问浏览器自动化、财务分析、位置跟踪及代码部署等多种服务）能将合法操作串联成复杂的攻击链条，突破了单个服务的安全边界。红队演练结果表明，当前MCP架构可能缺乏跨域安全机制，难以检测或防范这类组合攻击。我们还实证了多起通过服务编排实施的定向攻击链，例如数据窃取、财务篡改和基础设施入侵等具体危害场景。研究发现，当代理可跨域协同操作时，“服务隔离”这一核心安全假设便会失效，导致攻击面随代理能力的增加呈指数级扩张。我们构建了一个基础实验框架，其核心并非评估代理能否完成MCP基准任务，而是探究当代理“过于高效”——即跨服务优化时违反人类预期和安全限制——会引发何种后果。最后，我们基于现有MCP基准套件提出了三个具体的实验方向。

> This paper identifies and analyzes a novel vulnerability class in Model Context Protocol (MCP) based agent systems. The attack chain describes and demonstrates how benign, individually authorized tasks can be orchestrated to produce harmful emergent behaviors. Through systematic analysis using the MITRE ATLAS framework, we demonstrate how 95 agents tested with access to multiple services-including browser automation, financial analysis, location tracking, and code deployment-can chain legitimate operations into sophisticated attack sequences that extend beyond the security boundaries of any individual service. These red team exercises survey whether current MCP architectures lack cross-domain security measures necessary to detect or prevent a large category of compositional attacks. We present empirical evidence of specific attack chains that achieve targeted harm through service orchestration, including data exfiltration, financial manipulation, and infrastructure compromise. These findings reveal that the fundamental security assumption of service isolation fails when agents can coordinate actions across multiple domains, creating an exponential attack surface that grows with each additional capability. This research provides a barebones experimental framework that evaluate not whether agents can complete MCP benchmark tasks, but what happens when they complete them too well and optimize across multiple services in ways that violate human expectations and safety constraints. We propose three concrete experimental directions using the existing MCP benchmark suite.

[Arxiv](https://arxiv.org/abs/2508.19500)