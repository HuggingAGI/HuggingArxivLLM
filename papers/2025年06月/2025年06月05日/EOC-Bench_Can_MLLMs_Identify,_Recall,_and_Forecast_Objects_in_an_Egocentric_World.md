# EOC-Bench: 多语言大型模型能否在以自我为中心的世界中识别、回忆和预测物体？

发布时间：2025年06月05日

`LLM应用` `机器人` `自动驾驶`

> EOC-Bench: Can MLLMs Identify, Recall, and Forecast Objects in an Egocentric World?

# 摘要

> 多模态大型语言模型 (MLLMs) 的出现为自中心视觉应用带来了突破性进展。这些应用需要在动态复杂环境中持续感知对象，理解用户与工具的交互。然而，现有具身基准测试主要关注静态场景，侧重于对象外观和空间属性，忽视了用户交互带来的动态变化评估。为填补这一空白，我们提出了 EOC-Bench，一个全新基准测试，专注于动态自中心场景下对象为中心的具身认知能力评估。EOC-Bench 拥有 3,277 个精心标注的问答对，分为过去、现在、未来三个时间类别，涵盖 11 个细粒度评估维度和 3 种视觉对象引用类型。为确保全面评估，我们开发了混合格式的人在环注释框架，包含四种问题类型，并设计了新型多尺度时间准确性指标，支持开放式时间评估。基于 EOC-Bench，我们对多种专有、开源和对象级别 MLLMs 进行了全面评估。EOC-Bench 为提升 MLLMs 的具身对象认知能力提供了重要工具，为开发可靠的具身系统核心模型奠定了坚实基础。

> The emergence of multimodal large language models (MLLMs) has driven breakthroughs in egocentric vision applications. These applications necessitate persistent, context-aware understanding of objects, as users interact with tools in dynamic and cluttered environments. However, existing embodied benchmarks primarily focus on static scene exploration, emphasizing object's appearance and spatial attributes while neglecting the assessment of dynamic changes arising from users' interactions. To address this gap, we introduce EOC-Bench, an innovative benchmark designed to systematically evaluate object-centric embodied cognition in dynamic egocentric scenarios. Specially, EOC-Bench features 3,277 meticulously annotated QA pairs categorized into three temporal categories: Past, Present, and Future, covering 11 fine-grained evaluation dimensions and 3 visual object referencing types. To ensure thorough assessment, we develop a mixed-format human-in-the-loop annotation framework with four types of questions and design a novel multi-scale temporal accuracy metric for open-ended temporal evaluation. Based on EOC-Bench, we conduct comprehensive evaluations of various proprietary, open-source, and object-level MLLMs. EOC-Bench serves as a crucial tool for advancing the embodied object cognitive capabilities of MLLMs, establishing a robust foundation for developing reliable core models for embodied systems.

[Arxiv](https://arxiv.org/abs/2506.05287)