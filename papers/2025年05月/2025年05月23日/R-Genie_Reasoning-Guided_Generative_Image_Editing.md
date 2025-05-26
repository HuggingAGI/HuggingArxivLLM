# R-Genie：基于推理引导的生成式图像编辑

发布时间：2025年05月23日

`LLM应用` `图像编辑` `计算机视觉`

> R-Genie: Reasoning-Guided Generative Image Editing

# 摘要

> 图像编辑领域虽然取得了长足进步，但现有方法仍存在明显局限：它们依赖显式的文本指令，编辑操作有限，难以深入理解用户的隐含意图和上下文推理。针对这一问题，我们提出了一种全新的图像编辑范式——推理引导生成编辑。该方法能够处理复杂多维的文本查询，这些查询不仅包含丰富的世界知识，还能进行意图推断。

为实现这一目标，我们首先构建了一个包含1,000多个图像-指令-编辑三元组的综合性数据集，其中融入了丰富的推理上下文和现实世界知识。在此基础上，我们提出了R-Genie——一款推理引导的生成式图像编辑器。R-Genie巧妙结合了扩散模型的生成能力和多模态大语言模型的先进推理能力，并引入了推理注意力机制，实现了语言理解与视觉合成的深度结合。这使得R-Genie能够轻松应对那些涉及抽象用户意图和复杂上下文推理关系的编辑请求。

通过大量实验验证，R-Genie不仅成功赋予了扩散模型基于推理的高级编辑能力，更为智能图像合成开辟了新的可能性。


> While recent advances in image editing have enabled impressive visual synthesis capabilities, current methods remain constrained by explicit textual instructions and limited editing operations, lacking deep comprehension of implicit user intentions and contextual reasoning. In this work, we introduce a new image editing paradigm: reasoning-guided generative editing, which synthesizes images based on complex, multi-faceted textual queries accepting world knowledge and intention inference. To facilitate this task, we first construct a comprehensive dataset featuring over 1,000 image-instruction-edit triples that incorporate rich reasoning contexts and real-world knowledge. We then propose R-Genie: a reasoning-guided generative image editor, which synergizes the generation power of diffusion models with advanced reasoning capabilities of multimodal large language models. R-Genie incorporates a reasoning-attention mechanism to bridge linguistic understanding with visual synthesis, enabling it to handle intricate editing requests involving abstract user intentions and contextual reasoning relations. Extensive experimental results validate that R-Genie can equip diffusion models with advanced reasoning-based editing capabilities, unlocking new potentials for intelligent image synthesis.

[Arxiv](https://arxiv.org/abs/2505.17768)