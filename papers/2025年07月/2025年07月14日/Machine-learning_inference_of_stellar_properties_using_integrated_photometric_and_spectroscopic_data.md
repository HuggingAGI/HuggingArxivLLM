# 通过综合光度和光谱数据，利用机器学习方法推断恒星特性。

发布时间：2025年07月14日

`LLM应用` `天体物理学` `数据科学`

> Machine-learning inference of stellar properties using integrated photometric and spectroscopic data

# 摘要

> 恒星天体物理学依赖于多种观测方式，主要是测光光变曲线和光谱数据，从中推断恒星的基本性质。尽管机器学习在单个模态内的分析取得了进展，但跨模态中编码的互补信息仍未得到充分利用。我们提出DESA（用于恒星天体物理学的双嵌入模型），这是一种新型多模态基础模型，整合光变曲线和光谱数据，学习恒星统一且具有物理意义的潜在空间。

DESA首先使用混合监督/自监督方案训练单独的模态特定编码器，然后通过DualFormer（一种专为天文数据设计的基于Transformer的跨模态整合模块）对它们进行对齐。DualFormer结合了交叉注意力和自注意力、一种新颖的双投影对齐损失以及投影空间的特征分解，生成具有物理结构的嵌入。

我们证明DESA在多种任务中显著优于领先的单模态和自监督基线。在零样本和少样本设置下，DESA学习到的表示能够高保真地恢复恒星颜色-光度图和赫罗图（测光回归的R²=0.92）。在完全微调的情况下，DESA在双星检测（AUC=0.99，AP=1.00）和恒星年龄预测（RMSE=0.94 Gyr）方面达到了最先进的精度。

作为一个有力的案例，DESA仅凭UMAP空间中的嵌入位置，就能够自然地区分同步双星与年轻恒星，这两种群体具有几乎相同的光变曲线，而无需额外的运动学或光度信息。因此，DESA为多模态、数据驱动的恒星群体分析提供了一个强大的新框架，既支持精确预测，也支持新发现。

> Stellar astrophysics relies on diverse observational modalities-primarily photometric light curves and spectroscopic data-from which fundamental stellar properties are inferred. While machine learning (ML) has advanced analysis within individual modalities, the complementary information encoded across modalities remains largely underexploited. We present DESA (Dual Embedding model for Stellar Astrophysics), a novel multi-modal foundation model that integrates light curves and spectra to learn a unified, physically meaningful latent space for stars. DESA first trains separate modality-specific encoders using a hybrid supervised/self-supervised scheme, and then aligns them through DualFormer, a transformer-based cross-modal integration module tailored for astrophysical data. DualFormer combines cross- and self-attention, a novel dual-projection alignment loss, and a projection-space eigendecomposition that yields physically structured embeddings. We demonstrate that DESA significantly outperforms leading unimodal and self-supervised baselines across a range of tasks. In zero- and few-shot settings, DESA's learned representations recover stellar color-magnitude and Hertzsprung-Russell diagrams with high fidelity ($R^2 = 0.92$ for photometric regressions). In full fine-tuning, DESA achieves state-of-the-art accuracy for binary star detection (AUC = $0.99$, AP = $1.00$) and stellar age prediction (RMSE = $0.94$ Gyr). As a compelling case, DESA naturally separates synchronized binaries from young stars, two populations with nearly identical light curves, purely from their embedded positions in UMAP space, without requiring external kinematic or luminosity information. DESA thus offers a powerful new framework for multimodal, data-driven stellar population analysis, enabling both accurate prediction and novel discovery.

[Arxiv](https://arxiv.org/abs/2507.10666)