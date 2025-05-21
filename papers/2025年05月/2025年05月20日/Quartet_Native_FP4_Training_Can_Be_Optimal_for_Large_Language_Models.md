# # Quartet：原生 FP4 训练，大型语言模型的最佳选择

发布时间：2025年05月20日

`LLM理论

理由：这篇论文探讨了在低精度算术下训练大型语言模型的方法，特别是FP4运算，提出了一种新的训练方法Quartet，以提高计算效率和准确性。这属于LLM训练技术的理论研究，因此归类为LLM理论。` `计算机体系结构` `硬件优化`

> Quartet: Native FP4 Training Can Be Optimal for Large Language Models

# 摘要

> 大型语言模型（LLMs）的快速发展伴随着计算需求的空前增长，最先进的模型训练成本每隔几个月翻一番。在低精度算术中直接训练模型成为解决这一问题的关键，它不仅提升了计算吞吐量，还显著提高了能源效率。NVIDIA近期推出的Blackwell架构支持极低精度运算，特别是FP4变体，为效率提升带来了新希望。然而，当前用于FP4精度训练LLMs的算法面临着准确性大幅下降的问题，通常依赖于混合精度回退。本文系统地研究了硬件支持的FP4训练，并引入了Quartet，这是一种新方法，能够实现准确的端到端FP4训练，其中所有主要计算均以低精度执行。通过对Llama类型模型的广泛评估，我们揭示了一条新的低精度缩放定律，量化了不同位宽下的性能权衡，并识别出一种在准确性和计算之间达到“近似最优”的低精度训练技术，称为Quartet。我们使用针对NVIDIA Blackwell GPU优化的CUDA内核实现了Quartet，并展示了它在FP4精度下能够达到最先进的准确度，成功训练了百亿规模的模型。我们的方法证明，完全基于FP4的训练是标准精度和FP8训练的有力替代方案。我们的代码可在https://github.com/IST-DASLab/Quartet获取。

> The rapid advancement of large language models (LLMs) has been paralleled by unprecedented increases in computational demands, with training costs for state-of-the-art models doubling every few months. Training models directly in low-precision arithmetic offers a solution, by improving both computational throughput and energy efficiency. Specifically, NVIDIA's recent Blackwell architecture facilitates extremely low-precision operations, specifically FP4 variants, promising substantial efficiency gains. Yet, current algorithms for training LLMs in FP4 precision face significant accuracy degradation and often rely on mixed-precision fallbacks. In this paper, we systematically investigate hardware-supported FP4 training and introduce Quartet, a new approach enabling accurate, end-to-end FP4 training with all the major computations (in e.g. linear layers) being performed in low precision. Through extensive evaluations on Llama-type models, we reveal a new low-precision scaling law that quantifies performance trade-offs across varying bit-widths and allows us to identify a "near-optimal" low-precision training technique in terms of accuracy-vs-computation, called Quartet. We implement Quartet using optimized CUDA kernels tailored for NVIDIA Blackwell GPUs, and show that it can achieve state-of-the-art accuracy for FP4 precision, successfully training billion-scale models. Our method demonstrates that fully FP4-based training is a competitive alternative to standard-precision and FP8 training. Our code is available at https://github.com/IST-DASLab/Quartet.

[Arxiv](https://arxiv.org/abs/2505.14669)