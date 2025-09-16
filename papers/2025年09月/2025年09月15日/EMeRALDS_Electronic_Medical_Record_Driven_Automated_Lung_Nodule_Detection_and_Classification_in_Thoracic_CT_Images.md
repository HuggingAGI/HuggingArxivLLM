# EMeRALDS：电子病历驱动的胸部CT图像肺结节自动化检测与分类

发布时间：2025年09月15日

`LLM应用` `医疗健康`

> EMeRALDS: Electronic Medical Record Driven Automated Lung Nodule Detection and Classification in Thoracic CT Images

# 摘要

> 目的：肺癌是全球癌症相关死亡的首要原因，主要归因于诊断延迟和早期检测不足。本研究旨在开发一种计算机辅助诊断（CAD）系统，利用大型视觉语言模型（VLMs）实现对计算机断层扫描（CT）图像中肺结节的准确检测与分类。
  方法：我们提出端到端CAD流程，包含两个核心模块：（i）基于Segment Anything Model 2（SAM2）的检测模块（CADe），该模块将标准视觉提示替换为经CLIP（对比语言-图像预训练）编码的文本提示；（ii）诊断模块（CADx），计算分割结节与影像组学特征的相似度分数。为融入临床背景，基于专家放射科医生的影像组学评估生成合成电子病历（EMRs），并与相似度分数结合以进行最终分类。该方法在公开的LIDC-IDRI数据集（含1,018次CT扫描）上完成了测试。
  结果：该方法在零样本肺结节分析中表现出优异性能。CADe模块的结节分割Dice系数达0.92、交并比（IoU）达0.85；CADx模块的恶性分类特异性达0.97，优于现有全监督方法。
  结论：将视觉语言模型（VLMs）与影像组学、合成电子病历（EMRs）相结合，可实现CT扫描中肺结节的准确且具备临床相关性的计算机辅助诊断（CAD）。该系统有望显著增强早期肺癌检测、提升诊断信心并优化常规临床工作流程中的患者管理。

> Objective: Lung cancer is a leading cause of cancer-related mortality worldwide, primarily due to delayed diagnosis and poor early detection. This study aims to develop a computer-aided diagnosis (CAD) system that leverages large vision-language models (VLMs) for the accurate detection and classification of pulmonary nodules in computed tomography (CT) scans.
  Methods: We propose an end-to-end CAD pipeline consisting of two modules: (i) a detection module (CADe) based on the Segment Anything Model 2 (SAM2), in which the standard visual prompt is replaced with a text prompt encoded by CLIP (Contrastive Language-Image Pretraining), and (ii) a diagnosis module (CADx) that calculates similarity scores between segmented nodules and radiomic features. To add clinical context, synthetic electronic medical records (EMRs) were generated using radiomic assessments by expert radiologists and combined with similarity scores for final classification. The method was tested on the publicly available LIDC-IDRI dataset (1,018 CT scans).
  Results: The proposed approach demonstrated strong performance in zero-shot lung nodule analysis. The CADe module achieved a Dice score of 0.92 and an IoU of 0.85 for nodule segmentation. The CADx module attained a specificity of 0.97 for malignancy classification, surpassing existing fully supervised methods.
  Conclusions: The integration of VLMs with radiomics and synthetic EMRs allows for accurate and clinically relevant CAD of pulmonary nodules in CT scans. The proposed system shows strong potential to enhance early lung cancer detection, increase diagnostic confidence, and improve patient management in routine clinical workflows.

[Arxiv](https://arxiv.org/abs/2509.11714)