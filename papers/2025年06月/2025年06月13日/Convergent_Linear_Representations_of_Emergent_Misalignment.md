# 收敛线性表示下的新兴错位问题

发布时间：2025年06月13日

`LLM理论` `人工智能` `机器学习`

> Convergent Linear Representations of Emergent Misalignment

# 摘要

> 在狭窄的数据集上微调大型语言模型，可能会导致模型产生广泛偏离预期的行为，这种现象被称为“涌现性偏差”。然而，这种偏差背后的作用机制，以及为何它能够超出训练领域泛化到更广泛的场景，目前尚不明确，这表明我们在理解模型对齐机制方面仍存在重大知识缺口。在本研究中，我们训练并分析了一个极简化的模型，该模型仅使用9个秩1适配器就成功让Qwen2.5-14B-Instruct模型出现了涌现性偏差。通过研究发现，不同出现偏差的模型会收敛到相似的偏差表示形式。我们通过从一个微调模型的激活中提取“偏差方向”，并成功地利用它来消除更高维度LoRA和不同数据集微调模型中的偏差行为，从而证明了这种收敛性。借助秩1LoRA的标量隐藏状态，我们进一步开展了一系列实验，直接解析微调适配器的作用，结果显示其中6个适配器与普遍性偏差相关，而另外2个则专门负责微调领域内的偏差。涌现性偏差是一个特别典型的不良且意外模型行为的例子，通过深入理解其背后的机制，我们希望未来能够更好地理解并缓解更广泛的模型偏差问题。


> Fine-tuning large language models on narrow datasets can cause them to develop broadly misaligned behaviours: a phenomena known as emergent misalignment. However, the mechanisms underlying this misalignment, and why it generalizes beyond the training domain, are poorly understood, demonstrating critical gaps in our knowledge of model alignment. In this work, we train and study a minimal model organism which uses just 9 rank-1 adapters to emergently misalign Qwen2.5-14B-Instruct. Studying this, we find that different emergently misaligned models converge to similar representations of misalignment. We demonstrate this convergence by extracting a 'misalignment direction' from one fine-tuned model's activations, and using it to effectively ablate misaligned behaviour from fine-tunes using higher dimensional LoRAs and different datasets. Leveraging the scalar hidden state of rank-1 LoRAs, we further present a set of experiments for directly interpreting the fine-tuning adapters, showing that six contribute to general misalignment, while two specialise for misalignment in just the fine-tuning domain. Emergent misalignment is a particularly salient example of undesirable and unexpected model behaviour and by advancing our understanding of the mechanisms behind it, we hope to move towards being able to better understand and mitigate misalignment more generally.

[Arxiv](https://arxiv.org/abs/2506.11618)