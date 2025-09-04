# 在数据有限情况下部署自适应机器学习智能体用于实时细胞培养过程监测的经验教训

发布时间：2025年08月29日

`其他` `工业与制造`

> Lessons Learned from Deploying Adaptive Machine Learning Agents with Limited Data for Real-time Cell Culture Process Monitoring

# 摘要

> 本研究探索了三种机器学习（ML）方法的部署，旨在利用拉曼光谱作为输入特征，实时预测细胞培养过程中的葡萄糖、乳酸和铵浓度。研究针对数据稀缺和过程变异性带来的挑战，对预训练模型、即时学习（JITL）及在线学习算法进行了对比分析。通过两个工业案例研究，评估了不同生物工艺条件对模型性能的影响。研究结果揭示了预训练模型在特定条件下具有更高预测精度的情况，并指出了即时学习（JITL）或在线学习方法在自适应过程监控中更适用的场景。本研究还强调，在生物反应器运行期间，利用最新的离线分析测量值更新已部署模型/智能体至关重要，这能确保模型在整个运行过程中有效应对细胞生长行为和操作条件的变化，维持良好性能。此外，研究还证实，基于拉曼光谱数据，简单的专家混合框架有助于提升代谢物浓度实时预测的准确性和稳健性。这些见解为在动态多变的生物制造环境中高效部署机器学习模型提供了稳健策略的开发思路。

> This study explores the deployment of three machine learning (ML) approaches for real-time prediction of glucose, lactate, and ammonium concentrations in cell culture processes, using Raman spectroscopy as input features. The research addresses challenges associated with limited data availability and process variability, providing a comparative analysis of pretrained models, just-in-time learning (JITL), and online learning algorithms. Two industrial case studies are presented to evaluate the impact of varying bioprocess conditions on model performance. The findings highlight the specific conditions under which pretrained models demonstrate superior predictive accuracy and identify scenarios where JITL or online learning approaches are more effective for adaptive process monitoring. This study also highlights the critical importance of updating the deployed models/agents with the latest offline analytical measurements during bioreactor operations to maintain the model performance against the changes in cell growth behaviours and operating conditions throughout the bioreactor run. Additionally, the study confirms the usefulness of a simple mixture-of-experts framework in achieving enhanced accuracy and robustness for real-time predictions of metabolite concentrations based on Raman spectral data. These insights contribute to the development of robust strategies for the efficient deployment of ML models in dynamic and changing biomanufacturing environments.

[Arxiv](https://arxiv.org/abs/2509.02606)