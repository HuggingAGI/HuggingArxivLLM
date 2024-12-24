# 个性化的大型视觉语言模型

发布时间：2024年12月23日

`LLM应用` `图像生成` `视觉语言模型`

> Personalized Large Vision-Language Models

# 摘要

> 个性化模型在图像生成领域备受瞩目，然而在大型视觉语言模型（LVLMs）方面却研究不足。有了个性化，LVLMs 会运用参考概念（比如“迈克和苏珊正在交谈。”）而非通用表述（比如“一个男孩和一个女孩正在交谈。”）来处理交互式对话，让对话更具定制性和参考友好性。此外，PLVM 能够在对话中持续添加新的概念，且不会产生额外成本，极大地增强了实用性。PLVM 提出了 Aligner，这是一个预训练的视觉编码器，用于将参考概念与被查询的图像对齐。在对话过程中，它提取具有相应概念的参考图像的特征，并在被查询的图像中进行识别，从而实现个性化。我们发现，在整个框架中，Aligner 的计算成本和参数数量微不足道。通过全面的定性和定量分析，我们展现了 PLVM 的有效性和优越性。

> The personalization model has gained significant attention in image generation yet remains underexplored for large vision-language models (LVLMs). Beyond generic ones, with personalization, LVLMs handle interactive dialogues using referential concepts (e.g., ``Mike and Susan are talking.'') instead of the generic form (e.g., ``a boy and a girl are talking.''), making the conversation more customizable and referentially friendly. In addition, PLVM is equipped to continuously add new concepts during a dialogue without incurring additional costs, which significantly enhances the practicality. PLVM proposes Aligner, a pre-trained visual encoder to align referential concepts with the queried images. During the dialogues, it extracts features of reference images with these corresponding concepts and recognizes them in the queried image, enabling personalization. We note that the computational cost and parameter count of the Aligner are negligible within the entire framework. With comprehensive qualitative and quantitative analyses, we reveal the effectiveness and superiority of PLVM.

[Arxiv](https://arxiv.org/abs/2412.17610)