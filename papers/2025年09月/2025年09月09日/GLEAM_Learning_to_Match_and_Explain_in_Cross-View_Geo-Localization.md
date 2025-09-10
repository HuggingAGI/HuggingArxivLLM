# GLEAM：跨视角地理定位中的匹配与解释学习

发布时间：2025年09月09日

`LLM应用` `交通运输`

> GLEAM: Learning to Match and Explain in Cross-View Geo-Localization

# 摘要

> 跨视角地理定位（CVGL）旨在识别同一地理位置不同视角图像间的对应关系。然而，现有CVGL方法多局限于单一视角或模态，且直接视觉匹配策略缺乏可解释性——仅判断图像是否对应，却不说明匹配依据。为此，我们提出基础CVGL模型GLEAM-C，它通过将无人机图像、街道地图、全景视图、地面照片等多视角、多模态数据与卫星图像精准对齐，实现了多源数据的统一。该框架通过优化实现提升了训练效率，并采用两阶段训练策略，精度可与现有特定模态CVGL模型媲美。此外，针对传统CVGL方法的可解释性不足，我们借助多模态大型语言模型（MLLMs）的推理能力，提出新任务GLEAM-X，将跨视角对应预测与可解释推理融为一体。为支持该任务，我们利用GPT-4o和豆包-1.5-思考-视觉-Pro构建双语基准，生成训练与测试数据。测试集经人工细致修订后进一步优化，可系统评估可解释跨视角推理能力，同时提升地理定位的透明度与可扩展性。GLEAM-C与GLEAM-X共同构成全面的CVGL流程，整合多模态、多视角对齐与可解释对应分析，实现准确跨视角匹配与可解释推理的统一，通过让模型更好地“解释并匹配（Explain And Match）”推动地理定位技术发展。本研究的代码与数据集将在https://github.com/Lucky-Lance/GLEAM公开。

> Cross-View Geo-Localization (CVGL) focuses on identifying correspondences between images captured from distinct perspectives of the same geographical location. However, existing CVGL approaches are typically restricted to a single view or modality, and their direct visual matching strategy lacks interpretability: they merely predict whether two images correspond, without explaining the rationale behind the match. In this paper, we present GLEAM-C, a foundational CVGL model that unifies multiple views and modalities-including UAV imagery, street maps, panoramic views, and ground photographs-by aligning them exclusively with satellite imagery. Our framework enhances training efficiency through optimized implementation while achieving accuracy comparable to prior modality-specific CVGL models through a two-phase training strategy. Moreover, to address the lack of interpretability in traditional CVGL methods, we leverage the reasoning capabilities of multimodal large language models (MLLMs) to propose a new task, GLEAM-X, which combines cross-view correspondence prediction with explainable reasoning. To support this task, we construct a bilingual benchmark using GPT-4o and Doubao-1.5-Thinking-Vision-Pro to generate training and testing data. The test set is further refined through detailed human revision, enabling systematic evaluation of explainable cross-view reasoning and advancing transparency and scalability in geo-localization. Together, GLEAM-C and GLEAM-X form a comprehensive CVGL pipeline that integrates multi-modal, multi-view alignment with interpretable correspondence analysis, unifying accurate cross-view matching with explainable reasoning and advancing Geo-Localization by enabling models to better Explain And Match. Code and datasets used in this work will be made publicly accessible at https://github.com/Lucky-Lance/GLEAM.

[Arxiv](https://arxiv.org/abs/2509.07450)