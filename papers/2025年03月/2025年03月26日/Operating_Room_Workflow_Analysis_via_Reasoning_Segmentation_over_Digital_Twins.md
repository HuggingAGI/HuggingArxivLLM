# 基于数字孪生的手术室工作流程推理分割分析

发布时间：2025年03月26日

`LLM应用` `数字孪生`

> Operating Room Workflow Analysis via Reasoning Segmentation over Digital Twins

# 摘要

> 分析手术室 (OR) 工作流程以获取效率洞察，对医院提升患者护理和财务可持续性至关重要。此前的 OR 级工作流程分析主要依赖于端到端深度神经网络，尽管这些方法在受控环境中表现良好，但缺乏灵活性，无法适应不同场景（如大型学术中心与农村医疗机构）的 OR 分析需求，且需要数据收集、标注和重新训练。基于基础模型的推理分割 (RS) 通过仅使用隐式文本查询即可实现对手术室视频流的自动化分析，提供了这种灵活性。然而，现有 RS 方法受限于 LLM 微调，在推理语义/空间关系方面表现有限，且对 OR 视频的泛化能力不足。为解决这些问题，我们提出了一种新型数字孪生 (DT) 表示，保留了 OR 各组件间的语义和空间关系。在此基础上，我们提出了无需 LLM 微调的 ORDiRS 框架，重新定义了 RS 为“推理-检索-合成”范式。此外，我们还开发了 ORDiRS-Agent，这是一种基于 LLM 的代理，可将 OR 工作流程分析查询分解为可管理的 RS 子查询，并结合 RS 提供的详细文本解释和视觉证据生成响应。实验结果表明，与现有方法相比，ORDiRS 在内部和公共 OR 数据集上实现了 6.12%-9.74% 的 cIoU 提升。


> Analyzing operating room (OR) workflows to derive quantitative insights into OR efficiency is important for hospitals to maximize patient care and financial sustainability. Prior work on OR-level workflow analysis has relied on end-to-end deep neural networks. While these approaches work well in constrained settings, they are limited to the conditions specified at development time and do not offer the flexibility necessary to accommodate the OR workflow analysis needs of various OR scenarios (e.g., large academic center vs. rural provider) without data collection, annotation, and retraining. Reasoning segmentation (RS) based on foundation models offers this flexibility by enabling automated analysis of OR workflows from OR video feeds given only an implicit text query related to the objects of interest. Due to the reliance on large language model (LLM) fine-tuning, current RS approaches struggle with reasoning about semantic/spatial relationships and show limited generalization to OR video due to variations in visual characteristics and domain-specific terminology. To address these limitations, we first propose a novel digital twin (DT) representation that preserves both semantic and spatial relationships between the various OR components. Then, building on this foundation, we propose ORDiRS (Operating Room Digital twin representation for Reasoning Segmentation), an LLM-tuning-free RS framework that reformulates RS into a "reason-retrieval-synthesize" paradigm. Finally, we present ORDiRS-Agent, an LLM-based agent that decomposes OR workflow analysis queries into manageable RS sub-queries and generates responses by combining detailed textual explanations with supporting visual evidence from RS. Experimental results on both an in-house and a public OR dataset demonstrate that our ORDiRS achieves a cIoU improvement of 6.12%-9.74% compared to the existing state-of-the-arts.

[Arxiv](https://arxiv.org/abs/2503.21054)