# CLIPure：通过CLIP方法，在潜在空间中进行净化，实现对抗鲁棒的零样本分类

发布时间：2025年02月25日

`LLM应用` `计算机视觉` `零样本分类`

> CLIPure: Purification in Latent Space via CLIP for Adversarially Robust Zero-Shot Classification

# 摘要

> 本文致力于构建一种对抗鲁棒的零样本图像分类器。我们的研究基于CLIP这一视觉-语言预训练编码器模型，它通过将图像与 ``a photo of a <class-name>'' 这类文本提示匹配实现零样本分类。我们采用净化方法，因其无需针对特定攻击类型进行对抗训练，从而能应对各种已知攻击。我们通过双向随机微分方程（SDEs）将净化风险建模为对抗样本去噪过程与良性样本扰动添加过程的联合分布间KL散度。这一发现启发我们在CLIP的多模态潜在空间中探索净化方法。我们提出了两种CLIPure方法的变体：CLIPure-Diff基于DaLLE-2中的DiffusionPrior模块建模图像潜在向量的似然，CLIPure-Cos则通过图像与 ``a photo of a'' 嵌入间的余弦相似性建模似然。值得注意的是，CLIPure是首个在多模态潜在空间中进行净化的方法，而CLIPure-Cos更是首个不依赖生成模型的净化方法，显著提升了防御效率。我们在CIFAR-10、ImageNet及13个先前用于评估CLIP基防御方法零样本分类鲁棒性的数据集上进行了全面实验。结果显示，CLIPure大幅超越了当前最优水平：在CIFAR10上从71.7%提升至91.1%，在ImageNet上从59.6%提升至72.6%，并在13个数据集上实现了108%的平均鲁棒性相对提升。代码已开源，地址为https://github.com/TMLResearchGroup-CAS/CLIPure。

> In this paper, we aim to build an adversarially robust zero-shot image classifier. We ground our work on CLIP, a vision-language pre-trained encoder model that can perform zero-shot classification by matching an image with text prompts ``a photo of a <class-name>.''. Purification is the path we choose since it does not require adversarial training on specific attack types and thus can cope with any foreseen attacks. We then formulate purification risk as the KL divergence between the joint distributions of the purification process of denoising the adversarial samples and the attack process of adding perturbations to benign samples, through bidirectional Stochastic Differential Equations (SDEs). The final derived results inspire us to explore purification in the multi-modal latent space of CLIP. We propose two variants for our CLIPure approach: CLIPure-Diff which models the likelihood of images' latent vectors with the DiffusionPrior module in DaLLE-2 (modeling the generation process of CLIP's latent vectors), and CLIPure-Cos which models the likelihood with the cosine similarity between the embeddings of an image and ``a photo of a.''. As far as we know, CLIPure is the first purification method in multi-modal latent space and CLIPure-Cos is the first purification method that is not based on generative models, which substantially improves defense efficiency. We conducted extensive experiments on CIFAR-10, ImageNet, and 13 datasets that previous CLIP-based defense methods used for evaluating zero-shot classification robustness. Results show that CLIPure boosts the SOTA robustness by a large margin, e.g., from 71.7% to 91.1% on CIFAR10, from 59.6% to 72.6% on ImageNet, and 108% relative improvements of average robustness on the 13 datasets over previous SOTA. The code is available at https://github.com/TMLResearchGroup-CAS/CLIPure.

[Arxiv](https://arxiv.org/abs/2502.18176)