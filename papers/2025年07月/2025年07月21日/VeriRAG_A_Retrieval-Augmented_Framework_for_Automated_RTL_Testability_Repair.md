# VeriRAG：用于自动RTL可测试性修复的增强检索框架

发布时间：2025年07月21日

`LLM应用` `电子设计自动化` `计算机辅助设计`

> VeriRAG: A Retrieval-Augmented Framework for Automated RTL Testability Repair

# 摘要

> 大型语言模型（LLMs）在计算机辅助设计（CAD）领域展现出巨大潜力，特别是在电子设计自动化（EDA）工具中的自动化调试和验证方面。然而，可测试性设计（DFT）仍是一个相对未被充分探索的领域。本文介绍了VeriRAG——首个基于LLM的DFT-EDA框架。VeriRAG采用检索增强生成（RAG）方法，使LLM能够修改代码以确保符合DFT要求。VeriRAG整合了两个关键组件：(1) 一种基于自动编码器的相似性测量模型，用于为LLM精确检索参考RTL设计；(2) 一个迭代代码修订管道，允许LLM在保持可综合性的同时确保DFT合规。为了支持VeriRAG，我们引入了VeriDFT——一个基于Verilog的DFT数据集，专为DFT感知的RTL修复而整理。VeriRAG从VeriDFT中检索结构相似的RTL设计，每个设计都配有一个经过严格验证的修复方案，作为代码修复的参考。借助VeriRAG和VeriDFT，我们实现了完全自动化的DFT修复——与零-shot基线相比，成功修复率提高了7.72倍（见第五部分图5）。消融研究进一步证实了VeriRAG框架中各组件的贡献。我们已在GitHub上开源了我们的数据、模型和脚本，地址为https://github.com/yuyangdu01/LLM4DFT。

> Large language models (LLMs) have demonstrated immense potential in computer-aided design (CAD), particularly for automated debugging and verification within electronic design automation (EDA) tools. However, Design for Testability (DFT) remains a relatively underexplored area. This paper presents VeriRAG, the first LLM-assisted DFT-EDA framework. VeriRAG leverages a Retrieval-Augmented Generation (RAG) approach to enable LLM to revise code to ensure DFT compliance. VeriRAG integrates (1) an autoencoder-based similarity measurement model for precise retrieval of reference RTL designs for the LLM, and (2) an iterative code revision pipeline that allows the LLM to ensure DFT compliance while maintaining synthesizability. To support VeriRAG, we introduce VeriDFT, a Verilog-based DFT dataset curated for DFT-aware RTL repairs. VeriRAG retrieves structurally similar RTL designs from VeriDFT, each paired with a rigorously validated correction, as references for code repair. With VeriRAG and VeriDFT, we achieve fully automated DFT correction -- resulting in a 7.72-fold improvement in successful repair rate compared to the zero-shot baseline (Fig. 5 in Section V). Ablation studies further confirm the contribution of each component of the VeriRAG framework. We open-source our data, models, and scripts at https://github.com/yuyangdu01/LLM4DFT.

[Arxiv](https://arxiv.org/abs/2507.15664)