# SA-Person：基于文本的人物检索与场景感知重排序

发布时间：2025年05月30日

`LLM应用

理由：这篇论文主要探讨了如何利用多模态大型语言模型（LLM）来提升基于文本的人物检索任务的性能。通过引入SceneRanker，该方法利用LLM进行场景感知推理，属于LLM的实际应用。因此，这篇论文被归类为LLM应用。` `图像处理` `计算机视觉`

> SA-Person: Text-Based Person Retrieval with Scene-aware Re-ranking

# 摘要

> 基于文本的人物检索旨在通过自然语言描述从图像集中识别目标个体。这一任务面临现实场景复杂性和外观描述模糊性的双重挑战。现有方法多聚焦于基于外观的跨模态检索，往往忽视了场景中蕴含的上下文信息，而这些信息对检索具有重要补充价值。为此，我们推出了SCENEPERSON-13W，一个包含10万余场景的大规模数据集，配有丰富的标注信息，涵盖行人外观和环境线索。基于此，我们提出了SA-Person，一个创新的两阶段检索框架。第一阶段通过将文本线索与行人特定区域对齐，实现判别性外观定位；第二阶段引入SceneRanker，一种无需训练的场景感知重新排序方法，利用多模态大型语言模型，对行人外观和全局场景上下文进行联合推理。实验结果表明，我们的框架在复杂场景检索任务中表现出色。代码和数据集即将公开发布。

> Text-based person retrieval aims to identify a target individual from a gallery of images based on a natural language description. It presents a significant challenge due to the complexity of real-world scenes and the ambiguity of appearance-related descriptions. Existing methods primarily emphasize appearance-based cross-modal retrieval, often neglecting the contextual information embedded within the scene, which can offer valuable complementary insights for retrieval. To address this, we introduce SCENEPERSON-13W, a large-scale dataset featuring over 100,000 scenes with rich annotations covering both pedestrian appearance and environmental cues. Based on this, we propose SA-Person, a two-stage retrieval framework. In the first stage, it performs discriminative appearance grounding by aligning textual cues with pedestrian-specific regions. In the second stage, it introduces SceneRanker, a training-free, scene-aware re-ranking method leveraging multimodal large language models to jointly reason over pedestrian appearance and the global scene context. Experiments on SCENEPERSON-13W validate the effectiveness of our framework in challenging scene-level retrieval scenarios. The code and dataset will be made publicly available.

[Arxiv](https://arxiv.org/abs/2505.24466)