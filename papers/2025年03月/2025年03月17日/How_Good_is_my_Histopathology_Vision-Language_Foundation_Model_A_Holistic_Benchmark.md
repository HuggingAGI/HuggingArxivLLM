# 评估我的组织病理学视觉-语言基础模型：全面基准测试

发布时间：2025年03月17日

`LLM应用` `生命科学`

> How Good is my Histopathology Vision-Language Foundation Model? A Holistic Benchmark

# 摘要

> 近年来，组学视觉语言基础模型（VLMs）因其卓越的性能和跨任务泛化能力而备受关注。然而，现有组学基准存在以下局限：多为单模态、临床任务与器官类型多样性不足、获取设备有限，且因患者隐私问题难以完全公开。因此，目前尚缺乏一个统一的基准平台，能够全面评估现有组学 VLMs 并真实反映临床场景的多样性。为弥补这一空白，我们推出了 HistoVL，这是一个完全开源的综合性基准，整合了 11 种不同设备获取的图像，并为其配以精心设计的图像描述，涵盖类别名称和多样化病理特征。我们的 Histo-VL 包含 26 种器官、31 种癌症类型以及来自 14 个异质患者队列的丰富组织样本，总计超过 500 万个从 41,000 多张全玻片图像（WSIs）中提取的图像补丁，覆盖多种放大倍数。我们系统性地在 Histo-VL 上评估现有组学 VLMs，以模拟临床场景中专家面临的多样化任务。研究发现，现有组学 VLMs 存在以下问题：对文本变化高度敏感（如转移检测任务中平衡准确率下降高达 25%）、抗干扰能力较弱，以及模型校准不当（表现为高期望校准误差（ECE）值和低预测置信度），这些缺陷可能会影响其临床应用效果。

> Recently, histopathology vision-language foundation models (VLMs) have gained popularity due to their enhanced performance and generalizability across different downstream tasks. However, most existing histopathology benchmarks are either unimodal or limited in terms of diversity of clinical tasks, organs, and acquisition instruments, as well as their partial availability to the public due to patient data privacy. As a consequence, there is a lack of comprehensive evaluation of existing histopathology VLMs on a unified benchmark setting that better reflects a wide range of clinical scenarios. To address this gap, we introduce HistoVL, a fully open-source comprehensive benchmark comprising images acquired using up to 11 various acquisition tools that are paired with specifically crafted captions by incorporating class names and diverse pathology descriptions. Our Histo-VL includes 26 organs, 31 cancer types, and a wide variety of tissue obtained from 14 heterogeneous patient cohorts, totaling more than 5 million patches obtained from over 41K WSIs viewed under various magnification levels. We systematically evaluate existing histopathology VLMs on Histo-VL to simulate diverse tasks performed by experts in real-world clinical scenarios. Our analysis reveals interesting findings, including large sensitivity of most existing histopathology VLMs to textual changes with a drop in balanced accuracy of up to 25% in tasks such as Metastasis detection, low robustness to adversarial attacks, as well as improper calibration of models evident through high ECE values and low model prediction confidence, all of which can affect their clinical implementation.

[Arxiv](https://arxiv.org/abs/2503.12990)