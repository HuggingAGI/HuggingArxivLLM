# Adapt-Pruner: 自适应结构剪枝，助力高效小型语言模型训练

发布时间：2025年02月05日

`LLM理论

理由：这篇论文主要探讨了小型语言模型（SLMs）的优化方法，特别是通过结构化剪枝和模型训练的结合来提升模型性能。虽然涉及到了大型语言模型（LLMs）的剪枝和性能恢复，但核心内容集中在模型的理论优化和训练方法上，而不是具体的应用场景或代理（Agent）相关的技术。因此，将其归类为“LLM理论”更为合适。` `边缘计算` `模型压缩`

> Adapt-Pruner: Adaptive Structural Pruning for Efficient Small Language Model Training

# 摘要

> # 摘要
小型语言模型（SLMs）因其在边缘设备上的广泛应用而备受关注。传统方法要么从头预训练模型，计算成本高昂；要么压缩现有大型语言模型（LLMs），但性能往往不如预训练。本文研究了结合结构化剪枝和模型训练的加速方法。我们发现：1）分层自适应剪枝（Adapt-Pruner）在LLMs中效果显著，优于现有剪枝技术；2）自适应剪枝结合进一步训练，可媲美从头预训练的模型；3）增量剪枝通过训练中逐步移除少量神经元（$\sim$5%），带来显著性能提升。实验表明，Adapt-Pruner在LLaMA-3.1-8B上的常识基准测试中，准确率平均比LLM-Pruner、FLAP和SliceGPT高出1%-7%。此外，Adapt-Pruner通过剪枝将MobileLLM-125M在MMLU基准测试中的性能恢复到600M，且仅需200$	imes$更少的token，并发现了一个新的1B模型，其在多个基准测试中超越了LLaMA-3.2-1B。

> Small language models (SLMs) have attracted considerable attention from both academia and industry due to their broad range of applications in edge devices. To obtain SLMs with strong performance, conventional approaches either pre-train the models from scratch, which incurs substantial computational costs, or compress/prune existing large language models (LLMs), which results in performance drops and falls short in comparison to pre-training. In this paper, we investigate the family of acceleration methods that involve both structured pruning and model training. We found 1) layer-wise adaptive pruning (Adapt-Pruner) is extremely effective in LLMs and yields significant improvements over existing pruning techniques, 2) adaptive pruning equipped with further training leads to models comparable to those pre-training from scratch, 3) incremental pruning brings non-trivial performance gain by interleaving pruning with training and only removing a small portion of neurons ($\sim$5%) at a time. Experimental results on LLaMA-3.1-8B demonstrate that Adapt-Pruner outperforms conventional pruning methods, such as LLM-Pruner, FLAP, and SliceGPT, by an average of 1%-7% in accuracy on commonsense benchmarks. Additionally, Adapt-Pruner restores the performance of MobileLLM-125M to 600M on the MMLU benchmark with 200$\times$ fewer tokens via pruning from its larger counterparts, and discovers a new 1B model that surpasses LLaMA-3.2-1B in multiple benchmarks.

[Arxiv](https://arxiv.org/abs/2502.03460)