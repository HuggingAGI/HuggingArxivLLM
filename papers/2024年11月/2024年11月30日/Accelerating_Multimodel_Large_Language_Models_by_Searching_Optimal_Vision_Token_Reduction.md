# 通过搜索最优的视觉令牌精简方案来加速多模型大型语言模型

发布时间：2024年11月30日

`LLM应用` `计算机视觉` `人工智能`

> Accelerating Multimodel Large Language Models by Searching Optimal Vision Token Reduction

# 摘要

> 当下流行的多模态大型语言模型（MLLMs）会把输入图像编码成视觉标记，再输入语言骨干中，这跟大型语言模型（LLMs）处理文本标记的方式相似。但随着图像分辨率的提升，视觉标记的数量会呈二次方增长，带来巨大的计算成本。在本文里，我们从两个方面来考虑提升 MLLM 的效率：（I）在不影响性能的前提下降低计算成本；（II）在给定预算的情况下提高性能。我们首先有个重要发现，除了第一层，每层中按注意力分数排序的每个视觉标记的排名都很相似。基于此，我们假定关键的顶部视觉标记数量不会随层数增加。所以，针对场景 I，我们提出了一种贪婪搜索算法（G-Search），从浅到深找出每层要保留的最少视觉标记数量。有意思的是，G-Search 能够依据我们的假设得出最优的削减策略。对于场景 II，基于 G-Search 的削减策略，我们设计了一个参数化的 S 型函数（P-Sigmoid）来引导 MLLM 每层的削减，其参数通过贝叶斯优化来优化。大量实验表明，我们的方法能显著加快那些热门的 MLLMs，比如 LLaVA 和 InternVL2 模型，速度提升超过 2 倍且性能不减。在预算有限时，我们的方法也远超其他标记削减方法，在效率和效果之间达成了更优的平衡。

> Prevailing Multimodal Large Language Models (MLLMs) encode the input image(s) as vision tokens and feed them into the language backbone, similar to how Large Language Models (LLMs) process the text tokens. However, the number of vision tokens increases quadratically as the image resolutions, leading to huge computational costs. In this paper, we consider improving MLLM's efficiency from two scenarios, (I) Reducing computational cost without degrading the performance. (II) Improving the performance with given budgets. We start with our main finding that the ranking of each vision token sorted by attention scores is similar in each layer except the first layer. Based on it, we assume that the number of essential top vision tokens does not increase along layers. Accordingly, for Scenario I, we propose a greedy search algorithm (G-Search) to find the least number of vision tokens to keep at each layer from the shallow to the deep. Interestingly, G-Search is able to reach the optimal reduction strategy based on our assumption. For Scenario II, based on the reduction strategy from G-Search, we design a parametric sigmoid function (P-Sigmoid) to guide the reduction at each layer of the MLLM, whose parameters are optimized by Bayesian Optimization. Extensive experiments demonstrate that our approach can significantly accelerate those popular MLLMs, e.g. LLaVA, and InternVL2 models, by more than $2 \times$ without performance drops. Our approach also far outperforms other token reduction methods when budgets are limited, achieving a better trade-off between efficiency and effectiveness.

[Arxiv](https://arxiv.org/abs/2412.00556)