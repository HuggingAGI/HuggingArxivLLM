# 统一基于块的PTQ与蒸馏QAT，实现面向2位指令微调LLMs的渐进式量化

发布时间：2025年06月10日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在资源受限设备上的部署挑战，特别是通过极低比特量化（如2-bit）来优化模型的性能。研究提出了统一渐进量化（UPQ）框架，结合了后训练量化（PTQ）和蒸馏量化感知训练（Distill-QAT），以实现从FP16到INT4再到INT2的渐进量化。该研究的目标是提高LLMs在资源受限环境中的部署效率和性能，属于LLM应用的范畴。` `边缘计算` `模型优化`

> Unifying Block-wise PTQ and Distillation-based QAT for Progressive Quantization toward 2-bit Instruction-Tuned LLMs

# 摘要

> 大型语言模型（LLMs）的快速扩展带来了在资源受限设备上部署的挑战，因此对2-bit等极低比特量化的兴趣日益增长。尽管2-bit模型在准确性和延迟方面优于4-bit模型，但这些成果仅限于预训练模型，尚未扩展到指令微调模型。为解决这一问题，我们提出了统一渐进量化（UPQ），这是一种从FP16到INT4再到INT2的渐进量化框架，结合了基于块的后训练量化（PTQ）与蒸馏量化感知训练（Distill-QAT）。UPQ首先将FP16指令微调模型量化为INT4，大幅减少后续INT2量化带来的误差。然后通过最小化广义Jensen-Shannon散度（JSD），使INT2模型生成的响应与原版FP16模型一致。我们首次证明，UPQ无需依赖专有后训练数据，即可将开源指令微调模型量化为INT2，并在MMLU和IFEval（两个最具代表性的基准测试）中达到最优性能。

> As the rapid scaling of large language models (LLMs) poses significant challenges for deployment on resource-constrained devices, there is growing interest in extremely low-bit quantization, such as 2-bit. Although prior works have shown that 2-bit large models are pareto-optimal over their 4-bit smaller counterparts in both accuracy and latency, these advancements have been limited to pre-trained LLMs and have not yet been extended to instruction-tuned models. To bridge this gap, we propose Unified Progressive Quantization (UPQ)$-$a novel progressive quantization framework (FP16$\rightarrow$INT4$\rightarrow$INT2) that unifies block-wise post-training quantization (PTQ) with distillation-based quantization-aware training (Distill-QAT) for INT2 instruction-tuned LLM quantization. UPQ first quantizes FP16 instruction-tuned models to INT4 using block-wise PTQ to significantly reduce the quantization error introduced by subsequent INT2 quantization. Next, UPQ applies Distill-QAT to enable INT2 instruction-tuned LLMs to generate responses consistent with their original FP16 counterparts by minimizing the generalized Jensen-Shannon divergence (JSD) between the two. To the best of our knowledge, we are the first to demonstrate that UPQ can quantize open-source instruction-tuned LLMs to INT2 without relying on proprietary post-training data, while achieving state-of-the-art performances on MMLU and IFEval$-$two of the most representative benchmarks for evaluating instruction-tuned LLMs.

[Arxiv](https://arxiv.org/abs/2506.09104)