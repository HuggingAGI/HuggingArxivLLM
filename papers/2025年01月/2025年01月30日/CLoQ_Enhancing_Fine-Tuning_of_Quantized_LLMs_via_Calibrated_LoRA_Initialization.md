# CLoQ: 通过校准LoRA初始化优化量化LLMs的微调

发布时间：2025年01月30日

`LLM理论

理由：这篇论文主要讨论了在量化大型语言模型（LLMs）时使用低秩适应（LoRA）微调的技术挑战，并提出了一种新的初始化策略CLoQ来解决这些问题。论文还提出了一个新颖的理论结果来支持其方法的有效性。因此，这篇论文主要涉及LLM的理论研究和优化方法，属于LLM理论分类。` `机器学习`

> CLoQ: Enhancing Fine-Tuning of Quantized LLMs via Calibrated LoRA Initialization

# 摘要

> # 摘要
使用低秩适应（LoRA）微调大型语言模型（LLMs）已成为下游任务的高效方法，尤其在计算资源有限时。然而，量化LLMs的表示精度降低，使得应用LoRA技术面临独特挑战。本文提出CLoQ（量化LLMs的校准LoRA初始化），一种简洁的初始化策略，旨在解决这些挑战。CLoQ通过小型校准数据集量化预训练LLM，并确定每层的最佳LoRA组件，确保后续微调的坚实基础。关键贡献是一个新颖的理论结果，支持准确且封闭地构建这些最佳LoRA组件。我们在语言生成、算术推理和常识推理等任务上验证了CLoQ的有效性，证明其在量化LLMs上始终优于现有LoRA微调方法，尤其在超低比特宽度下表现突出。

> Fine-tuning large language models (LLMs) using low-rank adaptation (LoRA) has become a highly efficient approach for downstream tasks, particularly in scenarios with limited computational resources. However, applying LoRA techniques to quantized LLMs poses unique challenges due to the reduced representational precision of quantized weights. In this paper, we introduce CLoQ (Calibrated LoRA initialization for Quantized LLMs), a simplistic initialization strategy designed to overcome these challenges. Our approach focuses on minimizing the layer-wise discrepancy between the original LLM and its quantized counterpart with LoRA components during initialization. By leveraging a small calibration dataset, CLoQ quantizes a pre-trained LLM and determines the optimal LoRA components for each layer, ensuring a strong foundation for subsequent fine-tuning. A key contribution of this work is a novel theoretical result that enables the accurate and closed-form construction of these optimal LoRA components. We validate the efficacy of CLoQ across multiple tasks such as language generation, arithmetic reasoning, and commonsense reasoning, demonstrating that it consistently outperforms existing LoRA fine-tuning methods for quantized LLMs, especially at ultra low-bit widths.

[Arxiv](https://arxiv.org/abs/2501.18475)