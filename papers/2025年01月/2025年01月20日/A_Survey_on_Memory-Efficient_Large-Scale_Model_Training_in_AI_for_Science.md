# # 人工智能科学中内存高效的大规模模型训练综述

发布时间：2025年01月20日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）在生物学、医学、化学和气象学等科学领域的应用，并探讨了如何通过内存高效训练技术来优化这些模型的使用。虽然论文也涉及了一些技术细节（如transformer架构和内存优化方法），但其核心关注点仍然是LLMs在科研中的应用，因此应归类为“LLM应用”。`

> A Survey on Memory-Efficient Large-Scale Model Training in AI for Science

# 摘要

> 传统科研方法成本高、效率低，而深度学习和大型语言模型（LLMs）的崛起带来了创新解决方案。本文综述了LLMs在生物学、医学、化学和气象学等领域的应用，凸显了其在科研中的推动作用。然而，模型规模的持续膨胀带来了巨大的内存需求，限制了LLMs在科学领域的进一步发展。为此，我们探讨了基于transformer架构的LLMs内存高效训练技术，如分布式训练、混合精度训练和梯度检查点。以AlphaFold 2为例，我们展示了定制内存优化方法如何在保持预测精度的同时降低存储需求。此外，我们还讨论了内存优化在实际应用中的挑战及未来方向，旨在为科研人员和工程师提供有益参考。

> Scientific research faces high costs and inefficiencies with traditional methods, but the rise of deep learning and large language models (LLMs) offers innovative solutions. This survey reviews LLM applications across scientific fields such as biology, medicine, chemistry, and meteorology, underscoring their role in advancing research. However, the continuous expansion of model size has led to significant memory demands, hindering further development and application of LLMs for science. To address this, we review memory-efficient training techniques for LLMs based on the transformer architecture, including distributed training, mixed precision training, and gradient checkpointing. Using AlphaFold 2 as an example, we demonstrate how tailored memory optimization methods can reduce storage needs while preserving prediction accuracy. We also discuss the challenges of memory optimization in practice and potential future directions, hoping to provide valuable insights for researchers and engineers.

[Arxiv](https://arxiv.org/abs/2501.11847)