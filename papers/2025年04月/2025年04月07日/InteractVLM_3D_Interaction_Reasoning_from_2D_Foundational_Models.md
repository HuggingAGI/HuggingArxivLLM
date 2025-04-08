# InteractVLM：从2D基础模型推断3D交互关系

发布时间：2025年04月07日

`其他` `计算机视觉` `三维重建`

> InteractVLM: 3D Interaction Reasoning from 2D Foundational Models

# 摘要

> 我们推出了一项创新技术InteractVLM，它能够从单张真实图像中准确估算人体与物体的三维接触点，从而实现精准的三维人体-物体接触重建。这一任务面临诸多挑战，包括遮挡、深度模糊以及物体形状的多样性。目前的解决方案依赖于通过昂贵的动作捕捉系统或繁琐的人工标注获得的三维接触点数据，这极大限制了其应用范围和泛化能力。为突破这一瓶颈，InteractVLM巧妙地利用了大型视觉-语言模型（VLMs）的广泛视觉知识，并通过少量三维接触数据进行优化。然而，直接应用这些模型存在困难，因为它们仅在二维空间中进行推理，而人体与物体的接触本质上是三维的。为此，我们设计了一种全新的Render-Localize-Lift模块，该模块通过多视角渲染将三维人体与物体表面嵌入二维空间，训练一种新型多视角定位模型（MV-Loc）来推断二维空间中的接触点，并将这些接触点提升到三维空间。此外，我们还提出了一项名为语义人体接触估计的新任务，其中人体接触预测显式地基于物体语义，从而实现更丰富的交互建模。InteractVLM在接触点估计方面超越了现有方法，并且能够从真实图像中实现卓越的三维重建效果。代码和模型可在https://interactvlm.is.tue.mpg.de获取。

> We introduce InteractVLM, a novel method to estimate 3D contact points on human bodies and objects from single in-the-wild images, enabling accurate human-object joint reconstruction in 3D. This is challenging due to occlusions, depth ambiguities, and widely varying object shapes. Existing methods rely on 3D contact annotations collected via expensive motion-capture systems or tedious manual labeling, limiting scalability and generalization. To overcome this, InteractVLM harnesses the broad visual knowledge of large Vision-Language Models (VLMs), fine-tuned with limited 3D contact data. However, directly applying these models is non-trivial, as they reason only in 2D, while human-object contact is inherently 3D. Thus we introduce a novel Render-Localize-Lift module that: (1) embeds 3D body and object surfaces in 2D space via multi-view rendering, (2) trains a novel multi-view localization model (MV-Loc) to infer contacts in 2D, and (3) lifts these to 3D. Additionally, we propose a new task called Semantic Human Contact estimation, where human contact predictions are conditioned explicitly on object semantics, enabling richer interaction modeling. InteractVLM outperforms existing work on contact estimation and also facilitates 3D reconstruction from an in-the wild image. Code and models are available at https://interactvlm.is.tue.mpg.de.

[Arxiv](https://arxiv.org/abs/2504.05303)