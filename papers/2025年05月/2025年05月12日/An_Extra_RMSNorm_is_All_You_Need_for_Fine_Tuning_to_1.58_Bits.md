# 仅需一个额外的RMS归一化，就能实现1.58位的微调效果。

发布时间：2025年05月12日

`LLM理论` `模型优化`

> An Extra RMSNorm is All You Need for Fine Tuning to 1.58 Bits

# 摘要

> 大型语言模型（LLMs）彻底改变了自然语言处理领域，但其规模使实际部署成本高昂。后训练量化虽然能降低内存和计算需求，但通常会损害模型的准确性。而量化感知训练虽然可以恢复性能，但需要额外的训练成本。将量化推进到三进制（2位）可以节省更多资源，但其稳定性众所周知较差。基于最近的工作表明，无偏见、RMS归一化的Transformer结合直通估计可以达到1.58位的精度，我们证明，只需在每个线性投影前插入RMS归一化，并应用渐进的、分层的量化计划，即可稳定地将全精度检查点微调为三进制LLMs。我们的方法在标准语言模型基准上与更复杂的知识蒸馏管道相匹配甚至超越，而没有增加模型复杂度。这些结果表明，仅通过仔细的归一化就可以大大缩小三进制和全精度LLMs之间的准确度差距，使超低位推理成为可能。

> Large language models (LLMs) have transformed natural-language processing, yet their scale makes real-world deployment costly. Post-training quantization reduces memory and computation but often degrades accuracy, while quantization-aware training can recover performance at the cost of extra training. Pushing quantization to the ternary (2-bit) regime yields even larger savings but is notoriously unstable. Building on recent work showing that a bias-free, RMS-normalized Transformer with straight-through estimation can reach 1.58-bit precision, we demonstrate that simply inserting RMS normalization before every linear projection and applying a gradual, layer-wise quantization schedule stably fine-tunes full-precision checkpoints into ternary LLMs. Our approach matches or surpasses more elaborate knowledge-distillation pipelines on standard language-modeling benchmarks without adding model complexity. These results indicate that careful normalization alone can close much of the accuracy gap between ternary and full-precision LLMs, making ultra-low-bit inference practical.

[Arxiv](https://arxiv.org/abs/2505.08823)