# DeFTX: 去噪稀疏微调实现零样本跨语言迁移

发布时间：2025年05月21日

`LLM应用` `机器翻译`

> DeFTX: Denoised Sparse Fine-Tuning for Zero-Shot Cross-Lingual Transfer

# 摘要

> 跨语言迁移的有效性仍是将大型语言模型优势从高资源语言扩展至低资源语言的关键挑战。为实现这一目标，先前研究探索了多种方法，旨在融合高资源源语言的任务特定数据知识与低资源目标语言的无标签文本语言知识。其中，一种值得注意的方法提出了用于跨语言迁移的可组合稀疏微调（SFT），该方法通过学习任务特定和语言特定的稀疏掩码，选择预训练模型参数的子集进行微调。这些稀疏微调向量（SFTs）随后与预训练模型结合，仅使用源语言任务特定数据，实现零样本跨语言迁移至目标语言任务。这些SFT的稀疏掩码通过简单基于幅度的剪枝方法识别。在我们的工作中，我们引入了DeFT-X，这是一种新颖的可组合SFT方法，通过奇异值分解在幅度剪枝前对预训练模型的权重矩阵进行去噪，从而生成更稳健的SFT。我们在多样化的极低资源语言集合上评估了DeFT-X，涵盖情感分类（NusaX）和自然语言推理（AmericasNLI），结果显示其表现与SFT及其他突出的跨语言迁移基线相当或更优。

> Effective cross-lingual transfer remains a critical challenge in scaling the benefits of large language models from high-resource to low-resource languages. Towards this goal, prior studies have explored many approaches to combine task knowledge from task-specific data in a (high-resource) source language and language knowledge from unlabeled text in a (low-resource) target language. One notable approach proposed composable sparse fine-tuning (SFT) for cross-lingual transfer that learns task-specific and language-specific sparse masks to select a subset of the pretrained model's parameters that are further fine-tuned. These sparse fine-tuned vectors (SFTs) are subsequently composed with the pretrained model to facilitate zero-shot cross-lingual transfer to a task in a target language, using only task-specific data from a source language. These sparse masks for SFTs were identified using a simple magnitude-based pruning. In our work, we introduce DeFT-X, a novel composable SFT approach that denoises the weight matrices of a pretrained model before magnitude pruning using singular value decomposition, thus yielding more robust SFTs. We evaluate DeFT-X on a diverse set of extremely low-resource languages for sentiment classification (NusaX) and natural language inference (AmericasNLI) and demonstrate that it performs at par or outperforms SFT and other prominent cross-lingual transfer baselines.

[Arxiv](https://arxiv.org/abs/2505.15090)