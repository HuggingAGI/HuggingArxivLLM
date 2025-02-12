# # 扩散模型指令调优

发布时间：2025年02月04日

`LLM应用` `视觉语言模型`

> Diffusion Instruction Tuning

# 摘要

> 我们很高兴推出Lavender，这是一种简单却高效的监督微调（SFT）方法，它通过结合先进的图像生成模型（如Stable Diffusion）来显著提升视觉语言模型（VLM）的表现。与传统方法不同，Lavender在微调过程中巧妙地将视觉语言模型中的文本-视觉注意力机制与Stable Diffusion中的对齐，而非分别优化编码器。这种创新的对齐方式不仅深化了模型对视觉内容的理解，还在各种任务中带来了显著的性能提升，无论是分布内还是分布外任务。令人惊叹的是，Lavender仅需0.13百万训练样本，仅为典型大规模SFT数据集的2.5%，并且可以在标准硬件（8块GPU）上轻松完成微调，整个过程仅需一天。它在多个开源多模态LLM（如Llama-3.2-11B、MiniCPM-Llama3-v2.5）上表现出色，尤其在具有挑战性的分布外医学问答任务中实现了高达30%的提升和68%的性能飞跃。通过以最小的监督成本高效迁移图像生成器的视觉专业知识，Lavender为构建更精准的视觉语言系统提供了一种可扩展的解决方案。所有相关代码、训练数据和模型将在https://astrazeneca.github.io/vlm/上开放共享。

> We introduce Lavender, a simple supervised fine-tuning (SFT) method that boosts the performance of advanced vision-language models (VLMs) by leveraging state-of-the-art image generation models such as Stable Diffusion. Specifically, Lavender aligns the text-vision attention in the VLM transformer with the equivalent used by Stable Diffusion during SFT, instead of adapting separate encoders. This alignment enriches the model's visual understanding and significantly boosts performance across in- and out-of-distribution tasks. Lavender requires just 0.13 million training examples, 2.5% of typical large-scale SFT datasets, and fine-tunes on standard hardware (8 GPUs) in a single day. It consistently improves state-of-the-art open-source multimodal LLMs (e.g., Llama-3.2-11B, MiniCPM-Llama3-v2.5), achieving up to 30% gains and a 68% boost on challenging out-of-distribution medical QA tasks. By efficiently transferring the visual expertise of image generators with minimal supervision, Lavender offers a scalable solution for more accurate vision-language systems. All code, training data, and models will be shared at https://astrazeneca.github.io/vlm/.

[Arxiv](https://arxiv.org/abs/2502.06814)