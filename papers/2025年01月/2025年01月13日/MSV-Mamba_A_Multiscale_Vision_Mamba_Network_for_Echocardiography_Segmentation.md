# MSV-Mamba: 多尺度视觉 Mamba 网络在超声心动图分割中的应用

发布时间：2025年01月13日

`其他

理由：这篇论文主要讨论的是超声成像中的深度学习模型应用，特别是用于超声心动图分割的U形深度学习模型。虽然提到了Mamba模型，但整体内容与Agent、RAG、LLM应用或LLM理论无关，因此应归类为“其他”。` `超声成像`

> MSV-Mamba: A Multiscale Vision Mamba Network for Echocardiography Segmentation

# 摘要

> # 摘要
超声成像常面临高噪声、低时空分辨率和解剖结构复杂等挑战，这些因素严重影响了模型对心脏各区域结构关系和动态模式的准确捕捉与分析。Mamba作为一种新兴模型，广泛应用于视觉和语言任务，是当前最前沿的技术之一。为此，本文提出了一种U形深度学习模型，结合了大窗口Mamba尺度（LMS）模块和分层特征融合方法，用于超声心动图分割。首先，编码器采用级联残差块逐步提取多尺度细节特征；其次，解码器集成大窗口多尺度Mamba模块，捕捉跨区域的全局依赖关系，提升对复杂解剖结构的分割能力。此外，模型在每一层解码器中引入辅助损失，并采用双重注意力机制在空间和通道上融合多层特征，从而提升分割性能和对复杂解剖结构的描绘精度。实验结果表明，该模型在EchoNet-Dynamic和CAMUS数据集上的表现优于其他方法，左心室内膜（${LV}_{endo}$）分割分别达到95.01和93.36的最佳值，左心室外膜（${LV}_{epi}$）分割分别达到87.35和87.80的最佳值，较最佳模型提升了0.54到1.11。

> Ultrasound imaging frequently encounters challenges, such as those related to elevated noise levels, diminished spatiotemporal resolution, and the complexity of anatomical structures. These factors significantly hinder the model's ability to accurately capture and analyze structural relationships and dynamic patterns across various regions of the heart. Mamba, an emerging model, is one of the most cutting-edge approaches that is widely applied to diverse vision and language tasks. To this end, this paper introduces a U-shaped deep learning model incorporating a large-window Mamba scale (LMS) module and a hierarchical feature fusion approach for echocardiographic segmentation. First, a cascaded residual block serves as an encoder and is employed to incrementally extract multiscale detailed features. Second, a large-window multiscale mamba module is integrated into the decoder to capture global dependencies across regions and enhance the segmentation capability for complex anatomical structures. Furthermore, our model introduces auxiliary losses at each decoder layer and employs a dual attention mechanism to fuse multilayer features both spatially and across channels. This approach enhances segmentation performance and accuracy in delineating complex anatomical structures. Finally, the experimental results using the EchoNet-Dynamic and CAMUS datasets demonstrate that the model outperforms other methods in terms of both accuracy and robustness. For the segmentation of the left ventricular endocardium (${LV}_{endo}$), the model achieved optimal values of 95.01 and 93.36, respectively, while for the left ventricular epicardium (${LV}_{epi}$), values of 87.35 and 87.80, respectively, were achieved. This represents an improvement ranging between 0.54 and 1.11 compared with the best-performing model.

[Arxiv](https://arxiv.org/abs/2501.07120)