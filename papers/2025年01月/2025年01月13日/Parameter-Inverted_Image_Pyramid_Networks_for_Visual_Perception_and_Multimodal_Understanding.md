# 参数倒置图像金字塔网络：视觉感知与多模态理解的新视角

发布时间：2025年01月13日

`LLM应用

理由：该论文提出了一种新颖的网络架构——参数倒置图像金字塔网络（PIIP），并将其应用于多模态大模型LLaVA。论文的主要贡献在于通过优化计算成本与性能的平衡，提升了多模态理解任务的性能。虽然论文涉及图像处理和多模态模型，但其核心应用场景是与大模型（LLM）相关的多模态理解任务，因此应归类为LLM应用。` `计算机视觉` `多模态理解`

> Parameter-Inverted Image Pyramid Networks for Visual Perception and Multimodal Understanding

# 摘要

> # 摘要
图像金字塔在顶尖方法中广泛应用，用于获取多尺度特征，以实现精确的视觉感知和理解。然而，现有图像金字塔使用相同的大规模模型处理多分辨率图像，导致计算成本高昂。为此，我们提出了一种新颖的网络架构——参数倒置图像金字塔网络（PIIP）。PIIP利用预训练模型（如ViTs或CNNs）作为分支处理多尺度图像，高分辨率图像由较小的网络分支处理，从而平衡计算成本与性能。我们还提出了一种跨分支特征交互机制，以整合不同空间尺度的信息。为验证PIIP，我们将其应用于多种感知模型及多模态大模型LLaVA，并在目标检测、分割、图像分类和多模态理解等任务上进行了广泛实验。PIIP在较低计算成本下，性能优于单分支和现有多分辨率方法。应用于大规模视觉基础模型InternViT-6B时，PIIP仅需40%-60%的计算量，即可将检测和分割性能提升1%-2%，最终在MS COCO上达到60.0 box AP，在ADE20K上达到59.7 mIoU。在多模态理解任务中，PIIP-LLaVA仅用2.8M训练数据，便在TextVQA上取得73.0%的准确率，在MMBench上达到74.5%。代码已开源：https://github.com/OpenGVLab/PIIP。

> Image pyramids are widely adopted in top-performing methods to obtain multi-scale features for precise visual perception and understanding. However, current image pyramids use the same large-scale model to process multiple resolutions of images, leading to significant computational cost. To address this challenge, we propose a novel network architecture, called Parameter-Inverted Image Pyramid Networks (PIIP). Specifically, PIIP uses pretrained models (ViTs or CNNs) as branches to process multi-scale images, where images of higher resolutions are processed by smaller network branches to balance computational cost and performance. To integrate information from different spatial scales, we further propose a novel cross-branch feature interaction mechanism. To validate PIIP, we apply it to various perception models and a representative multimodal large language model called LLaVA, and conduct extensive experiments on various tasks such as object detection, segmentation, image classification and multimodal understanding. PIIP achieves superior performance compared to single-branch and existing multi-resolution approaches with lower computational cost. When applied to InternViT-6B, a large-scale vision foundation model, PIIP can improve its performance by 1%-2% on detection and segmentation with only 40%-60% of the original computation, finally achieving 60.0 box AP on MS COCO and 59.7 mIoU on ADE20K. For multimodal understanding, our PIIP-LLaVA achieves 73.0% accuracy on TextVQA and 74.5% on MMBench with only 2.8M training data. Our code is released at https://github.com/OpenGVLab/PIIP.

[Arxiv](https://arxiv.org/abs/2501.07783)