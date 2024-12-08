# 为实现准确的星系形态分析而对视觉语言模型进行有效的微调

发布时间：2024年11月29日

`其他` `星系研究`

> Effective Fine-Tuning of Vision-Language Models for Accurate Galaxy Morphology Analysis

# 摘要

> 星系形态分析就是依据星系的形状和结构来给星系分类。完成这个任务，直接在大型且有标注的天文数据集上训练特定领域的模型虽有效但成本高。相较而言，在少量天文图像上微调视觉基础模型更节省资源，不过通常准确性较低。为兼得两种方法的长处并弥补其短处，我们提出了 GalaxAlign 这一新方法，用于微调预训练的基础模型，从而在天文任务中达到高精度。具体来说，我们的方法拓展了对比学习架构，在微调中对齐三类数据：（1）一组代表星系形状和结构的示意符号；（2）这些符号的文本标签；（3）星系图像。如此一来，GalaxAlign 不但无需昂贵的预训练，还增强了微调的效果。在星系分类和相似性搜索上的大量实验表明，我们的方法通过融入特定领域的多模态知识，有效地为天文任务微调了通用的预训练模型。

> Galaxy morphology analysis involves classifying galaxies by their shapes and structures. For this task, directly training domain-specific models on large, annotated astronomical datasets is effective but costly. In contrast, fine-tuning vision foundation models on a smaller set of astronomical images is more resource-efficient but generally results in lower accuracy. To harness the benefits of both approaches and address their shortcomings, we propose GalaxAlign, a novel method that fine-tunes pre-trained foundation models to achieve high accuracy on astronomical tasks. Specifically, our method extends a contrastive learning architecture to align three types of data in fine-tuning: (1) a set of schematic symbols representing galaxy shapes and structures, (2) textual labels of these symbols, and (3) galaxy images. This way, GalaxAlign not only eliminates the need for expensive pretraining but also enhances the effectiveness of fine-tuning. Extensive experiments on galaxy classification and similarity search demonstrate that our method effectively fine-tunes general pre-trained models for astronomical tasks by incorporating domain-specific multi-modal knowledge.

[Arxiv](https://arxiv.org/abs/2411.19475)