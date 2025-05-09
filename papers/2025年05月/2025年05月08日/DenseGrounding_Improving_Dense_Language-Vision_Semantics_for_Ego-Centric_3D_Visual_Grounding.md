# 密集语义接地：提升自我中心3D视觉理解中的语言-视觉关联

发布时间：2025年05月08日

`Agent

理由：这篇论文主要关注智能体在三维环境中的定位和交互，特别是通过自然语言理解和增强视觉语义来提升定位的准确性。虽然提到了使用大型语言模型，但核心贡献在于智能体的技术改进，因此归类为Agent。` `机器人学` `自动驾驶`

> DenseGrounding: Improving Dense Language-Vision Semantics for Ego-Centric 3D Visual Grounding

# 摘要

> 让智能体通过自然语言理解并交互三维环境，对推动机器人学和人机交互至关重要。其中，自我中心3D视觉定位是一项核心任务，即智能体根据语言描述在真实世界的3D空间中定位目标物体。然而，这一任务面临两大挑战：(1) 点云与自我中心多视图图像的稀疏融合导致精细视觉语义丢失，(2) 由于任意语言描述的限制，文本语义上下文有限。为此，我们提出了DenseGrounding，一种通过增强视觉和文本语义来解决这些问题的创新方法。在视觉特征方面，我们引入了分层场景语义增强器，通过捕捉精细的全局场景特征并促进跨模态对齐来保留密集语义。在文本描述方面，我们提出了一种语言语义增强器，利用大型语言模型在模型训练过程中提供丰富的上下文和多样化的语言描述。大量实验表明，DenseGrounding在整体准确性上显著优于现有方法，分别在综合完整数据集和较小的迷你子集上训练时，准确率提升了5.81%和7.56%，进一步推动了自我中心3D视觉定位的最先进技术水平。我们的方法还在CVPR 2024自动驾驶大挑战的多视图3D视觉定位赛道中获得第一名，并荣获创新奖，充分验证了其有效性和鲁棒性。

> Enabling intelligent agents to comprehend and interact with 3D environments through natural language is crucial for advancing robotics and human-computer interaction. A fundamental task in this field is ego-centric 3D visual grounding, where agents locate target objects in real-world 3D spaces based on verbal descriptions. However, this task faces two significant challenges: (1) loss of fine-grained visual semantics due to sparse fusion of point clouds with ego-centric multi-view images, (2) limited textual semantic context due to arbitrary language descriptions. We propose DenseGrounding, a novel approach designed to address these issues by enhancing both visual and textual semantics. For visual features, we introduce the Hierarchical Scene Semantic Enhancer, which retains dense semantics by capturing fine-grained global scene features and facilitating cross-modal alignment. For text descriptions, we propose a Language Semantic Enhancer that leverages large language models to provide rich context and diverse language descriptions with additional context during model training. Extensive experiments show that DenseGrounding significantly outperforms existing methods in overall accuracy, with improvements of 5.81% and 7.56% when trained on the comprehensive full dataset and smaller mini subset, respectively, further advancing the SOTA in egocentric 3D visual grounding. Our method also achieves 1st place and receives the Innovation Award in the CVPR 2024 Autonomous Grand Challenge Multi-view 3D Visual Grounding Track, validating its effectiveness and robustness.

[Arxiv](https://arxiv.org/abs/2505.04965)