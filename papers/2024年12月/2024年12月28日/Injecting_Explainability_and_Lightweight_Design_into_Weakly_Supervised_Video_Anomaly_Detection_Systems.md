# 为弱监督视频异常检测系统注入可解释性与轻量级设计

发布时间：2024年12月28日

`其他` `智慧城市` `异常检测`

> Injecting Explainability and Lightweight Design into Weakly Supervised Video Anomaly Detection Systems

# 摘要

> 弱监督监测异常检测（WSMAD）借助弱监督学习来识别异常，这在智慧城市监测中是一项关键任务。然而，现有的多模态方法因其复杂性，常常难以满足边缘设备对实时性和可解释性的要求。本文推出了 TCVADS（两阶段跨模态视频异常检测系统），它借助知识蒸馏和跨模态对比学习，能在边缘设备上进行高效、准确且可解释的异常检测。TCVADS 分两个阶段运作：粗粒度快速分类和细粒度详细分析。在第一阶段，TCVADS 从视频帧提取特征，并将其输入时间序列分析模块，该模块充当教师模型。接着通过知识蒸馏将见解传递给简化的卷积网络（学生模型）以进行二分类。一旦检测到异常，就会触发第二阶段，采用细粒度多分类模型。此阶段利用 CLIP 与文本和图像进行跨模态对比学习，通过专门设计的三元组文本关系增强可解释性，实现精细分类。实验结果显示，TCVADS 在模型性能、检测效率和可解释性方面显著优于现有方法，为智慧城市监测应用贡献了重要价值。

> Weakly Supervised Monitoring Anomaly Detection (WSMAD) utilizes weak supervision learning to identify anomalies, a critical task for smart city monitoring. However, existing multimodal approaches often fail to meet the real-time and interpretability requirements of edge devices due to their complexity. This paper presents TCVADS (Two-stage Cross-modal Video Anomaly Detection System), which leverages knowledge distillation and cross-modal contrastive learning to enable efficient, accurate, and interpretable anomaly detection on edge devices.TCVADS operates in two stages: coarse-grained rapid classification and fine-grained detailed analysis. In the first stage, TCVADS extracts features from video frames and inputs them into a time series analysis module, which acts as the teacher model. Insights are then transferred via knowledge distillation to a simplified convolutional network (student model) for binary classification. Upon detecting an anomaly, the second stage is triggered, employing a fine-grained multi-class classification model. This stage uses CLIP for cross-modal contrastive learning with text and images, enhancing interpretability and achieving refined classification through specially designed triplet textual relationships. Experimental results demonstrate that TCVADS significantly outperforms existing methods in model performance, detection efficiency, and interpretability, offering valuable contributions to smart city monitoring applications.

[Arxiv](https://arxiv.org/abs/2412.20201)