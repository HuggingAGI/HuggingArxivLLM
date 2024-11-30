# 借助 LLM 强大的提示调优技术，我们能够实现无需原始数据的多标签图像识别。这项研究探讨了如何在没有数据的情况下，利用 LLM 的能力进行多标签图像识别任务的优化和提升。

发布时间：2024年03月02日

`LLM应用`

> Data-free Multi-label Image Recognition via LLM-powered Prompt Tuning

# 摘要

> 本研究提出了一项创新方案，用于无需任何训练数据的多标签图像识别，称为“数据免训框架”。这一框架巧妙借助预训练的大型语言模型（LLM）中的知识生成提示信息，以调整如CLIP这样的预训练视觉-语言模型(VLM)，使其适用于多标签分类任务。我们通过向LLM提出精心设计的问题，挖掘出各类物体的特性与上下文环境的详尽知识，并将其转化为有价值的文本描述以学习提示信息。进一步地，我们引入一种考虑多标签关联性的层级提示学习策略，其中，具有相似属性或更易共同出现的相关物体类别会共享部分类别特定的提示符号。受益于CLIP模型强大的视觉与语言语义对齐能力，由文本描述学习而来的层级提示被应用于图像分类的推断过程。我们的框架开创性地展示了如何有效整合多个预训练模型的力量，以应对新类别识别挑战。实验证明，在MS-COCO、VOC2007和NUS-WIDE三个公开数据集上，我们的方法不仅超越了当前最先进水平，尤其在MS-COCO的mAP评价指标上，相较于零样本多标签识别方法提高了4.7%，成绩斐然。

> This paper proposes a novel framework for multi-label image recognition without any training data, called data-free framework, which uses knowledge of pre-trained Large Language Model (LLM) to learn prompts to adapt pretrained Vision-Language Model (VLM) like CLIP to multilabel classification. Through asking LLM by well-designed questions, we acquire comprehensive knowledge about characteristics and contexts of objects, which provides valuable text descriptions for learning prompts. Then we propose a hierarchical prompt learning method by taking the multi-label dependency into consideration, wherein a subset of category-specific prompt tokens are shared when the corresponding objects exhibit similar attributes or are more likely to co-occur. Benefiting from the remarkable alignment between visual and linguistic semantics of CLIP, the hierarchical prompts learned from text descriptions are applied to perform classification of images during inference. Our framework presents a new way to explore the synergies between multiple pre-trained models for novel category recognition. Extensive experiments on three public datasets (MS-COCO, VOC2007, and NUS-WIDE) demonstrate that our method achieves better results than the state-of-the-art methods, especially outperforming the zero-shot multi-label recognition methods by 4.7% in mAP on MS-COCO.

[Arxiv](https://arxiv.org/abs/2403.01209)