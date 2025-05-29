# 少即是多：LLMs的高效多语言扩展新方案——分层专家混合

发布时间：2025年05月28日

`LLM理论

理由：这篇论文探讨了如何通过改进模型结构（如分层专家分配算法）来优化多语言大型语言模型的扩展，属于模型理论和结构改进的范畴。` `多语言模型` `机器翻译`

> Less, but Better: Efficient Multilingual Expansion for LLMs via Layer-wise Mixture-of-Experts

# 摘要

> 为现有大型语言模型（LLMs）持续扩展新语言，是构建功能强大的多语言LLMs的一种有前景但具挑战性的方法。最大的挑战在于，在持续学习新语言的同时保留旧语言的能力。近期研究通过专家混合（MoE）架构添加新专家来扩展新语言，并通过将相关标记路由到原模型主干（旧专家）来避免旧语言的灾难性遗忘。尽管直观，但这种扩展方式参数成本高且仍会影响旧语言性能。为了解决这些限制，我们分析了LLMs不同层的语言特征，并提出了一种分层专家分配算法（LayerMoE），以确定每层应添加的新专家数量。具体来说，我们发现不同层在语言表示相似性方面存在差异，然后利用这种相似性作为指标，为每层分配专家，即相似性越高，所需专家越少。此外，为了进一步缓解旧语言的遗忘问题，我们在相似性较高的层的路由网络前添加了一个分类器，以引导旧语言标记的路由。实验结果表明，与之前的最先进基线相比，我们在单次扩展设置中减少了60%的专家数量，在终身扩展设置中减少了33.3%的专家数量，证明了我们方法的有效性。

> Continually expanding new languages for existing large language models (LLMs) is a promising yet challenging approach to building powerful multilingual LLMs. The biggest challenge is to make the model continuously learn new languages while preserving the proficient ability of old languages. To achieve this, recent work utilizes the Mixture-of-Experts (MoE) architecture to expand new languages by adding new experts and avoid catastrophic forgetting of old languages by routing corresponding tokens to the original model backbone (old experts). Although intuitive, this kind of method is parameter-costly when expanding new languages and still inevitably impacts the performance of old languages. To address these limitations, we analyze the language characteristics of different layers in LLMs and propose a layer-wise expert allocation algorithm (LayerMoE) to determine the appropriate number of new experts for each layer. Specifically, we find different layers in LLMs exhibit different representation similarities between languages and then utilize the similarity as the indicator to allocate experts for each layer, i.e., the higher similarity, the fewer experts. Additionally, to further mitigate the forgetting of old languages, we add a classifier in front of the router network on the layers with higher similarity to guide the routing of old language tokens. Experimental results show that our method outperforms the previous state-of-the-art baseline with 60% fewer experts in the single-expansion setting and with 33.3% fewer experts in the lifelong-expansion setting, demonstrating the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2505.22582)