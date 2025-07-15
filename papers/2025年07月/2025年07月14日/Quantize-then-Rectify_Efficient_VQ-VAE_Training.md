# 高效训练 VQ-VAE：量化后再校正

发布时间：2025年07月14日

`其他

摘要主要讨论了视觉分词器在多模态大模型中的应用，以及如何通过优化训练方法降低计算成本。虽然涉及多模态模型，但其核心是关于视觉分词器的技术改进，而非直接探讨LLM的应用或理论。因此，归类为“其他”更合适。` `计算机视觉`

> Quantize-then-Rectify: Efficient VQ-VAE Training

# 摘要

> 视觉分词器在多模态大模型中发挥着桥梁作用，连接着连续输入与离散标记。然而，训练高压缩率的VQ-VAE仍然面临巨大的计算挑战，通常需要数千个GPU小时的资源投入。本研究发现，通过控制VAE的量化噪声在可接受范围内，可以将预训练的VAE高效转换为VQ-VAE。我们提出了	extbf{Quantize-then-Rectify (ReVQ)}，一个基于预训练VAE的框架，能够以极低的计算开销实现快速的VQ-VAE训练。通过整合	extbf{通道多组量化}技术来扩大码本容量，并采用	extbf{后置校正器}来缓解量化误差，ReVQ能够将ImageNet图像压缩至最多512个标记，同时保持rFID = 1.06的重建质量。尤为突出的是，与现有最优方法相比，ReVQ的训练成本降低了两个数量级：ReVQ在单个NVIDIA 4090 GPU上完成全部训练仅需约22小时，而类似的方法则需要在32个A100 GPU上运行4.5天。实验结果表明，ReVQ在效率与重建质量之间实现了更优的平衡。

> Visual tokenizers are pivotal in multimodal large models, acting as bridges between continuous inputs and discrete tokens. Nevertheless, training high-compression-rate VQ-VAEs remains computationally demanding, often necessitating thousands of GPU hours. This work demonstrates that a pre-trained VAE can be efficiently transformed into a VQ-VAE by controlling quantization noise within the VAE's tolerance threshold. We present \textbf{Quantize-then-Rectify (ReVQ)}, a framework leveraging pre-trained VAEs to enable rapid VQ-VAE training with minimal computational overhead. By integrating \textbf{channel multi-group quantization} to enlarge codebook capacity and a \textbf{post rectifier} to mitigate quantization errors, ReVQ compresses ImageNet images into at most 512 tokens while sustaining competitive reconstruction quality (rFID = 1.06). Significantly, ReVQ reduces training costs by over two orders of magnitude relative to state-of-the-art approaches: ReVQ finishes full training on a single NVIDIA 4090 in approximately 22 hours, whereas comparable methods require 4.5 days on 32 A100 GPUs. Experimental results show that ReVQ achieves superior efficiency-reconstruction trade-offs.

[Arxiv](https://arxiv.org/abs/2507.10547)