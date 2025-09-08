# MCANet：多尺度类别特定注意力网络——基于无人机影像的多标签飓风后损伤评估

发布时间：2025年09月04日

`其他` `能源与环保`

> MCANet: A Multi-Scale Class-Specific Attention Network for Multi-Label Post-Hurricane Damage Assessment using UAV Imagery

# 摘要

> 飓风过后，快速准确的损害评估对灾害响应与恢复至关重要。但现有基于CNN的方法在捕捉多尺度空间特征、区分视觉相似或共存的损害类型方面存在不足。为此，我们提出多标签分类框架MCANet，它能学习多尺度特征表示，并针对每个损害类别自适应关注空间相关区域。MCANet采用基于Res2Net的层次化骨干网络，丰富跨尺度空间上下文信息；同时引入多头特定类别残差注意力模块，增强特征区分能力。每个注意力分支聚焦不同空间粒度，实现局部细节与全局上下文的平衡。我们在RescueNet数据集（含飓风迈克尔过后的4494张无人机图像）上验证MCANet，其平均精度均值（mAP）达91.75%，性能超越ResNet、Res2Net、VGG、MobileNet、EfficientNet及ViT等模型。当使用8个注意力头时，mAP进一步提升至92.35%，“道路堵塞”等难分类别的平均精度提升超6%。类激活映射结果证实，MCANet能精准定位损害相关区域，确保模型可解释性。MCANet的输出可为灾后风险制图、紧急路线规划及基于数字孪生的灾害响应提供支撑。未来可整合灾害专用知识图谱与多模态大语言模型，以提升对未知灾害的适应能力，并丰富语义理解，更好服务实际决策。

> Rapid and accurate post-hurricane damage assessment is vital for disaster response and recovery. Yet existing CNN-based methods struggle to capture multi-scale spatial features and to distinguish visually similar or co-occurring damage types. To address these issues, we propose MCANet, a multi-label classification framework that learns multi-scale representations and adaptively attends to spatially relevant regions for each damage category. MCANet employs a Res2Net-based hierarchical backbone to enrich spatial context across scales and a multi-head class-specific residual attention module to enhance discrimination. Each attention branch focuses on different spatial granularities, balancing local detail with global context. We evaluate MCANet on the RescueNet dataset of 4,494 UAV images collected after Hurricane Michael. MCANet achieves a mean average precision (mAP) of 91.75%, outperforming ResNet, Res2Net, VGG, MobileNet, EfficientNet, and ViT. With eight attention heads, performance further improves to 92.35%, boosting average precision for challenging classes such as Road Blocked by over 6%. Class activation mapping confirms MCANet's ability to localize damage-relevant regions, supporting interpretability. Outputs from MCANet can inform post-disaster risk mapping, emergency routing, and digital twin-based disaster response. Future work could integrate disaster-specific knowledge graphs and multimodal large language models to improve adaptability to unseen disasters and enrich semantic understanding for real-world decision-making.

[Arxiv](https://arxiv.org/abs/2509.04757)