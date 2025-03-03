# 能力定位：能力可以被本地化，而不是个体知识

发布时间：2025年02月28日

`LLM理论` `人工智能` `机器学习`

> Capability Localization: Capabilities Can be Localized rather than Individual Knowledge

# 摘要

> 大规模语言模型在自然语言处理领域表现卓越，但模型参数如何影响性能提升仍是一个未解之谜。以往研究假设个体知识存储于局部参数中，以分散参数、参数层或参数链等形式存在，缺乏统一性。通过保真度和可靠性评估实验，我们发现个体知识无法实现局部化存储。随后，我们构建了用于解耦实验的数据集，发现了局部化存储数据共性的潜力。为了进一步揭示这一现象，本文提出了一种共性神经元定位（CNL）方法，成功定位了共性神经元，并在GSM8K数据集上实现了96.42%的神经元重叠率。最后，通过跨数据实验，我们证明共性神经元是一组能力神经元，具备提升模型性能的能力。我们的代码可在https://github.com/nlpkeg/Capability-Neuron-Localization获取。

> Large scale language models have achieved superior performance in tasks related to natural language processing, however, it is still unclear how model parameters affect performance improvement. Previous studies assumed that individual knowledge is stored in local parameters, and the storage form of individual knowledge is dispersed parameters, parameter layers, or parameter chains, which are not unified. We found through fidelity and reliability evaluation experiments that individual knowledge cannot be localized. Afterwards, we constructed a dataset for decoupling experiments and discovered the potential for localizing data commonalities. To further reveal this phenomenon, this paper proposes a Commonality Neuron Localization (CNL) method, which successfully locates commonality neurons and achieves a neuron overlap rate of 96.42% on the GSM8K dataset. Finally, we have demonstrated through cross data experiments that commonality neurons are a collection of capability neurons that possess the capability to enhance performance. Our code is available at https://github.com/nlpkeg/Capability-Neuron-Localization.

[Arxiv](https://arxiv.org/abs/2502.20992)