# 编码器-解码器 Gemma：通过自适应调整优化质量与效率的平衡

发布时间：2025年04月08日

`LLM理论`

> Encoder-Decoder Gemma: Improving the Quality-Efficiency Trade-Off via Adaptation

# 摘要

> 尽管仅解码器的大型语言模型 (LLMs) 已经取得了令人瞩目的成果，编码器-解码器模型凭借其推理效率和更丰富的编码器表示，在实际应用中仍然占据重要地位。本文提出了一种全新的研究方向：将预训练的仅解码器 LLMs 适配为编码器-解码器模型，旨在融合两种方法的优势，实现更优的质量-效率平衡。我们发现，这种适配不仅能够继承仅解码器 LLMs 的能力，还能显著降低从头预训练所需的计算成本。通过系统性地探索不同的预训练目标、参数初始化与优化技术，我们在 Gemma 2（2B 和 9B）以及一系列新预训练的 mT5 尺寸模型（最大 1.6B）上进行了大量实验，验证了适配方法的有效性。结果显示，在推理预算相同的情况下，编码器-解码器 LLMs 不仅能达到与仅解码器模型相当甚至更优的预训练性能，其微调性能更是远胜一筹。例如，经过指令调优后，Gemma 2B-2B 的性能比 Gemma 2B 高出约 7%。此外，编码器-解码器适配还支持灵活组合不同规模的模型，Gemma 9B-2B 相比 Gemma 2B-2B 的性能提升了超过 3%。值得注意的是，适配后的编码器表示在 SuperGLUE 上也表现更佳。我们计划发布相关检查点，以支持未来的研究工作。

> While decoder-only large language models (LLMs) have shown impressive results, encoder-decoder models are still widely adopted in real-world applications for their inference efficiency and richer encoder representation. In this paper, we study a novel problem: adapting pretrained decoder-only LLMs to encoder-decoder, with the goal of leveraging the strengths of both approaches to achieve a more favorable quality-efficiency trade-off. We argue that adaptation not only enables inheriting the capability of decoder-only LLMs but also reduces the demand for computation compared to pretraining from scratch. We rigorously explore different pretraining objectives and parameter initialization/optimization techniques. Through extensive experiments based on Gemma 2 (2B and 9B) and a suite of newly pretrained mT5-sized models (up to 1.6B), we demonstrate the effectiveness of adaptation and the advantage of encoder-decoder LLMs. Under similar inference budget, encoder-decoder LLMs achieve comparable (often better) pretraining performance but substantially better finetuning performance than their decoder-only counterpart. For example, Gemma 2B-2B outperforms Gemma 2B by $\sim$7\% after instruction tuning. Encoder-decoder adaptation also allows for flexible combination of different-sized models, where Gemma 9B-2B significantly surpasses Gemma 2B-2B by $>$3\%. The adapted encoder representation also yields better results on SuperGLUE. We will release our checkpoints to facilitate future research.

[Arxiv](https://arxiv.org/abs/2504.06225)