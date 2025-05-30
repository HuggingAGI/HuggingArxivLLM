# DenoiseRotator：通过重要性集中提升大型语言模型的剪枝鲁棒性

发布时间：2025年05月28日

`LLM理论`

> DenoiseRotator: Enhance Pruning Robustness for LLMs via Importance Concentration

# 摘要

> 剪枝技术是压缩大型语言模型（LLMs）的常用方法，通过去除不重要的权重来实现模型瘦身。然而，这种方法往往会导致性能大幅下降，特别是在半结构化稀疏性约束下。现有剪枝方法主要关注于评估单个权重的重要性，这限制了它们在保留模型关键能力方面的效果。在本研究中，我们提出了一个全新视角：与其只专注于选择哪些权重要剪枝，不如先重新分配参数的重要性，使模型本身更易于剪枝。通过最小化归一化重要性分数的信息熵，我们的方法将重要性集中在较少的权重上，从而显著提升了剪枝的鲁棒性。我们通过DenoiseRotator实现了这一思路，该方法对模型的权重矩阵应用可学习的正交变换。我们的方法具有通用性，能够无缝集成到现有剪枝技术（如Magnitude、SparseGPT和Wanda）中。在LLaMA3、Qwen2.5和Mistral模型上进行的50%无结构和2:4半结构化稀疏性条件下测试表明，DenoiseRotator始终能改善困惑度和零样本准确性。例如，在LLaMA3-70B模型上应用SparseGPT进行2:4半结构化剪枝时，DenoiseRotator将困惑度与密集模型的差距缩小了58%，将性能下降幅度从8.1降至3.4点。代码可在https://github.com/Axel-gu/DenoiseRotator获取。

> Pruning is a widely used technique to compress large language models (LLMs) by removing unimportant weights, but it often suffers from significant performance degradation - especially under semi-structured sparsity constraints. Existing pruning methods primarily focus on estimating the importance of individual weights, which limits their ability to preserve critical capabilities of the model. In this work, we propose a new perspective: rather than merely selecting which weights to prune, we first redistribute parameter importance to make the model inherently more amenable to pruning. By minimizing the information entropy of normalized importance scores, our approach concentrates importance onto a smaller subset of weights, thereby enhancing pruning robustness. We instantiate this idea through DenoiseRotator, which applies learnable orthogonal transformations to the model's weight matrices. Our method is model-agnostic and can be seamlessly integrated with existing pruning techniques such as Magnitude, SparseGPT, and Wanda. Evaluated on LLaMA3, Qwen2.5, and Mistral models under 50% unstructured and 2:4 semi-structured sparsity, DenoiseRotator consistently improves perplexity and zero-shot accuracy. For instance, on LLaMA3-70B pruned with SparseGPT at 2:4 semi-structured sparsity, DenoiseRotator reduces the perplexity gap to the dense model by 58%, narrowing the degradation from 8.1 to 3.4 points. Codes are available at https://github.com/Axel-gu/DenoiseRotator.

[Arxiv](https://arxiv.org/abs/2505.23049)