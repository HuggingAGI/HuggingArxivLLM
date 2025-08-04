# 探索更高有效秩的参数高效微调：基于 Khatri--Rao 积的解决方案

发布时间：2025年07月31日

`LLM理论` `视觉-语言模型` `大型语言模型`

> Towards Higher Effective Rank in Parameter-efficient Fine-tuning using Khatri--Rao Product

# 摘要

> 参数高效微调（PEFT）已成为适应大型预训练模型的常用方法。其中，低秩适应（LoRA）表现尤为突出。然而，近期研究表明，与全秩方法相比，LoRA在多模态和大型语言模型应用中存在局限性。本文通过一个具有受控谱特性的合成矩阵近似基准，对全秩与低秩PEFT方法进行了定量对比。实验结果表明，LoRA在近似谱分布较平缓或高频分量较多的矩阵时面临挑战——这表明其有效秩较低。为此，我们提出了KRAdapter，一种基于Khatri-Rao乘积的新型PEFT算法，其权重更新机制天然倾向于生成高有效秩的矩阵乘积。我们在视觉-语言模型（10亿参数级）和大型语言模型（80亿参数级）上验证了KRAdapter的性能优势，尤其在未见过的常识推理任务中表现突出。此外，KRAdapter继承了LoRA的内存与计算效率，成为微调十亿级参数模型的理想选择。

> Parameter-efficient fine-tuning (PEFT) has become a standard approach for adapting large pre-trained models. Amongst PEFT methods, low-rank adaptation (LoRA) has achieved notable success. However, recent studies have highlighted its limitations compared against full-rank alternatives, particularly when applied to multimodal and large language models. In this work, we present a quantitative comparison amongst full-rank and low-rank PEFT methods using a synthetic matrix approximation benchmark with controlled spectral properties. Our results confirm that LoRA struggles to approximate matrices with relatively flat spectrums or high frequency components -- signs of high effective ranks. To this end, we introduce KRAdapter, a novel PEFT algorithm that leverages the Khatri-Rao product to produce weight updates, which, by construction, tends to produce matrix product with a high effective rank. We demonstrate performance gains with KRAdapter on vision-language models up to 1B parameters and on large language models up to 8B parameters, particularly on unseen common-sense reasoning tasks. In addition, KRAdapter maintains the memory and compute efficiency of LoRA, making it a practical and robust alternative to fine-tune billion-scale parameter models.

[Arxiv](https://arxiv.org/abs/2508.00230)