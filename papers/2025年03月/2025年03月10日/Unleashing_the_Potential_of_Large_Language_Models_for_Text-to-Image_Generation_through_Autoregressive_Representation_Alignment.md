# 释放大型语言模型在文本到图像生成中的潜力，通过自回归表示对齐

发布时间：2025年03月10日

`LLM应用` `计算机视觉`

> Unleashing the Potential of Large Language Models for Text-to-Image Generation through Autoregressive Representation Alignment

# 摘要

> 我们提出了一种全新的训练框架——自回归表示对齐（ARRA），它无需改变模型架构即可在自回归语言模型中实现全局一致的文本到图像生成能力。与以往需要复杂架构重构的研究不同，ARRA通过全局视觉对齐损失和混合标记<HYBNEXT>，将语言模型的隐藏状态与外部视觉基础模型的视觉表示进行对齐。这个标记同时施加了两个约束：局部下一个标记预测和全局语义蒸馏，使语言模型能够在保持原有自回归范式的同时，隐式地学习空间和上下文一致性。大量实验验证了ARRA的即插即用灵活性。在仅从文本生成训练的语言模型或随机初始化开始训练时，ARRA为Chameleon和LlamaGen等先进自回归语言模型在医学图像（MIMIC-CXR）、深度眼网（DeepEyeNet）和ImageNet上分别降低了25.5%、8.8%和7.5%的FID值，且无需修改框架。在领域适应方面，ARRA使通用语言模型与专用模型（如BioMedCLIP）对齐，在医学图像（MIMIC-CXR）上比直接微调降低了18.6%的FID值。通过证明训练目标的重新设计——而不仅仅是架构创新——可以解决跨模态全局一致性挑战，ARRA为推进自回归模型提供了一种互补范式。代码和模型将被开源以促进自回归图像生成的发展。

> We present Autoregressive Representation Alignment (ARRA), a new training framework that unlocks global-coherent text-to-image generation in autoregressive LLMs without architectural changes. Unlike prior work that requires complex architectural redesigns, ARRA aligns LLM hidden states with visual representations from external visual foundational models via a global visual alignment loss and a hybrid token, <HYBNEXT>. This token enforces dual constraints: local next-token prediction and global semantic distillation, enabling LLMs to implicitly learn spatial and contextual coherence while retaining their original autoregressive paradigm. Extensive experiments validate ARRA's plug-and-play versatility. When training from text-generation-only LLMs or random initialization, ARRA reduces FID by 25.5% (MIMIC-CXR), 8.8% (DeepEyeNet), and 7.5% (ImageNet) for advanced autoregressive LLMs like Chameleon and LlamaGen, all without framework modifications. For domain adaption, ARRA aligns general-purpose LLMs with specialized models (e.g., BioMedCLIP), achieving an 18.6% FID reduction over direct fine-tuning on medical imaging (MIMIC-CXR). By demonstrating that training objective redesign -- not just architectural innovation -- can resolve cross-modal global coherence challenges, ARRA offers a complementary paradigm for advancing autoregressive models. Code and models will be released to advance autoregressive image generation.

[Arxiv](https://arxiv.org/abs/2503.07334)