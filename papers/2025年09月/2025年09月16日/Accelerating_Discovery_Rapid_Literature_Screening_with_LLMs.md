# # 加速发现：借助大型语言模型（LLMs）实现快速文献筛选

发布时间：2025年09月16日

`RAG` `交通运输`

> Accelerating Discovery: Rapid Literature Screening with LLMs

# 摘要

> 背景：开展多声音文献综述（MVLRs）往往耗时费力。研究人员需审查筛选大量非结构化来源，这些来源信息稀疏，且大多不会纳入最终研究。我们在航空电子领域开展上下文感知软件系统（CASS）测试的MVLR时，就遇到了这一难题——需审查的高度异质文档超过8000份。为此，我们开发了大型语言模型（LLM）助手，以辅助文档的搜索与筛选。
目标：开发并验证一款基于LLM的工具，支持研究人员为MVLR进行文档搜索与筛选，同时不降低研究方案的严谨性。
方法：我们采用规范的工程实践，开发了一款本地部署的基于LLM的工具，该工具整合检索增强生成（RAG）技术以处理候选来源。我们以阳性百分比一致性（PPA）为主要指标量化目标进展，确保该LLM工具的性能。在人工判断与统计抽样的辅助下，我们通过便利抽样验证了工具的实际使用质量。
结果：该工具在识别与研究无关的来源时，与人类研究人员的PPA一致性已达90%。我们还分享了开发细节，以便该工具能更好地适配特定领域。
结论：使用基于LLM的工具支持学术研究人员开展严谨的MVLR是可行的。这类工具能为研究人员节省宝贵时间，让他们专注于更高层次的抽象任务。不过，研究人员的参与仍是确保工具支持深入研究的关键。

> Background: Conducting Multi Vocal Literature Reviews (MVLRs) is often time and effort-intensive. Researchers must review and filter a large number of unstructured sources, which frequently contain sparse information and are unlikely to be included in the final study. Our experience conducting an MVLR on Context-Aware Software Systems (CASS) Testing in the avionics domain exemplified this challenge, with over 8,000 highly heterogeneous documents requiring review. Therefore, we developed a Large Language Model (LLM) assistant to support the search and filtering of documents. Aims: To develop and validate an LLM based tool that can support researchers in performing the search and filtering of documents for an MVLR without compromising the rigor of the research protocol. Method: We applied sound engineering practices to develop an on-premises LLM-based tool incorporating Retrieval Augmented Generation (RAG) to process candidate sources. Progress towards the aim was quantified using the Positive Percent Agreement (PPA) as the primary metric to ensure the performance of the LLM based tool. Convenience sampling, supported by human judgment and statistical sampling, were used to verify and validate the tool's quality-in-use. Results: The tool currently demonstrates a PPA agreement with human researchers of 90% for sources that are not relevant to the study. Development details are shared to support domain-specific adaptation of the tool. Conclusions: Using LLM-based tools to support academic researchers in rigorous MVLR is feasible. These tools can free valuable time for higher-level, abstract tasks. However, researcher participation remains essential to ensure that the tool supports thorough research.

[Arxiv](https://arxiv.org/abs/2509.13103)