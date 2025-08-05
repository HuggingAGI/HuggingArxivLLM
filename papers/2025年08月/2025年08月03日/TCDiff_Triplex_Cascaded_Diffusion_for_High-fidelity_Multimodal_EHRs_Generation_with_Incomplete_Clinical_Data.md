# TCDiff: 基于三重级联扩散模型的高保真多模态电子健康记录生成技术（适用于不完整临床数据）

发布时间：2025年08月03日

`其他

摘要主要讨论了生成高质量电子健康记录（EHRs）的方法，特别是针对传统中医的研究，使用扩散网络生成数据，属于数据生成和医疗信息处理领域，不属于前四个分类中的任何一个。`

> TCDiff: Triplex Cascaded Diffusion for High-fidelity Multimodal EHRs Generation with Incomplete Clinical Data

# 摘要

> 大规模、高质量电子健康记录（EHRs）的匮乏仍是生物医学研究的主要瓶颈，尤其在大型基础模型日益依赖海量数据的今天。合成大量去标识化且高保真的数据成为突破这一瓶颈的希望所在。然而，现有方法在处理异构多模态EHR数据时面临多重挑战：难以准确建模数据的内在特性，捕捉各模态间的复杂关联，以及有效应对数据不完整性。这些问题在传统中医（TCM）研究中尤为突出。针对这些挑战，我们提出了TCDiff（Triplex Cascaded Diffusion Network），一个创新的EHR生成框架。该框架通过级联三个扩散网络，构建了一个包含参考模态扩散、跨模态桥梁和目标模态扩散的多阶段生成流程，深入学习真实世界EHR数据的特征。此外，为验证TCDiff的效能，我们不仅采用了两个公开数据集，还特别构建并引入了TCM-SZ1——一个专为基准测试设计的多模态EHR数据集。实验结果表明，在不同缺失率下，TCDiff的数据保真度平均领先现有最先进方法10%，同时在隐私保护方面也表现优异。这充分证明了TCDiff在真实医疗场景中的有效性、稳健性和广泛适用性。

> The scarcity of large-scale and high-quality electronic health records (EHRs) remains a major bottleneck in biomedical research, especially as large foundation models become increasingly data-hungry. Synthesizing substantial volumes of de-identified and high-fidelity data from existing datasets has emerged as a promising solution. However, existing methods suffer from a series of limitations: they struggle to model the intrinsic properties of heterogeneous multimodal EHR data (e.g., continuous, discrete, and textual modalities), capture the complex dependencies among them, and robustly handle pervasive data incompleteness. These challenges are particularly acute in Traditional Chinese Medicine (TCM). To this end, we propose TCDiff (Triplex Cascaded Diffusion Network), a novel EHR generation framework that cascades three diffusion networks to learn the features of real-world EHR data, formatting a multi-stage generative process: Reference Modalities Diffusion, Cross-Modal Bridging, and Target Modality Diffusion. Furthermore, to validate our proposed framework, besides two public datasets, we also construct and introduce TCM-SZ1, a novel multimodal EHR dataset for benchmarking. Experimental results show that TCDiff consistently outperforms state-of-the-art baselines by an average of 10% in data fidelity under various missing rate, while maintaining competitive privacy guarantees. This highlights the effectiveness, robustness, and generalizability of our approach in real-world healthcare scenarios.

[Arxiv](https://arxiv.org/abs/2508.01615)