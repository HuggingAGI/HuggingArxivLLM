# 轨迹追踪结合大规模多模态模型，助力驾驶场景理解

发布时间：2025年03月18日

`LLM应用` `自动驾驶` `自动驾驶技术`

> Tracking Meets Large Multimodal Models for Driving Scenario Understanding

# 摘要

> 大语言模型（LMMs）在自动驾驶领域的研究中崭露头角，在多个新兴基准测试中展现出巨大潜力。这些专为自动驾驶设计的LMMs在感知、规划和预测能力方面表现出色。然而，现有方法在利用3D空间和时间信息方面仍有不足，主要依赖于图像数据，导致其在动态驾驶环境中的效果受限。我们提出通过引入追踪信息作为额外输入，来恢复图像中未能有效捕捉的3D空间和时间细节。我们还提出了一种新型方法，将追踪信息嵌入到LMMs中，以提升其对驾驶场景的时空理解能力。通过使用一个轨迹编码器整合3D追踪数据，我们能够在丰富视觉查询的同时，避免处理冗长视频序列或大量3D输入带来的计算负担。此外，我们采用自监督预训练方法来训练追踪编码器，为LMMs提供额外的上下文信息，从而显著提升了其在自动驾驶感知、规划和预测任务中的性能。实验结果表明，我们的方法在DriveLM-nuScenes基准测试中，准确率提升了9.5%，ChatGPT评分提高了7.04分，整体评分提升了9.4%，同时在DriveLM-CARLA测试中，最终评分也提升了3.7%。我们的代码可在GitHub上获取：https://github.com/mbzuai-oryx/TrackingMeetsLMM

> Large Multimodal Models (LMMs) have recently gained prominence in autonomous driving research, showcasing promising capabilities across various emerging benchmarks. LMMs specifically designed for this domain have demonstrated effective perception, planning, and prediction skills. However, many of these methods underutilize 3D spatial and temporal elements, relying mainly on image data. As a result, their effectiveness in dynamic driving environments is limited. We propose to integrate tracking information as an additional input to recover 3D spatial and temporal details that are not effectively captured in the images. We introduce a novel approach for embedding this tracking information into LMMs to enhance their spatiotemporal understanding of driving scenarios. By incorporating 3D tracking data through a track encoder, we enrich visual queries with crucial spatial and temporal cues while avoiding the computational overhead associated with processing lengthy video sequences or extensive 3D inputs. Moreover, we employ a self-supervised approach to pretrain the tracking encoder to provide LMMs with additional contextual information, significantly improving their performance in perception, planning, and prediction tasks for autonomous driving. Experimental results demonstrate the effectiveness of our approach, with a gain of 9.5% in accuracy, an increase of 7.04 points in the ChatGPT score, and 9.4% increase in the overall score over baseline models on DriveLM-nuScenes benchmark, along with a 3.7% final score improvement on DriveLM-CARLA. Our code is available at https://github.com/mbzuai-oryx/TrackingMeetsLMM

[Arxiv](https://arxiv.org/abs/2503.14498)