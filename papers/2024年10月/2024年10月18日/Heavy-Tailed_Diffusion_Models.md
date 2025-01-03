# 重尾扩散模型

发布时间：2024年10月18日

`其他

理由：这篇论文主要讨论的是扩散模型在重尾分布中的应用，特别是如何改进扩散模型以更好地捕捉罕见或极端事件。虽然涉及生成模型，但内容主要集中在扩散模型的理论和应用改进上，与LLM（大型语言模型）、Agent（智能体）、RAG（检索增强生成）等分类关系不大。因此，将其归类为“其他”更为合适。` `生成模型`

> Heavy-Tailed Diffusion Models

# 摘要

> # 摘要
扩散模型在众多应用中展现了卓越的生成质量，但其捕捉重尾分布中罕见或极端事件的能力尚不明确。本文揭示，传统的高斯先验扩散和流匹配模型难以捕捉重尾行为。为此，我们创新性地将扩散框架应用于重尾估计，采用多元学生t分布。我们设计了专用扰动核，并基于条件学生t分布推导了反向过程的去噪后验。受重尾分布的$\gamma$-散度启发，我们提出了重尾去噪器的训练目标。该框架仅需一个标量超参数即可实现可控尾部生成，便于适应多样化的现实分布。作为框架的具体实现，我们提出了t-EDM和t-Flow，它们是现有扩散和流模型的扩展，采用学生t先验。值得注意的是，我们的方法与标准高斯扩散模型无缝兼容，且代码改动极小。实验证明，在高分辨率天气数据集上，t-EDM和t-Flow在重尾估计中表现优异，尤其在生成罕见和极端事件方面至关重要。

> 
Abstract:Diffusion models achieve state-of-the-art generation quality across many applications, but their ability to capture rare or extreme events in heavy-tailed distributions remains unclear. In this work, we show that traditional diffusion and flow-matching models with standard Gaussian priors fail to capture heavy-tailed behavior. We address this by repurposing the diffusion framework for heavy-tail estimation using multivariate Student-t distributions. We develop a tailored perturbation kernel and derive the denoising posterior based on the conditional Student-t distribution for the backward process. Inspired by $\gamma$-divergence for heavy-tailed distributions, we derive a training objective for heavy-tailed denoisers. The resulting framework introduces controllable tail generation using only a single scalar hyperparameter, making it easily tunable for diverse real-world distributions. As specific instantiations of our framework, we introduce t-EDM and t-Flow, extensions of existing diffusion and flow models that employ a Student-t prior. Remarkably, our approach is readily compatible with standard Gaussian diffusion models and requires only minimal code changes. Empirically, we show that our t-EDM and t-Flow outperform standard diffusion models in heavy-tail estimation on high-resolution weather datasets in which generating rare and extreme events is crucial.
    

[Arxiv](https://arxiv.org/pdf/2410.14171)