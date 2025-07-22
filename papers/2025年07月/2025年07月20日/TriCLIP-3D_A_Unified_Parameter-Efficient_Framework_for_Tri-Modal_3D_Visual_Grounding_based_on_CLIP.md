# TriCLIP-3D：基于CLIP的三模态三维视觉定位统一高效框架

发布时间：2025年07月20日

`Agent` `计算机视觉` `三维建模`

> TriCLIP-3D: A Unified Parameter-Efficient Framework for Tri-Modal 3D Visual Grounding based on CLIP

# 摘要

> 3D视觉定位使具身智能体能够根据人类指令理解真实3D环境中的视觉信息，这对于具身智能至关重要。现有方法通常使用独立编码器处理不同模态（如RGB图像、文本和3D点云），导致模型复杂且训练低效。尽管一些研究尝试使用预训练的2D多模态模型（如CLIP）处理3D任务，但点云与2D编码器的对齐问题仍未解决，仍需依赖3D编码器提取特征，进一步增加了复杂性和训练难度。

在本文中，我们提出了一种统一的2D预训练多模态网络，用于处理RGB图像、文本和点云三种模态，大幅简化了网络架构。通过基于适配器的微调2D CLIP双模态模型，该框架能够有效适应三模态设置，提升跨模态的适应性和性能表现。我们的几何感知2D-3D特征恢复与融合（GARF）模块旨在融合点云和图像中的几何多尺度特征。然后，我们将文本特征进行整合以完成最终的模态融合，并引入一个多模态解码器以促进深度跨模态理解。通过以上方法，我们实现了对三种模态的统一特征提取与融合，构建了一个端到端的3D视觉定位模型。

实验结果表明，与基线方法相比，我们的方法将可训练参数数量减少了约58%，同时在3D检测任务中提升了6.52%的性能，在3D视觉定位任务中提升了6.25%的性能。

> 3D visual grounding allows an embodied agent to understand visual information in real-world 3D environments based on human instructions, which is crucial for embodied intelligence. Existing 3D visual grounding methods typically rely on separate encoders for different modalities (e.g., RGB images, text, and 3D point clouds), resulting in large and complex models that are inefficient to train. While some approaches use pre-trained 2D multi-modal models like CLIP for 3D tasks, they still struggle with aligning point cloud data to 2D encoders. As a result, these methods continue to depend on 3D encoders for feature extraction, further increasing model complexity and training inefficiency. In this paper, we propose a unified 2D pre-trained multi-modal network to process all three modalities (RGB images, text, and point clouds), significantly simplifying the architecture. By leveraging a 2D CLIP bi-modal model with adapter-based fine-tuning, this framework effectively adapts to the tri-modal setting, improving both adaptability and performance across modalities. Our Geometric-Aware 2D-3D Feature Recovery and Fusion (GARF) module is designed to fuse geometric multi-scale features from point clouds and images. We then integrate textual features for final modality fusion and introduce a multi-modal decoder to facilitate deep cross-modal understanding. Together, our method achieves unified feature extraction and fusion across the three modalities, enabling an end-to-end 3D visual grounding model. Compared to the baseline, our method reduces the number of trainable parameters by approximately 58\%, while achieving a 6.52\% improvement in the 3D detection task and a 6.25\% improvement in the 3D visual grounding task.

[Arxiv](https://arxiv.org/abs/2507.14904)