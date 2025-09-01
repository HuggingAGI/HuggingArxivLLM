# SCAR：面向多模态数据集的表征方案

发布时间：2025年08月27日

`LLM理论` `基础理论`

> SCAR: A Characterization Scheme for Multi-Modal Dataset

# 摘要

> 基础模型之所以能在各类任务中展现卓越的泛化能力，很大程度上归功于其训练数据的特性。近年来，剪枝、压缩等以数据为中心的方法虽致力于优化训练过程，却难以从理论层面揭示数据属性对泛化的影响机制，尤其是样本规模缩放时的数据特征。传统研究视角则过度聚焦数据量与训练效率，常忽略数据质量的结构性特征，这在一定程度上制约了研究进展。为此，本研究提出SCAR框架——一种基于原则的数据集内在结构特性表征方案，涵盖四个核心维度：规模（Scale）、覆盖度（Coverage）、真实性（Authenticity）和丰富度（Richness）。与现有以数据为中心的指标不同，SCAR能够捕捉数据集在规模缩放过程中保持不变的稳定特性，为数据理解奠定了稳健通用的理论基础。基于这些结构特性，我们进一步提出“基础数据”（Foundation Data）——即能保留完整数据集泛化能力的最小数据子集，且无需针对特定模型重新训练。我们将单模态任务建模为阶跃函数，通过估计基础数据规模的分布，捕捉目标多模态数据集中跨模态的逐步泛化偏差。最终，我们基于此泛化偏差设计了SCAR引导的数据补全策略，可高效且感知模态地扩展多模态数据集中特定模态的特征。在多种多模态数据集和模型架构上的实验结果表明，SCAR在数据效用预测与数据采集指导方面均表现出优异性能。相关代码已开源：https://github.com/McAloma/SCAR。

> Foundation models exhibit remarkable generalization across diverse tasks, largely driven by the characteristics of their training data. Recent data-centric methods like pruning and compression aim to optimize training but offer limited theoretical insight into how data properties affect generalization, especially the data characteristics in sample scaling. Traditional perspectives further constrain progress by focusing predominantly on data quantity and training efficiency, often overlooking structural aspects of data quality. In this study, we introduce SCAR, a principled scheme for characterizing the intrinsic structural properties of datasets across four key measures: Scale, Coverage, Authenticity, and Richness. Unlike prior data-centric measures, SCAR captures stable characteristics that remain invariant under dataset scaling, providing a robust and general foundation for data understanding. Leveraging these structural properties, we introduce Foundation Data-a minimal subset that preserves the generalization behavior of the full dataset without requiring model-specific retraining. We model single-modality tasks as step functions and estimate the distribution of the foundation data size to capture step-wise generalization bias across modalities in the target multi-modal dataset. Finally, we develop a SCAR-guided data completion strategy based on this generalization bias, which enables efficient, modality-aware expansion of modality-specific characteristics in multimodal datasets. Experiments across diverse multi-modal datasets and model architectures validate the effectiveness of SCAR in predicting data utility and guiding data acquisition. Code is available at https://github.com/McAloma/SCAR.

[Arxiv](https://arxiv.org/abs/2508.19659)