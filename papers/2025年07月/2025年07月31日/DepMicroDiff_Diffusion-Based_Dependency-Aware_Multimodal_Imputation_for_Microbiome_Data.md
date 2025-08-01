# DepMicroDiff: 针对微生物组数据的基于扩散模型的依赖感知多模态插补方法

发布时间：2025年07月31日

`其他` `生物科学`

> DepMicroDiff: Diffusion-Based Dependency-Aware Multimodal Imputation for Microbiome Data

# 摘要

> 微生物组数据分析是理解宿主健康与疾病的关键，但其固有的稀疏性和噪声特性为准确插补带来了巨大挑战，进而影响了生物标志物发现等下游任务。现有的插补方法，包括最近的扩散模型，往往无法有效捕捉微生物群落间的复杂相互依赖关系，同时也忽视了可能为插补提供重要信息的上下文元数据。我们提出了一种名为DepMicroDiff的新框架，它结合了扩散生成建模与依赖感知变换器（Dependency-Aware Transformer, DAT），能够显式地捕获微生物群落间的相互成对依赖关系和自回归关系。通过基于VAE的预训练在多样化的癌症数据集上进行增强，并结合通过大型语言模型（LLM）编码的患者元数据进行条件控制，DepMicroDiff的性能得到了进一步提升。在TCGA微生物组数据集上的实验结果表明，与现有最先进方法相比，DepMicroDiff在皮尔逊相关性（高达0.712）、余弦相似度（高达0.812）以及RMSE和MAE等指标上均表现出显著优势，充分证明了其在微生物组插补任务中的鲁棒性和泛化能力。

> Microbiome data analysis is essential for understanding host health and disease, yet its inherent sparsity and noise pose major challenges for accurate imputation, hindering downstream tasks such as biomarker discovery. Existing imputation methods, including recent diffusion-based models, often fail to capture the complex interdependencies between microbial taxa and overlook contextual metadata that can inform imputation. We introduce DepMicroDiff, a novel framework that combines diffusion-based generative modeling with a Dependency-Aware Transformer (DAT) to explicitly capture both mutual pairwise dependencies and autoregressive relationships. DepMicroDiff is further enhanced by VAE-based pretraining across diverse cancer datasets and conditioning on patient metadata encoded via a large language model (LLM). Experiments on TCGA microbiome datasets show that DepMicroDiff substantially outperforms state-of-the-art baselines, achieving higher Pearson correlation (up to 0.712), cosine similarity (up to 0.812), and lower RMSE and MAE across multiple cancer types, demonstrating its robustness and generalizability for microbiome imputation.

[Arxiv](https://arxiv.org/abs/2507.23676)