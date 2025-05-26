# 发现文本与图像中最具语义信息的深度表达方法

发布时间：2025年05月21日

`LLM理论` `计算机视觉`

> An approach to identify the most semantically informative deep representations of text and images

# 摘要

> 深度神经网络在处理语义相关数据时，会形成相似的数据表示方式，即使这些数据来自不同领域，比如图像与其描述，或是同一篇文本在不同语言中的表达。我们提出了一种通过测量语义相关数据表示的相对信息含量，并探究这些信息如何被编码到大型语言模型（LLMs）和视觉变压器模型的多令牌中的方法，以定量研究这一现象。首先研究LLMs处理翻译句子对的方式，我们发现内部存在包含最可跨语言迁移信息的“语义”层。我们还发现，在这些层中，较大的LLM（如DeepSeek-V3）提取了比小型模型（如Llama3.1-8B）显著更多的通用信息。语义信息分布于多个令牌中，其特征是令牌间存在长距离相关性，并具有因果左到右（即过去-未来）的不对称性。我们还在视觉变压器模型中识别出编码语义信息的层。我们发现，LLMs语义层中的标题表示能够预测对应图像的视觉表示。我们观察到图像和文本表示之间存在显著且与模型相关的语义信息不对称性。

> Deep neural networks are known to develop similar representations for semantically related data, even when they belong to different domains, such as an image and its description, or the same text in different languages. We present a method for quantitatively investigating this phenomenon by measuring the relative information content of the representations of semantically related data and probing how it is encoded into multiple tokens of large language models (LLMs) and vision transformers. Looking first at how LLMs process pairs of translated sentences, we identify inner ``semantic'' layers containing the most language-transferable information. We find moreover that, on these layers, a larger LLM (DeepSeek-V3) extracts significantly more general information than a smaller one (Llama3.1-8B). Semantic information is spread across many tokens and it is characterized by long-distance correlations between tokens and by a causal left-to-right (i.e., past-future) asymmetry. We also identify layers encoding semantic information within visual transformers. We show that caption representations in the semantic layers of LLMs predict visual representations of the corresponding images. We observe significant and model-dependent information asymmetries between image and text representations.

[Arxiv](https://arxiv.org/abs/2505.17101)