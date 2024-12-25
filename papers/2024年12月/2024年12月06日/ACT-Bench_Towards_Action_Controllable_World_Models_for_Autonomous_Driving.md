# ACT-Bench：致力于打造用于自动驾驶的动作可控世界模型

发布时间：2024年12月06日

`其他` `自动驾驶` `神经模拟`

> ACT-Bench: Towards Action Controllable World Models for Autonomous Driving

# 摘要

> 摘要：世界模型已成为自动驾驶领域颇具前景的神经模拟器，它能够补充稀缺的真实世界数据，还能实现闭环评估。然而，当下的研究主要依据视觉真实性或下游任务表现来评估这些模型，对特定动作指令的保真度关注不足，而这对于生成有针对性的模拟场景至关重要。虽然有部分研究涉及动作保真度，但其评估依赖闭源机制，可重复性受限。为填补这一空缺，我们开发了一个开放访问的评估框架 ACT-Bench 用于量化动作保真度，同时还构建了一个基准世界模型 Terra。我们的基准框架包含一个大规模数据集，将 nuScenes 的短上下文视频与相应的未来轨迹数据相匹配，为生成未来视频帧提供条件输入，并能够评估执行动作的动作保真度。此外，Terra 在多个大规模轨迹标注数据集上进行训练，以提升动作保真度。借助此框架，我们发现最先进的模型未完全遵循给定指令，而 Terra 实现了更优的动作保真度。我们基准框架的所有组件都将公开，以助力未来研究。

> 
Abstract:World models have emerged as promising neural simulators for autonomous driving, with the potential to supplement scarce real-world data and enable closed-loop evaluations. However, current research primarily evaluates these models based on visual realism or downstream task performance, with limited focus on fidelity to specific action instructions - a crucial property for generating targeted simulation scenes. Although some studies address action fidelity, their evaluations rely on closed-source mechanisms, limiting reproducibility. To address this gap, we develop an open-access evaluation framework, ACT-Bench, for quantifying action fidelity, along with a baseline world model, Terra. Our benchmarking framework includes a large-scale dataset pairing short context videos from nuScenes with corresponding future trajectory data, which provides conditional input for generating future video frames and enables evaluation of action fidelity for executed motions. Furthermore, Terra is trained on multiple large-scale trajectory-annotated datasets to enhance action fidelity. Leveraging this framework, we demonstrate that the state-of-the-art model does not fully adhere to given instructions, while Terra achieves improved action fidelity. All components of our benchmark framework will be made publicly available to support future research.
    

[Arxiv](https://arxiv.org/pdf/2412.05337)