# Omni-Scene：用于以自我为中心的稀疏视图场景重建的全方位高斯表示

发布时间：2024年12月09日

`其他` `自动驾驶` `3D 重建`

> Omni-Scene: Omni-Gaussian Representation for Ego-Centric Sparse-View Scene Reconstruction

# 摘要

> 先前基于像素的高斯表示的相关工作已在前馈稀疏视图重建中展现出成效。但这种表示方式需要跨视图重叠才能准确估计深度，且面临物体遮挡和视锥体截断的难题。所以，这些方法得通过以场景为中心的数据采集来维持跨视图重叠和完整的场景可见性，以避开遮挡和截断，这就限制了它们在以场景为中心的重建中的应用。相反，在自动驾驶场景里，更实用的是自我为中心的重建，其特征是跨视图重叠少，常有遮挡和截断。正因如此，基于像素的表示的局限性阻碍了先前工作在此任务中的作用。鉴于此，本文深入分析了不同的表示方式，并引入了具有定制网络设计的全高斯表示，以弥补其优势和减少其缺陷。实验表明，我们的方法在自我为中心的重建中大幅超越了先进的 pixelSplat 和 MVSplat 方法，在以场景为中心的重建中也取得了与先前工作相当的性能。此外，我们将方法与扩散模型相结合，率先实现了 3D 驾驶场景的前馈多模态生成。

> Prior works employing pixel-based Gaussian representation have demonstrated efficacy in feed-forward sparse-view reconstruction. However, such representation necessitates cross-view overlap for accurate depth estimation, and is challenged by object occlusions and frustum truncations. As a result, these methods require scene-centric data acquisition to maintain cross-view overlap and complete scene visibility to circumvent occlusions and truncations, which limits their applicability to scene-centric reconstruction. In contrast, in autonomous driving scenarios, a more practical paradigm is ego-centric reconstruction, which is characterized by minimal cross-view overlap and frequent occlusions and truncations. The limitations of pixel-based representation thus hinder the utility of prior works in this task. In light of this, this paper conducts an in-depth analysis of different representations, and introduces Omni-Gaussian representation with tailored network design to complement their strengths and mitigate their drawbacks. Experiments show that our method significantly surpasses state-of-the-art methods, pixelSplat and MVSplat, in ego-centric reconstruction, and achieves comparable performance to prior works in scene-centric reconstruction. Furthermore, we extend our method with diffusion models, pioneering feed-forward multi-modal generation of 3D driving scenes.

[Arxiv](https://arxiv.org/abs/2412.06273)