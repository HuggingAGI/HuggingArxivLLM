# 基于SAEs的机制可解释性：探究大型语言模型中的宗教、暴力与地理

发布时间：2025年09月22日

`LLM应用` `基础理论`

> Mechanistic Interpretability with SAEs: Probing Religion, Violence, and Geography in Large Language Models

# 摘要

> 尽管针对大型语言模型（LLMs）偏见的研究越来越多，但多数研究聚焦于性别和种族，对宗教身份的关注却十分有限。本文探究了宗教在LLMs中的内部表征机制，以及其与暴力、地理概念的交叉关联。通过Neuronpedia API，我们借助机制可解释性和稀疏自编码器（SAEs），分析了五个模型的潜在特征激活情况。我们测量了宗教与暴力相关提示之间的重叠度，并探究了激活语境中的语义模式。研究发现，尽管五种宗教的内部凝聚力相当，但伊斯兰教更常与暴力语言相关的特征产生关联。相比之下，地理关联在很大程度上反映了现实世界的宗教人口分布，揭示了模型既嵌入事实分布，又融入文化刻板印象的特点。这些发现凸显了结构分析在审计中的价值——不仅审计模型输出，更审计那些塑造模型行为的内部表征。

> Despite growing research on bias in large language models (LLMs), most work has focused on gender and race, with little attention to religious identity. This paper explores how religion is internally represented in LLMs and how it intersects with concepts of violence and geography. Using mechanistic interpretability and Sparse Autoencoders (SAEs) via the Neuronpedia API, we analyze latent feature activations across five models. We measure overlap between religion- and violence-related prompts and probe semantic patterns in activation contexts. While all five religions show comparable internal cohesion, Islam is more frequently linked to features associated with violent language. In contrast, geographic associations largely reflect real-world religious demographics, revealing how models embed both factual distributions and cultural stereotypes. These findings highlight the value of structural analysis in auditing not just outputs but also internal representations that shape model behavior.

[Arxiv](https://arxiv.org/abs/2509.17665)