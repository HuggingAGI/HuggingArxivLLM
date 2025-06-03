# EarthMind：多粒度、多传感器地球观测的大型多模态模型研究

发布时间：2025年06月02日

`LLM应用` `地球科学` `环境监测`

> EarthMind: Towards Multi-Granular and Multi-Sensor Earth Observation with Large Multimodal Models

# 摘要

> 大型多模态模型（LMMs）在视觉语言任务中表现出色，但在地球观测（EO）数据的理解方面仍存在挑战，这对环境监测及人类活动影响评估至关重要。本研究提出了一种名为EarthMind的新型视觉语言框架，专注于多粒度和多传感器地球观测数据的理解。该框架的核心创新包括：（1）空间注意力提示（SAP），通过重新分配模型注意力机制，提升像素级理解能力；（2）跨模态融合技术，通过异质模态对齐和信息密度自适应加权，实现高效的多模态融合。为评估多传感器融合效果，我们构建了EarthMind-Bench基准测试集，包含2000多个标注的多传感器图像-问题配对，覆盖广泛的感知与推理任务。实验结果表明，EarthMind不仅在基准测试中达到最先进的性能水平，超越40亿参数规模的GPT-4o，还在多个公开地球观测基准测试中超越现有方法，充分展现了其在统一框架下处理多粒度和多传感器挑战的潜力。

> Large Multimodal Models (LMMs) have demonstrated strong performance in various vision-language tasks. However, they often struggle to comprehensively understand Earth Observation (EO) data, which is critical for monitoring the environment and the effects of human activity on it. In this work, we present EarthMind, a novel vision-language framework for multi-granular and multi-sensor EO data understanding. EarthMind features two core components: (1) Spatial Attention Prompting (SAP), which reallocates attention within the LLM to enhance pixel-level understanding; and (2) Cross-modal Fusion, which aligns heterogeneous modalities into a shared space and adaptively reweighs tokens based on their information density for effective fusion. To facilitate multi-sensor fusion evaluation, we propose EarthMind-Bench, a comprehensive benchmark with over 2,000 human-annotated multi-sensor image-question pairs, covering a wide range of perception and reasoning tasks. Extensive experiments demonstrate the effectiveness of EarthMind. It achieves state-of-the-art performance on EarthMind-Bench, surpassing GPT-4o despite being only 4B in scale. Moreover, EarthMind outperforms existing methods on multiple public EO benchmarks, showcasing its potential to handle both multi-granular and multi-sensor challenges in a unified framework.

[Arxiv](https://arxiv.org/abs/2506.01667)