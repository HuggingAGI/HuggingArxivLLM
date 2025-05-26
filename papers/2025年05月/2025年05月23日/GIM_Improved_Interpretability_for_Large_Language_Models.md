# GIM：让大型语言模型更易理解

发布时间：2025年05月23日

`LLM理论` `人工智能` `大型语言模型`

> GIM: Improved Interpretability for Large Language Models

# 摘要

> 在大型语言模型中实现忠实可解释性是构建可靠AI的关键。然而，自修复现象构成了主要障碍：网络通过放大其他部分的信号来补偿某部分的减弱，从而掩盖了被削弱组件的真实重要性。虽然先前研究将自修复归因于层归一化和备用组件的补偿作用，但我们发现了一种新的机制——在注意力机制内部，softmax重分配掩盖了重要注意力分数的影响。这使得传统消融和梯度方法低估了所有对这些注意力分数产生贡献的组件的重要性。为此，我们提出了一种名为梯度交互修改（GIM）的技术，它在反向传播过程中考虑了自修复的影响。通过在Gemma、LLAMA和Qwen等多个大型语言模型以及多种任务上的广泛实验，我们发现GIM显著提升了忠实度，超越了现有的电路识别和特征归因方法。这项研究为深入理解LLMs的内在机制迈出了重要一步，这对提升模型性能和确保其安全性至关重要。我们的代码已开源，欢迎访问https://github.com/JoakimEdin/gim获取。

> Ensuring faithful interpretability in large language models is imperative for trustworthy and reliable AI. A key obstacle is self-repair, a phenomenon where networks compensate for reduced signal in one component by amplifying others, masking the true importance of the ablated component. While prior work attributes self-repair to layer normalization and back-up components that compensate for ablated components, we identify a novel form occurring within the attention mechanism, where softmax redistribution conceals the influence of important attention scores. This leads traditional ablation and gradient-based methods to underestimate the significance of all components contributing to these attention scores. We introduce Gradient Interaction Modifications (GIM), a technique that accounts for self-repair during backpropagation. Extensive experiments across multiple large language models (Gemma 2B/9B, LLAMA 1B/3B/8B, Qwen 1.5B/3B) and diverse tasks demonstrate that GIM significantly improves faithfulness over existing circuit identification and feature attribution methods. Our work is a significant step toward better understanding the inner mechanisms of LLMs, which is crucial for improving them and ensuring their safety. Our code is available at https://github.com/JoakimEdin/gim.

[Arxiv](https://arxiv.org/abs/2505.17630)