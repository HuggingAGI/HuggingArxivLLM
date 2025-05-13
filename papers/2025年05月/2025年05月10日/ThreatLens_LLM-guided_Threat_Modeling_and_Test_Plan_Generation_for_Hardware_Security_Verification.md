# ThreatLens: 硬件安全验证中的LLM引导威胁建模与测试计划生成

发布时间：2025年05月10日

`LLM应用` `硬件安全` `网络安全`

> ThreatLens: LLM-guided Threat Modeling and Test Plan Generation for Hardware Security Verification

# 摘要

> 硬件安全验证目前主要依赖手动威胁建模和测试计划生成，这种方式不仅耗时费力、容易出错，而且难以应对日益复杂的设计和不断变化的攻击手段。为了解决这些问题，我们提出了 ThreatLens——一个基于 LLM 的多智能体框架，致力于自动化硬件安全验证中的威胁建模和测试计划生成。ThreatLens 通过检索增强生成（RAG）提取相关安全知识，利用 LLM 的推理能力进行威胁评估，并结合用户反馈确保生成实用的测试计划。通过自动化这些流程，ThreatLens 不仅减少了人工验证的工作量，还提高了覆盖率，为安全验证提供了一种结构化且灵活的方法。我们在 NEORV32 SoC 上的评估证明，ThreatLens 能够通过结构化测试计划实现安全验证的自动化，并在实际应用中表现出显著的有效性。

> Current hardware security verification processes predominantly rely on manual threat modeling and test plan generation, which are labor-intensive, error-prone, and struggle to scale with increasing design complexity and evolving attack methodologies. To address these challenges, we propose ThreatLens, an LLM-driven multi-agent framework that automates security threat modeling and test plan generation for hardware security verification. ThreatLens integrates retrieval-augmented generation (RAG) to extract relevant security knowledge, LLM-powered reasoning for threat assessment, and interactive user feedback to ensure the generation of practical test plans. By automating these processes, the framework reduces the manual verification effort, enhances coverage, and ensures a structured, adaptable approach to security verification. We evaluated our framework on the NEORV32 SoC, demonstrating its capability to automate security verification through structured test plans and validating its effectiveness in real-world scenarios.

[Arxiv](https://arxiv.org/abs/2505.06821)