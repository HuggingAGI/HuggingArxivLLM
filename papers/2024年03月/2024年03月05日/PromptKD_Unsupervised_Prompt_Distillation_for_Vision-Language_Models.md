# PromptKD 是一种针对视觉-语言模型的创新方法，通过无监督的方式进行提示蒸馏，以提升此类模型的表现和泛化能力。

发布时间：2024年03月05日

`LLM应用`

> PromptKD: Unsupervised Prompt Distillation for Vision-Language Models

# 摘要

> 提示学习已成为一种有效策略，能显著增强CLIP等特定领域下游任务中的视觉-语言模型性能。然而，以往研究过于关注设计多样化的提示形式，却忽视了提示作为大模型知识萃取工具的潜力。本篇论文提出一种创新的无监督领域提示蒸馏框架，它旨在借助未标注的领域图片，通过提示引导模仿的方式，将大规模教师模型的知识迁移到轻量级目标模型上。该框架分两步实施：首先，运用少量领域标签预训练大型CLIP教师模型，并独辟蹊径地一次性通过教师文本编码器预先计算和存储文本特征作为类别向量。接下来，共享这些存储的类别向量于教师和学生图像编码器间，以预测对数几率值；并通过KL散度对齐两者模型的对数几率值，促使学生图像编码器借助可学习的提示逼近教师模型生成的相似概率分布。此方法突破性地摆脱了对标注数据的依赖，得以充分利用海量领域内未标注图像资源。最终，经过充分训练的学生图像编码器和预存储的文本特征（类别向量）将在推理阶段发挥作用。据我们了解，这是首次（1）针对CLIP实现无监督领域特异性提示驱动知识蒸馏，以及（2）构建起教师与学生间共享文本特征作为类别向量的实用预存储机制。我们在11个数据集上开展的广泛实验有力证明了我们方法的有效性。

> Prompt learning has emerged as a valuable technique in enhancing vision-language models (VLMs) such as CLIP for downstream tasks in specific domains. Existing work mainly focuses on designing various learning forms of prompts, neglecting the potential of prompts as effective distillers for learning from larger teacher models. In this paper, we introduce an unsupervised domain prompt distillation framework, which aims to transfer the knowledge of a larger teacher model to a lightweight target model through prompt-driven imitation using unlabeled domain images. Specifically, our framework consists of two distinct stages. In the initial stage, we pre-train a large CLIP teacher model using domain (few-shot) labels. After pre-training, we leverage the unique decoupled-modality characteristics of CLIP by pre-computing and storing the text features as class vectors only once through the teacher text encoder. In the subsequent stage, the stored class vectors are shared across teacher and student image encoders for calculating the predicted logits. Further, we align the logits of both the teacher and student models via KL divergence, encouraging the student image encoder to generate similar probability distributions to the teacher through the learnable prompts. The proposed prompt distillation process eliminates the reliance on labeled data, enabling the algorithm to leverage a vast amount of unlabeled images within the domain. Finally, the well-trained student image encoders and pre-stored text features (class vectors) are utilized for inference. To our best knowledge, we are the first to (1) perform unsupervised domain-specific prompt-driven knowledge distillation for CLIP, and (2) establish a practical pre-storing mechanism of text features as shared class vectors between teacher and student. Extensive experiments on 11 datasets demonstrate the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2403.02781)