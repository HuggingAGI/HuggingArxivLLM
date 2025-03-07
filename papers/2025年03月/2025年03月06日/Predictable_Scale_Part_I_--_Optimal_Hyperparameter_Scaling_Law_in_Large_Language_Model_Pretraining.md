# # 可预测的规模：第一部分——大型语言模型预训练中的最优超参数缩放法则

发布时间：2025年03月06日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的超参数优化，分析了学习率和批量大小与模型参数量和数据规模之间的关系，揭示了超参数优化的规律，并开发了一个通用的超参数优化工具。这些内容属于LLM的理论研究，特别是关于模型训练和优化的理论分析。` `机器学习`

> Predictable Scale: Part I -- Optimal Hyperparameter Scaling Law in Large Language Model Pretraining

# 摘要

> 大型语言模型（LLMs）在各类任务中的卓越能力已得到充分验证，但其有效部署仍需谨慎的超参数优化。通过广泛涵盖多种配置的网格搜索实证研究，我们发现了这些超参数的普适性扩展规律：最优学习率与模型参数量和数据规模均呈幂律关系，而最优批量大小则主要随数据规模增长。我们的分析表明，在固定模型和数据规模条件下，超参数的优化景观呈现凸性特征，这意味着存在一个超参数最优平台期。我们为社区贡献了一款通用且即插即用的最优超参数工具，其在测试集上的估计值与通过穷举搜索发现的全局最优LLM性能仅相差0.07%。这些规律在模型稀疏性、训练数据分布和模型形态的变化下展现出显著的鲁棒性。据我们所知，这是首个统一不同模型形态和结构（如专家混合模型和密集Transformer）并建立在各类数据分布下最优超参数扩展规律的研究。这一全面优化过程耗用了近一百万小时的NVIDIA H800 GPU计算资源，从零开始训练了3,700个不同规模和超参数的LLMs，并消耗了总计约10万亿个token。为了促进可重复性和进一步研究，我们将逐步通过指定仓库https://step-law.github.io/发布所有损失测量值和模型检查点。

> The impressive capabilities of Large Language Models (LLMs) across diverse tasks are now well-established, yet their effective deployment necessitates careful hyperparameter optimization. Through extensive empirical studies involving grid searches across diverse configurations, we discover universal scaling laws governing these hyperparameters: optimal learning rate follows a power-law relationship with both model parameters and data sizes, while optimal batch size scales primarily with data sizes. Our analysis reveals a convex optimization landscape for hyperparameters under fixed models and data size conditions. This convexity implies an optimal hyperparameter plateau. We contribute a universal, plug-and-play optimal hyperparameter tool for the community. Its estimated values on the test set are merely 0.07\% away from the globally optimal LLM performance found via an exhaustive search. These laws demonstrate remarkable robustness across variations in model sparsity, training data distribution, and model shape. To our best known, this is the first work that unifies different model shapes and structures, such as Mixture-of-Experts models and dense transformers, as well as establishes optimal hyperparameter scaling laws across diverse data distributions. This exhaustive optimization process demands substantial computational resources, utilizing nearly one million NVIDIA H800 GPU hours to train 3,700 LLMs of varying sizes and hyperparameters from scratch and consuming approximately 100 trillion tokens in total. To facilitate reproducibility and further research, we will progressively release all loss measurements and model checkpoints through our designated repository https://step-law.github.io/

[Arxiv](https://arxiv.org/abs/2503.04715)