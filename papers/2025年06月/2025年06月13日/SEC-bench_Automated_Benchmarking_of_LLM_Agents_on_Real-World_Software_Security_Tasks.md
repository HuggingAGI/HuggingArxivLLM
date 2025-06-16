# # SEC-bench: 针对真实世界软件安全任务的 LLM 代理自动化基准测试

发布时间：2025年06月13日

`LLM应用` `软件开发` `安全工程`

> SEC-bench: Automated Benchmarking of LLM Agents on Real-World Software Security Tasks

# 摘要

> 严格的安全评估是确保大型语言模型（LLM）代理在软件开发全流程中安全可靠部署的关键。然而，现有的评估基准大多依赖人工构造的挑战或简化的漏洞数据集，这些数据集无法反映安全工程师在实际工作中面临的复杂性和模糊性。为此，我们推出了SEC-bench——首个完全自动化的LLM代理安全工程能力评估框架。

SEC-bench采用创新的多代理架构，能够自动构建代码仓库、复现漏洞并生成黄金补丁，确保评估的准确性和可靠性。我们的框架以极低的成本（每实例仅0.87美元）生成高质量、可复现的软件漏洞数据集。通过SEC-bench，我们实现了两个关键的安全任务——概念验证（PoC）生成和漏洞修复，以全面评估LLM代理的能力。

对当前最先进的LLM代码代理的评估结果显示，现有模型在这两个任务上的表现仍有较大提升空间：在PoC生成任务中，最高成功率仅为18%；在漏洞修复任务中，成功率也只有34%。这些结果凸显了开发更实用、更智能和更自主的LLM代理以满足安全工程需求的关键挑战。


> Rigorous security-focused evaluation of large language model (LLM) agents is imperative for establishing trust in their safe deployment throughout the software development lifecycle. However, existing benchmarks largely rely on synthetic challenges or simplified vulnerability datasets that fail to capture the complexity and ambiguity encountered by security engineers in practice. We introduce SEC-bench, the first fully automated benchmarking framework for evaluating LLM agents on authentic security engineering tasks. SEC-bench employs a novel multi-agent scaffold that automatically constructs code repositories with harnesses, reproduces vulnerabilities in isolated environments, and generates gold patches for reliable evaluation. Our framework automatically creates high-quality software vulnerability datasets with reproducible artifacts at a cost of only $0.87 per instance. Using SEC-bench, we implement two critical software security tasks to rigorously evaluate LLM agents' capabilities: proof-of-concept (PoC) generation and vulnerability patching. A comprehensive evaluation of state-of-the-art LLM code agents reveals significant performance gaps, achieving at most 18.0% success in PoC generation and 34.0% in vulnerability patching on our complete dataset. These results highlight the crucial steps needed toward developing LLM agents that are more practical, intelligent, and autonomous for security engineering.

[Arxiv](https://arxiv.org/abs/2506.11791)