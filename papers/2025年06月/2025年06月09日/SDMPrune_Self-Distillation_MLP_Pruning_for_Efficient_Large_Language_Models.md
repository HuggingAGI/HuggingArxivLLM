# SDMPrune：通过自蒸馏MLP剪枝打造高效大型语言模型

发布时间：2025年06月09日

`LLM应用` `模型压缩` `人工智能`

> SDMPrune: Self-Distillation MLP Pruning for Efficient Large Language Models

# 摘要

> 尽管大型语言模型（LLMs）表现强劲，但其高昂的部署成本却令人望而却步。针对 LLM 的压缩问题，基于梯度的剪枝方法展现出巨大潜力。然而，现有方法在计算梯度时仅关注 one-hot 标签，忽略了对其他单词的潜在预测，导致丢失了原模型生成能力的关键信息。为了解决这一问题，我们创新性地在剪枝阶段引入自蒸馏损失，而非传统的训练后优化，从而充分挖掘原模型的预测能力，获得更精准的剪枝梯度信息。进一步研究发现，与注意力模块相比，LLM 的预测结果对多层感知机（MLP）模块的敏感度较低，而这些模块占据了超过 $5 	imes$ 的参数量（以 LLaMA3.2-1.2B 为例）。基于此发现，我们将剪枝重点放在 MLP 模块上，从而在不明显影响性能的前提下实现 LLM 的显著压缩。在广泛的零样本基准测试中，实验结果表明，我们的方法不仅显著优于现有的剪枝方法，更在 1B 参数规模的开源 LLM 中展现出极具竞争力的性能。源代码和训练权重已开源，详情请访问 https://github.com/visresearch/SDMPrune。

> In spite of strong performance achieved by LLMs, the costs of their deployment are unaffordable. For the compression of LLMs, gradient-based pruning methods present promising effectiveness. However, in these methods, the gradient computation with one-hot labels ignore the potential predictions on other words, thus missing key information for generative capability of the original model. To address this issue, we introduce a self-distillation loss during the pruning phase (rather than post-training) to fully exploit the predictions of the original model, thereby obtaining more accurate gradient information for pruning. Moreover, we find that, compared to attention modules, the predictions of LLM are less sensitive to multilayer perceptron (MLP) modules, which take up more than $5 \times$ parameters (LLaMA3.2-1.2B). To this end, we focus on the pruning of MLP modules, to significantly compress LLM without obvious performance degradation. Experimental results on extensive zero-shot benchmarks demonstrate that our method significantly outperforms existing pruning methods. Furthermore, our method achieves very competitive performance among 1B-scale open source LLMs. The source code and trained weights are available at https://github.com/visresearch/SDMPrune.

[Arxiv](https://arxiv.org/abs/2506.11120)