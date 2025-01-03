# Bridge-Coder: 释放LLMs在低资源代码中跨越语言鸿沟的潜力

发布时间：2024年10月24日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）来提升低资源编程语言（LRPLs）的代码生成性能。论文提出了一种名为Bridge-Coder的新方法，通过两个阶段（桥接生成阶段和桥接对齐阶段）来优化LLMs在LRPLs上的表现。这属于LLM在实际应用中的改进和优化，因此分类为LLM应用。` `编程语言`

> Bridge-Coder: Unlocking LLMs' Potential to Overcome Language Gaps in Low-Resource Code

# 摘要

> # 摘要
大型语言模型（LLMs）在生成高资源编程语言（HRPLs）如Python的代码时表现出色，但在低资源编程语言（LRPLs）如Racket或D上却表现不佳。这种性能差距加剧了数字鸿沟，使得使用LRPLs的开发者难以平等受益于LLM的进步，并进一步拉大了编程社区中的创新差距。虽然为LRPLs生成更多训练数据是一个可行的方向，但它面临两大挑战：手动注释既费时又昂贵，而LLM生成的LRPL代码质量往往不高。这一问题的根源在于自然语言与编程语言之间的差距（NL-PL Gap），由于对齐数据有限，这一差距在LRPLs中尤为明显。为此，我们提出了一种名为Bridge-Coder的新方法，利用LLMs的内在能力来提升LRPLs的性能。我们的方法分为两个关键阶段：桥接生成阶段，利用LLMs的通用知识理解、HRPLs的熟练度以及上下文学习能力，生成高质量的数据集；桥接对齐阶段，逐步优化自然语言指令与LRPLs之间的对齐。实验结果表明，Bridge-Coder在多个LRPLs上显著提升了模型性能，证明了该方法的有效性和泛化能力。此外，我们还对方法的关键组成部分进行了深入分析，为未来解决LRPLs相关挑战的研究提供了宝贵的见解。

> Large Language Models (LLMs) demonstrate strong proficiency in generating code for high-resource programming languages (HRPLs) like Python but struggle significantly with low-resource programming languages (LRPLs) such as Racket or D. This performance gap deepens the digital divide, preventing developers using LRPLs from benefiting equally from LLM advancements and reinforcing disparities in innovation within underrepresented programming communities. While generating additional training data for LRPLs is promising, it faces two key challenges: manual annotation is labor-intensive and costly, and LLM-generated LRPL code is often of subpar quality. The underlying cause of this issue is the gap between natural language to programming language gap (NL-PL Gap), which is especially pronounced in LRPLs due to limited aligned data. In this work, we introduce a novel approach called Bridge-Coder, which leverages LLMs' intrinsic capabilities to enhance the performance on LRPLs. Our method consists of two key stages. Bridge Generation, where we create high-quality dataset by utilizing LLMs' general knowledge understanding, proficiency in HRPLs, and in-context learning abilities. Then, we apply the Bridged Alignment, which progressively improves the alignment between NL instructions and LRPLs. Experimental results across multiple LRPLs show that Bridge-Coder significantly enhances model performance, demonstrating the effectiveness and generalization of our approach. Furthermore, we offer a detailed analysis of the key components of our method, providing valuable insights for future work aimed at addressing the challenges associated with LRPLs.

[Arxiv](https://arxiv.org/abs/2410.18957)