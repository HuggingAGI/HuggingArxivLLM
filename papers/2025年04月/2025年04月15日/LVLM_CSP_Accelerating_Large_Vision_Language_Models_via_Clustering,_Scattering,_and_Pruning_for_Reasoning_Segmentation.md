# LVLM_CSP: 利用聚类、扩散与剪枝加速大型视觉语言模型的推理分割能力

发布时间：2025年04月15日

`LLM应用` `计算机视觉` `图像处理`

> LVLM_CSP: Accelerating Large Vision Language Models via Clustering, Scattering, and Pruning for Reasoning Segmentation

# 摘要

> 大型视觉语言模型（LVLMs）在视觉推理分割任务中表现优异，但其显著的计算开销成为新的挑战。这种开销主要源于处理大量图像标记，因此，通过图像标记剪枝减少计算负担成为关键。此前研究多集中于高层次视觉任务，而精准的语义与空间推理需求使视觉掩膜生成更具挑战性。现有方法难以在控制计算开销的同时保持分割精度。为此，我们提出LVLM_CSP，一种专为LVLM推理分割设计的无训练视觉标记剪枝方法。该方法分为三个阶段：首先利用部分标记进行粗粒度推理，随后进行细粒度推理，最后剪枝冗余标记。实验表明，LVLM_CSP在几乎不损失精度的情况下，将推理FLOPs减少65%，并在7B模型上以仅1%的精度下降实现70%的优化。

> Large Vision Language Models (LVLMs) have been widely adopted to guide vision foundation models in performing reasoning segmentation tasks, achieving impressive performance. However, the substantial computational overhead associated with LVLMs presents a new challenge. The primary source of this computational cost arises from processing hundreds of image tokens. Therefore, an effective strategy to mitigate such overhead is to reduce the number of image tokens, a process known as image token pruning. Previous studies on image token pruning for LVLMs have primarily focused on high level visual understanding tasks, such as visual question answering and image captioning. In contrast, guiding vision foundation models to generate accurate visual masks based on textual queries demands precise semantic and spatial reasoning capabilities. Consequently, pruning methods must carefully control individual image tokens throughout the LVLM reasoning process. Our empirical analysis reveals that existing methods struggle to adequately balance reductions in computational overhead with the necessity to maintain high segmentation accuracy. In this work, we propose LVLM_CSP, a novel training free visual token pruning method specifically designed for LVLM based reasoning segmentation tasks. LVLM_CSP consists of three stages: clustering, scattering, and pruning. Initially, the LVLM performs coarse-grained visual reasoning using a subset of selected image tokens. Next, fine grained reasoning is conducted, and finally, most visual tokens are pruned in the last stage. Extensive experiments demonstrate that LVLM_CSP achieves a 65% reduction in image token inference FLOPs with virtually no accuracy degradation, and a 70% reduction with only a minor 1% drop in accuracy on the 7B LVLM.

[Arxiv](https://arxiv.org/abs/2504.10854)