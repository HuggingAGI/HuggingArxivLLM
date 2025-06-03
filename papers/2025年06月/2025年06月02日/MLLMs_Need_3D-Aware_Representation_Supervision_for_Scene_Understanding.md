# 多模态大型语言模型实现场景理解，需引入 3D 感知表示监督

发布时间：2025年06月02日

`LLM应用

理由：这篇论文探讨了如何利用多模态大型语言模型（MLLMs）进行3D推理，并提出了一种新的框架3DRS来增强其3D表示能力。研究集中在如何通过引入3D基础模型的监督来提升MLLMs在场景理解任务中的性能，属于将大型语言模型应用于特定任务的范畴，因此归类为LLM应用。` `计算机视觉` `计算机图形学`

> MLLMs Need 3D-Aware Representation Supervision for Scene Understanding

# 摘要

> 近年来，场景理解领域取得了显著进展，研究者们利用多模态大型语言模型（MLLMs）进行3D推理，充分发挥了其强大的2D预训练能力。然而，MLLMs在预训练过程中缺乏显式3D数据，这限制了其3D表示能力。本文通过评估多视图对应关系，深入研究了MLLMs的3D感知能力，并发现3D感知表示的质量与下游任务性能之间存在显著的正相关关系。基于这一发现，我们提出了3DRS框架，通过引入预训练3D基础模型的监督，有效增强了MLLM的3D表示学习。我们的方法通过将MLLM的视觉特征与从3D模型中提炼出的丰富3D知识进行对齐，显著提升了场景理解能力。在多个基准测试和MLLM上的广泛实验中，包括视觉定位、图像描述和问答任务，均展示了性能的一致提升。项目页面：https://visual-ai.github.io/3drs

> Recent advances in scene understanding have leveraged multimodal large language models (MLLMs) for 3D reasoning by capitalizing on their strong 2D pretraining. However, the lack of explicit 3D data during MLLM pretraining limits 3D representation capability. In this paper, we investigate the 3D-awareness of MLLMs by evaluating multi-view correspondence and reveal a strong positive correlation between the quality of 3D-aware representation and downstream task performance. Motivated by this, we propose 3DRS, a framework that enhances MLLM 3D representation learning by introducing supervision from pretrained 3D foundation models. Our approach aligns MLLM visual features with rich 3D knowledge distilled from 3D models, effectively improving scene understanding. Extensive experiments across multiple benchmarks and MLLMs -- including visual grounding, captioning, and question answering -- demonstrate consistent performance gains. Project page: https://visual-ai.github.io/3drs

[Arxiv](https://arxiv.org/abs/2506.01946)