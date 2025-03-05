# 多模态 AI 从临床前数据预测药物组合的临床效果

发布时间：2025年03月04日

`其他`

> Multimodal AI predicts clinical outcomes of drug combinations from preclinical data

# 摘要

> 从临床前数据预测临床结果对于识别安全有效的药物组合至关重要。当前模型依赖于结构或基于靶点的特征来识别高疗效、低毒性的药物组合。然而，这些方法未能整合进行准确、临床相关预测所需的多模态数据。在这里，我们介绍了MADRIGAL，一个多模态AI模型，它通过学习结构、通路、细胞活力和转录组学数据来预测药物组合效果，涵盖953种临床结果和21842种化合物，包括已批准药物和正在开发中的新化合物的组合。MADRIGAL采用变压器瓶颈模块来统一临床前药物数据模式，同时在训练和推理过程中处理缺失数据——这是多模态学习中的一个主要挑战。它在预测不良药物相互作用方面优于单一模态方法和最先进的模型。MADRIGAL对抗癌药物组合进行虚拟筛选，并支持II型糖尿病和与代谢功能障碍相关的脂肪肝炎（MASH）的多药管理。它识别转运体介导的药物相互作用。MADRIGAL预测了resmetirom，这是FDA批准的唯一用于MASH的药物，在安全性最佳的疗法中。它通过整合癌症患者的基因组资料支持个性化癌症治疗。利用原发性急性髓系白血病样本和患者来源的异种移植模型，它预测了个性化药物组合的疗效。将MADRIGAL与大型语言模型集成，允许用户用自然语言描述临床结果，通过识别潜在的不良相互作用和毒性风险来改善安全性评估。MADRIGAL为设计组合疗法提供了一种多模态方法，提高了预测准确性和临床相关性。

> Predicting clinical outcomes from preclinical data is essential for identifying safe and effective drug combinations. Current models rely on structural or target-based features to identify high-efficacy, low-toxicity drug combinations. However, these approaches fail to incorporate the multimodal data necessary for accurate, clinically-relevant predictions. Here, we introduce MADRIGAL, a multimodal AI model that learns from structural, pathway, cell viability, and transcriptomic data to predict drug combination effects across 953 clinical outcomes and 21842 compounds, including combinations of approved drugs and novel compounds in development. MADRIGAL uses a transformer bottleneck module to unify preclinical drug data modalities while handling missing data during training and inference--a major challenge in multimodal learning. It outperforms single-modality methods and state-of-the-art models in predicting adverse drug interactions. MADRIGAL performs virtual screening of anticancer drug combinations and supports polypharmacy management for type II diabetes and metabolic dysfunction-associated steatohepatitis (MASH). It identifies transporter-mediated drug interactions. MADRIGAL predicts resmetirom, the first and only FDA-approved drug for MASH, among therapies with the most favorable safety profile. It supports personalized cancer therapy by integrating genomic profiles from cancer patients. Using primary acute myeloid leukemia samples and patient-derived xenograft models, it predicts the efficacy of personalized drug combinations. Integrating MADRIGAL with a large language model allows users to describe clinical outcomes in natural language, improving safety assessment by identifying potential adverse interactions and toxicity risks. MADRIGAL provides a multimodal approach for designing combination therapies with improved predictive accuracy and clinical relevance.

[Arxiv](https://arxiv.org/abs/2503.02781)