# 驾驭多义性在大型语言模型中的表现：利用稀疏自动编码器实现特征的可证明恢复

发布时间：2025年06月16日

`LLM理论` `机器学习`

> Taming Polysemanticity in LLMs: Provable Feature Recovery via Sparse Autoencoders

# 摘要

> 我们研究了利用稀疏自动编码器（SAEs）实现理论上可靠的特征恢复，以解释大型语言模型。现有的SAE训练算法缺乏严格的数学保证，且存在超参数敏感性和不稳定等实际问题。为了解决这些挑战，我们首先提出了一种新的统计框架，用于特征恢复问题。该框架通过将多义特征建模为潜在单义概念的稀疏混合物，定义了特征可识别性。基于此框架，我们引入了一种基于``偏差适应''的新型SAE训练算法。该算法通过自适应调整神经网络的偏差参数，确保适当的激活稀疏性。我们从理论上证明，当输入数据采样自我们提出的统计模型时，该算法能够正确恢复所有单义特征。此外，我们开发了一个改进的实践经验变体——组偏差适应（GBA）。实验结果表明，当应用于具有多达15亿参数的大型语言模型时，GBA的性能优于现有基准方法。这项工作通过提供首个具有理论恢复保证的SAE算法，为解开SAE训练的奥秘奠定了基础。这将推动更透明和可信的人工智能系统的发展，通过增强机制可解释性，使AI系统更加可靠和值得信赖。

> We study the challenge of achieving theoretically grounded feature recovery using Sparse Autoencoders (SAEs) for the interpretation of Large Language Models. Existing SAE training algorithms often lack rigorous mathematical guarantees and suffer from practical limitations such as hyperparameter sensitivity and instability. To address these issues, we first propose a novel statistical framework for the feature recovery problem, which includes a new notion of feature identifiability by modeling polysemantic features as sparse mixtures of underlying monosemantic concepts. Building on this framework, we introduce a new SAE training algorithm based on ``bias adaptation'', a technique that adaptively adjusts neural network bias parameters to ensure appropriate activation sparsity. We theoretically \highlight{prove that this algorithm correctly recovers all monosemantic features} when input data is sampled from our proposed statistical model. Furthermore, we develop an improved empirical variant, Group Bias Adaptation (GBA), and \highlight{demonstrate its superior performance against benchmark methods when applied to LLMs with up to 1.5 billion parameters}. This work represents a foundational step in demystifying SAE training by providing the first SAE algorithm with theoretical recovery guarantees, thereby advancing the development of more transparent and trustworthy AI systems through enhanced mechanistic interpretability.

[Arxiv](https://arxiv.org/abs/2506.14002)