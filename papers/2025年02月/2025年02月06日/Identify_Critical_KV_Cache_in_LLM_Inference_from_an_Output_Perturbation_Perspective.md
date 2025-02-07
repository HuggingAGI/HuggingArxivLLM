# 从输出扰动视角识别LLM推理中的关键KV缓存

发布时间：2025年02月06日

`LLM理论

理由：这篇论文主要关注的是大型语言模型（LLM）的底层机制和理论问题，特别是Transformer架构中的自注意力机制和KV缓存问题。论文通过理论分析和提出新的算法来解决这些技术挑战，属于对LLM内部工作机制的深入研究和理论探讨，因此应归类为“LLM理论”。` `机器学习`

> Identify Critical KV Cache in LLM Inference from an Output Perturbation Perspective

# 摘要

> 大型语言模型在自然语言处理领域掀起了一场革命，但Transformer架构对自注意力机制的依赖，尤其是长序列推理中的大型键值（KV）缓存，带来了高存储和运行时成本的挑战。尽管近期通过修剪注意力权重较低的条目来压缩KV缓存的研究取得了一定进展，但这些方法仍缺乏理论支撑。本文通过分析注意力输出扰动，正式研究了如何识别关键KV缓存条目。研究发现，除了注意力权重，KV条目中的值状态和预训练参数矩阵同样至关重要。基于此，我们提出了一种扰动约束选择算法，通过优化最坏情况下的输出扰动来筛选关键条目。在Needle-in-a-Haystack测试和Longbench基准测试中，该算法显著提升了现有缓存淘汰方法的性能。实证分析进一步表明，在Llama模型中，该算法在超过92%的注意力头中实现了更低的输出扰动，显著优于现有方法。

> Large language models have revolutionized natural language processing but face significant challenges of high storage and runtime costs, due to the transformer architecture's reliance on self-attention, particularly the large Key-Value (KV) cache for long-sequence inference. Recent efforts to reduce KV cache size by pruning less critical entries based on attention weights remain empirical and lack formal grounding. This paper presents a formal study on identifying critical KV cache entries by analyzing attention output perturbation. Our analysis reveals that, beyond attention weights, the value states within KV entries and pretrained parameter matrices are also crucial. Based on this, we propose a perturbation-constrained selection algorithm that optimizes the worst-case output perturbation to identify critical entries. Evaluations on the Needle-in-a-Haystack test and Longbench benchmark show our algorithm enhances state-of-the-art cache eviction methods. Further empirical analysis confirms that our algorithm achieves lower output perturbations in over 92% attention heads in Llama model, thereby providing a significant improvement over existing methods.

[Arxiv](https://arxiv.org/abs/2502.03805)