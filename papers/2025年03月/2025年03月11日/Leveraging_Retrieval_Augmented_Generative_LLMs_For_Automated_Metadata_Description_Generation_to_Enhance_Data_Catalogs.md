# # 基于检索增强生成式LLM的自动化元数据描述生成优化数据目录

发布时间：2025年03月11日

`LLM应用` `数据管理` `数据治理`

> Leveraging Retrieval Augmented Generative LLMs For Automated Metadata Description Generation to Enhance Data Catalogs

# 摘要

> 数据目录是组织和访问多样化数据资产的存储库，但其效果取决于业务用户查找相关内容的便捷性。然而，许多组织的数据目录因元数据（如资产描述）不足而导致搜索能力受限。为此，本文提出了一种内容生成解决方案，旨在通过可扩展的方式丰富和整理元数据。研究聚焦于元数据创建的挑战，创新性地提出结合基于检索的少样本技术和生成式大型语言模型（LLM），充分利用现有元数据内容。我们还对比了少样本预训练LLM（如Llama、GPT3.5）与微调LLM（如Llama2-7b）的表现，从准确性、事实性和毒性三个维度进行了评估。实验数据显示，生成内容的Rouge-1 F1值超过80%，表明87%-88%的实例可直接使用或经少量编辑后由数据管理员采纳。通过精准生成表和列的描述，本研究为企业的元数据整理和数据目录优化提供了整体框架，显著提升了数据目录的可搜索性和实用性。

> Data catalogs serve as repositories for organizing and accessing diverse collection of data assets, but their effectiveness hinges on the ease with which business users can look-up relevant content. Unfortunately, many data catalogs within organizations suffer from limited searchability due to inadequate metadata like asset descriptions. Hence, there is a need of content generation solution to enrich and curate metadata in a scalable way. This paper explores the challenges associated with metadata creation and proposes a unique prompt enrichment idea of leveraging existing metadata content using retrieval based few-shot technique tied with generative large language models (LLM). The literature also considers finetuning an LLM on existing content and studies the behavior of few-shot pretrained LLM (Llama, GPT3.5) vis-à-vis few-shot finetuned LLM (Llama2-7b) by evaluating their performance based on accuracy, factual grounding, and toxicity. Our preliminary results exhibit more than 80% Rouge-1 F1 for the generated content. This implied 87%- 88% of instances accepted as is or curated with minor edits by data stewards. By automatically generating descriptions for tables and columns in most accurate way, the research attempts to provide an overall framework for enterprises to effectively scale metadata curation and enrich its data catalog thereby vastly improving the data catalog searchability and overall usability.

[Arxiv](https://arxiv.org/abs/2503.09003)