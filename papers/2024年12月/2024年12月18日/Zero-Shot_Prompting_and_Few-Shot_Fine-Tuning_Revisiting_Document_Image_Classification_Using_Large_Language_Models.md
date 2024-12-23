# 零样本提示与少样本微调：借助大型语言模型再度审视文档图像分类

发布时间：2024年12月18日

`LLM应用` `文档处理` `模型训练`

> Zero-Shot Prompting and Few-Shot Fine-Tuning: Revisiting Document Image Classification Using Large Language Models

# 摘要

> 对扫描文档进行分类是个颇具挑战的难题，需要从图像、布局和文本等方面进行分析以理解文档。不过，就某些基准数据集（尤其是 RVL-CDIP）而言，当考虑到数十万个训练样本时，其先进水平已接近近乎完美的表现。随着大型语言模型（LLMs）的问世，它们是出色的少样本学习者，于是就产生了这样的问题：仅用几个训练样本甚至完全不用训练样本，文档分类问题能在多大程度上得以解决。在本文中，我们在零样本提示和少样本模型微调的情境下对该问题展开研究，旨在尽可能降低对人工标注训练样本的需求。

> Classifying scanned documents is a challenging problem that involves image, layout, and text analysis for document understanding. Nevertheless, for certain benchmark datasets, notably RVL-CDIP, the state of the art is closing in to near-perfect performance when considering hundreds of thousands of training samples. With the advent of large language models (LLMs), which are excellent few-shot learners, the question arises to what extent the document classification problem can be addressed with only a few training samples, or even none at all. In this paper, we investigate this question in the context of zero-shot prompting and few-shot model fine-tuning, with the aim of reducing the need for human-annotated training samples as much as possible.

[Arxiv](https://arxiv.org/abs/2412.13859)