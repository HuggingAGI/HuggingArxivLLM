# # VQ-Logits：利用向量量化Logits压缩大型语言模型的输出瓶颈

发布时间：2025年05月15日

`LLM理论` `机器学习`

> VQ-Logits: Compressing the Output Bottleneck of Large Language Models via Vector Quantized Logits

# 摘要

> 大型语言模型（LLMs）虽然取得了显著的成功，但也面临着计算和内存方面的重大挑战，尤其是由于其庞大的输出词汇表。在推理过程中，最终的线性投影层通常占用了模型参数和计算成本的很大一部分，该层负责将隐藏状态映射到词汇量大小的对数几率。现有的自适应 softmax 或分层 softmax 方法虽然有效，但引入了结构复杂性。为了解决这些问题，我们在本文中提出了 VQ-Logits，一种利用向量量化（VQ）技术来大幅减少 LLM 输出层参数数量和计算负载的创新方法。VQ-Logits 通过使用一个小型共享代码本（K 个嵌入向量，K << V）替代了传统的 V * dmodel 输出嵌入矩阵。每个词汇表中的令牌都会被映射到这 K 个代码本向量中的一个。LLM 会首先在这个紧致的代码本上进行对数几率预测，然后通过学习或预设的映射关系，将这些对数几率高效地“分散”到完整的词汇空间中。我们在标准语言建模基准测试（如 WikiText-103 和 C4）上进行了大量实验，结果显示 VQ-Logits 可以在输出层实现高达 99% 的参数减少，并将对数几率计算速度提升 6 倍，同时与完整的 softmax 基线相比，困惑度仅增加 4%。此外，我们还对代码本大小、初始化策略和学习方法进行了详细的消融研究，进一步证明了我们方法的鲁棒性和有效性。

> Large Language Models (LLMs) have achieved remarkable success but face significant computational and memory challenges, particularly due to their extensive output vocabularies. The final linear projection layer, mapping hidden states to vocabulary-sized logits, often constitutes a substantial portion of the model's parameters and computational cost during inference. Existing methods like adaptive softmax or hierarchical softmax introduce structural complexities. In this paper, we propose VQ-Logits, a novel approach that leverages Vector Quantization (VQ) to drastically reduce the parameter count and computational load of the LLM output layer. VQ-Logits replaces the large V * dmodel output embedding matrix with a small, shared codebook of K embedding vectors (K << V ). Each token in the vocabulary is mapped to one of these K codebook vectors. The LLM predicts logits over this compact codebook, which are then efficiently "scattered" to the full vocabulary space using the learned or preassigned mapping. We demonstrate through extensive experiments on standard language modeling benchmarks (e.g., WikiText-103, C4) that VQ-Logits can achieve up to 99% parameter reduction in the output layer and 6x speedup in logit computation, with only a marginal 4% increase in perplexity compared to full softmax baselines. We further provide detailed ablation studies on codebook size, initialization, and learning strategies, showcasing the robustness and effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2505.10202)