# Tracr-Injection：将算法融入预训练语言模型

发布时间：2025年05月15日

`LLM理论` `人工智能` `机器学习`

> Tracr-Injection: Distilling Algorithms into Pre-trained Language Models

# 摘要

> 大型语言模型的快速发展推动了对Transformer架构符号能力的深入研究。研究者提出了一种名为RASP的编程语言，它能够直接将算法编译为Transformer权重以实现相关功能。然而，RASP中实现的任务往往难以从自然无监督数据中学习，这凸显了Transformer架构理论能力与实际学习能力之间的不匹配。我们提出了一种名为tracr-injection的新方法，该方法能够将RASP编写的算法直接注入到预训练语言模型中。我们通过向语言模型中注入3种不同算法展示了该方法的独特优势。实验表明，我们的方法能够在模型残差流中创建一个可解释的子空间，该子空间能够被解码为RASP算法代码中的变量。此外，与基线方法相比，我们的方法在分布外数据上的性能得到了显著提升，这表明模型内部确实正在发生更符号化的机制。我们已公开了实验所用的代码。

> Motivated by the surge of large language models, there has been a push to formally characterize the symbolic abilities intrinsic to the transformer architecture. A programming language, called RASP, has been proposed, which can be directly compiled into transformer weights to implement these algorithms. However, the tasks that can be implemented in RASP are often uncommon to learn from natural unsupervised data, showing a mismatch between theoretical capabilities of the transformer architecture, and the practical learnability of these capabilities from unsupervised data. We propose tracr-injection, a method that allows us to distill algorithms written in RASP directly into a pre-trained language model. We showcase our method by injecting 3 different algorithms into a language model. We show how our method creates an interpretable subspace within the model's residual stream, which can be decoded into the variables present in the code of the RASP algorithm. Additionally, we found that the proposed method can improve out of distribution performance compared to our baseline, indicating that indeed a more symbolic mechanism is taking place in the inner workings of the model. We release the code used to run our experiments.

[Arxiv](https://arxiv.org/abs/2505.10719)