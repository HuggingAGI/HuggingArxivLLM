# 基于解剖剂量双重约束的条件扩散模型实现端到端多肿瘤剂量预测

发布时间：2025年08月04日

`其他

论文摘要：放射治疗计划传统上依赖耗时的试错调整，高度依赖专家经验，而现有深度学习方法在泛化、预测精度和临床适用性上存在局限。我们提出ADDiff-Dose，一个基于解剖与剂量双重约束的条件扩散模型，用于端到端多肿瘤剂量预测。该模型通过LightweightVAE3D压缩高维CT数据，并在逐步加噪与去噪框架内整合多模态输入，包括靶区和危及器官掩膜及束参数。借助多头注意力机制引入条件特征，并采用结合MSE、条件项和KL散度的复合损失函数，确保剂量测量准确性和符合临床约束。在大规模公共数据集（2,877例）和三个外部机构队列（总计450例）上的评估显示，ADDiff-Dose显著优于传统基线模型，实现0.101-0.154的MAE（较UNet的0.316和GAN模型的0.169有显著提升），DICE系数达0.927（提升6.8%），并将脊髓最大剂量误差控制在0.1 Gy以内。每例计划生成时间平均缩短至22秒。消融研究表明，结构编码器使符合临床剂量约束的能力提升28.5%。这是首个将条件扩散模型框架应用于放射治疗剂量预测的研究，为多种肿瘤部位的自动化治疗计划提供通用高效方案，有望大幅缩短计划时间并提升临床工作流程效率。

其他` `放射治疗`

> Conditional Diffusion Model with Anatomical-Dose Dual Constraints for End-to-End Multi-Tumor Dose Prediction

# 摘要

> 放射治疗计划传统上依赖耗时的试错调整，高度依赖专家经验，而现有深度学习方法在泛化、预测精度和临床适用性上存在局限。我们提出ADDiff-Dose，一个基于解剖与剂量双重约束的条件扩散模型，用于端到端多肿瘤剂量预测。该模型通过LightweightVAE3D压缩高维CT数据，并在逐步加噪与去噪框架内整合多模态输入，包括靶区和危及器官掩膜及束参数。借助多头注意力机制引入条件特征，并采用结合MSE、条件项和KL散度的复合损失函数，确保剂量测量准确性和符合临床约束。在大规模公共数据集（2,877例）和三个外部机构队列（总计450例）上的评估显示，ADDiff-Dose显著优于传统基线模型，实现0.101-0.154的MAE（较UNet的0.316和GAN模型的0.169有显著提升），DICE系数达0.927（提升6.8%），并将脊髓最大剂量误差控制在0.1 Gy以内。每例计划生成时间平均缩短至22秒。消融研究表明，结构编码器使符合临床剂量约束的能力提升28.5%。这是首个将条件扩散模型框架应用于放射治疗剂量预测的研究，为多种肿瘤部位的自动化治疗计划提供通用高效方案，有望大幅缩短计划时间并提升临床工作流程效率。

> Radiotherapy treatment planning often relies on time-consuming, trial-and-error adjustments that heavily depend on the expertise of specialists, while existing deep learning methods face limitations in generalization, prediction accuracy, and clinical applicability. To tackle these challenges, we propose ADDiff-Dose, an Anatomical-Dose Dual Constraints Conditional Diffusion Model for end-to-end multi-tumor dose prediction. The model employs LightweightVAE3D to compress high-dimensional CT data and integrates multimodal inputs, including target and organ-at-risk (OAR) masks and beam parameters, within a progressive noise addition and denoising framework. It incorporates conditional features via a multi-head attention mechanism and utilizes a composite loss function combining MSE, conditional terms, and KL divergence to ensure both dosimetric accuracy and compliance with clinical constraints. Evaluation on a large-scale public dataset (2,877 cases) and three external institutional cohorts (450 cases in total) demonstrates that ADDiff-Dose significantly outperforms traditional baselines, achieving an MAE of 0.101-0.154 (compared to 0.316 for UNet and 0.169 for GAN models), a DICE coefficient of 0.927 (a 6.8% improvement), and limiting spinal cord maximum dose error to within 0.1 Gy. The average plan generation time per case is reduced to 22 seconds. Ablation studies confirm that the structural encoder enhances compliance with clinical dose constraints by 28.5%. To our knowledge, this is the first study to introduce a conditional diffusion model framework for radiotherapy dose prediction, offering a generalizable and efficient solution for automated treatment planning across diverse tumor sites, with the potential to substantially reduce planning time and improve clinical workflow efficiency.

[Arxiv](https://arxiv.org/abs/2508.02043)