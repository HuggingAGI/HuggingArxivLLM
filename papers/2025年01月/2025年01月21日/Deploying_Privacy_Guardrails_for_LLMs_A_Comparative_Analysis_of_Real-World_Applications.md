# 为LLMs部署隐私护栏：现实应用对比分析

发布时间：2025年01月21日

`LLM应用

**理由**：这篇论文主要讨论了一个名为OneShield Privacy Guard的框架，该框架旨在减轻用户输入和LLM输出中的隐私风险。论文详细描述了该框架在企业级数据治理和开源仓库中的应用案例，展示了其在隐私保护方面的实际效果。因此，这篇论文属于LLM应用类别，因为它关注的是如何在实际应用中解决LLM带来的隐私问题。` `隐私保护` `数据治理`

> Deploying Privacy Guardrails for LLMs: A Comparative Analysis of Real-World Applications

# 摘要

> 大型语言模型（LLMs）的广泛应用虽然推动了AI技术的革新，但也带来了用户隐私保护的严峻挑战。为了在遵守GDPR和CCPA等隐私法规的同时应对复杂的隐私风险，我们需要构建强大且可扩展的框架。本文深入探讨了OneShield Privacy Guard，这是一个专为减轻用户输入和LLM输出中隐私风险而设计的框架，适用于企业和开源场景。我们研究了两个实际案例：（1）一个与数据和模型工厂集成的多语言隐私保护系统，专注于企业级数据治理；（2）PR Insights，一个强调自动化分类和社区驱动改进的开源仓库。在第一个案例中，OneShield在检测26种语言中的敏感实体（如日期、姓名和电话号码）时，F1分数达到了0.95，比StarPII和Presidio等顶尖工具高出12%。在第二个案例中，平均F1分数为0.86，三个月内减少了300多小时的手动工作量，准确标记了1,256个拉取请求中的8.25%存在隐私风险，并增强了上下文敏感性。这些成果展示了OneShield在不同环境中的卓越适应性和高效性，为上下文感知的实体识别、自动化合规性和道德AI采用提供了宝贵的见解。这项研究推动了隐私保护框架的发展，增强了用户信任，并确保了跨操作环境的合规性。

> The adoption of Large Language Models (LLMs) has revolutionized AI applications but poses significant challenges in safeguarding user privacy. Ensuring compliance with privacy regulations such as GDPR and CCPA while addressing nuanced privacy risks requires robust and scalable frameworks. This paper presents a detailed study of OneShield Privacy Guard, a framework designed to mitigate privacy risks in user inputs and LLM outputs across enterprise and open-source settings. We analyze two real-world deployments:(1) a multilingual privacy-preserving system integrated with Data and Model Factory, focusing on enterprise-scale data governance; and (2) PR Insights, an open-source repository emphasizing automated triaging and community-driven refinements. In Deployment 1, OneShield achieved a 0.95 F1 score in detecting sensitive entities like dates, names, and phone numbers across 26 languages, outperforming state-of-the-art tool such as StarPII and Presidio by up to 12\%. Deployment 2, with an average F1 score of 0.86, reduced manual effort by over 300 hours in three months, accurately flagging 8.25\% of 1,256 pull requests for privacy risks with enhanced context sensitivity. These results demonstrate OneShield's adaptability and efficacy in diverse environments, offering actionable insights for context-aware entity recognition, automated compliance, and ethical AI adoption. This work advances privacy-preserving frameworks, supporting user trust and compliance across operational contexts.

[Arxiv](https://arxiv.org/abs/2501.12456)