# 结合阈值单元的人工振荡神经元

发布时间：2025年05月06日

`其他` `人工智能` `神经科学`

> Binding threshold units with artificial oscillatory neurons

# 摘要

> 人工Kuramoto振荡神经元近期被提出，作为阈值单元的替代方案。实证研究表明，振荡单元在无监督目标发现和特定推理问题等任务中表现优于阈值单元。针对这些振荡神经元的耦合机制是异质性的，结合了广义Kuramoto方程与用于阈值单元的标准耦合方法。

在本研究简报中，我们提出一个清晰区分振荡神经元与阈值单元的理论框架，并在它们之间建立耦合机制。我们从生物学角度认为，振荡单元和阈值单元实现了神经编码的不同方面：大致而言，阈值单元模拟神经元的放电强度，而振荡单元通过频率调制促进信息交换。

为了推导这两种单元之间的相互作用，我们将它们的动态约束在允许Lyapunov函数的动态系统中。对于阈值单元，这导致了Hopfield联想记忆模型，而对于振荡单元，则得到了一种特定形式的广义Kuramoto模型。这些动态系统可以自然地耦合形成一个Hopfield-Kuramoto联想记忆模型，该模型也允许Lyapunov函数。

存在多种耦合形式。值得注意的是，振荡神经元可用于实现Hopfield网络权重矩阵的低秩修正。这种修正可以被视为一种Hebbian学习形式，或是用于大型语言模型微调的流行LoRA方法。我们通过示例性玩具实验展示了这种特定耦合的实际实现。

> Artificial Kuramoto oscillatory neurons were recently introduced as an alternative to threshold units. Empirical evidence suggests that oscillatory units outperform threshold units in several tasks including unsupervised object discovery and certain reasoning problems. The proposed coupling mechanism for these oscillatory neurons is heterogeneous, combining a generalized Kuramoto equation with standard coupling methods used for threshold units. In this research note, we present a theoretical framework that clearly distinguishes oscillatory neurons from threshold units and establishes a coupling mechanism between them. We argue that, from a biological standpoint, oscillatory and threshold units realise distinct aspects of neural coding: roughly, threshold units model intensity of neuron firing, while oscillatory units facilitate information exchange by frequency modulation. To derive interaction between these two types of units, we constrain their dynamics by focusing on dynamical systems that admit Lyapunov functions. For threshold units, this leads to Hopfield associative memory model, and for oscillatory units it yields a specific form of generalized Kuramoto model. The resulting dynamical systems can be naturally coupled to form a Hopfield-Kuramoto associative memory model, which also admits a Lyapunov function. Various forms of coupling are possible. Notably, oscillatory neurons can be employed to implement a low-rank correction to the weight matrix of a Hopfield network. This correction can be viewed either as a form of Hebbian learning or as a popular LoRA method used for fine-tuning of large language models. We demonstrate the practical realization of this particular coupling through illustrative toy experiments.

[Arxiv](https://arxiv.org/abs/2505.03648)