# 用于高效 LLM 训练的梯度权重归一化低秩投影

发布时间：2024年12月27日

`LLM应用` `人工智能`

> Gradient Weight-normalized Low-rank Projection for Efficient LLM Training

# 摘要

> 大型语言模型（LLMs）在各类任务中表现出众，然而，对计算资源日益增长的需求构成了重大挑战，尤其在下游任务广泛运用全微调时。为应对此状况，参数高效微调（PEFT）方法应运而生，但其往往逊于全微调，且在内存效率方面存在难题。在本研究中，我们推出了梯度权重归一化低秩投影（GradNormLoRP）这一创新方法，在维持与全微调相近性能的同时，提升了参数和内存效率。GradNormLoRP 对权重矩阵进行归一化，以优化梯度条件，利于在优化过程中更好地收敛。此外，它对权重和梯度矩阵采用低秩近似，大幅降低了训练期间的内存占用。大量实验表明，我们的 8 位 GradNormLoRP 能将优化器的内存使用量减少多达 89.5%，并能在消费级 GPU（如 NVIDIA RTX 4090）上对大型 LLMs（如 LLaMA 7B）进行预训练，且无需额外的推理成本。而且，GradNormLoRP 在微调任务中的表现优于现有的低秩方法。比如，在以 8 的秩对所有 GLUE 任务微调 RoBERTa 模型时，GradNormLoRP 的平均分数达 80.65，超过了 LoRA 的 79.23 分。这些成果凸显了 GradNormLoRP 作为高效 LLM 预训练和微调的颇具前景的替代方案。源代码和附录：https://github.com/Jhhuangkay/Gradient-Weight-normalized-Low-rank-Projection-for-Efficient-LLM-Training

> Large Language Models (LLMs) have shown remarkable performance across various tasks, but the escalating demands on computational resources pose significant challenges, particularly in the extensive utilization of full fine-tuning for downstream tasks. To address this, parameter-efficient fine-tuning (PEFT) methods have been developed, but they often underperform compared to full fine-tuning and struggle with memory efficiency. In this work, we introduce Gradient Weight-Normalized Low-Rank Projection (GradNormLoRP), a novel approach that enhances both parameter and memory efficiency while maintaining comparable performance to full fine-tuning. GradNormLoRP normalizes the weight matrix to improve gradient conditioning, facilitating better convergence during optimization. Additionally, it applies low-rank approximations to the weight and gradient matrices, significantly reducing memory usage during training. Extensive experiments demonstrate that our 8-bit GradNormLoRP reduces optimizer memory usage by up to 89.5% and enables the pre-training of large LLMs, such as LLaMA 7B, on consumer-level GPUs like the NVIDIA RTX 4090, without additional inference costs. Moreover, GradNormLoRP outperforms existing low-rank methods in fine-tuning tasks. For instance, when fine-tuning the RoBERTa model on all GLUE tasks with a rank of 8, GradNormLoRP achieves an average score of 80.65, surpassing LoRA's score of 79.23. These results underscore GradNormLoRP as a promising alternative for efficient LLM pre-training and fine-tuning. Source code and Appendix: https://github.com/Jhhuangkay/Gradient-Weight-normalized-Low-rank-Projection-for-Efficient-LLM-Training

[Arxiv](https://arxiv.org/abs/2412.19616)