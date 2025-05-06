# 视觉与意图赋能大型语言模型，提升长期行为预测能力

发布时间：2025年05月03日

`LLM应用` `计算机视觉`

> Vision and Intention Boost Large Language Model in Long-Term Action Anticipation

# 摘要

> 长期动作预测 (LTA)旨在在较长时间内预测未来的动作。以往方法主要基于视频数据学习，但缺乏先验知识；近期研究则通过基于文本的输入利用大型语言模型 (LLMs)，但面临严重信息丢失的问题。为解决这些单模态方法的局限性，我们提出了一种新颖的意图条件化视觉语言 (ICVL) 模型，充分利用视觉数据的丰富语义信息和 LLMs 强大的推理能力。

考虑到意图作为指导动作演进的高级概念，我们提出使用视觉语言模型 (VLM) 从视频输入中直接推断行为意图，生成全面的文本特征。推断出的意图通过多模态融合策略与视觉特征融合，生成增强意图的视觉表示。这些增强的视觉表示连同文本提示被输入到 LLM 中，用于未来动作预测。此外，我们提出了一种综合考虑视觉和文本相似性的示例选择策略，为上下文学习提供更相关和信息丰富的示例。

我们在 Ego4D、EPIC-Kitchens-55 和 EGTEA GAZE+ 数据集上的大量实验表明，所提方法在长期动作预测任务中表现出显著的优势和有效性。

> Long-term action anticipation (LTA) aims to predict future actions over an extended period. Previous approaches primarily focus on learning exclusively from video data but lack prior knowledge. Recent researches leverage large language models (LLMs) by utilizing text-based inputs which suffer severe information loss. To tackle these limitations single-modality methods face, we propose a novel Intention-Conditioned Vision-Language (ICVL) model in this study that fully leverages the rich semantic information of visual data and the powerful reasoning capabilities of LLMs. Considering intention as a high-level concept guiding the evolution of actions, we first propose to employ a vision-language model (VLM) to infer behavioral intentions as comprehensive textual features directly from video inputs. The inferred intentions are then fused with visual features through a multi-modality fusion strategy, resulting in intention-enhanced visual representations. These enhanced visual representations, along with textual prompts, are fed into LLM for future action anticipation. Furthermore, we propose an effective example selection strategy jointly considers visual and textual similarities, providing more relevant and informative examples for in-context learning. Extensive experiments with state-of-the-art performance on Ego4D, EPIC-Kitchens-55, and EGTEA GAZE+ datasets fully demonstrate the effectiveness and superiority of the proposed method.

[Arxiv](https://arxiv.org/abs/2505.01713)