# 提升基于文本的人员搜索的视觉呈现

发布时间：2024年12月29日

`LLM应用` `人物搜索` `图像检索`

> Enhancing Visual Representation for Text-based Person Searching

# 摘要

> 文本型人物搜索旨在依据文本描述，从大规模图像数据库中检索出匹配的行人。此任务的核心难题在于怎样从行人图像和文本里提取有效细节，并在共同的潜在空间达成跨模态对齐。先前的工作运用在单模态数据上预训练的图像和文本编码器，分别从图像和文本中提取全局和局部特征，接着明确实现全局与局部的对齐。然而，这些方法在理解视觉细节方面能力不足，检索的准确性仍受身份混淆所限。为缓解上述问题，我们重新审视了视觉特征对于文本型人物搜索的重要性，提出了 VFE-TPS，即一种视觉特征增强的文本型人物搜索模型。它引入预训练的多模态骨干 CLIP 来学习基本的多模态特征，并构建了文本引导的掩码图像建模任务，在无明确注释的情况下增强模型学习局部视觉细节的能力。此外，我们设计了身份监督的全局视觉特征校准任务，引导模型学习具有身份感知的全局视觉特征。我们研究的关键发现是，借助我们提出的辅助任务，预训练的 CLIP 模型中嵌入的知识能够成功适配文本型人物搜索任务，且模型的视觉理解能力显著提升。在三个基准上的实验结果表明，我们提出的模型优于现有方法，Rank-1 准确率显著提高，约有 1%至 9%的显著差距。我们的代码可在 https://github.com/zhangweifeng1218/VFE_TPS 找到。

> Text-based person search aims to retrieve the matched pedestrians from a large-scale image database according to the text description. The core difficulty of this task is how to extract effective details from pedestrian images and texts, and achieve cross-modal alignment in a common latent space. Prior works adopt image and text encoders pre-trained on unimodal data to extract global and local features from image and text respectively, and then global-local alignment is achieved explicitly. However, these approaches still lack the ability of understanding visual details, and the retrieval accuracy is still limited by identity confusion. In order to alleviate the above problems, we rethink the importance of visual features for text-based person search, and propose VFE-TPS, a Visual Feature Enhanced Text-based Person Search model. It introduces a pre-trained multimodal backbone CLIP to learn basic multimodal features and constructs Text Guided Masked Image Modeling task to enhance the model's ability of learning local visual details without explicit annotation. In addition, we design Identity Supervised Global Visual Feature Calibration task to guide the model learn identity-aware global visual features. The key finding of our study is that, with the help of our proposed auxiliary tasks, the knowledge embedded in the pre-trained CLIP model can be successfully adapted to text-based person search task, and the model's visual understanding ability is significantly enhanced. Experimental results on three benchmarks demonstrate that our proposed model exceeds the existing approaches, and the Rank-1 accuracy is significantly improved with a notable margin of about $1\%\sim9\%$. Our code can be found at https://github.com/zhangweifeng1218/VFE_TPS.

[Arxiv](https://arxiv.org/abs/2412.20646)