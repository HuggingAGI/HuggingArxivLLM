# 优化语言模型的语法可接受性：微调技术对比研究

发布时间：2025年01月14日

`LLM应用

解释：这篇论文主要讨论了如何通过微调（Fine-Tuning）技术来优化大型语言模型（LLM）在特定任务（语法可接受性任务）上的表现，并对比了不同的微调方法（如VFT、PBFT、LoRA等）。这属于LLM在实际任务中的应用，因此分类为LLM应用。` `机器学习`

> Optimizing Language Models for Grammatical Acceptability: A Comparative Study of Fine-Tuning Techniques

# 摘要

> 本研究使用CoLA数据集对OPT-125M进行微调（FT），以完成语法可接受性任务。通过对比VFT、PBFT和PEFT（如LoRA），我们在保持高准确性的同时显著提升了计算效率。实验结果显示，VFT的准确性最高（81.2%），而LoRA通过减少50%以上的内存使用和迭代时间，进一步提升了PBFT的准确性。尽管CD在计算上高效，但其准确性仅为31%左右。我们的研究通过降低计算门槛，为普及LLM的使用做出了贡献。

> This study explores the fine-tuning (FT) of the Open Pre-trained Transformer (OPT-125M) for grammatical acceptability tasks using the CoLA dataset. By comparing Vanilla-Fine-Tuning (VFT), Pattern-Based-Fine-Tuning (PBFT), and Parameter-Efficient Fine-Tuning techniques (PEFT) like Low-Rank Adaptation (LoRA), we demonstrate significant improvements in computational efficiency while maintaining high accuracy. Our experiments reveal that while VFT achieves the highest accuracy (81.2%), LoRA enhancing FT by reducing memory usage and iteration time by more than 50%, and increases accuracy in PBFT case. Context Distillation (CD), though computationally efficient, underperformed with accuracy around 31%. Our findings contribute to democratizing access to large language models (LLM) by reducing computational barriers.

[Arxiv](https://arxiv.org/abs/2501.07853)