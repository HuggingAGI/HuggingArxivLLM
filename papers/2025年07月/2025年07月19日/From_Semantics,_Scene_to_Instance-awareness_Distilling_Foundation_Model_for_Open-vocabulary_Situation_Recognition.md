# 从语义、场景到实例感知：蒸馏基础模型，助力开放词汇情况识别

发布时间：2025年07月19日

`LLM应用` `计算机视觉` `人工智能`

> From Semantics, Scene to Instance-awareness: Distilling Foundation Model for Open-vocabulary Situation Recognition

# 摘要

> 多模态大语言模型（MLLMs）虽然拥有强大的零样本能力，但在复杂场景识别任务（GSR）中表现受限，且在边缘设备部署时资源消耗巨大。与此同时，传统GSR模型普遍缺乏泛化能力，难以准确识别未见及罕见场景。针对这一问题，我们提出了一种知识迁移方案，通过从教师MLLM向小型GSR模型迁移知识，提升其泛化与零样本能力，从而提出开放词汇的基于场景识别任务（Ov-GSR）。为此，我们设计了多模态交互式提示蒸馏（MIPD）框架，能够从基础模型中提取丰富的多模态知识，赋能学生端Ov-GSR模型识别未见场景并更好感知罕见场景。具体而言，MIPD框架首先借助基于LLM的判断性理由生成器（JRG）构建包含上下文语义信息的正负视角和凝视理由。随后，我们引入场景感知与实例感知的提示，通过负引导的多模态提示对齐（NMPA）模块，将理由与MLLM教师模型的视觉信息对齐，从而有效捕捉整体与感知层面的多模态知识。最终，我们将对齐后的多模态知识蒸馏到学生端Ov-GSR模型中，为其提供更强大的泛化基础，显著提升场景理解能力，弥合已见与未见场景之间的差距，并有效缓解罕见情况下的预测偏差。我们在优化后的Ov-SWiG数据集上对MIPD进行了全面评估，结果显示其在已见、罕见和未见场景中均表现出色，进一步在HICO-DET数据集上的实验也验证了其在未见场景检测上的显著改进。

> Recent Multimodal Large Language Models (MLLMs) exhibit strong zero-shot abilities but struggle with complex Grounded Situation Recognition (GSR) and are resource-intensive for edge device deployment. Meanwhile, conventional GSR models often lack generalization ability, falling short in recognizing unseen and rare situations. In this paper, we exploit transferring knowledge from a teacher MLLM to a small GSR model to enhance its generalization and zero-shot abilities, thereby introducing the task of Open-vocabulary Grounded Situation Recognition (Ov-GSR). To achieve this, we propose Multimodal Interactive Prompt Distillation (MIPD), a novel framework that distills enriched multimodal knowledge from the foundation model, enabling the student Ov-GSR model to recognize unseen situations and be better aware of rare situations. Specifically, the MIPD framework first leverages the LLM-based Judgmental Rationales Generator (JRG) to construct positive and negative glimpse and gaze rationales enriched with contextual semantic information. The proposed scene-aware and instance-perception prompts are then introduced to align rationales with visual information from the MLLM teacher via the Negative-Guided Multimodal Prompting Alignment (NMPA) module, effectively capturing holistic and perceptual multimodal knowledge. Finally, the aligned multimodal knowledge is distilled into the student Ov-GSR model, providing a stronger foundation for generalization that enhances situation understanding, bridges the gap between seen and unseen scenarios, and mitigates prediction bias in rare cases. We evaluate MIPD on the refined Ov-SWiG dataset, achieving superior performance on seen, rare, and unseen situations, and further demonstrate improved unseen detection on the HICO-DET dataset.

[Arxiv](https://arxiv.org/abs/2507.14686)