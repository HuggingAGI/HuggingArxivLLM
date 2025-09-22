# M-PACE：面向多模态合规的母子框架

发布时间：2025年09月17日

`LLM应用` `零售与电商`

> M-PACE: Mother Child Framework for Multimodal Compliance

# 摘要

> 在各个领域，确保多模态内容符合品牌、法律或平台特定的合规标准已成为一项日益复杂的挑战。传统合规框架往往依赖分散的多阶段流水线，集成了图像分类、文本提取、音频转录、手工检查及基于规则合并等独立模块。这种架构碎片化不仅增加了运营成本，还限制了可扩展性，同时削弱了高效适应动态指南的能力。随着多模态大型语言模型（MLLMs）的兴起，将这些工作流整合到一个能联合处理视觉与文本内容的单一通用框架中的潜力日益凸显。为此，我们提出多模态参数无关合规引擎（M-PACE），这一框架可通过单次处理完成对视觉-语言输入中各类属性的评估。作为典型应用场景，我们将M-PACE用于广告合规检测，结果表明它能评估15种以上的合规相关属性。为支持结构化评估，我们构建了人工标注的基准数据集，其中包含大量增强样本，可模拟视觉遮挡、不良用语植入等真实场景中的复杂挑战。M-PACE采用母子MLLM架构：由性能更强的母模型评估小型子模型的输出，这能大幅降低对人工审核的依赖，进而实现质量控制自动化。分析结果显示，M-PACE的推理成本降低了31倍以上：效率最优的配置（母模型选择Gemini 2.0 Flash作为子模型）每张图像成本仅0.0005，而准确率相近的Gemini 2.5 Pro成本为0.0159。这一结果充分体现了M-PACE在广告数据实际部署中，能实时平衡成本与输出质量的优势。

> Ensuring that multi-modal content adheres to brand, legal, or platform-specific compliance standards is an increasingly complex challenge across domains. Traditional compliance frameworks typically rely on disjointed, multi-stage pipelines that integrate separate modules for image classification, text extraction, audio transcription, hand-crafted checks, and rule-based merges. This architectural fragmentation increases operational overhead, hampers scalability, and hinders the ability to adapt to dynamic guidelines efficiently. With the emergence of Multimodal Large Language Models (MLLMs), there is growing potential to unify these workflows under a single, general-purpose framework capable of jointly processing visual and textual content. In light of this, we propose Multimodal Parameter Agnostic Compliance Engine (M-PACE), a framework designed for assessing attributes across vision-language inputs in a single pass. As a representative use case, we apply M-PACE to advertisement compliance, demonstrating its ability to evaluate over 15 compliance-related attributes. To support structured evaluation, we introduce a human-annotated benchmark enriched with augmented samples that simulate challenging real-world conditions, including visual obstructions and profanity injection. M-PACE employs a mother-child MLLM setup, demonstrating that a stronger parent MLLM evaluating the outputs of smaller child models can significantly reduce dependence on human reviewers, thereby automating quality control. Our analysis reveals that inference costs reduce by over 31 times, with the most efficient models (Gemini 2.0 Flash as child MLLM selected by mother MLLM) operating at 0.0005 per image, compared to 0.0159 for Gemini 2.5 Pro with comparable accuracy, highlighting the trade-off between cost and output quality achieved in real time by M-PACE in real life deployment over advertising data.

[Arxiv](https://arxiv.org/abs/2509.15241)