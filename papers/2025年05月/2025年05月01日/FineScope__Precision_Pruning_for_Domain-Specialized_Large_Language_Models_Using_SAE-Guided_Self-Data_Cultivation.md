# FineScope：基于SAE引导的自数据培养实现领域专用大型语言模型的精准剪枝。

发布时间：2025年05月01日

`LLM理论` `模型优化` `领域适应`

> FineScope : Precision Pruning for Domain-Specialized Large Language Models Using SAE-Guided Self-Data Cultivation

# 摘要

> 由于训练大型语言模型（LLMs）需要巨大的计算资源，开发小型、领域特定的LLMs成为了研究热点。这些模型不仅高效，还能在特定任务中表现出色。目前，中型模型如LLaMA等常用于领域特定的适配，但它们在专用数据集上的表现往往不尽如人意。为此，我们提出了FineScope框架，它能够从大型预训练模型中推导出紧凑且针对特定领域的LLMs。FineScope采用了稀疏自动编码器（SAE）框架，通过其生成可解释特征表示的能力，从大规模数据集中提取领域特定子集。我们还引入了结构化剪枝方法，并结合领域特定约束条件，确保剪枝后的模型仍能保留关键领域的核心知识。为了进一步提升模型性能，我们采用自我数据蒸馏技术，利用SAE整理的数据集恢复剪枝过程中丢失的关键领域信息。通过大量实验和消融研究，我们发现FineScope在领域特定任务中表现优异，甚至超越了多个大规模的先进LLMs。此外，我们的研究还表明，通过使用SAE整理的数据集进行微调，剪枝后的模型能够恢复大部分原始性能。值得注意的是，即使不进行剪枝，直接使用这些数据集对预训练LLMs进行微调，也能显著提升其在特定领域的准确性，这充分证明了我们方法的稳健性。最后，我们的代码即将公开发布，方便研究者进一步探索和应用。


> Training large language models (LLMs) from scratch requires significant computational resources, driving interest in developing smaller, domain-specific LLMs that maintain both efficiency and strong task performance. Medium-sized models such as LLaMA, llama} have served as starting points for domain-specific adaptation, but they often suffer from accuracy degradation when tested on specialized datasets. We introduce FineScope, a framework for deriving compact, domain-optimized LLMs from larger pretrained models. FineScope leverages the Sparse Autoencoder (SAE) framework, inspired by its ability to produce interpretable feature representations, to extract domain-specific subsets from large datasets. We apply structured pruning with domain-specific constraints, ensuring that the resulting pruned models retain essential knowledge for the target domain. To further enhance performance, these pruned models undergo self-data distillation, leveraging SAE-curated datasets to restore key domain-specific information lost during pruning. Extensive experiments and ablation studies demonstrate that FineScope achieves highly competitive performance, outperforming several large-scale state-of-the-art LLMs in domain-specific tasks. Additionally, our results show that FineScope enables pruned models to regain a substantial portion of their original performance when fine-tuned with SAE-curated datasets. Furthermore, applying these datasets to fine-tune pretrained LLMs without pruning also improves their domain-specific accuracy, highlighting the robustness of our approach. The code will be released.

[Arxiv](https://arxiv.org/abs/2505.00624)