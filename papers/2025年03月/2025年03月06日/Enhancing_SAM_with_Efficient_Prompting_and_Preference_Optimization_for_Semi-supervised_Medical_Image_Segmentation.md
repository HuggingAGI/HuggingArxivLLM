# # 摘要
通过高效提示与偏好优化提升SAM在半监督医学图像分割中的性能

发布时间：2025年03月06日

`LLM应用` `图像分割`

> Enhancing SAM with Efficient Prompting and Preference Optimization for Semi-supervised Medical Image Segmentation

# 摘要

> 基础模型如Segment Anything Model (SAM) 在医学图像分割领域展现出显著优势，支持多种下游任务。但这些模型本质上仍依赖于监督式学习，需要大量标注数据或专家提示。传统方法如主动学习虽然在一定程度上缓解了这些限制，但其适用范围有限，仍需持续的人工参与和复杂领域知识支持。

为解决这些挑战，我们提出了一种增强版SAM框架。该框架采用完全无监督生成的标注高效提示，通过对比语言-图像预训练和视觉问答技术，有效捕捉关键语义、位置和形状信息。我们创新性地引入直接偏好优化技术，设计出最优策略，使模型能够根据虚拟标注员提供的简单评分或排名生成高保真分割结果，完美模拟人类标注流程。

实验结果表明，我们的框架在肺部分割、乳腺肿瘤分割和多模态器官分割（包括X射线、超声和腹部CT等）等任务中均达到业界领先水平，充分证明了其在低标注数据场景中的卓越效果。

> Foundational models such as the Segment Anything Model (SAM) are gaining traction in medical imaging segmentation, supporting multiple downstream tasks. However, such models are supervised in nature, still relying on large annotated datasets or prompts supplied by experts. Conventional techniques such as active learning to alleviate such limitations are limited in scope and still necessitate continuous human involvement and complex domain knowledge for label refinement or establishing reward ground truth. To address these challenges, we propose an enhanced Segment Anything Model (SAM) framework that utilizes annotation-efficient prompts generated in a fully unsupervised fashion, while still capturing essential semantic, location, and shape information through contrastive language-image pretraining and visual question answering. We adopt the direct preference optimization technique to design an optimal policy that enables the model to generate high-fidelity segmentations with simple ratings or rankings provided by a virtual annotator simulating the human annotation process. State-of-the-art performance of our framework in tasks such as lung segmentation, breast tumor segmentation, and organ segmentation across various modalities, including X-ray, ultrasound, and abdominal CT, justifies its effectiveness in low-annotation data scenarios.

[Arxiv](https://arxiv.org/abs/2503.04639)