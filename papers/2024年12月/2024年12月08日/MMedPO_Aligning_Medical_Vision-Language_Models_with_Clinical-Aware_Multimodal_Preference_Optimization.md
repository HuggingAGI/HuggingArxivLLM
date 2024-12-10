# MMedPO：借助临床感知多模态偏好优化来对齐医疗视觉语言模型

发布时间：2024年12月08日

`LLM应用` `多模态`

> MMedPO: Aligning Medical Vision-Language Models with Clinical-Aware Multimodal Preference Optimization

# 摘要

> 大型视觉语言模型（LVLMs）的发展推动了其在医疗领域的应用。然而，医疗 LVLMs（Med-LVLMs）因模态不匹配面临事实性挑战，模型更看重文本知识而非视觉输入，从而产生与医学图像信息相悖的幻觉。此前通过偏好优化来增强 Med-LVLMs 模态对齐的尝试，未能充分降低偏好数据中的临床相关性，导致这些样本易于区分，降低了对齐效果。为应对此挑战，我们提出 MMedPO，这是一种新颖的多模态医疗偏好优化方法，它考虑偏好样本的临床相关性以增强 Med-LVLM 的对齐。MMedPO 通过引入两种不偏好类型来整理多模态偏好数据：（1）通过目标 Med-LVLMs 或 GPT-4o 注入看似合理的幻觉，产生医学上不准确的响应；（2）通过局部病变噪声实现病变区域的忽略，破坏对关键区域的视觉理解。接着，我们根据多个 Med-LLMs 和视觉工具的得分，为每个样本计算临床相关性，并将这些得分作为权重整合到偏好优化过程中，实现有效对齐。我们的实验表明，MMedPO 显著提高了 Med-LVLMs 的事实准确性，在 Med-VQA 和报告生成任务中，相较于现有偏好优化方法，平均分别提升了 14.2％和 51.7％。我们的代码可在 https://github.com/aiming-lab/MMedPO 获取。

> The advancement of Large Vision-Language Models (LVLMs) has propelled their application in the medical field. However, Medical LVLMs (Med-LVLMs) encounter factuality challenges due to modality misalignment, where the models prioritize textual knowledge over visual input, leading to hallucinations that contradict information in medical images. Previous attempts to enhance modality alignment in Med-LVLMs through preference optimization have inadequately mitigated clinical relevance in preference data, making these samples easily distinguishable and reducing alignment effectiveness. To address this challenge, we propose MMedPO, a novel multimodal medical preference optimization approach that considers the clinical relevance of preference samples to enhance Med-LVLM alignment. MMedPO curates multimodal preference data by introducing two types of dispreference: (1) plausible hallucinations injected through target Med-LVLMs or GPT-4o to produce medically inaccurate responses, and (2) lesion region neglect achieved through local lesion-noising, disrupting visual understanding of critical areas. We then calculate clinical relevance for each sample based on scores from multiple Med-LLMs and visual tools, and integrate these scores into the preference optimization process as weights, enabling effective alignment. Our experiments demonstrate that MMedPO significantly enhances factual accuracy in Med-LVLMs, achieving substantial improvements over existing preference optimization methods by averaging 14.2% and 51.7% across the Med-VQA and report generation tasks. Our code are available in https://github.com/aiming-lab/MMedPO.

[Arxiv](https://arxiv.org/abs/2412.06141)