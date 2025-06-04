# 显式困难负梯度放大：提升多模态嵌入学习的新方法

发布时间：2025年05月28日

`LLM理论` `多模态`

> Improve Multi-Modal Embedding Learning via Explicit Hard Negative Gradient Amplifying

# 摘要

> 近年来，多模态大语言模型（MLLMs）的快速发展使得最初的语言-图像对比预训练框架（CLIP）成功扩展到了MLLMs领域，为各类检索任务提供了更强大、更通用的多模态嵌入。尽管取得了这些进展，但核心对比学习范式从CLIP风格模型到MLLMs并未发生根本性改变。在这一框架下，有效挖掘硬负样本仍然是提升性能的关键因素。先前的研究工作提出了离线和在线两种策略用于硬负样本挖掘，以提高对比学习的效率。虽然这些方法改进了多模态嵌入的效果，但每个硬负样本对学习过程的具体贡献尚未得到深入研究。在本研究中，我们对info-NCE损失相对于查询、正样本和负样本的梯度进行了详细分析，阐明了硬负样本在更新模型参数中的作用。基于此分析，我们提出显式放大硬负样本相关的梯度，从而促使模型学习更具判别性的嵌入。我们的多模态嵌入模型基于LLaVA-OneVision-7B架构，并结合提出的显式梯度放大器进行训练，在MMEB基准测试中相较于采用相同MLLM主干的先前方法达到了最先进的性能。此外，当与我们自主研发的MLLM QQMM结合时，我们的方法在MMEB排行榜上位居榜首。代码和模型已发布在https://github.com/QQ-MM/QQMM-embed。

> With the rapid advancement of multi-modal large language models (MLLMs) in recent years, the foundational Contrastive Language-Image Pretraining (CLIP) framework has been successfully extended to MLLMs, enabling more powerful and universal multi-modal embeddings for a wide range of retrieval tasks. Despite these developments, the core contrastive learning paradigm remains largely unchanged from CLIP-style models to MLLMs. Within this framework, the effective mining of hard negative samples continues to be a critical factor for enhancing performance. Prior works have introduced both offline and online strategies for hard negative mining to improve the efficiency of contrastive learning. While these approaches have led to improved multi-modal embeddings, the specific contribution of each hard negative sample to the learning process has not been thoroughly investigated. In this work, we conduct a detailed analysis of the gradients of the info-NCE loss with respect to the query, positive, and negative samples, elucidating the role of hard negatives in updating model parameters. Building upon this analysis, we propose to explicitly amplify the gradients associated with hard negative samples, thereby encouraging the model to learn more discriminative embeddings. Our multi-modal embedding model, trained with the proposed Explicit Gradient Amplifier and based on the LLaVA-OneVision-7B architecture, achieves state-of-the-art performance on the MMEB benchmark compared to previous methods utilizing the same MLLM backbone. Furthermore, when integrated with our self-developed MLLM, QQMM, our approach attains the top rank on the MMEB leaderboard. Code and models are released on https://github.com/QQ-MM/QQMM-embed.

[Arxiv](https://arxiv.org/abs/2506.02020)