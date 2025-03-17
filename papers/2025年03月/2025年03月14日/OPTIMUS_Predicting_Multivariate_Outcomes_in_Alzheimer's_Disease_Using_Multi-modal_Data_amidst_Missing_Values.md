# OPTIMUS：基于多模态数据，面对缺失值，预测阿尔茨海默病的多变量结果

发布时间：2025年03月14日

`其他`

> OPTIMUS: Predicting Multivariate Outcomes in Alzheimer's Disease Using Multi-modal Data amidst Missing Values

# 摘要

> 阿尔茨海默病（AD）是一种神经退行性疾病，与神经、遗传和蛋白质组学等因素相关，同时影响多种认知和行为功能。传统AD预测主要关注单变量疾病结果，如疾病阶段和严重程度。多模态数据相较于单一模态编码了更广泛的疾病信息，因此可能提高疾病预测能力；但它们通常包含缺失值。近期更“深层”的机器学习方法在提高预测准确性方面展现出潜力，然而这些模型的生物学相关性仍需进一步探索。通过整合缺失数据分析、预测建模、多模态数据分析和可解释人工智能，我们提出了OPTIMUS——一个预测性、模块化且可解释的机器学习框架，旨在揭示多模态输入数据与多变量疾病结果之间的“多对多”预测通路，即便存在缺失值。OPTIMUS首先应用模态特定的插补方法，从每个模态中恢复数据，同时优化整体预测准确性。然后，它利用机器学习将多模态生物标志物映射到多变量结果，并分别提取预测每个结果的生物标志物。最后，OPTIMUS整合XAI来解释识别出的多模态生物标志物。基于346名认知正常个体、608名轻度认知障碍患者和251名AD患者的数据显示，OPTIMUS识别出神经和转录组学特征，这些特征共同但差异性地预测了与执行功能、语言、记忆和视空间功能相关的多变量结果。本研究证明了构建一个预测性且生物学可解释的机器学习框架的潜力，以揭示捕获不同认知背景下疾病特征的多模态生物标志物。我们的结果加深了对AD中复杂“多对多”通路的理解。

> Alzheimer's disease, a neurodegenerative disorder, is associated with neural, genetic, and proteomic factors while affecting multiple cognitive and behavioral faculties. Traditional AD prediction largely focuses on univariate disease outcomes, such as disease stages and severity. Multimodal data encode broader disease information than a single modality and may, therefore, improve disease prediction; but they often contain missing values. Recent "deeper" machine learning approaches show promise in improving prediction accuracy, yet the biological relevance of these models needs to be further charted. Integrating missing data analysis, predictive modeling, multimodal data analysis, and explainable AI, we propose OPTIMUS, a predictive, modular, and explainable machine learning framework, to unveil the many-to-many predictive pathways between multimodal input data and multivariate disease outcomes amidst missing values. OPTIMUS first applies modality-specific imputation to uncover data from each modality while optimizing overall prediction accuracy. It then maps multimodal biomarkers to multivariate outcomes using machine-learning and extracts biomarkers respectively predictive of each outcome. Finally, OPTIMUS incorporates XAI to explain the identified multimodal biomarkers. Using data from 346 cognitively normal subjects, 608 persons with mild cognitive impairment, and 251 AD patients, OPTIMUS identifies neural and transcriptomic signatures that jointly but differentially predict multivariate outcomes related to executive function, language, memory, and visuospatial function. Our work demonstrates the potential of building a predictive and biologically explainable machine-learning framework to uncover multimodal biomarkers that capture disease profiles across varying cognitive landscapes. The results improve our understanding of the complex many-to-many pathways in AD.

[Arxiv](https://arxiv.org/abs/2503.11282)