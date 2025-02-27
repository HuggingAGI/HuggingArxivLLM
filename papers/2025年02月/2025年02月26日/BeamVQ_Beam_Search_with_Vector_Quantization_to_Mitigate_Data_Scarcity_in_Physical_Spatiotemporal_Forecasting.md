# BeamVQ：通过向量量化优化束搜索，缓解物理时空预测中的数据稀缺性

发布时间：2025年02月26日

`LLM应用`

> BeamVQ: Beam Search with Vector Quantization to Mitigate Data Scarcity in Physical Spatiotemporal Forecasting

# 摘要

> 在实际应用中，物理时空预测常常面临数据稀缺的挑战，尤其是极端事件的数据收集难度更大。因此，我们提出了一种创新的概率框架，通过迭代自训练和新型自集成策略，显著提升了在极端事件预测中的物理一致性和泛化能力。该框架在任何基础预测模型之后，将模型的确定性输出编码到潜在空间，并通过检索多个代码本条目生成概率输出。BeamVQ 进一步将束搜索从离散空间扩展到连续状态空间。我们采用领域特定的评估指标（如极端事件的临界成功指数）筛选出最优候选，并结合高质量候选开发新型自集成策略。这种自集成方法不仅提升了推理的准确性和鲁棒性，还在持续自训练过程中不断优化训练数据集。因此，BeamVQ 能够探索数据集之外罕见但关键的物理现象。在多个基准和主干模型上的全面实验表明，BeamVQ 有效降低了预测均方误差（最高达 39%），显著提升了极端事件检测能力，充分证明了其在应对数据稀缺问题上的卓越效果。

> In practice, physical spatiotemporal forecasting can suffer from data scarcity, because collecting large-scale data is non-trivial, especially for extreme events. Hence, we propose \method{}, a novel probabilistic framework to realize iterative self-training with new self-ensemble strategies, achieving better physical consistency and generalization on extreme events. Following any base forecasting model, we can encode its deterministic outputs into a latent space and retrieve multiple codebook entries to generate probabilistic outputs. Then BeamVQ extends the beam search from discrete spaces to the continuous state spaces in this field. We can further employ domain-specific metrics (e.g., Critical Success Index for extreme events) to filter out the top-k candidates and develop the new self-ensemble strategy by combining the high-quality candidates. The self-ensemble can not only improve the inference quality and robustness but also iteratively augment the training datasets during continuous self-training. Consequently, BeamVQ realizes the exploration of rare but critical phenomena beyond the original dataset. Comprehensive experiments on different benchmarks and backbones show that BeamVQ consistently reduces forecasting MSE (up to 39%), enhancing extreme events detection and proving its effectiveness in handling data scarcity.

[Arxiv](https://arxiv.org/abs/2502.18925)