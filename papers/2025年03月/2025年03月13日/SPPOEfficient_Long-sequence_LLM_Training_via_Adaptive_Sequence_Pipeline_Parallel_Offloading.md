# # SPPO：高效长序列LLM训练的自适应流水线并行卸载方法

发布时间：2025年03月13日

`LLM应用

论文摘要主要讨论了大型语言模型（LLMs）在处理长序列输入时的训练挑战，并提出了一种新的训练框架SPPO，旨在优化内存和计算资源的使用效率。该研究专注于提高LLM的训练效率，属于应用层面的优化，因此归类为LLM应用。` `人工智能`

> SPPO:Efficient Long-sequence LLM Training via Adaptive Sequence Pipeline Parallel Offloading

# 摘要

> 近年来，大型语言模型（LLMs）展现了非凡的能力，推动了实际应用的发展。然而，随着输入序列长度的增加，训练LLMs对GPU内存和计算资源提出了巨大挑战。现有解决方案存在两大关键限制：(1) 内存缩减技术如激活重计算和CPU卸载会损害训练效率；(2) 分布式并行策略需要大量GPU资源，限制了输入序列长度的扩展性。
为了解决这些问题，我们提出了自适应序列流水线并行卸载（SPPO），这是一种新型的LLM训练框架，旨在优化长序列训练中的内存和计算资源效率。SPPO通过自适应卸载机制、感知序列的卸载策略和两级激活管理，降低了GPU内存消耗，同时保持了训练效率。此外，SPPO还开发了一种自适应流水线调度方法，结合启发式求解器和多路序列划分，提高了计算资源效率。实验结果表明，与Megatron-LM和DeepSpeed相比，SPPO实现了最高3.38倍的吞吐量提升，成功在仅128块A100 GPU上实现了对70亿参数LLM进行长达400万token序列的高效训练。

> In recent years, Large Language Models (LLMs) have exhibited remarkable capabilities, driving advancements in real-world applications. However, training LLMs on increasingly long input sequences imposes significant challenges due to high GPU memory and computational demands. Existing solutions face two key limitations: (1) memory reduction techniques, such as activation recomputation and CPU offloading, compromise training efficiency; (2) distributed parallelism strategies require excessive GPU resources, limiting the scalability of input sequence length.
  To address these gaps, we propose Adaptive Sequence Pipeline Parallel Offloading (SPPO), a novel LLM training framework that optimizes memory and computational resource efficiency for long-sequence training. SPPO introduces adaptive offloading, leveraging sequence-aware offloading, and two-level activation management to reduce GPU memory consumption without degrading the training efficiency. Additionally, SPPO develops an adaptive pipeline scheduling approach with a heuristic solver and multiplexed sequence partitioning to improve computational resource efficiency. Experimental results demonstrate that SPPO achieves up to 3.38x throughput improvement over Megatron-LM and DeepSpeed, realizing efficient training of a 7B LLM with sequence lengths of up to 4M tokens on only 128 A100 GPUs.

[Arxiv](https://arxiv.org/abs/2503.10377)