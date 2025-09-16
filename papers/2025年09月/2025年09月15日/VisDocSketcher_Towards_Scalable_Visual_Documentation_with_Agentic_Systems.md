# VisDocSketcher：基于智能体系统构建可扩展视觉文档

发布时间：2025年09月15日

`Agent` `工业与制造`

> VisDocSketcher: Towards Scalable Visual Documentation with Agentic Systems

# 摘要

> 视觉文档能有效降低开发人员理解陌生代码时的认知门槛，让理解过程更直观。相较于文本文档，它能帮助开发者从更高维度把握系统结构与数据流——面对大型软件系统时，开发者往往更青睐直观的视觉呈现，而非冗长的文字说明。然而，视觉文档的制作与评估均颇具挑战：手动绘制耗时费力，现有技术尚无法直接从代码自动生成高质量视觉文档；评估过程也常因主观性强，难以实现标准化与自动化。

针对这些痛点，本文首次探索利用智能体LLM系统实现视觉文档的自动化生成。我们提出了VisDocSketcher——首个融合静态分析与LLM智能体的智能体驱动方法，能够识别代码关键元素并生成对应视觉图谱。同时，我们设计了全新评估框架AutoSketchEval，通过代码级指标对生成的视觉文档质量进行量化评估。

实验结果显示，该方法可为74.4%的样本生成有效视觉文档，相较于简单的模板基线方法，性能提升了26.7%-39.8%。评估框架则能准确区分高质量（代码对齐）与低质量（非对齐）的视觉文档，AUC值超过0.87。这项研究通过提供“生成+评估”一体化的实用工具，为自动化视觉文档的未来研究奠定了基础。

> Visual documentation is an effective tool for reducing the cognitive barrier developers face when understanding unfamiliar code, enabling more intuitive comprehension. Compared to textual documentation, it provides a higher-level understanding of the system structure and data flow. Developers usually prefer visual representations over lengthy textual descriptions for large software systems. Visual documentation is both difficult to produce and challenging to evaluate. Manually creating it is time-consuming, and currently, no existing approach can automatically generate high-level visual documentation directly from code. Its evaluation is often subjective, making it difficult to standardize and automate. To address these challenges, this paper presents the first exploration of using agentic LLM systems to automatically generate visual documentation. We introduce VisDocSketcher, the first agent-based approach that combines static analysis with LLM agents to identify key elements in the code and produce corresponding visual representations. We propose a novel evaluation framework, AutoSketchEval, for assessing the quality of generated visual documentation using code-level metrics. The experimental results show that our approach can valid visual documentation for 74.4% of the samples. It shows an improvement of 26.7-39.8% over a simple template-based baseline. Our evaluation framework can reliably distinguish high-quality (code-aligned) visual documentation from low-quality (non-aligned) ones, achieving an AUC exceeding 0.87. Our work lays the foundation for future research on automated visual documentation by introducing practical tools that not only generate valid visual representations but also reliably assess their quality.

[Arxiv](https://arxiv.org/abs/2509.11942)