# 一种轻量级方法：干扰大型语言模型的记忆序列

发布时间：2025年02月07日

`LLM应用` `版权保护` `模型优化`

> A Lightweight Method to Disrupt Memorized Sequences in LLM

# 摘要

> 大型语言模型 (LLMs) 在多种任务中表现出色，但verbatim复制受版权保护内容的风险引发了法律和伦理问题。尽管差分隐私或神经元编辑等方法可以减少记忆，但它们通常需要昂贵的重新训练或直接访问模型权重，并可能影响性能。为了解决这些问题，我们提出了TokenSwap，这是一种轻量级的后处理方法，它将与语法相关的标记概率替换为来自小型辅助模型（例如DistilGPT-2）的概率。我们在Pythia-6.9b和LLaMA-3-8b等商用级别模型上进行了广泛实验，证明我们的方法可以将众所周知的记忆生成案例减少多达10倍，同时对下游任务的影响微乎其微。我们的方法为现实世界系统用户提供了一个独特且有效的解决方案，既易于访问又实用。

> Large language models (LLMs) demonstrate impressive capabilities across many tasks yet risk reproducing copyrighted content verbatim, raising legal and ethical concerns. Although methods like differential privacy or neuron editing can reduce memorization, they typically require costly retraining or direct access to model weights and may degrade performance. To address these challenges, we propose TokenSwap, a lightweight, post-hoc approach that replaces the probabilities of grammar-related tokens with those from a small auxiliary model (e.g., DistilGPT-2). We run extensive experiments on commercial grade models such as Pythia-6.9b and LLaMA-3-8b and demonstrate that our method effectively reduces well-known cases of memorized generation by upto 10x with little to no impact on downstream tasks. Our approach offers a uniquely accessible and effective solution to users of real-world systems.

[Arxiv](https://arxiv.org/abs/2502.05159)