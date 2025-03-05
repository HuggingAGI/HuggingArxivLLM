# 语言引导的视觉感知解耦在图像质量评估与条件图像生成中的应用

发布时间：2025年03月03日

`LLM应用` `图像处理` `图像生成`

> Language-Guided Visual Perception Disentanglement for Image Quality Assessment and Conditional Image Generation

# 摘要

> 对比视觉-语言模型（如CLIP）在语义识别任务中展现出了卓越的零样本能力，这主要得益于大规模I&1T（一图一文）数据集的训练支持。这种多模态表示通常融合了语义和感知元素，尤其侧重于语义信息。然而，这在图像质量评估（IQA）和条件图像生成（CIG）等热门任务中可能存在问题，因为这些任务通常需要对感知和语义特征进行精细控制。

基于以上事实，本文提出了一种新的多模态解耦表示学习框架，该框架利用解耦文本指导图像解耦。为此，我们首先构建了一个I&2T（一图两文，包含感知文本和语义文本）数据集，其中包含了图像的解耦感知和语义文本描述。接着，将解耦的文本描述用作监督信号，从CLIP原始的`粗糙'特征空间中解耦出纯粹的感知表示，称为DeCLIP。最后，利用解耦后的特征表示分别进行图像质量评估（技术质量和美学质量）和条件图像生成。

大量实验和对比验证了所提方法在两个热门任务中的优势。该数据集、代码和模型将开放使用。

> Contrastive vision-language models, such as CLIP, have demonstrated excellent zero-shot capability across semantic recognition tasks, mainly attributed to the training on a large-scale I&1T (one Image with one Text) dataset. This kind of multimodal representations often blend semantic and perceptual elements, placing a particular emphasis on semantics. However, this could be problematic for popular tasks like image quality assessment (IQA) and conditional image generation (CIG), which typically need to have fine control on perceptual and semantic features. Motivated by the above facts, this paper presents a new multimodal disentangled representation learning framework, which leverages disentangled text to guide image disentanglement. To this end, we first build an I&2T (one Image with a perceptual Text and a semantic Text) dataset, which consists of disentangled perceptual and semantic text descriptions for an image. Then, the disentangled text descriptions are utilized as supervisory signals to disentangle pure perceptual representations from CLIP's original `coarse' feature space, dubbed DeCLIP. Finally, the decoupled feature representations are used for both image quality assessment (technical quality and aesthetic quality) and conditional image generation. Extensive experiments and comparisons have demonstrated the advantages of the proposed method on the two popular tasks. The dataset, code, and model will be available.

[Arxiv](https://arxiv.org/abs/2503.02206)