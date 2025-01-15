# 3UR-LLM: 端到端多模态大语言模型，专为3D场景理解而生

发布时间：2025年01月13日

`LLM应用

理由：这篇论文主要讨论了多模态大型语言模型（MLLMs）在3D场景理解中的应用，特别是如何通过生成高质量的3D-文本对来增强预训练过程，并引入了一个新的3D MLLM模型（3UR-LLM）。论文的核心在于如何利用LLM技术来解决3D场景理解中的实际问题，属于LLM在实际应用中的研究和开发。因此，将其分类为“LLM应用”是合适的。` `计算机视觉` `3D建模`

> 3UR-LLM: An End-to-End Multimodal Large Language Model for 3D Scene Understanding

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）在2D任务中表现出色，但在从2D到3D的转换中，识别场景中的空间位置、相互关系和因果逻辑时遇到了挑战。这些挑战主要源于：i）高标注成本限制了3D场景数据量的扩展，ii）缺乏直接有效的方式来感知3D信息，导致训练时间延长并使框架复杂化。为此，我们开发了一个基于开源2D MLLMs和LLMs的流程，生成高质量的3D-文本对并构建3DS-160K，以增强预训练过程。利用这些高质量的预训练数据，我们引入了3UR-LLM模型，这是一个端到端的3D MLLM，旨在精确解释3D场景，展示了在应对物理世界复杂性方面的卓越能力。3UR-LLM直接接收3D点云作为输入，并将与文本指令融合的3D特征投影到一组可管理的token中。考虑到这些混合token带来的计算负担，我们设计了一个3D压缩模块，以协同压缩3D空间线索和文本叙述。3UR-LLM在之前的SOTAs中表现优异，例如，在ScanQA上，3UR-LLM以7.1%的CIDEr超过了其竞争对手，同时使用了更少的训练资源。3UR-LLM的代码和模型权重以及3DS-160K基准测试可在3UR-LLM上获取。

> Multi-modal Large Language Models (MLLMs) exhibit impressive capabilities in 2D tasks, yet encounter challenges in discerning the spatial positions, interrelations, and causal logic in scenes when transitioning from 2D to 3D representations. We find that the limitations mainly lie in: i) the high annotation cost restricting the scale-up of volumes of 3D scene data, and ii) the lack of a straightforward and effective way to perceive 3D information which results in prolonged training durations and complicates the streamlined framework. To this end, we develop pipeline based on open-source 2D MLLMs and LLMs to generate high-quality 3D-text pairs and construct 3DS-160K , to enhance the pre-training process. Leveraging this high-quality pre-training data, we introduce the 3UR-LLM model, an end-to-end 3D MLLM designed for precise interpretation of 3D scenes, showcasing exceptional capability in navigating the complexities of the physical world. 3UR-LLM directly receives 3D point cloud as input and project 3D features fused with text instructions into a manageable set of tokens. Considering the computation burden derived from these hybrid tokens, we design a 3D compressor module to cohesively compress the 3D spatial cues and textual narrative. 3UR-LLM achieves promising performance with respect to the previous SOTAs, for instance, 3UR-LLM exceeds its counterparts by 7.1\% CIDEr on ScanQA, while utilizing fewer training resources. The code and model weights for 3UR-LLM and the 3DS-160K benchmark are available at 3UR-LLM.

[Arxiv](https://arxiv.org/abs/2501.07819)