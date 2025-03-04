# EAGLE-3：加速大型语言模型推理的训练时间测试扩展方法

发布时间：2025年03月03日

`LLM理论` `人工智能`

> EAGLE-3: Scaling up Inference Acceleration of Large Language Models via Training-Time Test

# 摘要

> 现代大型语言模型（LLMs）的顺序性质导致其计算成本高昂且运行速度缓慢，而推测采样已被证明是解决这一问题的有效方法。EAGLE方法通过在特征级别进行自回归，并复用目标模型的顶层特征，实现了比普通推测采样更优的结果。近年来，LLM社区逐渐形成了一种趋势，即通过扩大训练数据规模来提升模型智能，而无需增加推理成本。然而，我们发现对于EAGLE而言，单纯扩大数据规模只能带来有限的改进。我们发现，这一局限性源于EAGLE在特征预测方面的固有限制。在本文中，我们提出了EAGLE-3，该方法放弃了特征预测，转而直接进行令牌预测，并通过一种名为“训练时测试”的技术，用多层特征融合替代了对顶层特征的依赖。这些改进显著提升了模型性能，使基础模型能够充分受益于训练数据规模的扩大。我们的实验涵盖了聊天模型和推理模型，并在五个任务上进行了评估。结果表明，EAGLE-3的加速比最高可达6.5倍，相比EAGLE-2提升了约1.4倍。代码可在https://github.com/SafeAILab/EAGLE获取。

> The sequential nature of modern LLMs makes them expensive and slow, and speculative sampling has proven to be an effective solution to this problem. Methods like EAGLE perform autoregression at the feature level, reusing top-layer features from the target model to achieve better results than vanilla speculative sampling. A growing trend in the LLM community is scaling up training data to improve model intelligence without increasing inference costs. However, we observe that scaling up data provides limited improvements for EAGLE. We identify that this limitation arises from EAGLE's feature prediction constraints. In this paper, we introduce EAGLE-3, which abandons feature prediction in favor of direct token prediction and replaces reliance on top-layer features with multi-layer feature fusion via a technique named training-time test. These improvements significantly enhance performance and enable the draft model to fully benefit from scaling up training data. Our experiments include both chat models and reasoning models, evaluated on five tasks. The results show that EAGLE-3 achieves a speedup ratio up to 6.5x, with about 1.4x improvement over EAGLE-2. The code is available at https://github.com/SafeAILab/EAGLE.

[Arxiv](https://arxiv.org/abs/2503.01840)