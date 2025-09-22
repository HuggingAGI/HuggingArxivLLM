# See&Trek：多模态大型语言模型的无需训练空间提示

发布时间：2025年09月19日

`LLM应用` `基础理论`

> See&Trek: Training-Free Spatial Prompting for Multimodal Large Language Model

# 摘要

> 我们提出SEE&TREK——首个专为纯视觉约束下增强多模态大型语言模型（MLLMs）空间理解能力设计的免训练提示框架。尽管已有研究通过整合深度或点云等模态来提升空间推理能力，但纯视觉空间理解领域仍有待深入探索。SEE&TREK聚焦两大核心原则以填补这一空白：提升视觉多样性与运动重建。在提升视觉多样性方面，我们采用最大语义丰富度采样策略——借助现成的感知模型提取语义丰富的关键帧，以捕捉场景结构。在运动重建方面，我们通过模拟视觉轨迹并将相对空间位置编码至关键帧，从而同时保留空间关系与时间连贯性。该方法无需训练和GPU，仅需单次前向传播，即可无缝集成到现有MLLMs中。在VSI-BENCH和STI-BENCH数据集上的大量实验验证，SEE&TREK能在各类空间推理任务中持续提升不同MLLMs的性能，最大提升幅度达3.5%，为构建更强的空间智能开辟了新路径。

> We introduce SEE&TREK, the first training-free prompting framework tailored to enhance the spatial understanding of Multimodal Large Language Models (MLLMS) under vision-only constraints. While prior efforts have incorporated modalities like depth or point clouds to improve spatial reasoning, purely visualspatial understanding remains underexplored. SEE&TREK addresses this gap by focusing on two core principles: increasing visual diversity and motion reconstruction. For visual diversity, we conduct Maximum Semantic Richness Sampling, which employs an off-the-shell perception model to extract semantically rich keyframes that capture scene structure. For motion reconstruction, we simulate visual trajectories and encode relative spatial positions into keyframes to preserve both spatial relations and temporal coherence. Our method is training&GPU-free, requiring only a single forward pass, and can be seamlessly integrated into existing MLLM'S. Extensive experiments on the VSI-B ENCH and STI-B ENCH show that S EE &T REK consistently boosts various MLLM S performance across diverse spatial reasoning tasks with the most +3.5% improvement, offering a promising path toward stronger spatial intelligence.

[Arxiv](https://arxiv.org/abs/2509.16087)