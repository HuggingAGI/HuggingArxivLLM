# 面向大型语言模型的强健4位量化的异常安全预训练方案。

发布时间：2025年06月24日

`LLM理论

摘要讨论了大型语言模型中的异常值问题，并提出了一种新的预训练方法（OSP）来解决这些问题，这属于模型训练和优化的理论层面，因此归类为LLM理论。` `人工智能` `机器学习`

> Outlier-Safe Pre-Training for Robust 4-Bit Quantization of Large Language Models

# 摘要

> 大型语言模型中的极端激活异常值严重损害量化性能，阻碍了高效设备端部署的实现。尽管通道级操作和自适应梯度缩放被认为是主要原因，但实际缓解仍然具有挑战性。我们引入了异常安全预训练（OSP），这是一种实用的指南，旨在主动预防异常值的形成，而非依赖事后缓解措施。OSP融合了三大关键创新：(1) Muon 优化器，在消除特权基的同时保持训练效率；(2) 单尺度 RMS 归一化，防止通道级放大；(3) 可学习的嵌入投影，重新分配源自嵌入矩阵的激活幅度。我们通过训练一个包含14亿参数的模型并使用1万亿个token进行验证，这是首个未出现此类异常值的生产规模大型语言模型。在激进的4位量化下，我们的OSP模型在10个基准测试中平均得分35.7（相比之下，Adam训练的模型得分为26.5），仅增加了2%的训练开销。值得注意的是，OSP模型的超额峰度接近零（0.04），而标准模型中存在极端值（1818.56），这从根本上改变了大型语言模型的量化行为。我们的研究表明，异常值并非大型语言模型的固有特性，而是训练策略的结果，为更高效的模型部署铺平了道路。源代码和预训练检查点可在以下地址获取：访问地址：https://github.com/dmis-lab/Outlier-Safe-Pre-Training。

> Extreme activation outliers in Large Language Models (LLMs) critically degrade quantization performance, hindering efficient on-device deployment. While channel-wise operations and adaptive gradient scaling are recognized causes, practical mitigation remains challenging. We introduce Outlier-Safe Pre-Training (OSP), a practical guideline that proactively prevents outlier formation rather than relying on post-hoc mitigation. OSP combines three key innovations: (1) the Muon optimizer, eliminating privileged bases while maintaining training efficiency; (2) Single-Scale RMSNorm, preventing channel-wise amplification; and (3) a learnable embedding projection, redistributing activation magnitudes originating from embedding matrices. We validate OSP by training a 1.4B-parameter model on 1 trillion tokens, which is the first production-scale LLM trained without such outliers. Under aggressive 4-bit quantization, our OSP model achieves a 35.7 average score across 10 benchmarks (compared to 26.5 for an Adam-trained model), with only a 2% training overhead. Remarkably, OSP models exhibit near-zero excess kurtosis (0.04) compared to extreme values (1818.56) in standard models, fundamentally altering LLM quantization behavior. Our work demonstrates that outliers are not inherent to LLMs but are consequences of training strategies, paving the way for more efficient LLM deployment. The source code and pretrained checkpoints are available at https://github.com/dmis-lab/Outlier-Safe-Pre-Training.

[Arxiv](https://arxiv.org/abs/2506.19697)