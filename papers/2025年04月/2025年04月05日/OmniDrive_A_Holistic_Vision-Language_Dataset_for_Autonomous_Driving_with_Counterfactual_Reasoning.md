# OmniDrive：一个用于自动驾驶反事实推理的综合性视觉-语言数据集。

发布时间：2025年04月05日

`Agent` `自动驾驶` `计算机视觉`

> OmniDrive: A Holistic Vision-Language Dataset for Autonomous Driving with Counterfactual Reasoning

# 摘要

> 视觉语言模型 (VLMs) 的进展在自动驾驶领域引发了广泛关注，因其强大的推理能力而备受期待。然而，将这些能力从2D扩展到3D理解对于实际应用至关重要。为此，我们提出了 OmniDrive，一个通过反事实推理将代理模型与3D驾驶任务对齐的综合性视觉语言数据集。这种方法通过评估潜在场景及其结果来增强决策-making，类似于人类驾驶员考虑替代行动。我们的基于反事实的合成数据标注流程生成大规模、高质量的数据集，提供更密集的监督信号，弥合规划轨迹与语言推理之间的差距。此外，我们探索了两个先进的 OmniDrive-Agent 框架，即 Omni-L 和 Omni-Q，以评估视觉语言对齐与3D感知的重要性，揭示了设计有效 LLM-代理的关键见解。在 DriveLM Q\&A 基准和 nuScenes 开环规划上的显著改进证明了我们数据集和方法的有效性。

> The advances in vision-language models (VLMs) have led to a growing interest in autonomous driving to leverage their strong reasoning capabilities. However, extending these capabilities from 2D to full 3D understanding is crucial for real-world applications. To address this challenge, we propose OmniDrive, a holistic vision-language dataset that aligns agent models with 3D driving tasks through counterfactual reasoning. This approach enhances decision-making by evaluating potential scenarios and their outcomes, similar to human drivers considering alternative actions. Our counterfactual-based synthetic data annotation process generates large-scale, high-quality datasets, providing denser supervision signals that bridge planning trajectories and language-based reasoning. Futher, we explore two advanced OmniDrive-Agent frameworks, namely Omni-L and Omni-Q, to assess the importance of vision-language alignment versus 3D perception, revealing critical insights into designing effective LLM-agents. Significant improvements on the DriveLM Q\&A benchmark and nuScenes open-loop planning demonstrate the effectiveness of our dataset and methods.

[Arxiv](https://arxiv.org/abs/2504.04348)