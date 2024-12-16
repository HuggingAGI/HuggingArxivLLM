# 基于残差向量量化令牌的高效生成式建模

发布时间：2024年12月13日

`其他` `图像生成` `语音合成`

> Efficient Generative Modeling with Residual Vector Quantization-Based Tokens

# 摘要

> 我们探究在向量量化生成模型中运用残差向量量化（RVQ）实现高保真生成。此量化技术借助更深入的令牌来维持更高的数据保真度。然而，生成模型中令牌数量的增加会致使推理速度减缓。为此，我们推出了 ResGen，这是一种基于高效 RVQ 的离散扩散模型，能在不影响采样速度的前提下生成高保真样本。我们的核心思路是直接预测集体令牌而非单个令牌的向量嵌入。另外，我们证实所提出的令牌掩码和多令牌预测方法能够在一个原则性的概率框架内，通过离散扩散过程和变分推理来构建。我们在不同模态的两项颇具挑战的任务中验证了所提方法的有效性和通用性：ImageNet 256x256 上的条件图像生成以及零样本文本到语音合成。实验结果表明，ResGen 在这两项任务中均优于自回归对应模型，在不牺牲采样速度的情况下展现出卓越性能。而且，当我们拓展 RVQ 的深度时，与规模相同的基线模型相比，我们的生成模型要么生成保真度更高，要么采样速度更快。项目页面可在 https://resgen-genai.github.io 查看。

> We explore the use of Residual Vector Quantization (RVQ) for high-fidelity generation in vector-quantized generative models. This quantization technique maintains higher data fidelity by employing more in-depth tokens. However, increasing the token number in generative models leads to slower inference speeds. To this end, we introduce ResGen, an efficient RVQ-based discrete diffusion model that generates high-fidelity samples without compromising sampling speed. Our key idea is a direct prediction of vector embedding of collective tokens rather than individual ones. Moreover, we demonstrate that our proposed token masking and multi-token prediction method can be formulated within a principled probabilistic framework using a discrete diffusion process and variational inference. We validate the efficacy and generalizability of the proposed method on two challenging tasks across different modalities: conditional image generation} on ImageNet 256x256 and zero-shot text-to-speech synthesis. Experimental results demonstrate that ResGen outperforms autoregressive counterparts in both tasks, delivering superior performance without compromising sampling speed. Furthermore, as we scale the depth of RVQ, our generative models exhibit enhanced generation fidelity or faster sampling speeds compared to similarly sized baseline models. The project page can be found at https://resgen-genai.github.io

[Arxiv](https://arxiv.org/abs/2412.10208)