# 基于LLM的自动化程序修复综述：分类法、设计范式及其应用

发布时间：2025年06月30日

`LLM应用` `软件工程` `程序修复`

> A Survey of LLM-based Automated Program Repair: Taxonomies, Design Paradigms, and Applications

# 摘要

> 大型语言模型（LLMs）正在重塑自动程序修复（APR）领域。我们根据2022年1月至2025年6月发布的63个基于LLMs的APR系统，将其归类为四种范式，并展示了检索增强或分析增强的上下文如何强化这些范式。这一分类明确了关键权衡：微调在高训练成本下实现强任务对齐；提示方法支持快速部署，但受限于提示设计和上下文窗口；流程管道提供可重复控制，具备适度开销；智能体框架处理多块或跨文件缺陷，但代价是增加延迟和复杂性。持续挑战包括超越测试套件验证语义正确性、修复仓库级缺陷以及降低LLMs成本。我们概述了结合轻量级人工反馈、仓库感知检索、代码分析和成本感知规划的研究方向，以推动可靠且高效的基于LLMs的APR发展。

> Large language models (LLMs) are reshaping automated program repair (APR). We categorize the recent 63 LLM-based APR systems published from January 2022 to June 2025 into four paradigms, and show how retrieval- or analysis-augmented contexts strengthen any of them. This taxonomy clarifies key trade-offs: fine-tuning delivers strong task alignment at high training cost; prompting enables rapid deployment but is limited by prompt design and context windows; procedural pipelines offer reproducible control with moderate overhead; agentic frameworks tackle multi-hunk or cross-file bugs at the price of increased latency and complexity. Persistent challenges include verifying semantic correctness beyond test suites, repairing repository-scale defects, and lowering the costs of LLMs. We outline research directions that combine lightweight human feedback, repository-aware retrieval, code analysis, and cost-aware planning to advance reliable and efficient LLM-based APR.

[Arxiv](https://arxiv.org/abs/2506.23749)