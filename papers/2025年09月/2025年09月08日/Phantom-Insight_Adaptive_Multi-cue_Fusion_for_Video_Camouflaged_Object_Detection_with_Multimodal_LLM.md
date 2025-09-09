# Phantom-Insight：结合多模态大型语言模型的自适应多线索融合视频伪装目标检测

发布时间：2025年09月08日

`LLM应用` `基础理论`

> Phantom-Insight: Adaptive Multi-cue Fusion for Video Camouflaged Object Detection with Multimodal LLM

# 摘要

> 视频伪装目标检测（VCOD）因动态环境而极具挑战性。现有方法存在两个主要问题：（1）基于SAM的方法因模型冻结，难以分离伪装目标的边缘；（2）基于MLLM的方法则因大型语言模型会融合前景与背景，导致目标可分离性不佳。针对这些问题，我们提出了一种基于SAM和MLLM的新型VCOD方法——Phantom-Insight。为增强目标边缘细节的可分离性，我们利用时空线索表征视频序列，并通过LLM进行特征融合以提升信息密度。随后，通过动态前景视觉标记评分模块与提示网络生成多线索，自适应引导并微调SAM模型，使其能够适应细微纹理。为增强目标与背景的可分离性，我们提出解耦的前景-背景学习策略。通过分别生成前景与背景线索并进行解耦训练，视觉标记能够独立且有效地整合前景与背景信息，从而让SAM更精准地分割视频中的伪装目标。在MoCA-Mask数据集上的实验表明，Phantom-Insight在各项指标上均达到了当前最优性能。此外，其在CAD2016数据集上对未见伪装目标的检测能力，彰显了其强大的泛化性能。

> Video camouflaged object detection (VCOD) is challenging due to dynamic environments. Existing methods face two main issues: (1) SAM-based methods struggle to separate camouflaged object edges due to model freezing, and (2) MLLM-based methods suffer from poor object separability as large language models merge foreground and background. To address these issues, we propose a novel VCOD method based on SAM and MLLM, called Phantom-Insight. To enhance the separability of object edge details, we represent video sequences with temporal and spatial clues and perform feature fusion via LLM to increase information density. Next, multiple cues are generated through the dynamic foreground visual token scoring module and the prompt network to adaptively guide and fine-tune the SAM model, enabling it to adapt to subtle textures. To enhance the separability of objects and background, we propose a decoupled foreground-background learning strategy. By generating foreground and background cues separately and performing decoupled training, the visual token can effectively integrate foreground and background information independently, enabling SAM to more accurately segment camouflaged objects in the video. Experiments on the MoCA-Mask dataset show that Phantom-Insight achieves state-of-the-art performance across various metrics. Additionally, its ability to detect unseen camouflaged objects on the CAD2016 dataset highlights its strong generalization ability.

[Arxiv](https://arxiv.org/abs/2509.06422)