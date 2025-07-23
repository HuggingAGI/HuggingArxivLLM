# # 空间感知3D-LLM：深入探讨三维视觉语言模型中的空间意识

发布时间：2025年07月22日

`LLM应用` `3D视觉` `空间感知`

> Spatial 3D-LLM: Exploring Spatial Awareness in 3D Vision-Language Models

# 摘要

> 新时代为扩展大型语言模型（LLMs）以应对3D视觉语言任务开启了令人兴奋的可能性。然而，现有的大多数3D多模态LLMs（MLLMs）依赖于压缩整体3D场景信息或分割独立物体来执行这些任务，这限制了它们的空间感知能力，因为3D场景中固有的丰富性未能得到充分表达。为克服这些限制，我们提出了一种名为Spatial 3D-LLM的3D MLLM，专门设计用于通过丰富3D场景的空间嵌入来增强3D视觉语言任务的空间感知能力。Spatial 3D-LLM将LLM主干与一种渐进式空间感知方案相结合，随着感知域的扩展，逐步捕获空间信息，生成位置增强的3D场景嵌入，作为视觉提示。此外，我们引入了两个新颖的任务：3D物体距离测量和3D布局编辑，并构建了一个3D指令数据集MODEL，以评估模型的空间感知能力。实验结果表明，Spatial 3D-LLM在广泛的3D视觉语言任务中实现了最先进的性能，揭示了我们渐进式空间感知方案带来的改进，该方案挖掘了更深层次的空间信息。我们的代码可在https://github.com/bjshuyuan/Spatial-3D-LLM获取。

> New era has unlocked exciting possibilities for extending Large Language Models (LLMs) to tackle 3D vision-language tasks. However, most existing 3D multimodal LLMs (MLLMs) rely on compressing holistic 3D scene information or segmenting independent objects to perform these tasks, which limits their spatial awareness due to insufficient representation of the richness inherent in 3D scenes. To overcome these limitations, we propose Spatial 3D-LLM, a 3D MLLM specifically designed to enhance spatial awareness for 3D vision-language tasks by enriching the spatial embeddings of 3D scenes. Spatial 3D-LLM integrates an LLM backbone with a progressive spatial awareness scheme that progressively captures spatial information as the perception field expands, generating location-enriched 3D scene embeddings to serve as visual prompts. Furthermore, we introduce two novel tasks: 3D object distance measurement and 3D layout editing, and construct a 3D instruction dataset, MODEL, to evaluate the model's spatial awareness capabilities. Experimental results demonstrate that Spatial 3D-LLM achieves state-of-the-art performance across a wide range of 3D vision-language tasks, revealing the improvements stemmed from our progressive spatial awareness scheme of mining more profound spatial information. Our code is available at https://github.com/bjshuyuan/Spatial-3D-LLM.

[Arxiv](https://arxiv.org/abs/2507.16524)