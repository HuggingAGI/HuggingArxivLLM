# MBQ：大型视觉语言模型的模态平衡量化方法

发布时间：2024年12月27日

`LLM应用` `计算机视觉` `模型量化`

> MBQ: Modality-Balanced Quantization for Large Vision-Language Models

# 摘要

> 视觉语言模型（VLMs）已在诸多现实场景中得以应用。然而，VLMs 的大参数规模致使内存和计算开销巨大，给部署造成严峻挑战。训练后量化（PTQ）是降低内存与计算开销的有效手段。现有的 PTQ 方法多聚焦于大型语言模型（LLMs），未考虑其他模态的差异。本文中，我们发现大型 VLMs 里语言和视觉标记的敏感性存在显著差别。所以，如现有 PTQ 方法那样对不同模态的标记一视同仁，可能会过度看重不敏感的模态，从而导致明显的精度损失。为应对此问题，我们为大型 VLMs 提出了一种简便且有效的方法——模态平衡量化（MBQ）。具体而言，MBQ 在校准过程中融入不同模态的敏感性差异，以将重建损失最小化，获取更优的量化参数。大量实验表明，相较于最先进的基线，对于 7B 至 70B 的 VLMs，MBQ 在 W3 和 W4A8 量化下能显著提升任务精度，分别高达 4.4%和 11.6%。另外，我们实现了一个 W3 GPU 内核，它融合了解量化和 GEMV 运算符，使 RTX 4090 上的 LLaVA-onevision-7B 实现了 1.4 倍的加速。代码可在 https://github.com/thu-nics/MBQ 获取。

> Vision-Language Models (VLMs) have enabled a variety of real-world applications. The large parameter size of VLMs brings large memory and computation overhead which poses significant challenges for deployment. Post-Training Quantization (PTQ) is an effective technique to reduce the memory and computation overhead. Existing PTQ methods mainly focus on large language models (LLMs), without considering the differences across other modalities. In this paper, we discover that there is a significant difference in sensitivity between language and vision tokens in large VLMs. Therefore, treating tokens from different modalities equally, as in existing PTQ methods, may over-emphasize the insensitive modalities, leading to significant accuracy loss. To deal with the above issue, we propose a simple yet effective method, Modality-Balanced Quantization (MBQ), for large VLMs. Specifically, MBQ incorporates the different sensitivities across modalities during the calibration process to minimize the reconstruction loss for better quantization parameters. Extensive experiments show that MBQ can significantly improve task accuracy by up to 4.4% and 11.6% under W3 and W4A8 quantization for 7B to 70B VLMs, compared to SOTA baselines. Additionally, we implement a W3 GPU kernel that fuses the dequantization and GEMV operators, achieving a 1.4x speedup on LLaVA-onevision-7B on the RTX 4090. The code is available at https://github.com/thu-nics/MBQ.

[Arxiv](https://arxiv.org/abs/2412.19509)