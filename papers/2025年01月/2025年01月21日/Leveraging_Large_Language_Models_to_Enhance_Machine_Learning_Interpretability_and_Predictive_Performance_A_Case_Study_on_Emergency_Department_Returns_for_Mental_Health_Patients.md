# 借助大型语言模型提升机器学习可解释性与预测性能：精神健康患者急诊科返回案例研究

发布时间：2025年01月21日

`LLM应用

**理由**：这篇论文主要探讨了如何将大型语言模型（LLMs）与传统机器学习方法结合，以提升急诊科心理健康复诊风险模型的预测准确性和临床可解释性。论文中使用了检索增强生成（RAG）框架，并结合SHAP值与临床背景知识来评估模型的可解释性。这些内容主要涉及LLM在实际应用中的使用，特别是如何通过LLM提升模型的性能和可解释性，因此将其分类为LLM应用。` `急诊科`

> Leveraging Large Language Models to Enhance Machine Learning Interpretability and Predictive Performance: A Case Study on Emergency Department Returns for Mental Health Patients

# 摘要

> # 目标
评估将大型语言模型（LLMs）与传统机器学习方法结合，是否能提升急诊科（ED）心理健康复诊风险模型的预测准确性和临床可解释性。

# 方法
这项回顾性队列研究分析了2018年1月至2022年12月期间，美国南部一所学术医疗中心27,904名心理健康患者的42,464次急诊科就诊。主要结果包括：（1）30天内急诊科复诊的预测准确性；（2）通过一种新颖的检索增强生成（RAG）框架，结合SHAP值与临床背景知识，评估模型的可解释性。

# 结果
提出的机器学习可解释性框架，利用LLM，将复杂模型预测转化为临床相关解释的准确率高达99%。LLM提取的特征集成提升了预测性能，XGBoost模型的AUC从0.73提升至0.76。基于LLM的特征提取使用10-shot学习显著优于传统方法，主诉分类的准确率达到0.882，F1得分为0.86（传统方法的准确率范围为0.59至0.63），并在多个社会决定健康（SDoH）类别中表现出0.65至0.93的准确率，突显了其在从临床笔记中提取特征方面的强大性能。

# 结论与相关性
将LLMs与传统机器学习模型结合，在急诊科复诊预测准确性上取得了适度但一致的改进，同时通过自动化的临床相关解释显著增强了模型的可解释性。该方法为将复杂的预测分析转化为可操作的临床见解提供了一个框架。

> Objective: To evaluate whether integrating large language models (LLMs) with traditional machine learning approaches improves both the predictive accuracy and clinical interpretability of ED mental health returns risk models. Methods: This retrospective cohort study analyzed 42,464 ED visits for 27,904 unique mental health patients at an Academic Medical Center in the deep South of the United States between January 2018 and December 2022. Main Outcomes and Measures: Two primary outcomes were evaluated: (1) 30 days ED return prediction accuracy and (2) model interpretability through a novel retrieval-augmented generation (RAG) framework integrating SHAP (SHapley Additive exPlanations) values with contextual clinical knowledge. Results: The proposed machine learning interpretability framework, leveraging LLM, achieved 99% accuracy in translating complex model predictions into clinically relevant explanations. Integration of LLM-extracted features enhanced predictive performance, improving the XGBoost model area under the curve (AUC) from 0.73 to 0.76. The LLM-based feature extraction using 10-shot learning significantly outperformed traditional approaches, achieving an accuracy of 0.882 and an F1 score of 0.86 for chief complaint classification (compared to conventional methods with an accuracy range of 0.59 to 0.63) and demonstrating accuracy values ranging from 0.65 to 0.93 across multiple SDoH categories, underscoring its robust performance in extracting features from clinical notes. Conclusions and Relevance: Integrating LLMs with traditional machine learning models yielded modest but consistent improvements in ED return prediction accuracy while substantially enhancing model interpretability through automated, clinically relevant explanations. This approach offers a framework for translating complex predictive analytics into actionable clinical insights.

[Arxiv](https://arxiv.org/abs/2502.00025)