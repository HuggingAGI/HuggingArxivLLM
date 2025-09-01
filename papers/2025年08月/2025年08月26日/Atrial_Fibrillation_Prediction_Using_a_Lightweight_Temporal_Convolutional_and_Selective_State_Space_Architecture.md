# 基于轻量级时间卷积与选择性状态空间架构的心房颤动预测

发布时间：2025年08月26日

`其他` `医疗健康`

> Atrial Fibrillation Prediction Using a Lightweight Temporal Convolutional and Selective State Space Architecture

# 摘要

> 心房颤动（AF）是最常见的心律失常，会增加中风、心力衰竭及其他心血管并发症的风险。尽管AF检测算法在识别持续性AF方面表现出色，但早期进展（如阵发性AF（PAF））因其突发且持续时间短，常难以被检测。然而，未被发现的PAF可能进展为持续性AF，进而增加死亡及严重并发症风险。AF的早期预测为通过预防性治疗（如儿茶酚胺节省剂或β受体阻滞剂）延缓疾病进展提供了可能。本研究提出一种仅基于RR间期（RRIs）的轻量级深度学习模型，将用于位置编码的时间卷积网络（TCN）与选择性状态空间模型Mamba相结合，通过高效并行序列建模实现AF的早期预测。在受试者水平测试中，该模型的敏感性达0.908、特异性0.933、F1分数0.930、AUROC 0.972、AUPRC 0.932。此外，该方法计算效率高，仅含7.35万个参数和38.3 MFLOPs，在准确性和模型紧凑性上均优于传统的卷积神经网络-循环神经网络（CNN-RNN）方法。值得关注的是，该模型仅需30分钟输入数据即可提前两小时预测AF，为预防性干预留出充足时间。

> Atrial fibrillation (AF) is the most common arrhythmia, increasing the risk of stroke, heart failure, and other cardiovascular complications. While AF detection algorithms perform well in identifying persistent AF, early-stage progression, such as paroxysmal AF (PAF), often goes undetected due to its sudden onset and short duration. However, undetected PAF can progress into sustained AF, increasing the risk of mortality and severe complications. Early prediction of AF offers an opportunity to reduce disease progression through preventive therapies, such as catecholamine-sparing agents or beta-blockers. In this study, we propose a lightweight deep learning model using only RR Intervals (RRIs), combining a Temporal Convolutional Network (TCN) for positional encoding with Mamba, a selective state space model, to enable early prediction of AF through efficient parallel sequence modeling. In subject-wise testing results, our model achieved a sensitivity of 0.908, specificity of 0.933, F1-score of 0.930, AUROC of 0.972, and AUPRC of 0.932. Additionally, our method demonstrates high computational efficiency, with only 73.5 thousand parameters and 38.3 MFLOPs, outperforming traditional Convolutional Neural Network-Recurrent Neural Network (CNN-RNN) approaches in both accuracy and model compactness. Notably, the model can predict AF up to two hours in advance using just 30 minutes of input data, providing enough lead time for preventive interventions.

[Arxiv](https://arxiv.org/abs/2508.19361)