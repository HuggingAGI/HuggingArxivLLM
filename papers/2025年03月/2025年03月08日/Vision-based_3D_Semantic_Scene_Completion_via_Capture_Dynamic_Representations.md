# # Vision-based 3D Semantic Scene Completion via Capture Dynamic Representations
# 视觉驱动的3D语义场景补全：利用动态表征捕捉

发布时间：2025年03月08日

`其他` `自动驾驶` `计算机视觉`

> Vision-based 3D Semantic Scene Completion via Capture Dynamic Representations

# 摘要

> 基于视觉的语义场景完成任务旨在从二维图像中预测密集几何和语义三维场景表示。然而，场景中存在的动态物体严重降低了模型从二维图像推断三维结构的准确性。现有方法简单地堆叠多帧图像输入以增加密集场景语义信息，但忽略了动态物体和非纹理区域会破坏多视图一致性和匹配可靠性这一事实。为了解决这些问题，我们提出了一种新方法，CDScene：通过捕获动态表示实现基于视觉的鲁棒语义场景完成。首先，我们利用多模态大规模模型提取二维显式语义，并将其对齐到三维空间中。其次，我们利用单目和双目深度的特性，将场景信息分解为动态特征和静态特征。动态特征包含动态物体周围的结构关系，而静态特征包含密集的上下文空间信息。最后，我们设计了一个动态静态自适应融合模块，能够有效提取和聚合互补特征，在自动驾驶场景中实现了鲁棒且准确的语义场景完成。在SemanticKITTI、SSCBench-KITTI360和SemanticKITTI-C数据集上的大量实验结果证明了CDScene相较于现有最先进方法的优越性和鲁棒性。

> The vision-based semantic scene completion task aims to predict dense geometric and semantic 3D scene representations from 2D images. However, the presence of dynamic objects in the scene seriously affects the accuracy of the model inferring 3D structures from 2D images. Existing methods simply stack multiple frames of image input to increase dense scene semantic information, but ignore the fact that dynamic objects and non-texture areas violate multi-view consistency and matching reliability. To address these issues, we propose a novel method, CDScene: Vision-based Robust Semantic Scene Completion via Capturing Dynamic Representations. First, we leverage a multimodal large-scale model to extract 2D explicit semantics and align them into 3D space. Second, we exploit the characteristics of monocular and stereo depth to decouple scene information into dynamic and static features. The dynamic features contain structural relationships around dynamic objects, and the static features contain dense contextual spatial information. Finally, we design a dynamic-static adaptive fusion module to effectively extract and aggregate complementary features, achieving robust and accurate semantic scene completion in autonomous driving scenarios. Extensive experimental results on the SemanticKITTI, SSCBench-KITTI360, and SemanticKITTI-C datasets demonstrate the superiority and robustness of CDScene over existing state-of-the-art methods.

[Arxiv](https://arxiv.org/abs/2503.06222)