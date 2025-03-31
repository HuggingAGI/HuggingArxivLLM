# NuGrounding：多视角3D视觉定位框架

发布时间：2025年03月28日

`LLM应用

理由：这篇论文主要探讨了多模态大语言模型（MLLMs）在自动驾驶中的应用，特别是如何结合3D视觉定位技术来提升目标物体的定位精度。研究中提出的创新性范式和数据集NuGrounding，以及实验结果都表明了MLLMs在这一具体任务中的应用价值。因此，这篇论文属于LLM应用类别。` `自动驾驶` `计算机视觉`

> NuGrounding: A Multi-View 3D Visual Grounding Framework in Autonomous Driving

# 摘要

> 多视图3D视觉定位是自动驾驶车辆在复杂环境中理解自然语言并精准定位目标物体的关键技术。然而，现有方法和数据集在语言指令粒度和3D几何推理与语言理解的结合上仍存在明显不足。为此，我们推出了首个面向自动驾驶的多视图3D视觉定位大规模基准数据集——NuGrounding。通过创新的分层定位方法（HoG），我们构建了NuGrounding，生成分层多级指令，全面覆盖人类指令模式。为应对这一具有挑战性的数据集，我们提出了一种融合多模态大语言模型（MLLMs）语言理解能力和专业检测模型精准定位能力的创新性范式。我们的方法通过两个解耦的任务令牌和上下文查询，有效聚合3D几何信息和语义指令，并借助融合解码器优化空间-语义特征融合，实现精准定位。实验结果表明，与现有方法相比，我们的方法在精度和召回率方面分别提升了50.8%和54.7%，达到了0.59和0.64的优异性能，显著超越现有技术。

> Multi-view 3D visual grounding is critical for autonomous driving vehicles to interpret natural languages and localize target objects in complex environments. However, existing datasets and methods suffer from coarse-grained language instructions, and inadequate integration of 3D geometric reasoning with linguistic comprehension. To this end, we introduce NuGrounding, the first large-scale benchmark for multi-view 3D visual grounding in autonomous driving. We present a Hierarchy of Grounding (HoG) method to construct NuGrounding to generate hierarchical multi-level instructions, ensuring comprehensive coverage of human instruction patterns. To tackle this challenging dataset, we propose a novel paradigm that seamlessly combines instruction comprehension abilities of multi-modal LLMs (MLLMs) with precise localization abilities of specialist detection models. Our approach introduces two decoupled task tokens and a context query to aggregate 3D geometric information and semantic instructions, followed by a fusion decoder to refine spatial-semantic feature fusion for precise localization. Extensive experiments demonstrate that our method significantly outperforms the baselines adapted from representative 3D scene understanding methods by a significant margin and achieves 0.59 in precision and 0.64 in recall, with improvements of 50.8% and 54.7%.

[Arxiv](https://arxiv.org/abs/2503.22436)