# 多导联特定建模的 ECG 低成本肺动脉高压评估方法

发布时间：2025年03月03日

`其他` `心血管`

> Multimodal Lead-Specific Modeling of ECG for Low-Cost Pulmonary Hypertension Assessment

# 摘要

> 肺动脉高压（PH）在低收入和中收入国家（LMICs）常常被漏诊，主要原因在于先进诊断工具的匮乏。尽管已有研究将机器学习应用于低成本诊断工具（如12导联心电图，12L-ECG），但这些研究主要关注资源有限的地区，却忽略了完全没有诊断工具的地区，例如LMICs的农村基层医疗。近期研究表明，6导联心电图（6L-ECG）作为一种更经济且便携的替代方案，在检测多种心脏疾病方面表现出色，但其在PH诊断中的临床价值尚未得到充分验证。

此外，现有方法将12L-/6L-ECG视为单一模态，仅捕捉共享特征，却忽视了对识别复杂心脏血流动力学变化至关重要的导联特异性特征。本文提出了一种基于导联特异性的心电图多模态变分自编码器（LS-EMVAE），该模型首先在大规模12L-ECG数据上进行预训练，然后在特定任务数据（12L-ECG或6L-ECG）上进行微调。LS-EMVAE将每个12L-ECG导联视为独立模态，并引入了基于专家混合与乘积的分层专家组合，实现了导联特异性与共享特征之间的自适应潜在特征融合。

与现有方法不同，LS-EMVAE在推理时对12L-ECG和6L-ECG均能做出更优预测，使其成为适用于诊断工具匮乏或完全没有诊断工具地区的公平解决方案。我们利用80万份公开的12L-ECG样本对LS-EMVAE进行预训练，并在内部数据集上针对两项任务进行微调：1）PH检测；2）前/后毛细血管PH的表型分类。实验结果表明，LS-EMVAE在两种心电图设置下均优于现有基线模型，而6L-ECG的表现可与12L-ECG相媲美，这为其在缺乏诊断工具地区开展全球PH筛查开辟了潜力。

> Pulmonary hypertension (PH) is frequently underdiagnosed in low- and middle-income countries (LMICs) primarily due to the scarcity of advanced diagnostic tools. Several studies in PH have applied machine learning to low-cost diagnostic tools like 12-lead ECG (12L-ECG), but they mainly focus on areas with limited resources, overlooking areas with no diagnostic tools, such as rural primary healthcare in LMICs. Recent studies have shown the effectiveness of 6-lead ECG (6L-ECG), as a cheaper and portable alternative in detecting various cardiac conditions, but its clinical value for PH detection is not well proved. Furthermore, existing methods treat 12L-/6L-ECG as a single modality, capturing only shared features while overlooking lead-specific features essential for identifying complex cardiac hemodynamic changes. In this paper, we propose Lead-Specific Electrocardiogram Multimodal Variational Autoencoder (LS-EMVAE), a model pre-trained on large-population 12L-ECG data and fine-tuned on task-specific data (12L-ECG or 6L-ECG). LS-EMVAE models each 12L-ECG lead as a separate modality and introduces a hierarchical expert composition using Mixture and Product of Experts for adaptive latent feature fusion between lead-specific and shared features. Unlike existing approaches, LS-EMVAE makes better predictions on both 12L-ECG and 6L-ECG at inference, making it an equitable solution for areas with limited or no diagnostic tools. We pre-trained LS-EMVAE on 800,000 publicly available 12L-ECG samples and fine-tuned it for two tasks: 1) PH detection and 2) phenotyping pre-/post-capillary PH, on in-house datasets of 892 and 691 subjects across 12L-ECG and 6L-ECG settings. Extensive experiments show that LS-EMVAE outperforms existing baselines in both ECG settings, while 6L-ECG achieves performance comparable to 12L-ECG, unlocking its potential for global PH screening in areas without diagnostic tools.

[Arxiv](https://arxiv.org/abs/2503.13470)