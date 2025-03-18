# ROMA：基于只读存储器的QLoRA设备端大语言模型加速器

发布时间：2025年03月17日

`LLM应用

理由：这篇论文探讨了如何在边缘设备上高效部署大型语言模型（LLMs），并提出了ROMA加速器，优化了存储和计算资源以提升性能。这属于将LLMs应用于实际设备端的具体实现和优化，因此归类为LLM应用。` `边缘计算` `芯片设计`

> ROMA: a Read-Only-Memory-based Accelerator for QLoRA-based On-Device LLM

# 摘要

> 大型语言模型（LLMs）的强大能力使其在边缘设备上的部署日益重要，这不仅提升了隐私保护，还实现了实时交互的优势。QLoRA 成为在设备端部署 LLMs 的标准方法，通过量化模型降低内存和计算成本，并借助低秩适应（LoRA）实现任务特定的灵活性。我们提出了一种名为 ROMA 的 QLoRA 加速器，采用混合存储架构，将量化基模型存储于 ROM，LoRA 权重和 KV 缓存则存储于 SRAM。我们的研究表明，量化基模型因其稳定性和收敛性，非常适合存储于 ROM。同时，LoRA 模块的灵活性使其能够适应新数据，而无需更新基模型。为了进一步优化 ROM 的面积成本，我们引入了创新的 B-ROM 设计，并将其与计算单元融合，形成高效利用芯片资源的融合单元。ROMA 可以将 4 位 3B 和 2 位 8B 的 LLaMA 模型完全存储在片上，生成速度突破 20,000 tokens/s，无需依赖外部存储。

> As large language models (LLMs) demonstrate powerful capabilities, deploying them on edge devices has become increasingly crucial, offering advantages in privacy and real-time interaction. QLoRA has emerged as the standard approach for on-device LLMs, leveraging quantized models to reduce memory and computational costs while utilizing LoRA for task-specific adaptability. In this work, we propose ROMA, a QLoRA accelerator with a hybrid storage architecture that uses ROM for quantized base models and SRAM for LoRA weights and KV cache. Our insight is that the quantized base model is stable and converged, making it well-suited for ROM storage. Meanwhile, LoRA modules offer the flexibility to adapt to new data without requiring updates to the base model. To further reduce the area cost of ROM, we introduce a novel B-ROM design and integrate it with the compute unit to form a fused cell for efficient use of chip resources. ROMA can effectively store both a 4-bit 3B and a 2-bit 8B LLaMA model entirely on-chip, achieving a notable generation speed exceeding 20,000 tokens/s without requiring external memory.

[Arxiv](https://arxiv.org/abs/2503.12988)