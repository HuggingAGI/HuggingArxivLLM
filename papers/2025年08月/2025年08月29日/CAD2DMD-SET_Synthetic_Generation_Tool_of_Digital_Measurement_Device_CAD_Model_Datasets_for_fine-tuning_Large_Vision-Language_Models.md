# CAD2DMD-SET：面向大型视觉语言模型微调的数字测量设备CAD模型数据集合成生成工具

发布时间：2025年08月29日

`LLM应用` `工业与制造`

> CAD2DMD-SET: Synthetic Generation Tool of Digital Measurement Device CAD Model Datasets for fine-tuning Large Vision-Language Models

# 摘要

> 大型视觉语言模型（LVLMs）的最新进展已在各类多模态任务中展现出令人瞩目的能力，然而在读取数字测量设备（DMDs）数值这类简单场景中，它们依然表现吃力——尤其是在现实环境中，常遇到的杂乱背景、物体遮挡、极端拍摄角度和运动模糊等问题，这些在头戴式相机和增强现实（AR）应用中十分普遍。针对这些不足，本研究推出了CAD2DMD-SET——一款专为支持DMDs相关视觉问答（VQA）任务设计的合成数据生成工具。该工具借助3D CAD模型、高级渲染技术和高保真图像合成，能够生成多样化且带VQA标注的合成DMD数据集，适用于LVLMs的微调。此外，我们还构建了DMDBench验证集——一个包含1000张真实场景标注图像的精选集合，用于评估模型在实际应用限制下的性能表现。通过平均归一化编辑距离相似度（ANLS）对三个最先进的LVLMs进行基准测试后，我们用CAD2DMD-SET生成的数据集微调这些模型的LoRA，结果显示性能大幅提升：InternVL的得分提高了200%，同时其他任务的性能未受影响。这表明CAD2DMD-SET训练数据集能显著增强LVLMs在上述复杂条件下的鲁棒性和表现。待本论文最终版本完成后，CAD2DMD-SET工具将开源发布，届时社区可自行添加不同测量设备并生成专属数据集。

> Recent advancements in Large Vision-Language Models (LVLMs) have demonstrated impressive capabilities across various multimodal tasks. They continue, however, to struggle with trivial scenarios such as reading values from Digital Measurement Devices (DMDs), particularly in real-world conditions involving clutter, occlusions, extreme viewpoints, and motion blur; common in head-mounted cameras and Augmented Reality (AR) applications. Motivated by these limitations, this work introduces CAD2DMD-SET, a synthetic data generation tool designed to support visual question answering (VQA) tasks involving DMDs. By leveraging 3D CAD models, advanced rendering, and high-fidelity image composition, our tool produces diverse, VQA-labelled synthetic DMD datasets suitable for fine-tuning LVLMs. Additionally, we present DMDBench, a curated validation set of 1,000 annotated real-world images designed to evaluate model performance under practical constraints. Benchmarking three state-of-the-art LVLMs using Average Normalised Levenshtein Similarity (ANLS) and further fine-tuning LoRA's of these models with CAD2DMD-SET's generated dataset yielded substantial improvements, with InternVL showcasing a score increase of 200% without degrading on other tasks. This demonstrates that the CAD2DMD-SET training dataset substantially improves the robustness and performance of LVLMs when operating under the previously stated challenging conditions. The CAD2DMD-SET tool is expected to be released as open-source once the final version of this manuscript is prepared, allowing the community to add different measurement devices and generate their own datasets.

[Arxiv](https://arxiv.org/abs/2508.21732)