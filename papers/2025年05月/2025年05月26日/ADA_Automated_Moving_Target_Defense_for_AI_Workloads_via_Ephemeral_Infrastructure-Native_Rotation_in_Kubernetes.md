# ADA：基于Kubernetes的临时基础设施原生轮换实现AI工作负载的自动化的动态目标防御

发布时间：2025年05月26日

`其他` `AI安全` `云原生安全`

> ADA: Automated Moving Target Defense for AI Workloads via Ephemeral Infrastructure-Native Rotation in Kubernetes

# 摘要

> 本文介绍了自适应防御代理（ADA），一种创新型自动化移动目标防御（AMTD）系统，旨在从根本上提升AI工作负载的安全性。ADA通过在基础设施级别持续自动旋转工作负载，利用Kubernetes pods的瞬时性特征。这种可控的旋转机制系统性地打破攻击者的假设，扰乱潜在的攻击链，通过定期破坏并重生AI服务实例。这种方法以混沌工程原则为指导，作为持续主动防御，开创性地实现了从传统静态防御到主动防御的范式转变。传统防御依赖复杂昂贵的保密或可信计算方案来保护底层计算平台，而ADA同时又能无差别支持最新的智能体和非智能体AI生态系统与解决方案，例如智能体间（A2A）通信框架或模型上下文协议（MCP）。这种原生AI基础设施设计，依托广泛普及的云原生Kubernetes技术，实现了更简便的部署，通过旋转实现的零信任原生特性简化了维护，并促进了更快的采用。我们认为，ADA在AMTD方面的创新方法为AI服务提供了一种更强大、敏捷且运营高效的零信任模型，通过主动环境操控实现安全，而非被动补丁修复。
    

> This paper introduces the Adaptive Defense Agent (ADA), an innovative Automated Moving Target Defense (AMTD) system designed to fundamentally enhance the security posture of AI workloads. ADA operates by continuously and automatically rotating these workloads at the infrastructure level, leveraging the inherent ephemerality of Kubernetes pods. This constant managed churn systematically invalidates attacker assumptions and disrupts potential kill chains by regularly destroying and respawning AI service instances. This methodology, applying principles of chaos engineering as a continuous, proactive defense, offers a paradigm shift from traditional static defenses that rely on complex and expensive confidential or trusted computing solutions to secure the underlying compute platforms, while at the same time agnostically supporting the latest advancements in agentic and nonagentic AI ecosystems and solutions such as agent-to-agent (A2A) communication frameworks or model context protocols (MCP). This AI-native infrastructure design, relying on the widely proliferated cloud-native Kubernetes technologies, facilitates easier deployment, simplifies maintenance through an inherent zero trust posture achieved by rotation, and promotes faster adoption. We posit that ADA's novel approach to AMTD provides a more robust, agile, and operationally efficient zero-trust model for AI services, achieving security through proactive environmental manipulation rather than reactive patching.

[Arxiv](https://arxiv.org/abs/2505.23805)