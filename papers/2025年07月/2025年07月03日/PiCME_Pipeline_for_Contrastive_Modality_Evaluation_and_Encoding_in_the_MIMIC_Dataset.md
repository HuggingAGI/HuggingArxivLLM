# # PiCME：MIMIC 数据集中的对比模态评估与编码流程

发布时间：2025年07月03日

`其他`

> PiCME: Pipeline for Contrastive Modality Evaluation and Encoding in the MIMIC Dataset

# 摘要

> # 摘要  
多模态深度学习在提升临床预测方面展现出巨大潜力，通过整合文本、影像、时序数据和结构化人口统计等多种患者数据。对比学习通过生成可跨任务复用的统一表示，促进了这种整合，减少了对独立模型或编码器的需求。尽管对比学习在视觉-语言领域取得了成功，但在临床场景中的应用仍主要局限于图像和文本配对。我们提出了一种名为 Pipeline for Contrastive Modality Evaluation and Encoding（PiCME）的管道，系统性评估了来自 MIMIC 数据库的五种临床数据类型：出院总结、放射报告、胸部 X 光片、人口统计信息和时序数据。我们在所有 26 种两到五模态的组合上预训练对比模型，并评估其在院内死亡率和表型预测中的实用性。为了解决更多模态带来的性能瓶颈，我们引入了 Modality-Gated LSTM，根据对比学习中模态的重要性对其进行加权。我们的结果显示，对比模型在三模态设置下仍能与监督基线相媲美。超过三模态后，性能有所下降，而监督模型无法恢复。Modality-Gated LSTM 缓解了这一下降趋势，在五模态设置下将 AUROC 从 73.19% 提升至 76.93%，AUPRC 从 51.27% 提升至 62.26%。我们还对比了对比学习中模态重要性评分与归因评分，并评估了其在不同人口统计子群中的泛化能力，突出了其在可解释性和公平性方面的优势。PiCME 是首个在 MIMIC 数据集中所有模态组合上扩展对比学习的研究，为模态选择、训练策略和公平临床预测提供了指导。

> Multimodal deep learning holds promise for improving clinical prediction by integrating diverse patient data, including text, imaging, time-series, and structured demographics. Contrastive learning facilitates this integration by producing a unified representation that can be reused across tasks, reducing the need for separate models or encoders. Although contrastive learning has seen success in vision-language domains, its use in clinical settings remains largely limited to image and text pairs. We propose the Pipeline for Contrastive Modality Evaluation and Encoding (PiCME), which systematically assesses five clinical data types from MIMIC: discharge summaries, radiology reports, chest X-rays, demographics, and time-series. We pre-train contrastive models on all 26 combinations of two to five modalities and evaluate their utility on in-hospital mortality and phenotype prediction. To address performance plateaus with more modalities, we introduce a Modality-Gated LSTM that weights each modality according to its contrastively learned importance. Our results show that contrastive models remain competitive with supervised baselines, particularly in three-modality settings. Performance declines beyond three modalities, which supervised models fail to recover. The Modality-Gated LSTM mitigates this drop, improving AUROC from 73.19% to 76.93% and AUPRC from 51.27% to 62.26% in the five-modality setting. We also compare contrastively learned modality importance scores with attribution scores and evaluate generalization across demographic subgroups, highlighting strengths in interpretability and fairness. PiCME is the first to scale contrastive learning across all modality combinations in MIMIC, offering guidance for modality selection, training strategies, and equitable clinical prediction.

[Arxiv](https://arxiv.org/abs/2507.03165)