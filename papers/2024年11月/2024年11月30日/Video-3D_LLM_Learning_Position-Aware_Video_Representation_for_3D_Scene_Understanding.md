# 视频-3D LLM：为理解 3D 场景学习具有位置感知的视频表示

发布时间：2024年11月30日

`LLM应用` `3D 场景理解` `多模态任务`

> Video-3D LLM: Learning Position-Aware Video Representation for 3D Scene Understanding

# 摘要

> 多模态大型语言模型（MLLMs）的迅猛发展，给各类多模态任务带来了显著影响。然而，这些模型在需要对 3D 环境进行空间理解的任务中遭遇挑战。为强化 MLLMs，比如融入点云特征，已付诸努力，可模型的学习表征与 3D 场景的固有复杂性之间仍存在较大差距。这种差距很大程度上源于 MLLMs 主要基于 2D 数据的训练，限制了其对 3D 空间的理解能力。为应对此问题，本文中，我们提出一种新颖的通用模型——Video-3D LLM，用于 3D 场景理解。通过将 3D 场景视作动态视频，并把 3D 位置编码纳入这些表征，我们的 Video-3D LLM 能更精准地将视频表征与现实世界的空间语境相匹配。此外，我们还采用了最大覆盖采样技术，以优化计算成本与性能效率之间的平衡。大量实验表明，我们的模型在包括 ScanRefer、Multi3DRefer、Scan2Cap、ScanQA 和 SQA3D 等多个 3D 场景理解基准测试中达到了领先水平。

> The rapid advancement of Multimodal Large Language Models (MLLMs) has significantly impacted various multimodal tasks. However, these models face challenges in tasks that require spatial understanding within 3D environments. Efforts to enhance MLLMs, such as incorporating point cloud features, have been made, yet a considerable gap remains between the models' learned representations and the inherent complexity of 3D scenes. This discrepancy largely stems from the training of MLLMs on predominantly 2D data, which restricts their effectiveness in comprehending 3D spaces. To address this issue, in this paper, we propose a novel generalist model, i.e., Video-3D LLM, for 3D scene understanding. By treating 3D scenes as dynamic videos and incorporating 3D position encoding into these representations, our Video-3D LLM aligns video representations with real-world spatial contexts more accurately. Additionally, we have implemented a maximum coverage sampling technique to optimize the balance between computational costs and performance efficiency. Extensive experiments demonstrate that our model achieves state-of-the-art performance on several 3D scene understanding benchmarks, including ScanRefer, Multi3DRefer, Scan2Cap, ScanQA, and SQA3D.

[Arxiv](https://arxiv.org/abs/2412.00493)