# # 大型语言模型中的金字塔向量量化

发布时间：2024年10月22日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLM）的量化技术，特别是通过重新参数化架构和金字塔向量量化（PVQ）来优化量化过程。这些技术涉及到LLM的底层理论和方法，旨在提高模型的效率和性能，而不涉及具体的应用场景或代理（Agent）的实现。因此，这篇论文更适合归类为“LLM理论”。` `机器学习` `量化技术`

> Pyramid Vector Quantization for LLMs

# 摘要

> # 摘要
最近的研究通过重新参数化架构，将大型语言模型（LLM）的权重分布在球面上，显著提升了量化能力，减少了权重异常值且不影响网络输出。本研究进一步利用权重的球面几何特性，采用金字塔向量量化（PVQ）进行量化。在高维空间中，均匀分布球面上的点极为困难，且近似解通常无法在代码本中显式表示。PVQ通过将点投影到1-球面上，使用固定整数格点，实现了高效编码和解码，无需显式存储代码本。我们提出将PVQ与尺度量化结合，并在经验验证的假设下推导出理论上最优的量化。此外，我们扩展了PVQ，利用Hessian信息在预期特征激活下最小化量化误差，而不仅依赖权重大小。实验表明，与现有方法相比，我们在性能和每权重比特数及每激活比特数之间实现了帕累托最优的权衡，达到了最先进的量化性能。在仅量化权重的情况下，Llama-3 70B模型可量化为每权重3.25比特，并在下游任务中保持98%的准确率。

> Recent works on compression of large language models (LLM) using quantization considered reparameterizing the architecture such that weights are distributed on the sphere. This demonstratively improves the ability to quantize by increasing the mathematical notion of coherence, resulting in fewer weight outliers without affecting the network output. In this work, we aim to further exploit this spherical geometry of the weights when performing quantization by considering Pyramid Vector Quantization (PVQ) for large language models. Arranging points evenly on the sphere is notoriously difficult, especially in high dimensions, and in case approximate solutions exists, representing points explicitly in a codebook is typically not feasible due to its additional memory cost. Instead, PVQ uses a fixed integer lattice on the sphere by projecting points onto the 1-sphere, which allows for efficient encoding and decoding without requiring an explicit codebook in memory. To obtain a practical algorithm, we propose to combine PVQ with scale quantization for which we derive theoretically optimal quantizations, under empirically verified assumptions. Further, we extend pyramid vector quantization to use Hessian information to minimize quantization error under expected feature activations, instead of only relying on weight magnitudes. Experimentally, we achieves state-of-the-art quantization performance with pareto-optimal trade-off between performance and bits per weight and bits per activation, compared to compared methods. On weight-only, we find that we can quantize a Llama-3 70B model to 3.25 bits per weight and retain 98\% accuracy on downstream tasks.

[Arxiv](https://arxiv.org/abs/2410.16926)