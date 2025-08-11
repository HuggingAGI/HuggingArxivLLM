# 基于检索增强的佛罗里达沼泽地水位预测方法

发布时间：2025年08月06日

`RAG

理由：这篇论文介绍了检索增强预测（RAF）框架在水文学中的应用，通过检索历史数据中的类似事件来提升水位预测的准确性。虽然RAF主要用于预测任务，但其核心技术与RAG（检索增强生成）相似，都是通过检索外部信息来增强模型性能。因此，这篇论文属于RAG类别。` `水文学` `环境科学`

> Retrieval-Augmented Water Level Forecasting for Everglades

# 摘要

> 准确的水位预测对于管理像佛罗里达礁岛群这样的生态系统至关重要，该地区是一个对防洪、抗旱、水资源规划和生物多样性保护至关重要的亚热带湿地。尽管深度学习的最新进展，特别是时间序列基础模型，在通用领域预测中取得了成功，但它们在水文学中的应用仍鲜为人知。此外，由于缺乏有效的适应机制，它们通常难以在不同的未见数据集和领域中进行泛化。

为了解决这一差距，我们将检索增强预测（RAF）引入水文学领域，提出了一种框架，通过检索历史上类似的多变量水文事件来丰富模型输入，以便在预测前进行数据增强。通过维护一个外部的历史观测档案，RAF能够识别并整合历史数据中的相关模式，从而提升模型的背景感知能力和预测精度，而无需针对特定任务重新训练或微调模型。

此外，我们探索并比较了基于相似性和基于互信息的RAF方法。我们在佛罗里达礁岛群的真实数据上进行了全面评估，结果表明，RAF框架在水位预测准确度方面取得了显著提升。本研究突显了RAF方法在环境水文学中的潜力，并为生态系统管理领域的专家更广泛地采用自适应AI方法铺平了道路。代码和数据可在https://github.com/rahuul2992000/WaterRAF获取。

> Accurate water level forecasting is crucial for managing ecosystems such as the Everglades, a subtropical wetland vital for flood mitigation, drought management, water resource planning, and biodiversity conservation. While recent advances in deep learning, particularly time series foundation models, have demonstrated success in general-domain forecasting, their application in hydrology remains underexplored. Furthermore, they often struggle to generalize across diverse unseen datasets and domains, due to the lack of effective mechanisms for adaptation. To address this gap, we introduce Retrieval-Augmented Forecasting (RAF) into the hydrology domain, proposing a framework that retrieves historically analogous multivariate hydrological episodes to enrich the model input before forecasting. By maintaining an external archive of past observations, RAF identifies and incorporates relevant patterns from historical data, thereby enhancing contextual awareness and predictive accuracy without requiring the model for task-specific retraining or fine-tuning. Furthermore, we explore and compare both similarity-based and mutual information-based RAF methods. We conduct a comprehensive evaluation on real-world data from the Everglades, demonstrating that the RAF framework yields substantial improvements in water level forecasting accuracy. This study highlights the potential of RAF approaches in environmental hydrology and paves the way for broader adoption of adaptive AI methods by domain experts in ecosystem management. The code and data are available at https://github.com/rahuul2992000/WaterRAF.

[Arxiv](https://arxiv.org/abs/2508.04888)