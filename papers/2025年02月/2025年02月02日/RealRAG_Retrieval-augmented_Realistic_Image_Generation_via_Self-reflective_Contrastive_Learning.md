# RealRAG: 基于自反对比学习的检索增强现实图像生成

发布时间：2025年02月02日

`RAG

理由：该论文提出了一个基于真实对象的检索增强生成框架（RealRAG），通过检索现实图像来弥补生成模型的知识缺口，从而提升生成效果。这属于检索增强生成（Retrieval-Augmented Generation, RAG）的范畴，因此应归类为RAG。` `计算机视觉` `图像生成`

> RealRAG: Retrieval-augmented Realistic Image Generation via Self-reflective Contrastive Learning

# 摘要

> # 摘要
近期，Stable Diffusion V3 和 Flux 等文本到图像生成模型取得了显著进展。然而，这些模型受限于其固定参数和封闭数据集训练的知识范围，导致在面对细粒度或未见过的现实世界对象（如特斯拉 Cybertruck）时，容易出现幻觉或失真。为此，我们提出了首个基于真实对象的检索增强生成框架（RealRAG），通过学习并检索现实图像来弥补生成模型的知识缺口，从而提升细粒度和未见对象的生成效果。具体而言，我们通过自反对比学习训练了一个反射检索器，将生成器的知识注入自反负样本中，确保检索到的图像能够填补模型的缺失知识。此外，该框架还为生成模型整合了细粒度视觉知识，有效解决了失真问题，并提升了细粒度对象生成的逼真度。RealRAG 不仅模块化适配所有先进文本到图像生成模型，还显著提升了它们的性能，例如在斯坦福汽车基准测试中，自回归模型的 FID 得分提升了 16.18%。

> Recent text-to-image generative models, e.g., Stable Diffusion V3 and Flux, have achieved notable progress. However, these models are strongly restricted to their limited knowledge, a.k.a., their own fixed parameters, that are trained with closed datasets. This leads to significant hallucinations or distortions when facing fine-grained and unseen novel real-world objects, e.g., the appearance of the Tesla Cybertruck. To this end, we present the first real-object-based retrieval-augmented generation framework (RealRAG), which augments fine-grained and unseen novel object generation by learning and retrieving real-world images to overcome the knowledge gaps of generative models. Specifically, to integrate missing memory for unseen novel object generation, we train a reflective retriever by self-reflective contrastive learning, which injects the generator's knowledge into the sef-reflective negatives, ensuring that the retrieved augmented images compensate for the model's missing knowledge. Furthermore, the real-object-based framework integrates fine-grained visual knowledge for the generative models, tackling the distortion problem and improving the realism for fine-grained object generation. Our Real-RAG is superior in its modular application to all types of state-of-the-art text-to-image generative models and also delivers remarkable performance boosts with all of them, such as a gain of 16.18% FID score with the auto-regressive model on the Stanford Car benchmark.

[Arxiv](https://arxiv.org/abs/2502.00848)