# HessFormer：探索基础模型规模下的Hessian矩阵

发布时间：2025年05月16日

`LLM理论` `人工智能`

> HessFormer: Hessians at Foundation Scale

# 摘要

> 尽管深度学习模型的一阶优化领域取得了重大进展，其中最先进的开源专家混合模型已达到数百亿参数级别，但基于Hessian向量乘积的方法仍受限于单GPU运行，无法处理十亿级别参数的模型。我们发布了	extbf{HessFormer}软件包，它与Transformers包完美集成，并支持多GPU环境下的分布式Hessian向量计算。我们的实现基于分布式随机Lanczos正交算法，已公开发布。利用此软件包，我们深入研究了Deepseek 700亿参数模型的Hessian谱密度。

> Whilst there have been major advancements in the field of first order optimisation of deep learning models, where state of the art open source mixture of expert models go into the hundreds of billions of parameters, methods that rely on Hessian vector products, are still limited to run on a single GPU and thus cannot even work for models in the billion parameter range. We release a software package \textbf{HessFormer}, which integrates nicely with the well known Transformers package and allows for distributed hessian vector computation across a single node with multiple GPUs. Underpinning our implementation is a distributed stochastic lanczos quadrature algorithm, which we release for public consumption. Using this package we investigate the Hessian spectral density of the recent Deepseek $70$bn parameter model.

[Arxiv](https://arxiv.org/abs/2505.11564)