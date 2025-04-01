# EagleVision：对象级别属性多模态大语言模型（LLM）在遥感中的应用

发布时间：2025年03月30日

`LLM应用` `计算机视觉`

> EagleVision: Object-level Attribute Multimodal LLM for Remote Sensing

# 摘要

> 多模态大型语言模型（MLLMs）在视觉任务中取得了令人瞩目的成果，但在遥感（RS）领域，现有MLLMs在高分辨率和小比例目标的处理上仍面临挑战，特别是在目标检测的精确定位和细粒度属性描述方面表现不足。当前的遥感MLLMs尚未超越经典视觉感知模型，仅能提供粗略的图像理解，在实际应用中的效果有限。为解决这一问题，我们开发了EagleVision——专为遥感设计的MLLM，它在目标检测和属性理解方面表现出色。通过引入属性解耦模块，EagleVision能够学习解耦视觉令牌以表达不同属性。为支持目标级别的视觉-语言对齐，我们构建了EVAttrs-95K——首个用于遥感领域的大型目标属性理解数据集，并开发了新的评估基准EVBench。EagleVision在细粒度目标检测和属性理解任务中达到顶尖水平，展现了MLLMs中检测与理解能力的协同提升。更多资源可访问https://github.com/XiangTodayEatsWhat/EagleVision获取。

> Recent advances in multimodal large language models (MLLMs) have demonstrated impressive results in various visual tasks. However, in remote sensing (RS), high resolution and small proportion of objects pose challenges to existing MLLMs, which struggle with object-centric tasks, particularly in precise localization and fine-grained attribute description for each object. These RS MLLMs have not yet surpassed classical visual perception models, as they only provide coarse image understanding, leading to limited gains in real-world scenarios. To address this gap, we establish EagleVision, an MLLM tailored for remote sensing that excels in object detection and attribute comprehension. Equipped with the Attribute Disentangle module, EagleVision learns disentanglement vision tokens to express distinct attributes. To support object-level visual-language alignment, we construct EVAttrs-95K, the first large-scale object attribute understanding dataset in RS for instruction tuning, along with a novel evaluation benchmark, EVBench. EagleVision achieves state-of-the-art performance on both fine-grained object detection and object attribute understanding tasks, highlighting the mutual promotion between detection and understanding capabilities in MLLMs. The code, model, data, and demo will be available at https://github.com/XiangTodayEatsWhat/EagleVision.

[Arxiv](https://arxiv.org/abs/2503.23330)