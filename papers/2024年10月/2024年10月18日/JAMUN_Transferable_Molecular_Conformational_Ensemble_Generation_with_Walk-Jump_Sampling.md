# JAMUN：利用 Walk-Jump 采样生成可迁移的分子构象集合

发布时间：2024年10月18日

`其他

理由：这篇论文主要讨论的是蛋白质构象集合的采样技术，属于生物信息学或计算化学领域，与Agent、RAG、LLM应用、LLM理论等分类无关。因此，将其归类为其他。` `生物医药` `蛋白质科学`

> JAMUN: Transferable Molecular Conformational Ensemble Generation with Walk-Jump Sampling

# 摘要

> 摘要：蛋白质构象集合在理解蛋白质功能及新型药物发现（如隐秘口袋）中至关重要。然而，现有采样技术效率低下，且难以泛化到训练数据之外的系统。我们提出了JAMUN（walk-Jump Accelerated Molecular ensembles with Universal Noise），旨在高效采样任意蛋白质的玻尔兹曼分布。通过将Walk-Jump Sampling扩展至点云，JAMUN能以远超传统分子动力学和前沿机器学习方法的速度生成构象集合。此外，JAMUN还能预测训练中未见的小肽稳定盆地。

> 
Abstract:Conformational ensembles of protein structures are immensely important both to understanding protein function, and for drug discovery in novel modalities such as cryptic pockets. Current techniques for sampling ensembles are computationally inefficient, or do not transfer to systems outside their training data. We present walk-Jump Accelerated Molecular ensembles with Universal Noise (JAMUN), a step towards the goal of efficiently sampling the Boltzmann distribution of arbitrary proteins. By extending Walk-Jump Sampling to point clouds, JAMUN enables ensemble generation at orders of magnitude faster rates than traditional molecular dynamics or state-of-the-art ML methods. Further, JAMUN is able to predict the stable basins of small peptides that were not seen during training.
    

[Arxiv](https://arxiv.org/pdf/2410.14621)