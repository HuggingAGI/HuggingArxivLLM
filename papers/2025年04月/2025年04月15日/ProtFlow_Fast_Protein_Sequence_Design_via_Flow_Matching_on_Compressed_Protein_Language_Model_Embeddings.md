# ProtFlow：基于流匹配技术，利用压缩的蛋白质语言模型嵌入实现快速蛋白质序列设计

发布时间：2025年04月15日

`LLM应用` `生物技术`

> ProtFlow: Fast Protein Sequence Design via Flow Matching on Compressed Protein Language Model Embeddings

# 摘要

> 蛋白质工程中设计具有特定功能的蛋白质序列是一项基础性任务。深度生成方法，如自回归模型和扩散模型，极大推动了新型蛋白质序列的发现。然而，这些方法主要关注局部或浅层的残余语义，并在推理效率、模型空间规模和训练成本方面面临挑战。为了解决这些问题，我们开发了ProtFlow——一个基于流匹配框架的蛋白质序列设计系统。该系统利用蛋白质语言模型中语义丰富的潜在空间进行序列设计。通过压缩和优化潜在空间，ProtFlow在有限计算资源下提升设计效能。借助重流技术，ProtFlow实现了高质量的单步序列生成。此外，我们还开发了一个联合设计流程，专门针对多链蛋白质的设计场景。我们在多种蛋白质设计任务中评估了ProtFlow，包括普通肽、长链蛋白质、抗菌肽和抗体等。实验结果表明，ProtFlow在这些应用场景中超越了专门针对特定任务的方法，凸显了其在计算蛋白质序列设计与分析中的潜力和广泛应用前景。

> The design of protein sequences with desired functionalities is a fundamental task in protein engineering. Deep generative methods, such as autoregressive models and diffusion models, have greatly accelerated the discovery of novel protein sequences. However, these methods mainly focus on local or shallow residual semantics and suffer from low inference efficiency, large modeling space and high training cost. To address these challenges, we introduce ProtFlow, a fast flow matching-based protein sequence design framework that operates on embeddings derived from semantically meaningful latent space of protein language models. By compressing and smoothing the latent space, ProtFlow enhances performance while training on limited computational resources. Leveraging reflow techniques, ProtFlow enables high-quality single-step sequence generation. Additionally, we develop a joint design pipeline for the design scene of multichain proteins. We evaluate ProtFlow across diverse protein design tasks, including general peptides and long-chain proteins, antimicrobial peptides, and antibodies. Experimental results demonstrate that ProtFlow outperforms task-specific methods in these applications, underscoring its potential and broad applicability in computational protein sequence design and analysis.

[Arxiv](https://arxiv.org/abs/2504.10983)