# 无需窥探的微调：LLM后训练的隐私与泛化性能分析

发布时间：2025年07月02日

`LLM应用` `人工智能` `隐私保护`

> Tuning without Peeking: Provable Privacy and Generalization Bounds for LLM Post-Training

# 摘要

> 基于梯度的优化是深度学习的核心驱动力，通过反向传播实现高效且可扩展的训练。然而，这种方法对大量标注数据的依赖引发了隐私和安全问题，如易受数据投毒攻击和过拟合风险。相比之下，黑盒优化方法将模型视为不透明函数，仅依赖于函数评估结果来指导优化，为数据受限、对抗风险高或担心过拟合的场景提供了一种有前景的替代方案。然而，黑盒方法也面临重大挑战，包括难以扩展到高维参数空间（如大型语言模型（LLMs）中常见的情况）以及由于依赖大量模型评估而导致的高昂计算成本。

本文介绍了BBoxER，一种用于LLM后训练的进化黑盒方法，通过训练数据的隐式压缩引入信息瓶颈。借助信息流的可处理性，我们为泛化、差分隐私、数据投毒攻击易感性和抗提取攻击稳健性提供了强有力的理论保障。BBoxER建立在预训练好的LLMs之上，提供了一种轻量级且模块化的增强方案，适用于受限或隐私敏感环境的部署，同时提供了非空洞的泛化保证。

在对LLMs的实验中，我们实证展示了Retrofitting方法的学习能力，展示了BBoxER经过几次迭代后如何在推理数据集基准上提升性能并实现良好泛化。这使BBoxER成为基于梯度优化之上一个具有吸引力的附加组件。

> Gradient-based optimization is the workhorse of deep learning, offering efficient and scalable training via backpropagation. However, its reliance on large volumes of labeled data raises privacy and security concerns such as susceptibility to data poisoning attacks and the risk of overfitting. In contrast, black box optimization methods, which treat the model as an opaque function, relying solely on function evaluations to guide optimization, offer a promising alternative in scenarios where data access is restricted, adversarial risks are high, or overfitting is a concern. However, black box methods also pose significant challenges, including poor scalability to high-dimensional parameter spaces, as prevalent in large language models (LLMs), and high computational costs due to reliance on numerous model evaluations. This paper introduces BBoxER, an evolutionary black-box method for LLM post-training that induces an information bottleneck via implicit compression of the training data. Leveraging the tractability of information flow, we provide strong theoretical bounds on generalization, differential privacy, susceptibility to data poisoning attacks, and robustness to extraction attacks. BBoxER operates on top of pre-trained LLMs, offering a lightweight and modular enhancement suitable for deployment in restricted or privacy-sensitive environments, in addition to non-vacuous generalization guarantees. In experiments with LLMs, we demonstrate empirically that Retrofitting methods are able to learn, showing how a few iterations of BBoxER improve performance and generalize well on a benchmark of reasoning datasets. This positions BBoxER as an attractive add-on on top of gradient-based optimization.

[Arxiv](https://arxiv.org/abs/2507.01752)