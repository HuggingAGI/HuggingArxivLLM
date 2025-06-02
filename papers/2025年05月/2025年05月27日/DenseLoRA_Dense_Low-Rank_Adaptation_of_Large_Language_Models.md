# # DenseLoRA：大型语言模型的密集低秩调整

发布时间：2025年05月27日

`LLM理论` `人工智能`

> DenseLoRA: Dense Low-Rank Adaptation of Large Language Models

# 摘要

> 低秩适配（LoRA）是一种通过微调两个低秩矩阵来高效适应大型语言模型（LLMs）的方法，从而减少可训练参数的数量。然而，先前的研究表明，这些矩阵中的许多权重都是冗余的，导致参数利用率低下。为了解决这一限制，我们引入了密集低秩适配（DenseLoRA），这是一种新型方法，能够在实现优于LoRA的性能的同时，提高参数效率。DenseLoRA基于表示微调的概念，在应用适配之前，通过一个单一的Encoder-Decoder对所有适配层的隐藏表示进行精炼和压缩。与LoRA依赖两个冗余的低秩矩阵不同，DenseLoRA通过一个密集的低秩矩阵来适配LLMs，从而提高了参数利用率和适配效率。我们在各种基准上评估了DenseLoRA，结果显示，它仅使用0.01%的可训练参数即可达到83.8%的准确率，而LoRA在LLaMA3-8B上使用0.70%的可训练参数仅达到80.8%的准确率。此外，我们进行了大量实验，系统评估了DenseLoRA各个组件对整体模型性能的影响。代码可在https://github.com/mulin-ahu/DenseLoRA上获得。

> Low-rank adaptation (LoRA) has been developed as an efficient approach for adapting large language models (LLMs) by fine-tuning two low-rank matrices, thereby reducing the number of trainable parameters. However, prior research indicates that many of the weights in these matrices are redundant, leading to inefficiencies in parameter utilization. To address this limitation, we introduce Dense Low-Rank Adaptation (DenseLoRA), a novel approach that enhances parameter efficiency while achieving superior performance compared to LoRA. DenseLoRA builds upon the concept of representation fine-tuning, incorporating a single Encoder-Decoder to refine and compress hidden representations across all adaptation layers before applying adaptation. Instead of relying on two redundant low-rank matrices as in LoRA, DenseLoRA adapts LLMs through a dense low-rank matrix, improving parameter utilization and adaptation efficiency. We evaluate DenseLoRA on various benchmarks, showing that it achieves 83.8% accuracy with only 0.01% of trainable parameters, compared to LoRA's 80.8% accuracy with 0.70% of trainable parameters on LLaMA3-8B. Additionally, we conduct extensive experiments to systematically assess the impact of DenseLoRA's components on overall model performance. Code is available at https://github.com/mulin-ahu/DenseLoRA.

[Arxiv](https://arxiv.org/abs/2505.23808)