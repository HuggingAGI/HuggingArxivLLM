# MiniGPT-Pancreas：用于胰腺癌分类与检测的多模态大型语言模型

发布时间：2024年12月20日

`LLM应用` `医学影像`

> MiniGPT-Pancreas: Multimodal Large Language Model for Pancreas Cancer Classification and Detection

# 摘要

> 问题：由于胰腺体积小、边界模糊，且患者间胰腺的形状和位置多变，胰腺的放射学成像颇具挑战。目标：在本研究中，我们推出了 MiniGPT-Pancreas，这是一个多模态大型语言模型（MLLM），以交互式聊天机器人的形式，通过整合视觉和文本信息，为临床医生进行胰腺癌诊断提供支持。方法：通用的 MLLM MiniGPT-v2 以级联方式进行了微调，用于胰腺检测、肿瘤分类和肿瘤检测，采用了结合来自美国国立卫生研究院（NIH）和医学分割十项全能（MSD）数据集的问题与计算机断层扫描的多模态提示。AbdomenCT-1k 数据集用于检测肝脏、脾脏、肾脏和胰腺。结果：MiniGPT-Pancreas 在 NIH 和 MSD 数据集上检测胰腺的交并比（IoU）分别达 0.595 和 0.550。在 MSD 数据集上的胰腺癌分类任务中，准确率、精度和召回率分别为 0.876、0.874 和 0.878。在 AbdomenCT-1k 数据集上评估 MiniGPT-Pancreas 进行多器官检测时，肝脏的 IoU 为 0.8399，肾脏为 0.722，脾脏为 0.705，胰腺为 0.497。对于胰腺肿瘤检测任务，在 MSD 数据集上的 IoU 分数为 0.168。结论：MiniGPT-Pancreas 为支持临床医生对有胰腺肿瘤的胰腺图像进行分类提供了颇具前景的解决方案。未来的研究需提升检测任务的分数，尤其是针对胰腺肿瘤的检测。

> Problem: Pancreas radiological imaging is challenging due to the small size, blurred boundaries, and variability of shape and position of the organ among patients. Goal: In this work we present MiniGPT-Pancreas, a Multimodal Large Language Model (MLLM), as an interactive chatbot to support clinicians in pancreas cancer diagnosis by integrating visual and textual information. Methods: MiniGPT-v2, a general-purpose MLLM, was fine-tuned in a cascaded way for pancreas detection, tumor classification, and tumor detection with multimodal prompts combining questions and computed tomography scans from the National Institute of Health (NIH), and Medical Segmentation Decathlon (MSD) datasets. The AbdomenCT-1k dataset was used to detect the liver, spleen, kidney, and pancreas. Results: MiniGPT-Pancreas achieved an Intersection over Union (IoU) of 0.595 and 0.550 for the detection of pancreas on NIH and MSD datasets, respectively. For the pancreas cancer classification task on the MSD dataset, accuracy, precision, and recall were 0.876, 0.874, and 0.878, respectively. When evaluating MiniGPT-Pancreas on the AbdomenCT-1k dataset for multi-organ detection, the IoU was 0.8399 for the liver, 0.722 for the kidney, 0.705 for the spleen, and 0.497 for the pancreas. For the pancreas tumor detection task, the IoU score was 0.168 on the MSD dataset. Conclusions: MiniGPT-Pancreas represents a promising solution to support clinicians in the classification of pancreas images with pancreas tumors. Future research is needed to improve the score on the detection task, especially for pancreas tumors.

[Arxiv](https://arxiv.org/abs/2412.15925)