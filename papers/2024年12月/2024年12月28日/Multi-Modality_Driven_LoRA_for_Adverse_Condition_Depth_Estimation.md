# 多模态驱动的 LoRA 用于不利条件下的深度估算

发布时间：2024年12月28日

`其他` `自动驾驶` `深度估计`

> Multi-Modality Driven LoRA for Adverse Condition Depth Estimation

# 摘要

> 自动驾驶领域日益聚焦于攻克极端情况难题，尤其是那些关乎在恶劣条件（如夜间、雾天、雨天）下保障驾驶安全的问题。正因如此，不利条件深度估计（ACDE）任务备受瞩目。此前 ACDE 中的方法主要依赖生成模型，这要么需要额外的目标图像把晴天状况转变为恶劣天气，要么需要可学习的参数来进行特征增强以适应领域差异，致使模型复杂度上升且调试工作加重。而且，不同于基于 CLIP 的方法中已预先对齐的文本和视觉特征，深度估计模型在多模态特征间缺乏足够的对齐，妨碍了在不利条件下的连贯理解。为应对这些局限，我们提出了多模态驱动的 LoRA（MMD-LoRA），它借助低秩适应矩阵实现从源域到目标域的高效微调。它包含两个核心组件：提示驱动域对齐（PDDA）和视觉 - 文本一致对比学习（VTCCL）。在 PDDA 过程中，配备 MMD-LoRA 的图像编码器生成目标域视觉表征，并由对齐损失进行监督，要求语言和图像之间的源 - 目标差异相等。同时，VTCCL 填补了来自 CLIP 的文本特征与来自扩散模型的视觉特征之间的鸿沟，将不同天气的表示（视觉和文本）区分开，把相似的表示聚拢起来。通过大量实验，所提方法在 nuScenes 和 Oxford RobotCar 数据集上取得了领先水平的性能，彰显出在适应各类恶劣环境时的稳健性和高效性。

> The autonomous driving community is increasingly focused on addressing corner case problems, particularly those related to ensuring driving safety under adverse conditions (e.g., nighttime, fog, rain). To this end, the task of Adverse Condition Depth Estimation (ACDE) has gained significant attention. Previous approaches in ACDE have primarily relied on generative models, which necessitate additional target images to convert the sunny condition into adverse weather, or learnable parameters for feature augmentation to adapt domain gaps, resulting in increased model complexity and tuning efforts. Furthermore, unlike CLIP-based methods where textual and visual features have been pre-aligned, depth estimation models lack sufficient alignment between multimodal features, hindering coherent understanding under adverse conditions. To address these limitations, we propose Multi-Modality Driven LoRA (MMD-LoRA), which leverages low-rank adaptation matrices for efficient fine-tuning from source-domain to target-domain. It consists of two core components: Prompt Driven Domain Alignment (PDDA) and Visual-Text Consistent Contrastive Learning(VTCCL). During PDDA, the image encoder with MMD-LoRA generates target-domain visual representations, supervised by alignment loss that the source-target difference between language and image should be equal. Meanwhile, VTCCL bridges the gap between textual features from CLIP and visual features from diffusion model, pushing apart different weather representations (vision and text) and bringing together similar ones. Through extensive experiments, the proposed method achieves state-of-the-art performance on the nuScenes and Oxford RobotCar datasets, underscoring robustness and efficiency in adapting to varied adverse environments.

[Arxiv](https://arxiv.org/abs/2412.20162)