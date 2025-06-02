# 优势参数扩展训练造就更优大型语言模型

发布时间：2025年05月30日

`LLM理论`

> Advantageous Parameter Expansion Training Makes Better Large Language Models

# 摘要

> 虽然增加大语言模型预训练和微调中的可训练参数数量能有效提升性能，但也会显著增加计算开销。深入研究参数差异后，我们发现了一类关键的“优势参数”，它们对模型性能起决定性作用。进一步分析表明，模型能力越强，其优势参数越多。本文提出了一种名为APEX（优势参数扩展训练）的方法，通过逐步将优势参数扩展至非优势参数空间，增加优势参数比例，从而提升训练效果。从矩阵有效秩的理论分析解释了APEX的性能优势。实验结果表明，在指令微调中，APEX仅使用52%的可训练参数就优于全参数微调；在持续预训练中，APEX仅用33%的训练数据就达到了传统训练的困惑度水平，并显著提升了下游任务表现。

> Although scaling up the number of trainable parameters in both pre-training and fine-tuning can effectively improve the performance of large language models, it also leads to increased computational overhead. When delving into the parameter difference, we find that a subset of parameters, termed advantageous parameters, plays a crucial role in determining model performance. Further analysis reveals that stronger models tend to possess more such parameters. In this paper, we propose Advantageous Parameter EXpansion Training (APEX), a method that progressively expands advantageous parameters into the space of disadvantageous ones, thereby increasing their proportion and enhancing training effectiveness. Further theoretical analysis from the perspective of matrix effective rank explains the performance gains of APEX. Extensive experiments on both instruction tuning and continued pre-training demonstrate that, in instruction tuning, APEX outperforms full-parameter tuning while using only 52% of the trainable parameters. In continued pre-training, APEX achieves the same perplexity level as conventional training with just 33% of the training data, and yields significant improvements on downstream tasks.

[Arxiv](https://arxiv.org/abs/2505.24241)