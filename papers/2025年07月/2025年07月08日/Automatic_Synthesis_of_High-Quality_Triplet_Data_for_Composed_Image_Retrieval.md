# # 自动合成高质量三元组数据，助力组合图像检索

发布时间：2025年07月08日

`LLM应用

论文摘要：组合图像检索（CIR）是一项具有挑战性的视觉语言任务，旨在通过多模态（图像+文本）查询检索目标图像。尽管现有方法已取得显著进展，但其对昂贵的手动标注三元组的依赖限制了扩展性和零样本能力。为解决这一问题，我们提出了一种自动三元组生成的可扩展管道，并创建了一个名为“基于高质量合成三元组的组合图像检索”（CIRHS）的完全合成数据集。该管道利用大型语言模型生成多样化提示，控制文本到图像的生成模型，生成具有相同元素的图像对，经筛选和重组后形成CIRHS数据集。此外，我们还提出了“混合上下文对齐”（CoAlign），一种新型CIR框架，可在更广泛的上下文中实现全局对齐和局部推理，帮助模型学习更稳健和信息丰富的表示。借助合成的CIRHS数据集，CoAlign在三个常用基准测试中展现出卓越的零样本性能，首次证明了在完全合成数据集上训练CIR模型的可行性。同时，在监督训练下，我们的方法超越了所有现有监督式CIR方法，验证了所提出的检索框架的有效性。代码和CIRHS数据集即将发布。

LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLM）生成多样化提示，并控制文本到图像的生成模型，从而提升组合图像检索（CIR）的效果。论文中提到了使用LLM在数据生成和模型训练中的应用，属于LLM的具体应用领域，因此归类为LLM应用。` `视觉检索` `多模态处理`

> Automatic Synthesis of High-Quality Triplet Data for Composed Image Retrieval

# 摘要

> 组合图像检索（CIR）是一项具有挑战性的视觉语言任务，旨在通过多模态（图像+文本）查询检索目标图像。尽管现有方法已取得显著进展，但其对昂贵的手动标注三元组的依赖限制了扩展性和零样本能力。为解决这一问题，我们提出了一种自动三元组生成的可扩展管道，并创建了一个名为“基于高质量合成三元组的组合图像检索”（CIRHS）的完全合成数据集。该管道利用大型语言模型生成多样化提示，控制文本到图像的生成模型，生成具有相同元素的图像对，经筛选和重组后形成CIRHS数据集。此外，我们还提出了“混合上下文对齐”（CoAlign），一种新型CIR框架，可在更广泛的上下文中实现全局对齐和局部推理，帮助模型学习更稳健和信息丰富的表示。借助合成的CIRHS数据集，CoAlign在三个常用基准测试中展现出卓越的零样本性能，首次证明了在完全合成数据集上训练CIR模型的可行性。同时，在监督训练下，我们的方法超越了所有现有监督式CIR方法，验证了所提出的检索框架的有效性。代码和CIRHS数据集即将发布。

> As a challenging vision-language (VL) task, Composed Image Retrieval (CIR) aims to retrieve target images using multimodal (image+text) queries. Although many existing CIR methods have attained promising performance, their reliance on costly, manually labeled triplets hinders scalability and zero-shot capability. To address this issue, we propose a scalable pipeline for automatic triplet generation, along with a fully synthetic dataset named Composed Image Retrieval on High-quality Synthetic Triplets (CIRHS). Our pipeline leverages a large language model (LLM) to generate diverse prompts, controlling a text-to-image generative model to produce image pairs with identical elements in each pair, which are then filtered and reorganized to form the CIRHS dataset. In addition, we introduce Hybrid Contextual Alignment (CoAlign), a novel CIR framework, which can accomplish global alignment and local reasoning within a broader context, enabling the model to learn more robust and informative representations. By utilizing the synthetic CIRHS dataset, CoAlign achieves outstanding zero-shot performance on three commonly used benchmarks, demonstrating for the first time the feasibility of training CIR models on a fully synthetic dataset. Furthermore, under supervised training, our method outperforms all the state-of-the-art supervised CIR approaches, validating the effectiveness of our proposed retrieval framework. The code and the CIRHS dataset will be released soon.

[Arxiv](https://arxiv.org/abs/2507.05970)