# 针对机器学习模型的LLM适配解释框架

发布时间：2025年07月26日

`LLM应用` `知识蒸馏`

> LLM-Adapted Interpretation Framework for Machine Learning Models

# 摘要

> 背景与目标：高性能机器学习模型（如XGBoost）常被视为“黑箱”，由于缺乏可解释性，这限制了它们在临床中的应用。本研究旨在在肌肉减少症风险评估中弥合预测准确性和叙述透明度之间的差距。

方法：我们提出了一个基于大型语言模型（LLM）的新型知识蒸馏架构——LAI-ML（LLM-Adapted Interpretation Framework）。LAI-ML采用专门技术（HAGA和CACS），将训练好的XGBoost模型的特征属性转换为概率格式。随后，一个大型语言模型（LLM）在强化学习循环和基于案例的检索指导下，生成符合数据事实的诊断叙述。

结果：LAI-ML框架在预测准确性方面达到了83%，显著优于基线XGBoost模型，高出13个百分点。值得注意的是，LLM不仅复制了教师模型的逻辑，还在21.7%的不一致案例中纠正了其预测，展示了增强的推理能力。

结论：LAI-ML成功地将不透明的模型预测转化为可信且可解释的临床见解，为医学AI中的“黑箱”问题提供了一个可部署的解决方案。

> Background & Aims: High-performance machine learning models like XGBoost are often "black boxes," limiting their clinical adoption due to a lack of interpretability. This study aims to bridge the gap between predictive accuracy and narrative transparency for sarcopenia risk assessment. Methods: We propose the LLM-Adapted Interpretation Framework (LAI-ML), a novel knowledge distillation architecture. LAI-ML transforms feature attributions from a trained XGBoost model into a probabilistic format using specialized techniques (HAGA and CACS). A Large Language Model (LLM), guided by a reinforcement learning loop and case-based retrieval, then generates data-faithful diagnostic narratives. Results: The LAI-ML framework achieved 83% prediction accuracy, significantly outperforming the baseline XGBoost model, 13% higher. Notably, the LLM not only replicated the teacher model's logic but also corrected its predictions in 21.7% of discordant cases, demonstrating enhanced reasoning. Conclusion: LAI-ML effectively translates opaque model predictions into trustworthy and interpretable clinical insights, offering a deployable solution to the "black-box" problem in medical AI.

[Arxiv](https://arxiv.org/abs/2507.21179)