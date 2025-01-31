# 低比特大型语言模型的混合精度图神经量化

发布时间：2025年01月30日

`LLM理论

理由：这篇论文主要讨论了在资源受限环境中部署大型语言模型（LLMs）时，如何通过训练后量化（PTQ）来减少资源需求。论文提出了一种新的混合精度图神经PTQ（MG-PTQ）方法，利用图神经网络（GNN）模块来捕捉权重之间的依赖关系，并自适应地分配量化比特宽度。这种方法在低比特宽度下显著提高了量化性能。由于论文的核心内容集中在LLMs的量化技术和理论改进上，因此将其分类为LLM理论。` `模型压缩`

> Mixed-Precision Graph Neural Quantization for Low Bit Large Language Models

# 摘要

> # 摘要
训练后量化（PTQ）在资源受限的环境中部署大型语言模型（LLMs）至关重要，因为它显著减少了资源需求。然而，现有的PTQ策略在低于3比特的低比特水平下表现不佳，这是由于量化权重与原始权重之间的显著差异。为了在低比特宽度下提高量化性能，我们引入了一种混合精度图神经PTQ（MG-PTQ）方法，采用图神经网络（GNN）模块来捕捉权重之间的依赖关系，并自适应地分配量化比特宽度。通过GNN模块的信息传播，我们的方法更有效地捕捉目标权重之间的依赖关系，从而更准确地评估权重重要性并优化量化策略的分配。在WikiText2和C4数据集上的大量实验表明，我们的MG-PTQ方法优于之前最先进的PTQ方法GPTQ，为低比特条件下的量化性能设定了新的基准。

> Post-Training Quantization (PTQ) is pivotal for deploying large language models (LLMs) within resource-limited settings by significantly reducing resource demands. However, existing PTQ strategies underperform at low bit levels < 3 bits due to the significant difference between the quantized and original weights. To enhance the quantization performance at low bit widths, we introduce a Mixed-precision Graph Neural PTQ (MG-PTQ) approach, employing a graph neural network (GNN) module to capture dependencies among weights and adaptively assign quantization bit-widths. Through the information propagation of the GNN module, our method more effectively captures dependencies among target weights, leading to a more accurate assessment of weight importance and optimized allocation of quantization strategies. Extensive experiments on the WikiText2 and C4 datasets demonstrate that our MG-PTQ method outperforms previous state-of-the-art PTQ method GPTQ, setting new benchmarks for quantization performance under low-bit conditions.

[Arxiv](https://arxiv.org/abs/2501.18154)