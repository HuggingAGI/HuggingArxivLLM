# 基于LLMs的架构设计决策制定

发布时间：2025年04月10日

`LLM应用` `软件开发` `软件工程`

> DRAFT-ing Architectural Design Decisions using LLMs

# 摘要

> 架构知识管理（AKM）是软件开发中的关键环节，但因缺乏标准化和高人工投入而面临挑战。架构决策记录（ADRs）作为结构化方法，本应有助于捕获架构设计决策（ADDs），但其应用受限于人工成本和工具支持不足。

我们的前期研究发现，大型语言模型（LLMs）在生成ADDs方面具有潜力。然而，仅靠简单的提示难以获得高质量的ADDs。此外，使用第三方LLMs会引发隐私问题，而自行托管则面临资源挑战。

为解决这些问题，我们尝试了多种方法，包括Few-Shot学习、检索增强生成（RAG）和微调，以提升LLMs生成ADDs的能力。实验结果表明，这些方法均能显著提升效果。在此基础上，我们提出了领域特定的检索增强 Few-Shot 微调方法——DRAFT，它结合了这三种方法的优势，以更高效地生成ADDs。

DRAFT分为两个阶段：离线阶段对LLM进行微调，利用检索到的示例生成ADDs；在线阶段则通过检索ADRs并结合微调后的模型生成ADDs。

我们对DRAFT进行了全面评估，使用包含4,911个ADRs的数据集和多种LLMs，通过自动化指标和人工评估进行了分析。结果显示，DRAFT在效果上优于其他方法，同时保持了效率。我们的研究发现，DRAFT不仅能够帮助架构师起草ADDs，还能有效应对隐私和资源方面的限制。


> Architectural Knowledge Management (AKM) is crucial for software development but remains challenging due to the lack of standardization and high manual effort. Architecture Decision Records (ADRs) provide a structured approach to capture Architecture Design Decisions (ADDs), but their adoption is limited due to the manual effort involved and insufficient tool support. Our previous work has shown that Large Language Models (LLMs) can assist in generating ADDs. However, simply prompting the LLM does not produce quality ADDs. Moreover, using third-party LLMs raises privacy concerns, while self-hosting them poses resource challenges.
  To this end, we experimented with different approaches like few-shot, retrieval-augmented generation (RAG) and fine-tuning to enhance LLM's ability to generate ADDs. Our results show that both techniques improve effectiveness. Building on this, we propose Domain Specific Retreival Augumented Few Shot Fine Tuninng, DRAFT, which combines the strengths of all these three approaches for more effective ADD generation. DRAFT operates in two phases: an offline phase that fine-tunes an LLM on generating ADDs augmented with retrieved examples and an online phase that generates ADDs by leveraging retrieved ADRs and the fine-tuned model.
  We evaluated DRAFT against existing approaches on a dataset of 4,911 ADRs and various LLMs and analyzed them using automated metrics and human evaluations. Results show DRAFT outperforms all other approaches in effectiveness while maintaining efficiency. Our findings indicate that DRAFT can aid architects in drafting ADDs while addressing privacy and resource constraints.

[Arxiv](https://arxiv.org/abs/2504.08207)