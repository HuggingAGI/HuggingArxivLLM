# 隐私实践：面向LLM驱动智能体的切实隐私缓解与评估

发布时间：2025年09月22日

`Agent` `基础理论`

> Privacy in Action: Towards Realistic Privacy Mitigation and Evaluation for LLM-Powered Agents

# 摘要

> 在模型上下文协议（MCP）与智能体间（A2A）框架的加速推动下，LLM智能体处理敏感通信的自主性日益增强，由此引发了严峻的隐私挑战。尽管近期研究发现LLMs在隐私问答中的表现与其智能体行为存在巨大差异，但现有基准测试仍局限于静态、简化的场景。为此，我们提出了PrivacyChecker——一种与模型无关、基于情境完整性的缓解方案，它能有效将DeepSeek-R1的隐私泄露率从36.08%降至7.30%，将GPT-4o的隐私泄露率从33.06%降至8.32%，同时确保任务的有用性不受影响。我们还开发了PrivacyLens-Live，将静态基准测试升级为动态MCP和A2A环境，从而揭示了实际应用中显著更高的隐私风险。该模块化缓解方案通过三种部署策略无缝融入智能体协议，为新兴的智能体生态系统提供了实用的隐私防护。相关数据与代码将在https://aka.ms/privacy_in_action公开。

> The increasing autonomy of LLM agents in handling sensitive communications, accelerated by Model Context Protocol (MCP) and Agent-to-Agent (A2A) frameworks, creates urgent privacy challenges. While recent work reveals significant gaps between LLMs' privacy Q&A performance and their agent behavior, existing benchmarks remain limited to static, simplified scenarios. We present PrivacyChecker, a model-agnostic, contextual integrity based mitigation approach that effectively reduces privacy leakage from 36.08% to 7.30% on DeepSeek-R1 and from 33.06% to 8.32% on GPT-4o, all while preserving task helpfulness. We also introduce PrivacyLens-Live, transforming static benchmarks into dynamic MCP and A2A environments that reveal substantially higher privacy risks in practical. Our modular mitigation approach integrates seamlessly into agent protocols through three deployment strategies, providing practical privacy protection for the emerging agentic ecosystem. Our data and code will be made available at https://aka.ms/privacy_in_action.

[Arxiv](https://arxiv.org/abs/2509.17488)