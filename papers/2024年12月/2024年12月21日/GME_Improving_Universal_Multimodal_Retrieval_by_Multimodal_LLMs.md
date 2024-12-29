# GME：借助多模态 LLM 提升通用多模态检索能力

发布时间：2024年12月21日

`LLM应用` `多模态检索` `数据合成`

> GME: Improving Universal Multimodal Retrieval by Multimodal LLMs

# 摘要

> 通用多模态检索（UMR）致力于借助统一模型达成多种模态的搜索，查询和候选内容可以是纯文本、图像或者二者的结合。此前的工作尝试运用多模态大型语言模型（MLLMs）仅依靠文本数据来实现 UMR。然而，我们的初步实验显示，更丰富多样的多模态训练数据能够进一步挖掘 MLLMs 的潜力。虽然有效，但现有的多模态训练数据在模态上严重失衡，这促使我们开发训练数据合成管道，并构建大规模、高质量的融合模态训练数据集。基于合成训练数据，我们开发了通用多模态嵌入器（GME），这是一种基于 MLLM 的密集检索器，专为 UMR 打造。此外，我们构建了全面的 UMR 基准（UMRB）来评估我们方法的成效。实验结果表明，我们的方法在现有的 UMR 方法中达到了领先水平。最后，我们深入分析了模型缩放、训练策略，并对模型和合成数据进行了消融研究。

> Universal Multimodal Retrieval (UMR) aims to enable search across various modalities using a unified model, where queries and candidates can consist of pure text, images, or a combination of both. Previous work has attempted to adopt multimodal large language models (MLLMs) to realize UMR using only text data. However, our preliminary experiments demonstrate that more diverse multimodal training data can further unlock the potential of MLLMs. Despite its effectiveness, the existing multimodal training data is highly imbalanced in terms of modality, which motivates us to develop a training data synthesis pipeline and construct a large-scale, high-quality fused-modal training dataset. Based on the synthetic training data, we develop the General Multimodal Embedder (GME), an MLLM-based dense retriever designed for UMR. Furthermore, we construct a comprehensive UMR Benchmark (UMRB) to evaluate the effectiveness of our approach. Experimental results show that our method achieves state-of-the-art performance among existing UMR methods. Last, we provide in-depth analyses of model scaling, training strategies, and perform ablation studies on both the model and synthetic data.

[Arxiv](https://arxiv.org/abs/2412.16855)