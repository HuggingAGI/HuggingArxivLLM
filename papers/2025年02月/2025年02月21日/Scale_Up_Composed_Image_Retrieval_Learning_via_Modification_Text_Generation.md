# 扩展组合图像检索学习：基于修改文本生成的方法

发布时间：2025年02月21日

`LLM应用` `计算机视觉` `生成对抗网络`

> Scale Up Composed Image Retrieval Learning via Modification Text Generation

# 摘要

> 合成图像检索（CIR）旨在通过结合参考图像和修改文本作为查询来搜索感兴趣的目标图像。尽管最近取得了进展，但该任务仍然面临挑战，主要原因是训练数据有限以及繁琐的三元组标注过程。为了解决这一问题，本文提出通过合成训练三元组来扩充合成图像检索问题的训练资源。

具体而言，我们首先利用大规模多模态模型训练一个修改文本生成器，并在预训练和微调阶段逐步提升CIR的学习效果。在预训练阶段，我们利用训练好的生成器直接创建基于图像对的修改文本导向合成三元组（MTST）。在微调阶段，我们首先合成反向修改文本以连接目标图像与参考图像，随后设计了一种两跳对齐策略来逐步缩小多模态对与目标图像之间的语义差距。我们首先在循环模式下利用原始三元组及其反向版本学习一个隐式原型，然后将隐式原型特征与修改文本相结合，以实现与目标图像的准确对齐。

大量实验验证了生成三元组的有效性，并证实了我们提出的方法在CIRR和FashionIQ基准测试中均达到了具有竞争力的召回率。

> Composed Image Retrieval (CIR) aims to search an image of interest using a combination of a reference image and modification text as the query. Despite recent advancements, this task remains challenging due to limited training data and laborious triplet annotation processes. To address this issue, this paper proposes to synthesize the training triplets to augment the training resource for the CIR problem. Specifically, we commence by training a modification text generator exploiting large-scale multimodal models and scale up the CIR learning throughout both the pretraining and fine-tuning stages. During pretraining, we leverage the trained generator to directly create Modification Text-oriented Synthetic Triplets(MTST) conditioned on pairs of images. For fine-tuning, we first synthesize reverse modification text to connect the target image back to the reference image. Subsequently, we devise a two-hop alignment strategy to incrementally close the semantic gap between the multimodal pair and the target image. We initially learn an implicit prototype utilizing both the original triplet and its reversed version in a cycle manner, followed by combining the implicit prototype feature with the modification text to facilitate accurate alignment with the target image. Extensive experiments validate the efficacy of the generated triplets and confirm that our proposed methodology attains competitive recall on both the CIRR and FashionIQ benchmarks.

[Arxiv](https://arxiv.org/abs/2504.05316)