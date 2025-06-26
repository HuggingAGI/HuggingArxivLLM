# 借助大型语言模型实现财务报表审计自动化

发布时间：2025年06月14日

`LLM应用`

> Automating Financial Statement Audits with Large Language Models

# 摘要

> 财务报表审计是帮助利益相关者掌握企业财务健康状况的关键环节，但目前的手动审计流程效率低下且错误频发。即便经过详尽的验证程序，审计师仍可能遗漏问题，导致财务报表失准，难以满足各方对透明度和可靠性的期待。为此，我们探索利用大型语言模型（LLMs）实现财务报表审计的自动化，并对其能力进行严格评估，揭示其在自动化审计场景下的性能边界。我们的研究构建了一个基于精心策划数据集的全面基准，将真实世界财务表格与合成交易数据相结合。在基准测试中，我们设计了一套严谨的五阶段评估框架，用于全面考察LLMs的审计能力。该基准还通过测试用例模拟真实审计场景，要求模型将特定财务报表错误与会计标准违规行为相对应。测试结果显示，当前先进的LLMs在拥有历史交易数据支持时，能够有效识别财务报表中的错误。然而，这些模型在解释错误成因和引用相关会计标准方面表现不足。此外，LLMs在执行完整审计流程和进行必要财务报表修订方面仍显吃力。这些发现揭示了LLMs在会计专业知识方面的明显短板。未来研究需着重提升LLMs对审计原则和流程的理解能力。我们的基准测试和评估框架为开发更高效的自动化审计工具奠定了基础，有望显著提升真实世界财务报表审计的准确性和效率。

> Financial statement auditing is essential for stakeholders to understand a company's financial health, yet current manual processes are inefficient and error-prone. Even with extensive verification procedures, auditors frequently miss errors, leading to inaccurate financial statements that fail to meet stakeholder expectations for transparency and reliability. To this end, we harness large language models (LLMs) to automate financial statement auditing and rigorously assess their capabilities, providing insights on their performance boundaries in the scenario of automated auditing. Our work introduces a comprehensive benchmark using a curated dataset combining real-world financial tables with synthesized transaction data. In the benchmark, we developed a rigorous five-stage evaluation framework to assess LLMs' auditing capabilities. The benchmark also challenges models to map specific financial statement errors to corresponding violations of accounting standards, simulating real-world auditing scenarios through test cases. Our testing reveals that current state-of-the-art LLMs successfully identify financial statement errors when given historical transaction data. However, these models demonstrate significant limitations in explaining detected errors and citing relevant accounting standards. Furthermore, LLMs struggle to execute complete audits and make necessary financial statement revisions. These findings highlight a critical gap in LLMs' domain-specific accounting knowledge. Future research must focus on enhancing LLMs' understanding of auditing principles and procedures. Our benchmark and evaluation framework establish a foundation for developing more effective automated auditing tools that will substantially improve the accuracy and efficiency of real-world financial statement auditing.

[Arxiv](https://arxiv.org/abs/2506.17282)