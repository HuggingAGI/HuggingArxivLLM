# 评测多模态理解与复杂推理能力在ESG任务中的表现

发布时间：2025年07月24日

`LLM应用` `数据科学`

> Benchmarking Multimodal Understanding and Complex Reasoning for ESG Tasks

# 摘要

> 环境、社会和治理（ESG）报告在评估可持续性实践、确保合规性以及提升财务透明度方面发挥着关键作用。然而，这类文档通常内容繁杂、结构多样且包含多模态信息，如密集文本、结构化表格、复杂图表及依赖布局的语义。现有AI系统在处理这类文档时，往往难以实现可靠的文档级别推理，且目前尚无针对ESG领域的专用基准测试。为解决这一问题，我们推出了	extbf{MMESGBench}——首个专注于评测多模态理解和复杂推理能力的基准数据集，覆盖结构多样和多来源的ESG文档。该数据集通过人机协作的多阶段流程构建：首先，多模态LLM基于布局感知文档页面的文本、表格和视觉信息生成问答（QA）对；随后，LLM对每个QA对的语义准确性、完整性和推理复杂性进行验证；最后，领域专家参与验证，确保QA对的质量、相关性和多样性。MMESGBench包含从45份ESG文档中提取的933份验证QA对，涵盖7种文档类型和3个主要ESG来源类别。问题分为单页、跨页或不可回答类型，每类问题均配有细粒度的多模态证据。初步实验表明，多模态和检索增强模型在视觉和跨页任务上显著优于仅文本的基线模型。该数据集已作为开源资源发布于https://github.com/Zhanglei1103/MMESGBench。

> Environmental, Social, and Governance (ESG) reports are essential for evaluating sustainability practices, ensuring regulatory compliance, and promoting financial transparency. However, these documents are often lengthy, structurally diverse, and multimodal, comprising dense text, structured tables, complex figures, and layout-dependent semantics. Existing AI systems often struggle to perform reliable document-level reasoning in such settings, and no dedicated benchmark currently exists in ESG domain. To fill the gap, we introduce \textbf{MMESGBench}, a first-of-its-kind benchmark dataset targeted to evaluate multimodal understanding and complex reasoning across structurally diverse and multi-source ESG documents. This dataset is constructed via a human-AI collaborative, multi-stage pipeline. First, a multimodal LLM generates candidate question-answer (QA) pairs by jointly interpreting rich textual, tabular, and visual information from layout-aware document pages. Second, an LLM verifies the semantic accuracy, completeness, and reasoning complexity of each QA pair. This automated process is followed by an expert-in-the-loop validation, where domain specialists validate and calibrate QA pairs to ensure quality, relevance, and diversity. MMESGBench comprises 933 validated QA pairs derived from 45 ESG documents, spanning across seven distinct document types and three major ESG source categories. Questions are categorized as single-page, cross-page, or unanswerable, with each accompanied by fine-grained multimodal evidence. Initial experiments validate that multimodal and retrieval-augmented models substantially outperform text-only baselines, particularly on visually grounded and cross-page tasks. MMESGBench is publicly available as an open-source dataset at https://github.com/Zhanglei1103/MMESGBench.

[Arxiv](https://arxiv.org/abs/2507.18932)