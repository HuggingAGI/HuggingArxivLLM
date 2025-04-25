# # **FLAG**: 基于形式化方法和LLM辅助的SVA生成，用于片上通信协议的形式化规范

发布时间：2025年04月23日

`LLM应用` `问答系统`

> FLAG: Formal and LLM-assisted SVA Generation for Formal Specifications of On-Chip Communication Protocols

# 摘要

> <翻译失败>

> Formal specifications of on-chip communication protocols are crucial for system-on-chip (SoC) design and verification. However, manually constructing these formal specifications from informal documents remains a tedious and error-prone task. Although recent efforts have used Large Language Models (LLMs) to generate SystemVerilog Assertion (SVA) properties from design documents for Register-Transfer Level (RTL) design verification, in our experience these approaches have not shown promise in generating SVA properties for communication protocols. Since protocol specification documents are unstructured and ambiguous in nature, LLMs often fail to extract the necessary information and end up generating irrelevant or even incorrect properties. We propose FLAG, a two-stage framework to help construct formal protocol specifications from informal documents. In the first stage, a predefined template set is used to generate candidate SVA properties. To avoid missing necessary properties, we develop a grammar-based approach to generate comprehensive template sets that capture critical signal behaviors for various communication protocols. In the second stage, we utilize unambiguous timing diagrams in conjunction with textual descriptions from the specification documents to filter out incorrect properties. A formal approach is first implemented to check the candidate properties and filter out those inconsistent with the timing diagrams. An LLM is then consulted to further remove incorrect properties with respect to the textual description, obtaining the final property set. Experiments on various open-source communication protocols demonstrate the effectiveness of FLAG in generating SVA properties from informal documents.

[Arxiv](https://arxiv.org/abs/2504.17226)