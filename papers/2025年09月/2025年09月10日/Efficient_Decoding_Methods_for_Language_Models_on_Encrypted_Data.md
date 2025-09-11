# 加密数据上语言模型的高效解码方法

发布时间：2025年09月10日

`LLM应用` `基础理论`

> Efficient Decoding Methods for Language Models on Encrypted Data

# 摘要

> 大型语言模型（LLMs）是现代AI应用的核心驱动力，但在不可信服务器上处理敏感数据会引发隐私问题。同态加密（HE）能够对加密数据进行计算，从而实现安全推理。然而，神经文本生成需要argmax和采样等解码方法，这些方法是非多项式的，因此在加密状态下计算成本极高，形成了严重的性能瓶颈。我们提出了cutmax——一种HE友好型argmax算法，与现有方法相比减少了密文操作，可在加密状态下实现实用的贪婪解码。我们还首次提出了HE兼容的nucleus（top-p）采样方法，借助cutmax实现高效的随机解码，并提供可证明的隐私保障。这两种技术均为多项式算法，支持在隐私保护场景下进行高效推理。此外，它们的可微性有助于实现基于梯度的序列级优化，成为直通估计器的多项式替代方案。我们还为cutmax提供了坚实的理论保证，证明其全局收敛到唯一的两级不动点，且收敛性与最大化元素身份之外的输入值无关，这也解释了为何它仅需几次迭代就能快速收敛。在真实LLM输出上的评估表明，与基线方法相比，延迟降低了24倍至35倍，为安全文本生成领域带来了重要进展。

> Large language models (LLMs) power modern AI applications, but processing sensitive data on untrusted servers raises privacy concerns. Homomorphic encryption (HE) enables computation on encrypted data for secure inference. However, neural text generation requires decoding methods like argmax and sampling, which are non-polynomial and thus computationally expensive under encryption, creating a significant performance bottleneck. We introduce cutmax, an HE-friendly argmax algorithm that reduces ciphertext operations compared to prior methods, enabling practical greedy decoding under encryption. We also propose the first HE-compatible nucleus (top-p) sampling method, leveraging cutmax for efficient stochastic decoding with provable privacy guarantees. Both techniques are polynomial, supporting efficient inference in privacy-preserving settings. Moreover, their differentiability facilitates gradient-based sequence-level optimization as a polynomial alternative to straight-through estimators. We further provide strong theoretical guarantees for cutmax, proving it converges globally to a unique two-level fixed point, independent of the input values beyond the identity of the maximizer, which explains its rapid convergence in just a few iterations. Evaluations on realistic LLM outputs show latency reductions of 24x-35x over baselines, advancing secure text generation.

[Arxiv](https://arxiv.org/abs/2509.08383)