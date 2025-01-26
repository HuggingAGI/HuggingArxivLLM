# Sigma: 通过差分缩放查询、键和值，打造高效语言模型

发布时间：2025年01月23日

`LLM理论

理由：这篇论文主要介绍了一种新型的大型语言模型Sigma，并详细描述了其创新的DiffQKV注意力机制。论文通过理论和实证分析，探讨了该机制在推理效率和模型表示能力方面的改进。这些内容主要涉及大型语言模型的理论和架构创新，因此将其分类为LLM理论。` `系统领域` `语言模型`

> Sigma: Differential Rescaling of Query, Key and Value for Efficient Language Models

# 摘要

> 我们推出了Sigma，一个专为系统领域打造的高效大型语言模型，采用创新的DiffQKV注意力机制，并在精心收集的系统领域数据上进行了预训练。DiffQKV通过差异化优化注意力机制中的Q、K、V组件，显著提升了推理效率。具体而言，我们（1）通过大量实验发现模型对K和V压缩的敏感性不同，从而开发了差异化压缩的KV，（2）提出增强Q以扩展Q头维度，在不显著影响推理速度的情况下提升模型表示能力。理论和实证分析表明，DiffQKV在长上下文场景中比传统GQA提升了高达33.36%的推理速度。我们在6T tokens上预训练了Sigma，包括19.5B系统领域数据和1T tokens的合成数据。在一般领域，Sigma性能媲美其他顶尖模型；在系统领域，我们推出了首个全面基准AIMicius，Sigma在所有任务中表现卓越，显著超越GPT-4，绝对改进高达52.5%。

> We introduce Sigma, an efficient large language model specialized for the system domain, empowered by a novel architecture including DiffQKV attention, and pre-trained on our meticulously collected system domain data. DiffQKV attention significantly enhances the inference efficiency of Sigma by optimizing the Query (Q), Key (K), and Value (V) components in the attention mechanism differentially, based on their varying impacts on the model performance and efficiency indicators. Specifically, we (1) conduct extensive experiments that demonstrate the model's varying sensitivity to the compression of K and V components, leading to the development of differentially compressed KV, and (2) propose augmented Q to expand the Q head dimension, which enhances the model's representation capacity with minimal impacts on the inference speed. Rigorous theoretical and empirical analyses reveal that DiffQKV attention significantly enhances efficiency, achieving up to a 33.36% improvement in inference speed over the conventional grouped-query attention (GQA) in long-context scenarios. We pre-train Sigma on 6T tokens from various sources, including 19.5B system domain data that we carefully collect and 1T tokens of synthesized and rewritten data. In general domains, Sigma achieves comparable performance to other state-of-arts models. In the system domain, we introduce the first comprehensive benchmark AIMicius, where Sigma demonstrates remarkable performance across all tasks, significantly outperforming GPT-4 with an absolute improvement up to 52.5%.

[Arxiv](https://arxiv.org/abs/2501.13629)