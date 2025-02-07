# 通过噪声注入提升幻觉检测能力

发布时间：2025年02月06日

`LLM理论

理由：该论文主要探讨了大型语言模型（LLMs）生成“幻觉”的问题，并提出了一种基于贝叶斯不确定性的方法来检测幻觉。这涉及到对LLMs内部机制和理论的研究，属于对LLMs的理论分析和改进，因此归类为“LLM理论”。` `模型安全`

> Enhancing Hallucination Detection through Noise Injection

# 摘要

> 大型语言模型（LLMs）容易生成看似合理但错误的回答，即“幻觉”。有效检测幻觉对LLMs的安全部署至关重要。最近研究表明，幻觉与模型不确定性相关，通过测量从模型抽取的样本答案分布的离散度可以检测幻觉。然而，直接从token分布中采样并非最优方法。我们提出了一种基于贝叶斯不确定性的高效方法，通过扰动模型参数或隐藏单元激活来显著提升检测效果，并在多个数据集和模型架构上验证了其有效性。

> Large Language Models (LLMs) are prone to generating plausible yet incorrect responses, known as hallucinations. Effectively detecting hallucinations is therefore crucial for the safe deployment of LLMs. Recent research has linked hallucinations to model uncertainty, suggesting that hallucinations can be detected by measuring dispersion over answer distributions obtained from a set of samples drawn from a model. While drawing from the distribution over tokens defined by the model is a natural way to obtain samples, in this work, we argue that it is sub-optimal for the purpose of detecting hallucinations. We show that detection can be improved significantly by taking into account model uncertainty in the Bayesian sense. To this end, we propose a very simple and efficient approach that perturbs an appropriate subset of model parameters, or equivalently hidden unit activations, during sampling. We demonstrate its effectiveness across a wide range of datasets and model architectures.

[Arxiv](https://arxiv.org/abs/2502.03799)