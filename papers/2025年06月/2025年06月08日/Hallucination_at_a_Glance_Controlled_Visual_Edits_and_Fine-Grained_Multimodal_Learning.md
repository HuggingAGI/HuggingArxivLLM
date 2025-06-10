# 一目了然的幻觉：可控视觉编辑与细粒度多模态学习

发布时间：2025年06月08日

`LLM应用

LLM应用` `计算机视觉`

> Hallucination at a Glance: Controlled Visual Edits and Fine-Grained Multimodal Learning

# 摘要

> 多模态大型语言模型 (MLLMs) 在视觉语言任务中表现出色，但在处理细微视觉差异时仍存在不足，容易产生幻觉或遗漏语义变化。我们发现这主要源于训练数据和学习目标的局限性。为了解决这一问题，我们提出了一种受控的数据生成管道，用于生成带有语义对齐说明的最小编辑图像对。基于此，我们构建了包含50,000多个图像-文本对的 Micro Edit Dataset (MED)，涵盖11个细粒度编辑类别，包括属性、计数、位置和物体存在变化。在此基础上，我们引入了一个监督微调 (SFT) 框架，采用特征级别的一致性损失，以在小编辑下保持稳定的视觉嵌入。我们在 Micro Edit Detection 基准上评估我们的方法，该基准包含精心平衡的评估对，旨在测试对同一编辑类别中微妙视觉变化的敏感性。与强大的基线（包括 GPT-4o）相比，我们的方法显著提高了差异检测的准确性并减少了幻觉现象。此外，它在标准视觉语言任务（如图像描述和视觉问答）上也带来了持续的改进。这些结果证明了结合针对性数据和对齐目标来增强 MLLMs 细粒度视觉推理的有效性。

> Multimodal large language models (MLLMs) have achieved strong performance on vision-language tasks but still struggle with fine-grained visual differences, leading to hallucinations or missed semantic shifts. We attribute this to limitations in both training data and learning objectives. To address these issues, we propose a controlled data generation pipeline that produces minimally edited image pairs with semantically aligned captions. Using this pipeline, we construct the Micro Edit Dataset (MED), containing over 50K image-text pairs spanning 11 fine-grained edit categories, including attribute, count, position, and object presence changes. Building on MED, we introduce a supervised fine-tuning (SFT) framework with a feature-level consistency loss that promotes stable visual embeddings under small edits. We evaluate our approach on the Micro Edit Detection benchmark, which includes carefully balanced evaluation pairs designed to test sensitivity to subtle visual variations across the same edit categories. Our method improves difference detection accuracy and reduces hallucinations compared to strong baselines, including GPT-4o. Moreover, it yields consistent gains on standard vision-language tasks such as image captioning and visual question answering. These results demonstrate the effectiveness of combining targeted data and alignment objectives for enhancing fine-grained visual reasoning in MLLMs.

[Arxiv](https://arxiv.org/abs/2506.07227)