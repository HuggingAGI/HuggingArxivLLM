# 双空间框架用于大型语言模型的通用知识蒸馏

发布时间：2025年04月15日

`LLM理论` `人工智能`

> A Dual-Space Framework for General Knowledge Distillation of Large Language Models

# 摘要

> 知识蒸馏 (KD) 是一种有效的解决方案，通过将大型语言模型 (LLMs) 的知识迁移到更小的模型中实现模型压缩。在这一过程中，白盒 KD 方法通常通过最小化教师模型和学生模型输出分布之间的差异来传递更多信息。然而，我们发现当前的白盒 KD 框架存在两大局限：a) 不同输出空间的概率分布难以有效对齐，这限制了教师与学生模型之间的相似性；b) 该框架无法处理具有不同词汇表的 LLMs。这些局限的根本原因在于，用于 KD 的教师和学生模型的预测头不同，导致它们生成的分布处于不同的输出空间和维度中。因此，本文提出了一种双空间知识蒸馏 (DSKD) 框架，通过统一教师和学生模型的预测头来实现更高效的 KD。具体而言，我们引入了两个理想初始化的投影器，将教师和学生的隐藏状态分别映射到对方的表示空间中。这样一来，不同模型的隐藏状态可以共享相同的预测头，从而统一分布的输出空间。此外，我们还开发了一种精确标记对齐 (ETA) 算法，用于对齐两个不同标记化序列中的相同标记。基于以上创新，我们的 DSKD 框架成为一个通用的 KD 框架，不仅支持离策略和在线策略 KD，还可以在任意两个 LLMs 之间进行 KD，无论它们的词汇表是否相同。在指令遵循、数学推理和代码生成等基准测试中的大量实验表明，DSKD 的性能显著优于现有基于白盒 KD 框架的方法，并且在处理具有不同词汇表的 LLMs 时，也超越了其他跨标记化器的 KD 方法。


> Knowledge distillation (KD) is a promising solution to compress large language models (LLMs) by transferring their knowledge to smaller models. During this process, white-box KD methods usually minimize the distance between the output distributions of the teacher model and the student model to transfer more information. However, we reveal that the current white-box KD framework exhibits two limitations: a) bridging probability distributions from different output spaces will limit the similarity between the teacher model and the student model; b) this framework cannot be applied to LLMs with different vocabularies. One of the root causes for these limitations is that the distributions from the teacher and the student for KD are output by different prediction heads, which yield distributions in different output spaces and dimensions. Therefore, in this paper, we propose a dual-space knowledge distillation (DSKD) framework that unifies the prediction heads of the teacher and the student models for KD. Specifically, we first introduce two projectors with ideal initialization to project the teacher/student hidden states into the student/teacher representation spaces. After this, the hidden states from different models can share the same head and unify the output spaces of the distributions. Furthermore, we develop an exact token alignment (ETA) algorithm to align the same tokens in two differently-tokenized sequences. Based on the above, our DSKD framework is a general KD framework that supports both off-policy and on-policy KD, and KD between any two LLMs regardless of their vocabularies. Extensive experiments on instruction-following, mathematical reasoning, and code generation benchmarks show that DSKD significantly outperforms existing methods based on the current white-box KD framework and surpasses other cross-tokenizer KD methods for LLMs with different vocabularies.

[Arxiv](https://arxiv.org/abs/2504.11426)